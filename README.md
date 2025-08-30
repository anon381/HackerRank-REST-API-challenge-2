# HackerRank REST API Challenge 2

This project contains a Python script (`api.py`) that interacts with the HackerRank Football Matches API to calculate the total number of goals scored by the winner of a football competition in a given year.

## Features

- Fetches football match data from the HackerRank mock API.
- Calculates total goals scored by the winning team in a specified competition and year.
- Handles API pagination and aggregates results.

## Requirements

- Python 3
- `requests` library

Install dependencies:
```bash
pip install requests
```

## Usage

Run the script and provide the competition name and year as input:

```bash
python api.py
```

You will be prompted to enter:
- Competition name (e.g., "English Premier League")
- Year (e.g., 2011)

The script will output the total goals scored by the winner of the specified competition and year.

## Environment Variable

Set the `OUTPUT_PATH` environment variable to specify the output file for the result.

Example (Windows PowerShell):
```powershell
$env:OUTPUT_PATH = "output.txt"
python api.py
```

## API Reference

- [Football Matches API](https://jsonmock.hackerrank.com/api/football_matches)
- [Football Competitions API](https://jsonmock.hackerrank.com/api/football_competitions)

## License

This project is for educational purposes only.
