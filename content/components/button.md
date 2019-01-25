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

    <h5>Example Implementation Code</h5>
    
    <pre>

    <code>&lt;button href=&quot;#&quot; theme=&quot;&quot;&gt; myButton &lt;/button&gt;</code>
    </pre>

    <h5>Result</h5>
    {{<button href="#">}}myButton{{</button>}}

</div>

<div id="Guidelines" class="tabcontent">
    <h5>Anatomy</h5>
    <div style="display:flex;">
    <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F1CohpRuQZDOxIDHVQgMp4ly0VAZ8KW2jO%2Fbuttons-anatomy-all.png" style="max-width:800px;">
    </div>
    <div style="display:flex;">
        <ol start="1">
            <li>Text button
                <ol type="A">
                    <li>Text label</li>
                    <li>Icon (optional)</li>
                </ol>
            </li>
        </ol>
        <ol start="2">
            <li>Outlined button
                <ol type="A">
                    <li>Text label</li>
                    <li>Container</li>
                    <li>Icon (optional)</li>
                </ol>
            </li>
        </ol>
        <ol start="3">
            <li>Contained button
                <ol type="A">
                    <li>Text label</li>
                    <li>Container</li>
                    <li>Icon (optional)</li>
                </ol>
            </li>
        </ol>
        <ol start="4">
            <li>Toggle button
                <ol type="A">
                    <li>Text label</li>
                    <li>Container</li>
                    <li>Icon (optional)</li>
                </ol>
            </li>
        </ol>
    </div>
    <h5>Hiearchy</h5>
    <strong>A single, prominent button</strong>
    <p>A layout should contain a single prominent button that makes it clear that other buttons have less importance in the hierarchy. This high-emphasis button commands the most attention.</p>
    <strong>Other buttons</strong>
    <p>An app can show more than one button in a layout at a time, so a high-emphasis button can be accompanied by medium- and low-emphasis buttons that perform less important actions. When using multiple buttons, ensure the available state of one button doesn’t look like the disabled state of another.</p>
    <div style="display:flex;">
    <img src="https://storage.googleapis.com/spec-host-backup/mio-design%2Fassets%2F0B4V689etGs17czJ6LUFBUkswdkU%2Fbuttons-layout-diagram-01.png" style="max-width:800px;">
    </div>

</div>




    







