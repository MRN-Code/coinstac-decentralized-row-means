# decentralized-row-means
This repository contains code for decentralized row means written for the new coinstac simulator (v3.1.6). It contains the following files:
1. local.py - computes the local row means from local data and sends results to remote site.
2. remote.py - aggreagates the local row means sent by local sites and returns the global row means and array containing all local means.
3. compspec.json - computation specifications
4. generate_data.py - python file for generating data, not used in the simulator

## Usage
1. Build the docker image:\
`docker build -t decentralized-row-means .`
2. Run the code:\
`coinstac-simulator`
