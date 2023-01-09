# cdf-codespace-devops
Python for DevOps Codespace repo

## Create Virtual Environment
```bash
virtualenv ~/.codespace
source ~/.codespace/bin/activate
which python
```

## Setup the CLI

Make the `.py` file executable
```bash
chmod +x hello.py
```

Run with help
```bash
./hello.py --help
```

Example 
```bash
./hello.py --path . --ftype py
./hello.py --path . --ftype txt
```