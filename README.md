# Robb's i3 Desktop

1. Start with a desktop that has XFCE enabled
2. Install i3 and i3blocks
    ```
    $ sudo apt install i3 i3blocks
    ```
3. In settings, open `Session and Startup` and go to the `Session` tab.


4. For `xfwm4` and `xfdesktop`, change `Immediately` to `Never`. These processes will be replaced by i3.


5. Click `Save Session`. 

6. Still in `Session and Startup` go to the `Application Autostart` tab. 

7. Click `Add` to add i3 to the list of startup applications. 
    - Name: i3 (or whatever you like)
    - Description: Tiling Window Manager (or whatever you like)
    - Command: i3 (must be i3, that's the name of the binary)

8. Click `OK`. 

9. You will probably want to remove all XFCE keyboard shortcuts and let i3 handle that via its config. 
    - In settings, go to `Keyboard`
    - Go to `Application Shortcuts` tab
    - Shift-select them all and click `Remove`.

10. Grab config files from this repo and edit to taste:
    - `~/.config/i3/config`
    - `~/.i3blocks.conf`

