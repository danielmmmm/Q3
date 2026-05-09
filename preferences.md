
/data/oculus/preferences/system.db
/data/oculus/preferences/user0.db


adb root
adb shell oculuspreferences --setc 


|**Preference**|**Default**|**New**|**Effective**|**Description**|**Comments**|
|:-|:-:|:-:|:-:|:-|:-|
|<sub>`app_auto_updates_enabled`</sub>|0|||||
|<sub>`debug_disable_shell_transition_animations`</sub>|0|1|Immediately|Removes transition|Games fail to load into their UI and leave an empty screen instwead|
|<sub>`keyboard_long_press_timeout`</sub>|0.65|0.5|Immediately|Long press delay until secondary characters<br>pop up on the virtual keyboard|-|
|<sub>`debug_vr_shell_input_visualizations`</sub>|0|1|Immediately|Shows green markers for hand scelletons|Markers are shown on top and not occluded by controllers|


