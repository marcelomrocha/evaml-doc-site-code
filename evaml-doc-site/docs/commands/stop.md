# Stop

The `<stop>` command stops the script from running. In the following example, the command that lights the bulb green will not be executed, as the script is stopped by the command `<stop>`. The example is not very good, as it does not make sense to put any command after a `<stop>` command, but the purpose is just to show that the script will be terminated before the `<light>` command in line 5. The use of the `<stop>` command is best justified when used inside a `<case>` command in a `<switch>` block. Its use allows interrupting an execution flow created by the `<case>` command.

```xml title="stop_example.xml" linenums="1"
<script>
    <light state="ON" color="RED" />
    <wait duration="1500" />
    <stop />
    <light state="ON" color="GREEN" />
</script>
```