This repository contains an Instagram Bot created using Selenium to automate various tasks such as following/unfollowing profiles, liking/unliking posts, extracting followers, and analyzing the habits of food bloggers. The bot is designed to help users grow their Instagram presence by automating repetitive tasks. The project includes code to login, search, follow/unfollow, like/unlike posts, extract followers, check stories, and perform data analysis on Instagram handles.


## Overview
This project is an Instagram Bot created using Selenium to automate various tasks on Instagram. The bot can help users grow their Instagram presence by automating repetitive tasks such as following/unfollowing profiles, liking/unliking posts, extracting followers, and analyzing the habits of food bloggers.

## Technologies Used:
Selenium for web automation.
Python for scripting and data analysis.
Matplotlib for data visualization.

## Features
- **Login to Instagram**: Automate the login process using provided credentials.
- **Search and Print Handles**: Search for "food" and print all Instagram handles (excluding hashtags).
- **Profile Interaction**:
  - Open and follow/unfollow the profile "So Delhi".
  - Like/unlike the top 30 posts of "dilsefoodie".
- **Extract Followers**: Extract the first 500 followers of "foodtalkindia" and "sodelhi".
- **Story Check**: Check and view the story of "coding.ninjas" based on certain conditions.
- **Data Analysis**:
  - Analyze the top 10 handles from the "food" search based on followers.
  - Count the number of posts made by these handles in the last 3 days.
  - Scrape and analyze hashtags from the top 10 posts of selected handles.
  - Calculate the followers-to-likes ratio and depict it using a bar graph.


## Usage
1. **Login to Instagram**:
    - Update the `username` and `password` fields with your credentials in the code (use "SAMPLE USERNAME" and "SAMPLE PASSWORD" before submission).
2. **Run the Bot**:
    - Execute the script to perform the desired tasks such as searching, following/unfollowing, liking/unliking posts, extracting followers, and checking stories.
3. **Data Analysis**:
    - Use the provided functions to analyze the habits of food bloggers, scrape hashtags, and calculate the followers-to-likes ratio.

