## Installation

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
3. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Move the `chrome` folder into the directory.
5. Make all the customizations you want [here](#-customization).
6. Enjoy!

## Usage

This userstyle was made for a keyboard centered usage, like Tilling Window Manager users or just cool people that loves them! Use the following for a better experience:

-   `Alt` You can access to the global menu for an extended options you need
-   `Alt + Left Arrow` You can go Back
-   `Alt + Right Arrow` You can go Forward
-   `Ctrl + L` focuses the Navbar
-   `Ctrl + B` shows you the Bookmarks 
-   `Ctrl + H` shows you the History Bar
-   `Ctrl + T` Opens a new Tab
-   `Ctrl + W` Closes a Tab
-   `Ctrl + Shift + T` Re-opens a tab that you just closed
-   `Ctrl + R` Refresh the page you're on
-   `Ctrl + Shift + A` Quick open for Add-Ons

## Customization

All the configuration will be managed in the `userChrome.css` file. And also all the code is commented so you can easily change values and colors as you like.

### Colors

In this section of the code you can change the colors, there's a window color and a tabs / urlbar color. 

```css

:root {
  --sfwindow: #101010;
  --sfsecondary: #222222;
}

```


### My settings

- Install the [SimpleFox](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox/) add on theme.
- Install the [Tabliss](https://addons.mozilla.org/en-US/firefox/addon/tabliss/) new tab add on.
