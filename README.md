# Simple Load Balancer in Go (Round-Robin Algorithm)

## What is this?

This is a simple load balancer written in Go, using the round-robin algorithm. It distributes incoming requests across a pool of backend servers in a round-robin manner, ensuring fair distribution of load.

## How it works?

1. The load balancer listens for incoming requests.
2. When a request comes in, it forwards the request to one of the backend servers based on the round-robin algorithm.
3. The round-robin algorithm cycles through the available backend servers in a circular order, ensuring each server gets an equal number of requests over time.
4. If a backend server is down or unresponsive, it's automatically excluded from the pool until it becomes available again.

## Test it out!

- Once the load balancer is running, you can test it by sending requests to its endpoint.
- going to the http://localhost:8000/
