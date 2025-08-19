# Settings Section

In this first section, some global characteristics of the script are defined in the `<settings>` element. It is
possible to define how the voice tone and the language in which the robot will communicate. It is also possible
to define whether the generated code will perform light effects, sound effects or even play music. By configuring
these parameters, it is possible to globally modify the operation of the script without having to directly change
the definitions of its individual elements. Here is an example from the `<settings>` element.

<!-- hl_lines="2 3" -->
```xml title="settings_example.xml" linenums="1" 
<settings>
    <voice tone=”en-US_AllisonV3Voice” />
    <lightEffects mode=”ON” />
    <audioEffects mode=”ON” />
</settings>
```