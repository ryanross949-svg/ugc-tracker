UGC Brand & Daily Post Tracker
A clean, simple, and offline-first web app for User Generated Content (UGC) creators to manage brand deals and track daily posting requirements. Built as a single HTML file, it requires no database and runs perfectly on GitHub Pages.

Status: ActiveType: Single FileHosting: GitHub Pages

✨ Features
Dynamic Brand Management: Add brand deals, input the required social handles, set the number of posts required per day, and toggle whether a brand requires verification before posting.
Granular Daily Checklist: Every required post generates a specific task block including:
📝 Warm-up (15m): 15 minutes of scrolling and engaging before posting.
✅ Verified: Check if the post was approved (only shows if the brand requires it).
🚀 Posted: The actual posting action.
📉 Wind-down (15m): 15 minutes of scrolling and engaging after posting.
Automatic Daily Reset: The app checks the date every minute. When midnight hits, the checklist automatically clears for the new day.
Live Progress Tracking: A banner at the top calculates your total daily tasks and updates in real-time. It turns green and celebrates when you are completely done for the day.
Local Auto-Save: Uses your browser's LocalStorage. Your brands and daily progress are saved automatically, so you never lose data if you close the tab or refresh the page.
🚀 How to Deploy on GitHub Pages
Create a Repository: Go to GitHub and create a new repository (e.g., ugc-tracker).
Add the File: Create a new file in the repository named index.html and paste the tracker code into it. Commit the file.
Enable Pages: Go to your repository's Settings > Pages.
Configure Source: Under the "Source" section, select the main (or master) branch and click Save.
Access Your Tracker: Wait a minute or two, and your tracker will be live at https://yourusername.github.io/ugc-tracker/.
(Tip: Bookmark this URL on your phone or computer browser for easy daily access!)

🛠️ Tech Stack
HTML5: Structure and layout.
CSS3: Modern dark-mode UI with responsive design (works on mobile and desktop).
Vanilla JavaScript: App logic, date tracking, and LocalStorage management.
📋 How to Use
Add a Brand: Type the brand name, the handles you need to tag, how many times you need to post today, and check the "Needs Verif." box if the brand requires approval.
Work Through the Day: Scroll down to "Today's Checklist". For every post, work through the 15-minute warm-up, get verified (if needed), post, and do your 15-minute wind-down.
Check Tasks: Click the checkboxes as you complete them.
Finish: Watch the banner at the top turn green when all tasks for all brands are completed!
Note: Because this app uses browser LocalStorage, your saved brands and daily progress are tied to the specific browser you are using. Clearing your browser data will reset your saved brands.
