# Snapshots for AI

Snapshots for AI is a tool that allows you to quickly generate machine/AI-readable documentation that shows your project's current folder and file structure, as well as the updated contents of all the files, all inside a markdown file.

![Snapshots Quick Demonstration](https://gbti.io/wp-content/uploads/2023/03/snapshots_for_ai_gif.gif)

## Installation

To use Snapshots for AI, you'll need to have Python installed on your machine. If you don't have Python installed, you can download it from the [official Python website](https://www.python.org/downloads/).

After installing Python, you need to install the required dependencies by running the following command in the terminal:

`pip install -r requirements.txt`

This will install all the required packages listed in the `requirements.txt` file.

## Usage

Snapshots can be generated by running the `snapshot.py` script, which can be executed in the terminal of your code editor. 

`python snapshot.py`

The resulting snapshot markdown files will be present inside the `snapshots/captures` folder.

To preview a snapshot, you can navigate to the `snapshots/captures` folder in the GitHub repo and click on one of the markdown files.

## Features

Snapshots for AI includes the following features:

* Auto-detect sensitive keys in JSON files and obfuscate them, so your data is better protected from AI.
* Customizable pattern-based ignore system that helps you prevent including unwanted information in your markdown reports.
* Prependable message to explain to the AI the nature of the markdown document and how to interpret it.

These features can be customized in the `snapshot.py` file.
