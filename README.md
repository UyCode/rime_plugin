# this uyghur input method plugin perfectly mathch with rime and windows uyghur input method style.

# step 1
### download the uycode.schema.yaml file from this repository

# step 2
### copy doanloaded file to rime user settings ( by default on windows: C:\Users\{your-computer-name}\Appdata\Roaming\Rime\build )
> if you choise the user settings folder when install, then go that folder
> 
# step 3
### edit default.yaml file in same directory, add:
```yaml
schema_list:
  - schema: luna_pinyin_simp
  - schema: uycode
```
 add this to the schema_list
 
 # step 4
 ### click redeploy(重新部署）button to refresh rime settings on the status bar
 
 # step 5
 ### click F4 and switch to uyghur input method on the list
 
 # Enjoy!
