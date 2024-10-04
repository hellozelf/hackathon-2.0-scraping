# Develop a Scraping System that Scrapes Social Media

As a dynamic research team, we're diving into the fascinating world of social media
posts. We're diving deep into social media posts, their success, and how they affect
society. Since we can't get much data directly from social media sites, we're going
to collect it ourselves. That's where you come in as our Scraping Engineer. Your job
is to create a clever system that can gather social media data, working around any
roadblocks. Let's get scraping!

We are looking to identify the leading influencers in the tourism industry to engage with them in promoting the new brand we are currently partnering with.

## Project Objective

The aim of this project is to develop a scraping system that collects data from TikTok, based on specified keywords and hashtags, and then analyzes that data to identify top influencers in the tourism industry. The project includes key features such as keyword & hashtag scraping, profile information scraping, and influencer identification.

## Core Features

### 1. Keyword & Hashtag Scraping
- Scrape TikTok posts based on the following keywords:
  - `beautiful destinations`
  - `places to visit`
  - `places to travel`
  - `places that don't feel real`
  - `travel hacks`
- Scrape TikTok posts based on the following hashtags:
  - `#traveltok`, `#wanderlust`, `#backpackingadventures`, `#luxurytravel`, `#hiddengems`, `#solotravel`, `#roadtripvibes`, `#travelhacks`, `#foodietravel`, `#sustainabletravel`

### 2. Extract and save the following data from each TikTok post:
  - `video_url`
  - `video_caption`
  - `author_username`

### 3. Collect and save Author Information
- For each post found during the keyword & hashtag scraping, collect the following Author's information:
  - `username`
  - `follower_count`
  - `following_count`
  - `like_count`

### 4. Identify and save Influencers Information
- Analyze the collected data to identify top influencers who meet the following criteria:
  - Have at least **100k followers**.
  - Have received over **1 million likes**.

### 5. Robust Data Storage
- Data storage solutions can vary from simple file storage (e.g., CSV, JSON) to more complex database management systems (e.g., SQL, NoSQL).
- Flexibility in choosing the storage method allows the developer to design the schema based on their own preferences and project scale.
 

## Bonus Features

### 1. Engagement Script
- A script that accepts a TikTok video URL as input and allows you to:
  - **Like** the video.
  - **Post a comment** on the video.
- Note: For this feature, the user must be logged in (login does not need to be automated).

### 2. Engagement Verification: 
-Develop a mechanism to verify whether your automated comments were successfully posted, using your own comment scraper to check for the presence of your comments.

## Language and Tools
-  Python solutions are preferred, you are free to use any programming language, tools, or libraries to build a robust data collection solution.
-  If choosing a non-Python approach, please be prepared to explain your choice.

## Evaluation Criteria
- **Feature Implementation:** The primary focus is on how effectively each feature has been implemented, covering both scraping functionality and data handling.
- **Code Quality:** Writing clear, maintainable, and efficient code is essential. Proper comments, concise functions, and well-organized modules are expected.
- **Optimizations:** Any smart optimizations that improve scraping performance, such as handling rate limits, efficient data storage, and error-handling strategies, will be considered highly.
- **scalable solution:** A scraper that is efficient in CPU and memory usage, capable of handling large volumes of data.
- **Bonus Features:** While bonus features are appreciated, the core functionality must be completed before attempting bonus tasks.
- **Mobile App Scraping:** Scraping from the official TikTok app is encouraged, but that doesn't mean a poorly written app scraper will be prioritized over a well-optimized web scraper.

## Submit the Project
- Create a public github repository and push all the codes to that repository including any sql/csv files you have.
- Send the github repo link to scraping@zelflive.com email address


