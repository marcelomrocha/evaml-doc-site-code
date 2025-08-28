# Light

The `<light>` command controls the smart bulb and has two attributes. The **state**, which can assume the values "ON" and "OFF" and the **color** attribute, which defines the bulb color. This color can be indicated using the RGB hexadecimal representation "#00ff00" or some of the elements from the predefined list: "WHITE", "RED", "PINK", "GREEN", "YELLOW", "BLUE".

```xml title="light_example.xml" linenums="0"
<script>
  <light state="ON" color="RED" />
  <wait duration="1000" />
  <light state="ON" color="#00ff00" />
  <wait duration="1000" />
  <light state="ON" color="BLUE" />
  <wait duration="1000" />
  <light state="OFF" />
</script>
```

!!! Note
    If the **state** is "OFF", the **color** attribute value will not be used. In this specific case, the **color** attribute can be ommited.