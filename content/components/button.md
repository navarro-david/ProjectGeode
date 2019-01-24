+++
title = "button"
description = "Display an actionable button in your page."
+++

Display an actionable button in your page.

{{<button align="center" href="#" theme="warning" >}} This is a warning button {{< /button >}}

## Implementation


<!-- Tab links -->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Implementation')">Implementation</button>
  <button class="tablinks" onclick="openTab(event, 'Guidelines')">Guidelines</button>
</div>

<!-- Tab content -->
<div id="Implementation" class="tabcontent active" style="display: block;">
  <h3>Implementation</h3>

  <table>
  <tr>
    <th>Style</th>
    <th>Class</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>{{<button align="center" href="#" >}} Continue {{< /button >}}</td>
    <td>theme=</td>
    <td>Just a Regular Button</td>
  </tr>
  <tr>
    <td>{{<button align="center" href="#" theme="success">}} Success {{< /button >}}</td>
    <td>theme='success'</td>
    <td>Just a Successful Button</td>
  </tr>
  <tr>
    <td>{{<button align="center" href="#" theme="info">}} Info {{< /button >}}</td>
    <td>theme='info'</td>
    <td>Just a Smart Button</td>
  </tr>
  <tr>
    <td>{{<button align="center" href="#" theme="warning">}} Warning {{< /button >}}</td>
    <td>theme='warning'</td>
    <td>Just a Cautious Button</td>
  </tr>
  <tr>
    <td>{{<button align="center" href="#" theme="danger">}} Danger ! {{< /button >}}</td>
    <td>theme='danger'</td>
    <td>Just a Dramatic Button</td>
  </tr>
  <tr>
    <td>{{<button align="center" href="#" theme="default">}} Ok {{< /button >}} </td>
    <td>theme='default'</td>
    <td>Just a Boring Button</td>
  </tr>
  </table>
</div>

<div id="Guidelines" class="tabcontent">
    <h3>Design Guidelines</h3>
    <p>Button labels use sentence case and are as short as possible, while clearly explaining what happens when the button is activated.</p>
    <img src="https://atlassian.design/uploads/guidelines/product/buttons/button-naming.png">
</div>




    







