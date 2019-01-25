+++
title = "button"
description = "Display an actionable button in your page."
+++

Display an actionable button in your page.

<!-- Tab links -->
<div class="tab">
  <button class="tablinks active" onclick="openTab(event, 'Implementation')">Implementation</button>
  <button class="tablinks" onclick="openTab(event, 'Guidelines')">Guidelines</button>
</div>

<!-- Tab content -->
<div id="Implementation" class="tabcontent active" style="display: block;">
  <h5>Button Variations</h5>

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

    <h5>Example Button Implementation</h5>
    
    <pre>

    <code>&lt;button href=&quot;#&quot; theme=&quot;&quot;&gt; myButton &lt;/button&gt;</code>
    </pre>

    <h5>Result</h5>
    {{<button href="#">}}myButton{{</button>}}

</div>

<div id="Guidelines" class="tabcontent">
    <h5>Button</h5>
    <p>Use buttons to trigger actions and links. Buttons can contain a combination of a clear label and an icon while links are always text.</p>
    <img src="https://atlassian.design/uploads/guidelines/product/buttons/button-anatomy.png" style="max-width:800px;">

    <h5>Writing Labels</h5>
    <p>Button labels use sentence case and are as short as possible, while clearly explaining what happens when the button is activated.</p>
    <ol>
        <li><strong>Icon: </strong>Use an icon to convey more meaning.</li>
        <li><strong>Label: </strong>Text that indicates the result of selecting the button.</li>
    </ol>
    <img src="https://atlassian.design/uploads/guidelines/product/buttons/button-naming.png" style="max-width:800px;">

    <h5>Button Order and Alignment</h5>
    <p>Buttons are aligned depending on context:</p>
    <ui>
        <li>For single page forms and focused tasks, left-align buttons and sort by importance from left to right.</li>
        <li>When using buttons to prompt a user to move through a sequence of screens (e.g. getting started guides), right-align the primary button to visually support navigation. Exceptions include user benefits modals and other modals where buttons are centered, with the primary button on the right.
        </li>
    </ui>

    <h5>Grouped Buttons</h5>
    <p>Grouped buttons give people access to frequently performed, related actions. Use grouped buttons when there is a close relationship between a number of buttons. Common placements of grouped buttons can be found in Jira issues or while editing Confluence pages. This pattern is normally used at the top of the page.</p>
     <img src="https://atlassian.design/uploads/guidelines/product/buttons/button-group.png" style="max-width:800px;">


</div>




    







