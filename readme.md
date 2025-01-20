<a name="readme-top"></a>

# Template for Creating Chromium-based Web Browser Theme

> [!TIP]
>
> # :star: Star This Repository
>
> ### Give a star to this repository if you find it useful.

### Template repository for customizing your browsing experience by designing your unique Chromium-based web browser theme from scratch.

## List of Chromium-based Web Browsers

| Browser | Tested | Theme Supported | Browser Developer |
| --- | --- | --- | --- |
| [Google Chrome](https://www.google.com/chrome/) | :white_check_mark: | :white_check_mark: | Google |
| [Microsoft Edge](https://www.microsoft.com/en-us/edge) | :white_check_mark: | :white_check_mark: | Microsoft |
| [Ungoogle Chromium](https://github.com/ungoogled-software/ungoogled-chromium) | :white_check_mark: | :white_check_mark: | Slimjet |
| [Vivaldi](https://vivaldi.com/) | :red_circle: | :ballot_box_with_check: | Vivaldi Technologies |
| [Opera](https://www.opera.com/) | :red_circle: | :ballot_box_with_check: | Opera Software |
| [Brave](https://brave.com/) | :red_circle: | :ballot_box_with_check: | Brave Software |
|  |  |  |  |

> [!NOTE]
>
> ### This theme uses Manifest V3 to ensure compatibility with the latest Chromium extension standards.

## A sample of the `manifest.json` file containing all supported properties.

```json
{
  "author": "I am Programmer <contact@iamprogrammer.lk>",
  "description": "Chrome theme by I am Programmer",
  "icons": {
    "128": "image/store_icon_128x128.png"
  },
  "manifest_version": 3,
  "name": "Simple Theme",
  "short_name": "simple_theme",
  "theme": {
    "colors": {
      "control_background": [0, 0, 0],
      "control_button_background": [0, 0, 0],
      "background_tab": [0, 0, 0],
      "background_tab_inactive": [0, 0, 0],
      "background_tab_incognito": [0, 0, 0],
      "background_tab_incognito_inactive": [0, 0, 0],
      "bookmark_text": [0, 0, 0],
      "button_background": [0, 0, 0],
      "frame": [0, 0, 0],
      "frame_inactive": [0, 0, 0],
      "frame_incognito": [0, 0, 0],
      "frame_incognito_inactive": [0, 0, 0],
      "ntp_background": [0, 0, 0],
      "ntp_header": [0, 0, 0],
      "ntp_link": [0, 0, 0],
      "ntp_link_underline": [0, 0, 0],
      "ntp_text": [0, 0, 0],
      "ntp_section": [0, 0, 0],
      "ntp_section_link": [0, 0, 0],
      "ntp_section_link_underline": [0, 0, 0],
      "ntp_section_text": [0, 0, 0],
      "omnibox_background": [0, 0, 0],
      "omnibox_text": [0, 0, 0],
      "tab_background_text": [0, 0, 0],
      "tab_background_text_inactive": [0, 0, 0],
      "tab_background_text_incognito": [0, 0, 0],
      "tab_background_text_incognito_inactive": [0, 0, 0],
      "tab_text": [0, 0, 0],
      "toolbar": [0, 0, 0],
      "toolbar_button_icon": [0, 0, 0],
      "toolbar_text": [0, 0, 0]
    },
    "images": {
      "theme_frame": "images/theme_frame.png",
      "theme_frame_inactive": "images/theme_frame_inactive.png",
      "theme_frame_incognito": "images/theme_frame_incognito.png",
      "theme_frame_incognito_inactive": "images/theme_frame_incognito_inactive.png",
      "theme_frame_overlay": "images/theme_frame_overlay.png",
      "theme_frame_overlay_inactive": "images/theme_frame_overlay_inactive.png",
      "theme_toolbar": "images/theme_toolbar.png",
      "theme_ntp_background": "images/theme_ntp_background.png",
      "theme_tab_background": "image/theme_tab_background.png",
      "theme_tab_background_incognito": "images/theme_tab_background_incognito.png",
      "theme_tab_background_inactive": "images/theme_tab_background_inactive.png",
      "theme_tab_background_incognito_inactive": "images/theme_tab_background_incognito_inactive.png",
      "theme_ntp_attribution": "images/theme_ntp_attribution.png",
      "theme_button_background": "images/theme_button_background.png",
      "theme_window_control_background": "images/theme_window_control_background.png"
    },
    "tints": {
      "background_tab": [0, 0, 0],
      "buttons": [0, 0, 0],
      "frame": [0, 0, 0],
      "frame_inactive": [0, 0, 0],
      "frame_incognito": [0, 0, 0],
      "frame_incognito_inactive": [0, 0, 0]
    },
    "properties": {
      "ntp_background_alignment": "bottom",
      "ntp_background_repeat": "repeat",
      "ntp_logo_alternate": 1
    }
  },
  "version": "1.0.0",
  "version_name": "simple_theme_v1.0.0"
}
```

> [!IMPORTANT]
>
> ### Chromium has discontinued the use of "ntp_section," but it still utilizes it as a fallback option for "ntp_header" in order to support legacy themes.
>
> ```
> {
>  "theme": {
>    "colors": {
>      "ntp_section": [0, 0, 0],
>    }
>  }
> }
> ```

Please remove all unused properties from the `manifest.json` file. If you use `images`, make sure that the image file exists at the path and that the image dimensions are correct.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# :toolbox: Resource

- The list of properties supported by the Chromium browser has been extracted from this source.

  - https://source.chromium.org/chromium/chromium/src/+/main:chrome/browser/themes/browser_theme_pack.cc

- Theme Creation Guide By Patrick Batenburg

  - https://github.com/Patrick-Batenburg/GoogleChromeThemeCreationGuide

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# :two_hearts: Credits

- I am Programmer [@iamprogrammerlk](https://github.com/iamprogrammerlk)

  > [iamprogrammer.lk](https://iamprogrammer.lk) | [contact@iamprogrammer.lk](mailto:contact@iamprogrammer.lk) | [x.com/iamprogrammerlk](https://x.com/iamprogrammerlk) | [youtube.com/@iamprogrammerlk](https://youtube.com/@iamprogrammerlk)

- [Contributors](/../../graphs/contributors)

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# :sparkles: Get Involved

Get in touch with the project developers and the community through our [GitHub Discussions](/../../discussions) forum. View [contributing.md](/contributing.md) for information.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# :fire: Issues

Bug reports and feature requests can be submitted on the [Github Issues](/../../issues).

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# :thumbsup: Code of Conduct

This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Code of Conduct](/code_of_conduct.md), [Security Policy](/security.md), and be bound by the terms of the [Contributor License Agreement](/contributor_license_agreement.md).

> [!IMPORTANT]
>
> ### This project is not a platform for discussing politics, social issues, race, religion, gender, or sexual orientation. Please keep those discussions elsewhere.

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# :balance_scale: License

### This work is distributed under the [MIT License](https://choosealicense.com/licenses/mit/) License. See [license](/license.md) for more information.

### Permissions

- :white_check_mark: Commercial use
- :white_check_mark: Distribution
- :white_check_mark: Modification
- :no_entry: ~~Patent use~~
- :white_check_mark: Private use

### Conditions

- :no_entry: ~~Disclose source~~
- :white_check_mark: License and copyright notice
- :no_entry: ~~Network use is distribution~~
- :no_entry: ~~Same license~~
- :no_entry: ~~State changes~~

### Limitations

- :x: Liability
- :no_entry: ~~Trademark use~~
- :x: Warranty

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

# :copyright: Copyright

- Copyright © 2025 :sri_lanka: I am Programmer [@iamprogrammerlk](https://github.com/iamprogrammerlk).
- Copyright © 2025 :heart: [Contributors](/../../graphs/contributors).

<br>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

---
