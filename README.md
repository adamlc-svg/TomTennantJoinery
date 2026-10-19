# Tom Tennant Carpentry

A simple one-page website for Tom Tennant Carpentry. Open `index.html` in a browser to view it.

## Choosing a style
A **"Try a style"** panel sits in the bottom-right corner. It switches between 5 wood-themed colour schemes and 3 friendly fonts:

| Colour scheme | Feel |
|---|---|
| Light Oak | Warm pale oak, brown accents, sage green |
| Dark Walnut | Dark and rich, copper accents |
| Pine & Forest | Pale pine with forest green |
| Red Cedar | Warm reddish timber tones |
| Ash & Charcoal | Pale ash with charcoal, more modern |

Fonts: Fraunces + Nunito (soft serif headings), Nunito (rounded all over), Quicksand + Nunito (light and round).

Once a choice is made: set `data-palette` and `data-font` on the `<html>` tag, then delete the `#picker` block and the unused palettes.

## Adding photos
Every grey-brown wood-grain box is a photo placeholder. Put the photo in `images/`, then add it to the box, e.g.

```html
<div class="photo" style="--img:url(images/kitchen-1.jpg)"><span class="tag">Photo</span></div>
```

The "Photo" label hides itself automatically once an image is set.

## Still to fill in
Anything in `[square brackets]` or shown as `XX`: town, years of experience, qualifications, phone, email, social media links (currently point to the sites' home pages) and real customer reviews (the current ones are marked as examples).
The quote form is not connected to an inbox yet. A service such as Formspree or Netlify Forms can do this later.
