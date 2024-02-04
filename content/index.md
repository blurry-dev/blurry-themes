+++
"@type" = "WebSite"
name = "Blurry Themes"
abstract = "A demo site for Blurry themes"
datePublished = 2024-02-09
dateModified = 2024-02-10
+++

# Blurry themes

A demo site and testing ground for themes for [Blurry](https://github.com/blurry-dev/blurry), a static site generator.

## How to use a Blurry theme

The themes are available here:

1. Clone the `blurry-themes` repo (<https://github.com/blurry-dev/blurry-themes>):

    ```bash
    git clone git@github.com:blurry-dev/blurry-themes.git
    ```

2. Try out the different themes by editing the `templates_directory_name` setting in `blurry.toml`, or by passing the equivalent environment variable to `blurry runserver`:

    ```bash
    BLURRY_TEMPLATES_DIRECTORY_NAME=themes/pico blurry runserver
    ```

3. Once you find a theme you like, copy its folder into your project at the path that matches your site's `TEMPLATES_DIRECTORY_NAME` setting, which defaults to `templates`.

---

## Demo

Below is a quick demonstration of how common Markdown elements appear with this theme.

### Typography

These should all look great:

1. **Bold text**
1. _Italics_
1. ~~Strikethroughs~~
    - Indented list items

### Code

#### Inline

Inline `code` and <kbd>kbd</kbd> tags should be <kbd>=</kbd>ly easy on the eyes.

#### Block

```html
Block code should work <strong>well</strong>, too.
```

### Tables

| Blurry repo                                                                                    | Type   | Stars |
| ---------------------------------------------------------------------------------------------- | ------ | ----- |
| [blurry](https://github.com/blurry-dev/blurry)                                                 | CLI    | 10+   |
| [blurry-plugin-blur-blurry-name](https://github.com/blurry-dev/blurry-plugin-blur-blurry-name) | Plugin | 0     |

### Images

Images are responsive out-of-the-box so they stay in-the-box if the box is a browser's viewport:

![Photo by Marek Piwnicki on Unsplash](./images/marek-piwnicki-jjNcP78A8XE-unsplash.jpg)
