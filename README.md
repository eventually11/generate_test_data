# Overview

This repository contains scripts and tools for generating and processing test data, particularly focusing on geographical data and route calculations. It includes utilities for searching locations using the OpenStreetMap API and calculating distances and durations using the OSRM API.
Features

    OpenStreetMap API Integration: Search for places (e.g., restaurants, schools) around a specified location.
    OSRM Route Calculations: Compute driving distances and travel times between locations.
    Data Handling: Combine and process location data into Pandas DataFrames for further analysis.

## Installation

To get started, clone the repository, navigate to the project directory, and install the package:

bash

    git clone https://github.com/eventually11/MockOrderDataGenerator.git
    cd MockOrderDataGenerator
    pip install .


# Usage

Install Dependencies: Ensure all required Python packages are installed.

bash

    pip install requests pandas

Run Scripts: Use the provided scripts to generate and process test data.


bash

    python script_name.py

Testing: The repository includes unit tests to verify functionality. Run the tests with:

bash

    python -m unittest discover
