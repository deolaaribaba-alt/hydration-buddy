# Hydration Buddy

This is a static, single-page browser app. Open `index.html` locally, or publish this folder to a static site host to share it. When hosted over HTTPS, browsers that support installable web apps can offer an **Install app** button. On iPhone/iPad, use Safari's Share menu and choose **Add to Home Screen**.

## Reminders and offline use

Choose a reminder interval and active hours in the Reminders card, then select **Start reminders**. Nudges run only while the page is open. Browser notifications are optional and require browser permission; closing the page pauses reminder timing. The app shell can load offline after its first successful visit, but weather lookups need an internet connection.

## Publish with Netlify Drop

1. Sign in to Netlify and open its manual deploy page: https://app.netlify.com/drop
2. Drag the `hydration-buddy-site` folder onto the deploy area.
3. Netlify will provide an HTTPS link you can share.

The app has no server or account system. Drink logs, goals, and reminder preferences stay in each visitor's browser storage on that device. City searches go to Open-Meteo. Browser speech recognition may process microphone audio through the browser's recognition service; voice is optional. Review the privacy notice in the app before sharing it broadly.

## Health guidance

Hydration targets are general guidance, not a medical plan. Visitors should use targets or fluid limits set by their own healthcare team.
