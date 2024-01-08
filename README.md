# Web Crawler and Indexer

This project consists of a web crawler and indexer written in Python, designed to crawl web pages, extract relevant information, and index this information in a MySQL database. The system is particularly geared towards indexing words and their locations on web pages, as well as tracking the connections between different URLs.

## Features

- **Crawl Web Pages**: Traverses through web pages, following links to discover new pages.
- **Text Extraction**: Extracts visible text from pages, ignoring scripts and styles.
- **Word Indexing**: Indexes words found on each page, storing their locations and occurrences.
- **Database Integration**: Utilizes MySQL for storing indexed information and URL tracking.
- **Link Analysis**: Analyzes and records the links between different web pages.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.x
- MySQL server

## Setup and Installation

1. Clone the repository
2. Navigate to the project directory
3. Install the required dependencies

## Usage

To start the web crawler, run the following command:
python crawler.py

Ensure that the MySQL server is running and the database is set up as per the configuration in the script.

## Contributing to Web Crawler and Indexer

To contribute to this project, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`.
4. Push to the original branch: `git push origin <project_name>/<location>`.
5. Create the pull request.

Alternatively, see the GitHub documentation on [creating a pull request](https://help.github.com/en/articles/creating-a-pull-request).

## Contact

If you want to contact me, you can reach me in my [Linkedin](https://www.linkedin.com/in/vinicius-capozzi)!!
