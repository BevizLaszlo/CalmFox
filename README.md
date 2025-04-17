<h1 align=center>CleanTheme - Firefox</h1>

![ftheme](https://github.com/user-attachments/assets/e05444fd-e5f3-4d46-8b7a-53c2ff07cb2e)

## Features

* **Purple Private Browsing**
* **Homepage Color:** home page is slightly recolored based on your system's preferred color scheme (light or dark).
* **Centered URL Bar**
* **UI Adjustments:** Minor tweaks are included to hide unnecessary elements like the "All Tabs" button.

## Installation

To install this theme, simply copy the `chrome` folder included in this repository to your Firefox profile directory. Follow these steps:

1.  **Open Firefox Profile Directory:**
    * In Firefox, type `about:support` in the address bar and press Enter.
    * Under the "Application Basics" section, find the "Profile Directory" row.
    * Click the "Open Directory" button (or "Show in Finder" on macOS). This will open your Firefox profile folder in file manager.

2.  **Copy the `chrome` Folder:**
    * Copy the entire `chrome` folder from this repository into your Firefox profile directory.

3.  **Enable CSS Modifications:**
    * In Firefox, type `about:config` in the address bar and press Enter.
    * Click "Accept the Risk and Continue".
    * In the search bar, type `toolkit.legacyUserProfileCustomizations.stylesheets`.
    * Toggle the value to `true` by clicking the toggle button next to it.

4.  **Restart Firefox:**
    * Close and restart Firefox for the changes to take effect.

## Customization

You can further customize the colors by modifying the `--dark-purple`, `--purple`, and `--light-purple` variables at the beginning of the `userChrome.css` file within the `chrome` folder. Experiment with different hex color codes to achieve your desired look.

## Contributing

Feel free to contribute to this theme by submitting pull requests with improvements or bug fixes.
