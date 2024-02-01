# kafka-setup

## Overview
Contains files for running kafka and zookeeper in containerized environment and its basic demonstration using kafka-python

## Description
`producer.py` - simulates a simple order with its details

`consumer.py` - simulates a order/transaction validation service

## Setup
1. Clone this repo using `git clone https://github.com/adhirajpandey/kafka-setup` and `cd` into it.
2. `docker compose up` to run essential kafka containers.
3. `pip install -r requirements.txt` to install the requiremnts.
4. `python3 consumer.py` and `python3 producer.py` to run both simulation scripts.