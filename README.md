# Younix OC Theme
Just a simple OpenCore Theme

-   **OpenCanopy Theme**

    -   [younix rad theme](https://github.com/iamyounix/msimagb460_tomahawk/releases/download/Release/theme_younix.zip)

        ![30073939](https://github.com/iamyounix/msimagb460_tomahawk/assets/72515939/6c640b15-32a6-4b01-ba5c-307afdb74167)

    -   Rad Theme Config Example:
        -   PickerAttributes = `147`
        -   PickerMode = `External`
        -   PickerVariant = `younix\Rad`
        -   ShowPicker = `Yes`
        -   Entries
            -   Arguments = `Auxiliary` (Only appear when pressing Tab)
            -   Comment = `macOS Installation Media (FS1:)` (Your Comment/Any)
            -   Enabled = ` Yes`/`True`
            -   Flavour = `Disc:Disc` (Provided Icon Name)
            -   Name = `Install macOS 12` (Label)
            -   Path = `PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x0,0xFFFF,0x0)/HD(2,GPT,XFX5XEX0-XCX1-XAXA-X3X3-X4X3X3XCXAXF,0xX4X2X,0xX4X8X9X)/\System\Library\CoreServices\boot.efi` (Use OpenShell.efi to dump GUID path)
            -   TextMode = `No`/`False`
