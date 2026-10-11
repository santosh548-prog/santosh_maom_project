MAOM ACTIVITIES WEBSITE — QUICK START

1. Open index.html in a browser to preview the site.
2. To edit the site, open index.html in a text editor (VS Code, Notepad, etc.).
3. Near the bottom, find `const siteData = { ... }`.
4. Edit:
   - brand, eyebrow, title, intro, group, footer
   - members: change the sample names
   - activities: change title, description, date, and link URL
5. Save and refresh the browser.

To add an activity, add another object inside the activities array, separated by a comma:
{
  title: "Reflection",
  description: "Our group's reflection activity.",
  date: "10 Oct 2026",
  links: [
    { label: "Open video", url: "https://www.youtube.com/" }
  ]
}

To publish it free using GitHub Pages:
1. Sign in to GitHub and create a new repository.
2. Upload index.html (you can upload this file directly; README is optional).
3. In repository Settings > Pages, choose deploy from the main branch and root folder.
4. Save and wait for GitHub Pages to publish the site.

This is an original layout and starter template. Replace sample content and use your own group details and links.
