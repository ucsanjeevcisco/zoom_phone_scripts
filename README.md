# Zoom Phone Sample Scripts

These scripts are sample scripts for Zoom Phone. See Zoom API documentation on marketplace.zoom.us

## Installation

1. Install Python
2. Install required Libraries from requirements.txt
3. Download zoomus library from https://github.com/jsteinberg1/zoomus

```bash
pip install requirements.txt
```

## Usage

### Call Log Exporter

python call_logs.py -h

python call_logs.py <API_KEY> <API_SECRET> --from_date=2019-12-31 --number_of_days=30 --call_direction=all
