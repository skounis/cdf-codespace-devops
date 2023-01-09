# cdf-codespace-devops
[![Python CI Steps Github Actions](https://github.com/skounis/cdf-codespace-devops/actions/workflows/main.yml/badge.svg)](https://github.com/skounis/cdf-codespace-devops/actions/workflows/main.yml)

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

## Container
See:
* https://github.com/noahgift/container-from-scratch-python

Run a CLI commant in a remote container (already published)
```bash
docker run -it noahgift/cloudapp python app.py --name "Big John"
```

Run the local CLI
```bash
python app.py --name John
```

### Deploy the container
Search for the Actions 
* Publish Docker Container
* Build and Deploy to GKE
* Deploy to Amazon ECS
