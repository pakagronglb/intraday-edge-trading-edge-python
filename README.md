 # Intraday Trading Edge Python 🐍

A Python-based cryptocurrency trading analysis tool that leverages the Binance API to fetch and analyze historical price data for various trading pairs.

## Overview 🚀

This project implements an intraday trading analysis system that allows users to:
- Fetch historical price data from Binance
- Analyze price movements and patterns
- Generate trading insights based on historical data

## Features 🫡

- Real-time data fetching from Binance API
- Historical price data analysis
- Customizable time intervals and trading pairs
- Data visualisation capabilities

## Prerequisites 🔑

- Python 3.13 or higher
- Binance API access
- Required Python packages:
  - pandas
  - python-binance
  - matplotlib

## Installation 📦

1. Clone the repository:
```bash
git clone https://github.com/pakagronglb/intraday-trading-edge-python.git
cd intraday-trading-edge-python
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage 🚀

1. Import the required libraries:
```python
import pandas as pd
from binance.client import Client
from datetime import datetime, timedelta, UTC
import matplotlib.pyplot as plt
```

2. Initialize the Binance client:
```python
client = Client()
```

3. Use the provided functions to fetch and analyze data:
```python
df = getdata(symbol='BTCUSDT', interval='1h', lookback='300 day')
```

## Configuration ⚙️

The default configuration includes:
- Trading pair: BTCUSDT
- Time interval: 1 hour
- Lookback period: 300 days

You can modify these parameters in the `getdata()` function call.

## Contributing 🙏🏻

Contributions are welcome! Please feel free to submit a Pull Request.

## License 📝

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments 🙏🏻

This project is based on the work and teachings from [Algovibes](https://www.youtube.com/watch?v=jFa6u-7E10U). Special thanks to Algovibes for providing the foundational knowledge and inspiration for this trading analysis tool.

## Disclaimer 📍

This tool is for educational purposes only. Cryptocurrency trading involves significant risk, and past performance does not guarantee future results. Always do your own research and trade responsibly.
