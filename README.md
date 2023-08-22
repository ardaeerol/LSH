# In Progress..

# Locality Sensitive Hashing Algorithm Implementation

This repository contains an implementation of the Locality Sensitive Hashing (LSH) algorithm as a part of the CS 476 Data Mining course project.

## Overview

Locality Sensitive Hashing is a technique used for approximate nearest neighbor search in high-dimensional data. It aims to efficiently identify similar items by mapping them to the same "bucket" with high probability. This implementation provides a scalable and efficient solution for similarity search in large datasets.

## Features

- **LSH Algorithm**: Implements the Locality Sensitive Hashing technique.
- **Hash Functions**: Includes various hash functions such as random projection, **_min-hash_**, or permutation-based hashing.
- **Similarity Search**: Performs approximate nearest neighbor search using LSH for efficient similarity matching.
- **Modularity**: The implementation is designed with a modular approach, allowing easy customization and experimentation with different components.

## Getting Started

To get started with this implementation, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/ardaeerol/LSH.git
```

2. Install the necessary dependencies:

```bash
cd LSH
pip install -r requirements.txt
```

4. Customize the LSH parameters and hash functions according to your specific use case.

5. Run the main script to perform similarity search on your dataset:

```bash
python main.py
```

## Contributions
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](./LICENSE)



