# Claude Prompt

Put photos of your two sketches in the `sketches` folder first. Then copy everything below the line into the Claude Code panel in VS Code and fill in every [bracket]. Type `@` to point Claude to a file.

---

I'm an interaction design student.
My hand-drawn sketches of a homepage and detail page are @sketches/[homepage photo] and @sketches/[detail page photo]. They're for a website that archives 41 observations of play at Northeastern University. Please replace @index.html with my website, built as a working web page, and keep all the code in that one file. Don't change anything in the data or photos folders.

**The Data**
All 41 entries the site must include are in @data/play-time-database.csv. Use only this data. Don't invent entries, fields, or details. Every entry must appear on the homepage. Show each entry's photo using the path in its photo column, for example photos/row-02.jpg. Row 26 also has a video in its video column, and row 17 has no photo.

**My Sketches: Homepage**
I organized the homepage primarily by [Location / Alphabet / Time / Category / Hierarchy], combined with [second one, if any].

- Please include my definition: [your definition]
- Colors: [e.g., green = Curiosity, orange = Challenge]
- Typefaces: [a superfamily from Google Fonts, e.g., IBM Plex Sans + IBM Plex Serif]
- Size or position means: [e.g., bigger circles = more people playing]
- What you can tap/click: [e.g., each circle opens that entry's detail page; tapping a color in the legend highlights only those entries; tapping "By time" rearranges the cards into a timeline]

**My Sketches: Detail page**
When someone clicks an entry, show a detail page with: [list the fields you want, e.g., name, date, place, description, the Insight quote]. Include a way back to the homepage.

**Design**
Don't design it for me.
Match the layout of my sketches as closely as you can.
Default colors to black, white, and gray unless I indicate otherwise.
Make it mobile friendly: the layout should work on a phone screen, with text readable without zooming and tap targets big enough for a finger.
Don't add hover effects or tooltips. Everything should work by tapping or clicking, and nothing should be hidden behind a hover.
Follow usability and accessibility best practices.
If something in my sketches is unclear, tell me what you assumed instead of guessing silently.
