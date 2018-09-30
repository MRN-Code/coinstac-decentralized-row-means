# decentralized-row-means
This repository contains code for decentralized row means written for the new coinstac simulator (`v4.0.0`). It contains the following files:
1. local.py - computes the local row means from local data and sends results to remote site.
2. remote.py - aggreagates the local row means sent by local sites and returns the global row means and array containing all local means.
3. compspec.json - computation specifications

## Written For
- Python 3.6.6
- coinstac-simulator 4.0.0

## Usage
1. Update `npm`:\
`sudo npm i npm@latest -g`
2. Install `coinstac-simulator`:\
`sudo npm i -g coinstac-simulator@4.0.0`
3. Clone this repository:\
`git clone https://github.com/rsilva8/decentralized-row-means`
4. Change directory:
`cd decentralized-row-means`
5. Build the docker image (Docker must be running):\
`docker build -t decentralized-row-means .`
7. Run the code:\
`sudo coinstac-simulator`
