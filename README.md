# Simple Moving Average (SMA) Crossover Signal Generator

This project is a Python script that analyzes historical stock data to generate buy and sell signals based on a Simple Moving Average (SMA) crossover strategy. It fetches data for a specific stock ticker from Yahoo Finance, calculates short-term and long-term SMAs, identifies crossover points, and visualizes the results in a clear and informative plot.

## Sample Output

The script will generate a plot visualizing the stock's closing price, the two moving averages, and the generated buy (▲) and sell (▼) signals.

![Sample Plot](Averages_Stock_Strategy/Assets/Plot Example.png)
*Note: You will need to run the script and save your own plot image as `plot.png` to display it here.*

## Features

- Fetches historical stock data from Yahoo Finance using the `yfinance` library.
- Calculates two customizable Simple Moving Averages (e.g., 30-day and 100-day).
- Implements a classic crossover strategy to generate trading signals.
- Visualizes the stock price, SMAs, and signals using Matplotlib.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Python 3.8+
- pip (Python package installer)

### Installation

1.  **Clone the repository (if you haven't already):**
    ```bash
    git clone <your-repository-url>
    cd <your-repository-directory>
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install the required packages:**
    The script requires `yfinance`, `matplotlib`, and `pandas`.
    ```bash
    pip install yfinance matplotlib pandas
    ```
    *(Pro-tip: You can create a `requirements.txt` file containing these package names and install them all at once with `pip install -r requirements.txt`)*

## Usage

To run the analysis, simply execute the `main.py` script from your terminal:
```bash
python main.py
