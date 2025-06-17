# Armygrid User Behavior Analysis

## Project Overview
This project analyzes user behavior in the Armygrid web-based MMO game, focusing on the current game server. The goal is to uncover insights about user engagement and identify points where players may stop playing. The analysis uses data from `user.json` (player data and game progression) and `chats.json` (user messages) to examine player activity and sentiment.

## Repository Structure
- **armygrid.ipynb**: The main Jupyter Notebook containing the analysis code, including data loading, cleaning, processing, sentiment analysis, and visualization.

## Used libraries
- pandas
- numpy
- matplotlib
- nltk
- textblob
- wordcloud
- scipy

## Key Findings
- The analysis identifies the total number of players on the current server and examines user retention from previous servers.
- Sentiment analysis of chat messages highlights words like "hard" and "impossible," suggesting potential difficulty in game elements such as the Maze.
- The notebook provides insights into user engagement patterns and potential drop-off points.