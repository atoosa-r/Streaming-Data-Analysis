# Spotify Streaming Data Analysis

Create your own personalized "Spotify Wrapped" and explore detailed trends and patterns in your listening habits. This project is designed to help users analyze their Spotify streaming data and uncover insights about their music preferences, seasonal listening habits, and overall streaming behavior.

## Introduction

This project analyzes Spotify streaming data to uncover unique listening trends and patterns. Whether you're curious about your favorite artists, seasonal preferences, or how your music taste evolves over time, this analysis can guide you to find those insights. 

The repository is beginner-friendly and serves as a resource for anyone interested in exploring their streaming data more thoroughly.

## Getting Started

### How to Get Your Spotify Streaming Data

To analyze your Spotify streaming habits, you first need to obtain your personal data from Spotify. Follow these steps to request and download your data:

1. **Visit Spotify's Privacy Settings**  
   - Go to [Spotify's Privacy Settings](https://www.spotify.com/account/privacy/).

2. **Log in to your Spotify account**  
   - If prompted, log in to your Spotify account.

3. **Request Your Data**  
   - Under the "Privacy Settings" section, locate and click on **"Request Your Data"**.  
   - Spotify allows you to request your streaming history, account information, and other data.

4. **Confirm Your Request**  
   - You may be asked to verify your account details before completing the request.

5. **Wait for Spotify to Process Your Request**  
   - Spotify will send you an email when your data is ready for download. While the process can take up to 30 days, I received my data within a week.

6. **Download Your Data**  
   - Use the link provided in Spotify's email to download your data.  
   - Extract the downloaded ZIP file to access your streaming history files in JSON format.

For more details on Spotify's data access process, visit [Spotify Data Rights and Privacy Settings](https://www.spotify.com/account/privacy/).

## Project Structure

This repository contains the following Jupyter notebooks, each focusing on a different aspect of analysis:

1. **Data Cleaning and Preparation**  
   - Prepares the raw Spotify streaming data for analysis by cleaning and organizing it.
     
2. **Trends Over Time**  
   - Explores how your listening habits evolve across different timeframes, including daily, monthly, and seasonal trends.

## Environment Setup

To run the analysis, ensure you have Python installed along with the following libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `os` (built-in)
- `wordcloud`
