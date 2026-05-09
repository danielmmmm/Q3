/data/system_de/0/accounts_de.db

adb root
adb shell oculuspreferences --setc 

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

|**Preference**|**Default**|**New value**|**Effective**|**Description**|**Comments**|
|:-|:-:|:-:|:-:|:-|:-|
|`app_auto_updates_enabled`|0|||||
|debug_disable_shell_transition_animations|0|1|Immediately|Removes transition|Games fail to load into their UI and leave an empty screen instwead|
|keyboard_long_press_timeout|0.65|0.5|Immediately|Long press delay until secondary characters<br>pop up on the virtual keyboard|-|




