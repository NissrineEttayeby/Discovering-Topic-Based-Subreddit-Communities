# Discovering Topic-Based Subreddit Communities

## Overview

This project focuses on the discovery and analysis of topic-based communities within Reddit, a popular social media platform composed of various subreddits (community-specific forums). By employing natural language processing (NLP) techniques and network analysis, this project aims to uncover clusters of subreddits that revolve around similar themes or topics.

## Motivation

Reddit hosts an immense amount of diverse content spanning numerous topics, making it an invaluable resource for exploring various interests and discussions. However, navigating through this vast sea of subreddits can be challenging, especially for users looking to discover new communities related to their interests. This project addresses this challenge by providing insights into the thematic connections between different subreddits, thereby facilitating the exploration and discovery of topic-based communities.

## Features

- **Thematic Community Detection**: Applying community detection techniques to identify cohesive clusters of subreddits sharing similar topics. Additionally, the same methodology has been applied to the network of authors, revealing cohesive clusters based on the thematic structure of their contributions.
- **In-Depth Analysis of Community Characteristics**: Detecting the most popular topics and authors within each community.
- **Identification of Thematic Overlaps**: Exploring potential overlaps between different communities, revealing thematic intersections and links between discussed topics.
- **Intuitive Visualization**: Creating a visual representation of the identified communities using NetworkX, enabling users to grasp the relationships between subreddits and authors effortlessly.
- **Evaluation of the Effectiveness of Techniques Used**: Assessing the performance of chosen community detection and topic modeling techniques to ensure the reliability of results.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**: Clone this GitHub repository to your local machine.
   ```bash
   git clone https://github.com/NissrineEttayeby/Discovering-Topic-Based-Subreddit-Communities.git
   ```

2. **Install Dependencies**: Install the required Python dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Code**: Execute the main script to start the analysis and visualization process.
   ```bash
   python main.py
   ```

4. **Explore the Results**: Once the analysis is complete, explore the generated visualizations and insights to discover topic-based subreddit communities.

## Contributing

Contributions to this project are welcome! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a pull request.
