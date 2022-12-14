# Quickstart Guide
1. A Gurobi license is required to run this app. Visit  [Gurobi for Academics and Researchers](https://www.gurobi.com/academia/academic-program-and-licenses/) for instructions on obtaining an individual academic license 
   1. The only requirement is to fill out an online form
2. Install the required packages
3. Run ```python3 stratisfimal.py``` and follow the input prompts to perform a stratisfimal layout optimization 
   1. A graph is created using the Rome-Lib data, then the Berger-Shor min-FAS heuristic, min-width algorithm and vertex promotion heuristic of Tarassov et al. are performed on it to create a reasonable layering
   2. Optionally, run ```sh scripts/full_test_suite.sh``` or ```sh scripts/mini_test_suite.sh``` to perform a test suite which optimizes a number of graphs and saves the output to a file in the scripts folder