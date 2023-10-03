#NerdFont
https://www.nerdfonts.com/font-downloads

Font: MesoloLG

## Installing a Nerd Font on Ubuntu involves a few steps. Below is a guide on how to do it.


 **Install the Font**: You can install the font for your user or system-wide.
to unzip the downloaded font folder
 ```bash
unzip filename.zip -d /path/to/output/directory/

```

    - For your user only:
        ```bash
        mkdir -p ~/.local/share/fonts
        cp /path/to/your/font.ttf ~/.local/share/fonts/
        ```

    - System-wide:
        ```bash
        sudo cp /path/to/your/font.ttf /usr/local/share/fonts/
        ```

 **Update Font Cache**: Update the font cache using `fc-cache`.

    ```bash
    fc-cache -fv
    ```

 **Set the Font in Your Terminal**: Open the preferences/settings of your terminal and set the newly installed font as the default.
