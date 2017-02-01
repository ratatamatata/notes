#Notes

##Intel VSync for ASUS N551JK
    Section "Device"
        Identifier  "Intel Graphics"
        Option      "AccelMethod"    "SNA"
        Option      "SwapbuffersWait"        "true"
        Option      "TearFree"    "true"
        Driver      "intel"
    EndSection
    
##Gnome panel size
/home/user/.local/share/themes/NameThemes/gnome-shell/gnome-shell.css
##In-System Memory
the_altsyncram.lpm_hint = "ENABLE_RUNTIME_MOD = YES",

the_altsyncram.INSTANCE_NAME = "nios_onchip_mem";
