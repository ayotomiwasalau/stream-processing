# Optimizing Public Transportation

Run the following commands

```
python producers/simulation.py

python consumers/faust_stream.py worker

python consumers/ksql.py

python consumers/server.py

```