# Unraid Glass Themes

> [!WARNING]
> **Beta Release**
>
> These themes are currently in **Beta**. Some areas of the Unraid WebUI or plugin pages may not be fully styled yet, and future Unraid updates may require CSS changes.

> [!NOTE]
> These themes have only been tested on **Unraid 7.3.x**.

Custom glass-style themes for the Unraid WebUI with matching **Purple** and **Red** variants.

These themes provide a modern translucent interface while preserving readability and the overall Unraid experience.

<img width="1708" height="1278" alt="image" src="https://github.com/TechLovin/Unraid-Themes/blob/main/Screenshot%202026-06-17%20190720.png?raw=true" />

<img width="1708" height="1275" alt="image" src="https://github.com/TechLovin/Unraid-Themes/blob/main/Screenshot%202026-06-17%20191045.png?raw=true" />

## Features

* Glass / frosted-glass dashboard widgets
* Transparent header and navigation
* Theme-colored dashboard controls and icons
* Themed server name gradient
* Themed Unraid logo tint
* Consistent spacing and widget styling
* Glass-styled table containers
* Docker widget transparency improvements
* Green active navigation indicator
* Matching Purple and Red theme variants


## Requirements

* Unraid 7.x
* Tested on Unraid 7.3.x
* Custom CSS plugin or another method of loading custom CSS
* A background image located at:

```text
flash/plugins/custom.css/assets/bg.jpg
```

If you use a different image location, update the CSS accordingly.

## Installation

1. Switch to the Dark Theme:  
   **Settings > Display Settings > Dynamix color theme: Black**

2. Install the **Custom CSS** plugin from **Community Apps**.

3. Copy the desired theme CSS file.

4. Paste the contents into your Custom CSS configuration in the **Black Theme** section.  
   **Do not paste it into Global.**

5. Save the configuration.

6. Refresh the Unraid WebUI.
## Custom Background

The themes expect a background image at:

```text
/plugins/custom.css/assets/bg.jpg
```

You can replace this with your own image by updating:

```css
body {
  background-image: url('/plugins/custom.css/assets/bg.jpg');
}
```

## Theme Variables

The following variables control most of the appearance:

```css
--custom-dashboard-tile-bg
--custom-dashboard-tile-border
--custom-dashboard-tile-shadow
--custom-dashboard-tile-blur

--custom-theme-accent
--custom-theme-accent-strong
--custom-theme-text
--custom-theme-icon
--custom-theme-icon-hover
```

Adjusting these values allows you to create additional color variants.

## Notes

* These themes are currently in Beta.
* The themes use modern CSS features including `:has()`.
* Tested primarily with Chromium-based browsers.
* Custom plugin pages may require additional styling depending on the plugin.
* Personal overrides are best kept in a separate CSS file so updates remain simple.

## License

MIT License

Feel free to modify, redistribute, and build upon these themes.
