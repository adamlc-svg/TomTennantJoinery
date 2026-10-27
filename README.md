# Tom Tennant Carpentry

One-page website for Tom Tennant Carpentry, a carpenter and joiner in Hull, East Yorkshire. Open `index.html` in a browser to view it. Photos and the logo are in `images/`.

All details on the site come from Tom's answers in `tom-answers.txt`. Colours: Dark Walnut. Font: Plus Jakarta Sans.

## Still to do
- **Reviews:** the reviews section is hidden until Tom has real reviews (Google Business profile recommended).
- **Photo of Tom:** the About section uses a timber roof photo until there is one.
- **Website address:** none yet. tomtennantcarpentry.co.uk is worth checking.

## Adding or swapping photos
Put the photo in `images/` and set it on a box, e.g.
`<div class="photo" style="--img:url(images/new-job.jpg)"></div>`

## Quote form
The form sends requests through FormSubmit (formsubmit.co) to tomtennantcarpentry@gmail.com. No account needed.

To switch it on:
1. Put the site online (e.g. drag this folder onto app.netlify.com/drop).
2. Send one test request through the form on the live site.
3. Tom opens the "Activate" email from FormSubmit (check spam/promotions) and clicks Activate Form.
4. Send another test. From then on every request goes straight to Tom.

After sending, customers come back to the page and see a thank-you message.
