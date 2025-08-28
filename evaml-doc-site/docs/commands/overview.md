# EvaML - Commands

## Overview

Before presenting each EvaML command with its description and usage examples, Table 2.2 shows EvaML elements that represent the language commands. Its attributes and what each element can contain will also be listed. For such representation, the same notation used in Table 2.1 will be used. The description of each symbol
used can be seen in Section 2.2.

<table class="commands">
  <tr>
    <th><b>Command</b></th>
    <th><b>Attributes</b></th>
    <th><b>Content</b></th>
  </tr>
  <tr>
    <td>voice</td>
    <td><u>tone</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>lightEffects</td>
    <td><u>mode</u></td>
    <td>empty</td>
  </tr>
  <tr>
    <td>audioEffects</td>
    <td><u>mode</u></td>
    <td>empty</td>
  </tr>
  <tr>
    <td>random</td>
    <td>id, <u>min</u>, <u>max</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>wait</td>
    <td>id, <u>duration<u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>talk</td>
    <td>id</td>   
    <td>text</td>
  </tr>
  <tr>
    <td>stop</td>
    <td></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>light</td>
    <td>id, <u>state</u>, color</td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>goto</td>
    <td><u>target</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>motion</td>
    <td>id, <u>type</u></td>   
    <td></td>
  </tr>
  <tr>
    <td>userEmotion</td>
    <td>id</td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>evaEmotion</td>
    <td>id, <u>emotion</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>useMacro</td>
    <td><u>macro</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>listen</td>
    <td>id</td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>audio</td>
    <td>id, <u>source</u>, <u>block</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>led</td>
    <td>id, <u>animation</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>counter</td>
    <td>id, <u>var</u>, <u>op</u>, <u>value</u></td>   
    <td>empty</td>
  </tr>
  <tr>
    <td>switch</td>
    <td>id, <u>var<u></td>   
    <td>(case+, default?)</td>
  </tr>
  <tr>
    <td>macro</td>
    <td><u>id</u></td>   
    <td>(random* | wait* | talk* | stop* | light* | goto* | motion* | loop* | userEmotion* | evaEmotion* | listen* | audio* | led* | counter* | switch*)</td>
  </tr>
  <tr>
    <td>case</td>
    <td><u>op</u>, <u>value</u></td>   
    <td>(random* | wait* | talk* | stop* | light* | goto* | motion* | loop* | userEmotion* | evaEmotion* | useMacro* | listen* | audio* | led* | counter* | switch*)</td>
  </tr>
  <tr>
    <td>default</td>
    <td></td>   
    <td>(random* | wait* | talk* | stop* | light* | goto* | motion* | loop* | userEmotion* | evaEmotion* | useMacro* | listen* | audio* | led* | counter* | switch*)</td>
  </tr>
  <tr>
    <td>loop</td>
    <td>id, var, <u>times</u></td>   
    <td>(random* | wait* | talk* | stop* | light* | goto* | motion* | loop* | userEmotion* | evaEmotion* | useMacro* | listen* | audio* | led* | counter* | switch*)</td>
  </tr>
  <tr>
    <td>...</td>
    <td></td>   
    <td>Faltam os comandos novos e as modificações</td>
  </tr>
</table>
<p style="text-align: center;"><b>Table</b>: EvaML - Document Elements (Commands)</p>