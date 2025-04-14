# Building AI Agents

🍷 Wine & Whiskey is an AI-powered sommelier that helps users discover ideal wine or whiskey pairings based on their dinner menu. Built with a no-code approach using Mind Studio, the tool allows users to upload meal plans and receive curated pairing suggestions, making entertaining and dining experiences more refined and enjoyable.

Overview
This project explores the use of no-code tools to build an AI-powered assistant that suggests wine pairings for dinner menus. Developed using Mind Studio, the application leverages modern no-code capabilities to offer practical solutions without traditional software development.

🔧 Original Goal
The initial objective was to scrape restaurant menus online and automatically recommend wine pairings using AI. To achieve this, the Firecrawl web scraper was integrated to collect menu data from restaurant websites.

🚧 Challenges Encountered
While Firecrawl successfully scraped data, converting the extracted content into usable JSON through automation tools proved unreliable. Formatting issues and inconsistent outputs prevented the integration of the scraped data with the AI model, ultimately leading to a pivot in the project's direction.

🔄 Project Pivot & Current Status
To overcome these challenges, the project shifted focus from automated scraping to a more controlled input method: allowing users to upload their own dinner party menus. The AI then analyzes this text to provide wine pairing suggestions. This pivot:

Reduced dependency on external data sources

Simplified the workflow

Ensured functionality within the submission timeline

At this stage, the restaurant scraping component has been paused in favor of delivering a functional, user-ready experience via the revised upload-based model.

✅ Tools Used
Mind Studio – No-code AI development platform

Firecrawl – Web scraper (experimental phase)

JSON Parsers & Automation Tools – For attempted data processing

📌 Next Steps
Further development post-submission may include:

Revisiting web scraping with more reliable parsing methods

Adding visual pairing suggestions or interactive UI

Expanding food categories beyond dinner party menus

## 🎥 Demo Video

Watch the demo on YouTube: Wine & Whiskey: Your Personal Sommelier (https://youtu.be/vqJk-dEdzCM)
