# Zenith Hackers Intelligence — GitHub Pages

Upload `index.html` and the `assets` folder to the root of a GitHub repository.

## Publish
Repository → Settings → Pages → Deploy from branch → `main` → `/ (root)`.

The page is responsive and includes the screenshot-derived visual background, animated sections, WhatsApp floating button and a FormSubmit contact form.

Before publishing, verify that the phone number, email addresses, address, testimonials and success metrics are authorized and accurate for public use.


## Visitor consent prompt
The visitor prompt is now fully client-side:
- **Allow** immediately closes the popup, remembers the choice, and submits a basic visitor event to FormSubmit in a hidden iframe.
- **No thanks** immediately closes the popup and remembers the choice.
- The prompt will not appear again on that browser unless its local storage is cleared.

If FormSubmit has not yet been activated for `zenithintel@consultant.com`, the popup will still close correctly, but the email notification will not be delivered until the FormSubmit recipient is activated.
