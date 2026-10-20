# Robotronics Robo Rescue

A lightweight, static robotics mini-game for Vercel.

## Deploy
1. Upload this folder to a GitHub repository.
2. Import the repository in Vercel.
3. Use the default framework preset or select Other. No build command is required.
4. Keep `index.html` at the project root so Vercel serves it as the site homepage.

## Configured links
- Instagram: https://www.instagram.com/robotronics._iet/
- Study material: https://drive.google.com/drive/folders/1H53FxRYLJtf9GjnzqeesAvj4j2BJQqut?usp=sharing

## Analytics
The game emits events for game starts, answers, completions, Instagram clicks, and study material clicks. Events are only sent to Google Analytics if a GA4 Measurement ID is configured in `CONFIG.gaMeasurementId`. Without that, events appear only in the browser console and are not collected across visitors.

Instagram follows cannot be verified by a website click. A click to a Google Drive link does not confirm that a file was downloaded.
