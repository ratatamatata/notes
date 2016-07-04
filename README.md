#Notes

##Intel VSync for ASUS N551JK
    Section "Device"
        Identifier  "Intel Graphics"
        Option      "AccelMethod"    "SNA"
        Option      "SwapbuffersWait"        "true"
        Option      "TearFree"    "true"
        Driver      "intel"
    EndSection
