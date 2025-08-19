# Script Section

The `<script>` element contains the sequence of commands that the robot must execute. We can see some of them on following code snippet. We can see in line 2 of the script, the `<light>` command that lights the smart bulb setting its color to blue. Next we have the `<talk>` command, which makes the robot say something, for example, introducing itself. The `<wait>` command on line 4 causes the script to pause for 2000 ms (2s). In the next line, the `<audio>` command plays an audio file named "mario-start". Then the robot speaks "bye" and turns off the smart bulb. A detailed explanation of each of these commands will be presented in Section 2.3.

<!-- hl_lines="2 3" -->
```xml title="script_example.xml" linenums="1" 
<script>
  <light state="ON" color="BLUE" />
  <talk>Hi, I am robot EVA</talk>
  <wait duration="2000" />
  <audio source="mario-start" block="TRUE" />
  <talk>Bye</talk>
  <light state="OFF" />
</script>
```