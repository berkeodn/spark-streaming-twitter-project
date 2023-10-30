# Spark Streaming Twitter Project

## Overview
This project is an application designed to connect to a local stream of data, specifically an open terminal, through a socket connection. It aims to capture hashtags and their corresponding count values from tweets that are filtered by a user-specified keyword. The captured data is then visualized in real-time on a live dashboard.

## Features
Real-time Data Capture: The application connects to a local data stream via a socket connection and captures tweets containing hashtags and their counts in real-time.

Keyword Filtering: Users can specify a keyword of interest, and the application will filter tweets based on this keyword to capture relevant data.

Live Dashboard: The captured hashtags and counts are displayed on a live dashboard, providing an up-to-the-minute view of the data.


## Prerequisites
Before you begin, ensure you have met the following requirements:

Python: This project is written in Python, so you need to have it installed on your system.

Socket Connection: You should have access to the local data stream (open terminal) and the necessary permissions to establish a socket connection.

Tweepy: In order to get access to the Twitter API and get the streaming data.

Pyspark: You need to include Pyspark to use its functionality in project.

## Usage
1. Configure the application by specifying the keyword you want to filter tweets by.

2. Run the application to start capturing real-time data from the local stream.

3. Access the live dashboard to view the captured hashtags and their counts.

4. Enjoy real-time insights into the data related to your chosen keyword!
