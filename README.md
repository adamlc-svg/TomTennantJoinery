# Tom Tennant Carpentry

One-page website for Tom Tennant Carpentry, a carpenter and joiner in Hull, East Yorkshire. Open `index.html` in a browser to view it. Photos and the logo are in `images/`.

All details on the site come from Tom's answers in `tom-answers.txt`.

## Still to do
- **Facebook link:** it currently points to facebook.com/tomtenantjoinery (as given, with one N). Check the exact link with Tom.
- **Reviews:** the reviews section is hidden until Tom has real reviews (Google Business profile recommended).
- **Photo of Tom:** the About section uses a timber roof photo until there is one.
- **Website address:** none yet. tomtennantcarpentry.co.uk is worth checking.
- **Style panel:** the "Try a style" box (bottom right) is for choosing colours and fonts. Remove the `#picker` block once decided.

## Adding or swapping photos
Put the photo in `images/` and set it on a box, e.g.
`<div class="photo" style="--img:url(images/new-job.jpg)"></div>`

## Quote form
There's no server, so pressing "Send request" opens the visitor's email app with their details filled in, addressed to tomtennantcarpentry@gmail.com.
