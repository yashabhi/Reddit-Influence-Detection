# Community and Influence Detection Using Reddit Dataset

## Project Overview
This project analyzes community structures and influential users within Reddit subreddits using data from the Reddit API. It focuses on the 'AskReddit' subreddit, employing network analysis techniques to identify communities and key influencers.

## Features
- Data collection from Reddit using PRAW (Python Reddit API Wrapper)
- Network construction and analysis using NetworkX
- Community detection using the Louvain method
- Influencer identification using PageRank algorithm
- Interactive network visualization with Pyvis

## Requirements
- Python 3.x
- PRAW
- NetworkX
- Python-louvain
- Pyvis

## Installation
1. Clone the repository
   git clone https://github.com/your-username/repository-name.git
2. Install required packages:
   pip install praw networkx python-louvain pyvis

## Usage
1. Set up Reddit API credentials in the script
2. Run the main script:
  python reddit_network_analysis.py

3. View the generated HTML file for interactive network visualization

## Key Components
- Data collection from 'AskReddit' subreddit
- Network construction with users as nodes and interactions as edges
- Community detection using Louvain method
- Influencer identification using PageRank
- Interactive visualization of the network

## Results
- Identifies top influencers in the subreddit
- Reveals community structures within the network
- Generates an interactive HTML visualization

## Future Improvements
- Expand data collection to multiple subreddits
- Implement real-time analysis
- Integrate additional influence metrics
- Apply NLP for content analysis
## Authors
- Yashwanth Gudivada

## Acknowledgments
- Reddit API and PRAW documentation
- NetworkX and Pyvis libraries
- Louvain method for community detection
