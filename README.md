# Emergency Networking API - Connection and Data Fetching

## Description

This is a jupyter notebook that demonstrates how to connect to the Emergency Networking API and fetch data from it. The Emergency Networking API is a RESTful API that provides information about emergency services in the United States. The API provides information about hospitals, fire stations, police stations, and other emergency services in a given area.

## Features

- Data fetching from the Emergency Networking API
- Data visualization using matplotlib
- Data analysis using pandas
- Data manipulation
- Data export to CSV

## Installation

To run this notebook you will need a Bearer Token from the Emergency Networking API. Place in a .txt file named `token.txt` in the `assets` directory.
Also, you will need to install the following dependencies:

- requests
- pandas
- numpy
- matplotlib
- seaborn

We recommend using a conda virtual environment to install the dependencies. You can create a virtual environment using the following command:

### Create a virtual environment

```bash
conda create -n emergency-networking-api python=3.12.4
```

### Install dependencies

```bash
conda activate emergency-networking-api
conda install requests pandas numpy matplotlib seaborn
```
