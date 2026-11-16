# Kendra Cooke

Personal site. One page, no build step. GitHub Pages serves `index.html` from the main branch.

## Turning on the contact form

The Selected work and Email links open a form. To send it to your inbox:

1. Create a free form at formspree.io with the email you want messages to go to.
2. Copy the form's endpoint, which looks like `https://formspree.io/f/abcdwxyz`.
3. In `index.html`, search for `FORM_ENDPOINT=''` and paste the endpoint between the quotes.

Your email address never appears in the page.
