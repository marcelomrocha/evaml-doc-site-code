# EvaML - Document Sections

We can see in Figure 2.1 an EvaML script that shows the document root element `<evaml>`, with its name
attribute that defines the script name, and which contains the following three elements: the `<settings>`, `<script>`
and `<macros>`.

<!-- <p align="center">
  <img src="../img/evaml-sections-manual.png" alt="Create User Diagram" width="400"/>
</p> -->

![Create User Diagram](../img/evaml-sections-manual.png)


Table 2.1 shows the root element of the EvaML document (`<evaml>`) and the elements `<settings>`, `<script>` and `<macros>` that represent the sections of the document. You can also observe the attributes of each element and its contents. In the attribute column, an underlined attribute indicates that it should be used. In the column of contents, occurrence indicators are used to indicate the order and number of times an element can occur. The "," (comma) symbol indicates that all child elements listed must be used in the sequence shown. The "|" (pipe bar) indicates that either element can occur within the parent element. The "+" (plus sign) symbol, on the other hand, indicates that the child element must appear one or more times. The "*" (asterisk) symbol indicates that the element may be used zero or more times within the parent element. The "?" (question mark) indicates that the element is optional, the element may not exist or there is only one occurrence of it.

<table class="commands">
  <tr>
    <th><b>Element</b></th>
    <th><b>Attributes</b></th>
    <th><b>Content</b></th>
  </tr>
  <tr>
    <td>evaml</td>
    <td><u>name</u></td>   
    <td>(settings, script, macros?)</td>
  </tr>
  <tr>
    <td>settings</td>
    <td></td>
    <td>(voice | lightEffects? | audioEffects?)</td>
  </tr>
  <tr>
    <td>script</td>
    <td></td>
    <td>(random* | wait* | talk* | stop* | light* | goto* | motion* | loop* | userEmotion* | evaEmotion* | useMacro* | listen* | audio* | led* | counter* | switch*)</td>
  </tr>
  <tr>
    <td>macros</td>
    <td></td>   
    <td>(macro+)</td>
  </tr>
</table>

<p style="text-align: center;"><b>Table</b>: EvaML - Document Elements (Root and Main Elements)</p>

