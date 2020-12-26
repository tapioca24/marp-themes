# marp-themes

This is the marp theme for tapioca24.

## Usage for Marp for VS Code

Add the following code to your `setting.json`.

```js
{
  "markdown.marp.themes": [
    "https://tapioca24.github.io/marp-themes/tapioca24.css"
  ]
}
```

Then start the slide with the following code.

```md
---
marp: true
theme: tapioca24
---
```

## Utility Classes

There are several utility classes that can be used to enrich the presentation of slides.

| Class         | Description                                                                                 |
| ------------- | ------------------------------------------------------------------------------------------- |
| `text-center` | Align all content to the center.                                                            |
| `text-<size>` | Increase the font size.<br>The `size` can be specified in intervals of 25 from 125 to 1000. |

Give the class to only the desired page by writing the following in the slide.

```html
<!-- _class: text-center text-125 -->
```
