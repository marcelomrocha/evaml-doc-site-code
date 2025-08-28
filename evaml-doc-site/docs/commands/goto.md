# Goto

The `<goto>` command switches the execution flow to the command with **id** referenced in its target attribute. The **id** attribute defines the label that will be used as a value in the target attribute of the `<goto>` command. In this example, the script is looped.

```xml title="goto_example.xml" linenums="0"
<script>
  <light id="BEGIN" state="ON" color="RED" />
  <wait duration="1000" />
  <light state="OFF" />
  <wait duration="1000" />
  <goto target="BEGIN" />
</script>
```

As can be seen in the table that presents the EvaML elements, in the Overview Section, some commands do not have the id attribute and therefore cannot be referenced as "targets" of `<goto>` commands. These are the commands: `<voice>`, `<stop>`, `<goto>`, `<macro>`, `<useMacro>`, `<case>` and `<default>`.