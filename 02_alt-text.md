# Alt Text

## What it is

The `alt` text is read by the screen reader when it encounters an image element.

## How to use it

There's no need to start the `alt` text with "A picture of..." or "An image of...". That's already stated by the screen reader. Simply provide a brief but specific description of the image.

## If it isn't provided

If an `alt` attribute isn't provided then a screen reader will often read aloud the file name.

Generated file names for images that are user uploaded, for example, can be quite long and cryptic.

In those cases you should either require the user to include an image description (for the `alt` text) or provide one automatically when the image is uploaded and saved.

## When is it not necessary

If an image is purely decorative then leaving the `alt` attribute as an empty string (`alt=""`) will force the screen reader to skip over that image.

## ADDITIONAL RESOURCES:

- [WebAIM Accessible Images](https://webaim.org/techniques/images/)
- [WebAIM Alternative Text](https://webaim.org/techniques/alttext/)
