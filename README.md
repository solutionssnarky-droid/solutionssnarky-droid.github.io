Snarky Solutions 🔥
Real Talk. No Filter. Actionable.

Sharp, honest takes on work, career growth, geopolitics, finance, AI, and the messy middle of modern professional life — written for people who prefer useful insight over empty advice.

🌐 Live site: https://solutionssnarky-droid.github.io/

How the blog archive works
The homepage (index.html) automatically discovers standalone .html article files in the repository root using the GitHub API. It then reads each article's HTML metadata to display its title and description, and links each entry directly to the post.

This means new root-level HTML posts are included automatically after they are pushed to the main branch. You do not need to manually add a row to the homepage or maintain a separate list in this README.

index.html — homepage, featured article, searchable archive, and about section.
*.html in the repository root — individual published articles.
README.md — repository guide.
Publishing a new article
Create the article as a standalone .html file.
Add a meaningful <title> tag. For the best homepage description, include a <meta name="description" content="..."> tag in the article's <head>.
Upload the file to the repository root and commit it to main.
Wait for GitHub Pages to publish the change, then refresh the homepage.
Important: Keep article files in the repository root if you want the homepage's automatic archive to discover them. The homepage excludes index.html so it is not listed as an article.

Topics
Professional growth, leadership, and self-awareness
Indian geopolitics and global shifts
Personal finance, markets, and economic change
AI, technology, and the future of work
Operations, governance, and practical workplace lessons
Design
The site uses a dark editorial style with Fraunces headings, Plus Jakarta Sans body text, and DM Mono labels.

Token	Value
Background	#111013
Surface	#18151c
Coral accent	#FF6B6B
Yellow accent	#FFD93D
Lavender accent	#C4AAFF
Pink accent	#FF80C8
Text	#F0EBF8
Deployment
The site is intended for GitHub Pages from the main branch, using the repository root as the publishing source. The automatic archive reads the public GitHub repository and raw HTML article files in the browser; if the GitHub API is temporarily unavailable or rate-limited, the archive will display a link to the repository instead.

About
Snarky Solutions covers professional growth, Indian geopolitics, personal finance, and AI's real-world impact with a direct, peer-to-peer voice: no hype, no preaching, and no empty motivation.

© 2026 Snarky Solutions · Kolkata, India