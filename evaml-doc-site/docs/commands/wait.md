# Wait

The `<wait>` command pauses the script execution. The **duration** attribute is expressed in milliseconds. In this example, the command causes the script to pause for one second (1000ms).

<!-- hl_lines="2 3" -->
```xml title="wait_example.xml" linenums="0"
<script>
    <talk>I will wait for one second</talk>
    <wait duration="1000" />
    <talk>Ready!</talk>
</script>
```

