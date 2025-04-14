# Webscraper for Restaurant Information using Google API

## Overview

This project is a webscraper that takes a CSV file containing a list of restaurants as input and fetches additional information for each restaurant using the Google API. The collected data is then output either as a new CSV file or displayed in another suitable format. This tool is ideal for projects or data analysis that require enriched location details, reviews, ratings, and more related to various restaurants.

## Features

- **CSV Input:** Reads a CSV file containing restaurant information such as names and addresses.
- **Google API Integration:** Connects to the Google API (e.g., Google Places API) to retrieve detailed data about each restaurant.
- **Data Enrichment:** Augments your initial CSV data with additional details like ratings, contact information, location coordinates, etc.
- **Output Options:** Saves the enriched data as a new CSV file for further analysis or reporting.
- **Error Handling:** Includes basic error handling for API request failures and data formatting issues.

## Prerequisites

- **Python 3.6+**
- **Pip** – Python package installer
- **Google API Key:**  
  You need to have an API key for the Google API you intend to use (e.g., Google Places API). [Get your API key here](https://developers.google.com/maps/documentation/places/web-service/get-api-key).

## Installation

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
