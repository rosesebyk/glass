# Prem Delivery AI

Prem Delivery AI is a lightweight hackathon demo for smarter last-mile delivery.

It showcases:

- Delivery risk scoring before dispatch
- QR GatePass support for gated communities
- AI-guided delivery actions and timing suggestions
- A simple interactive demo flow in the browser

## Project Structure

This project is a static site with a single entry file:

- `index.html` - full UI, styles, and demo logic

## Run Locally

Because this is a static HTML project, you can open it directly in a browser.

Option 1:

- Double-click `index.html`

Option 2:

- Right-click `index.html`
- Open it in Chrome, Safari, or another browser

## Deploy For Hackathon Submission

The fastest way to get a public link is Netlify Drop.

### Netlify Drop

1. Go to `https://app.netlify.com/drop`
2. Drag `index.html` onto the page
3. Netlify will generate a public URL instantly
4. Use that URL as your hackathon submission link

### GitHub Pages

If you want a more permanent link:

1. Push this folder to a GitHub repository
2. Open the repository on GitHub
3. Go to `Settings > Pages`
4. Under source, choose `Deploy from a branch`
5. Select the main branch and `/ (root)`
6. Save and wait for the site URL to be generated

## Demo Flow

The page presents a delivery operations concept:

1. A risk score is calculated before dispatch
2. The system recommends a delivery action
3. A QR GatePass can be generated for gated access
4. The driver completes delivery with fewer delays

Use the `Start Demo` or `Run Demo Scenario` buttons to show the interactive flow.

## Notes

- This is a front-end demo and does not include a backend
- The PDF download button is currently a placeholder
- The site is mobile-friendly and works as a single-page demo
