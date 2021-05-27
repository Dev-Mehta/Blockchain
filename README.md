# Blockchain
A simple yet fully functional blockchain made with Python and Flask for my blog's tutorial

## Setup
Setup the virtual environment for this project and installed the required dependencies
```
virtualenv env
source env/bin/activate <-(for unix systems)
env\Scripts\activate <- (for windows systems)
pip install -r requirements.txt
```


## Run the server
```
python blockchain.py <- runs at port 5000
python blockchain.py -p 5001
python blockchain.py --port 5002
```

### API Endpoints
| Endpoint | Description |
|---|---|
| `/mine` | Mine a new block and add it to the chain. Return reward to the miner of 1 coin |
| `/transactions/new` | Add transactions to the new block. You can add as many transactions before mining new block |
| `/chain` | Display full blockchain |
| `/nodes/register` | Register a new node to the network with unique identifier |
| `/nodes/resolve` | Implement the Consensus algorithm and get the current state of full chain to the client making the request |

You can learn how to create your own blockchain with python and flask here.
