# Voice

The `<voice>` command does not produce any action, it actually sets a parameter that defines, at the same time, the voice tone (its gender) to be used by the robot, and the language that will be taken into account during the Text-To-Speech (TTS) process from the IBM Watson service. It defines only one attribute, **tone** and as we presented previously, in the attribute column, an underlined attribute indicating that it should be used. As it is a configuration command, it is placed inside the `<settings>` section. In the following table, we can see a small list with some voice options for the robot. In the following code, we select the **"en-US_AllisonV3Voice"** option, which is female.


<div <div align="center">
<table class="commands"; style="text-align: center;">
  <tr>
    <th><b>Code</th>
    <th><b>Gender</b></th>
    <th><b>Dialect</b></th>
  </tr>
  <tr>
    <td>pt-BR_IsabelaV3Voice</td>
    <td>Female</td>   
    <td>Brazilian</td>
  </tr>
    <td>en-US_AllisonV3Voice</td>
    <td>Female</td>   
    <td>American</td>
  </tr>
  </tr>
    <td>en-US_EmilyV3Voice</td>
    <td>Female</td>   
    <td>American</td>
  </tr>
  </tr>
    <td>en-US_HenryV3Voice</td>
    <td>Male</td>   
    <td>American</td>
  </tr>
  </tr>
    <td>es-LA_SofiaV3Voice</td>
    <td>Female</td>   
    <td>Spanish (Latin American)</td>
  </tr>
  </tr>
    <td>es-ES_EnriqueV3Voice</td>
    <td>Female</td>   
    <td>Spanish</td>
  </tr>
</table>
</div>

<p style="text-align: center;"><b>Table</b>: Voice options from IBM Watson (TTS)</p>

<br>
The following small code snippet shows the usage of the `<voice>` command.
<!-- hl_lines="2 3" -->
```xml title="voice_example.xml" linenums="0"
<settings>
    <voice tone="en-US_AllisonV3Voice" />
</settings>
```

