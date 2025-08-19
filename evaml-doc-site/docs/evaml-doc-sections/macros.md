# Macros Section

The `<macros>` element is one of the abstractions created in the EvaML language. As you can see in the next code snippet, it is possible to create macros that can be referenced within the `<script>` element. A macro has the id attribute that serves to identify it. These macros can be used within the `<script>` section using the `<useMacro>` command. The macro attribute of the command `<useMacro>` references the `<macro>` element defined in the `<macros>` section. During the parsing process of the EvaML document, macros are expanded with their code in the `<script>` section. There is no limit to the number of macros created, nor to the number of references to these macros within the script. As can be seen in Table 2.1 the macros section is not mandatory.

<!-- hl_lines="2 3" -->
```xml title="macros_example.xml" linenums="1" 
<script>
  <useMacro macro="START" />
</script>
<macros>
  <macro id="START">
    <talk>Hello, I'm robot Eva. I'll pick a number from one to four</talk>
    <talk>For each one, I'll turn the bulb on in a different color</talk>
    <talk>I will only terminate when the number drawn is three</talk>
  </macro>
</macros>
```