# Ultra Low Latency Market Making Engine

## Overview
This project is a low latency market making engine built for high-frequency trading.

## Libraries Used
- **QuickFIX**: FIX protocol engine for message handling.
- **Google Benchmark**: For measuring performance.
- **Catch2**: Unit testing framework.
- **Boost**: Used mainly for lock-free queues.
- **Redis client**: For caching and state management.

## Project Structure
- `src/` — source code
- `include/` — header files
- `tests/` — unit tests
- `benchmarks/` — performance benchmarks

## Build Instructions
```bash
mkdir build
cd build
cmake ..
make
