# kafka-offsets
Simple python app to set offsets

# Why does this exist?
`kt` is one of the easiest ways to set offsets, but sometimes doesn't work for unknown reasons. Instead of messing around with docker containers and Confluent scripts, this is a quick/dirty way of reading messages and committing offsets.

# How to get offsets
`kt group -group <group name> -topic <topic> -brokers <broker address>`

# Use
`python3 -m venv venv`
`pip install -r requirements.txt`
