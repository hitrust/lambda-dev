## Installation and Configuration

First, we’ll install the CDK.

```javascript
$ npm install -g aws-cdk
```
You should now have a cdk executable you can run.

```javascript
$ cdk --version
2.35.0 (build 5c23578)
```

Next we’ll create a Python virtual environment and install Chalice. Be sure to use Python 3.6 or greater.

```
$ python3 -m venv demo
$ . demo/bin/activate
$ python3 -m pip install chalice
$ chalice --version
chalice 1.22.0, python 3.7.8, darwin 19.6.0
chalice 1.27.1, python 3.9.13, windows 10
```
CDK integration with Chalice is available as an optional package installation. cdk version 2 is recommended. To install the necessary dependencies run the following command:

```
$ python3 -m pip install "chalice[cdkv2]"
```
## Project Creation

use the `chalice new-project` command

```
$ chalice new-project
```

Your project has been generated in ./cdkdemo

Next, we’ll cd into the cdkdemo directory and see what Chalice has generated.

```
$ cd cdkdemo
$ tree
.
├── README.rst
├── infrastructure           # CDK Application
│   ├── app.py
│   ├── cdk.json
│   ├── requirements.txt
│   └── stacks
│       ├── __init__.py
│       └── chaliceapp.py
├── requirements.txt
└── runtime                  # Chalice Application
    ├── app.py
    └── requirements.txt
```
then, install dependencies.

```
$ python3 -m pip install -r requirements.txt
```
first time using the CDK, you’ll need to bootstrap your account.

```
$ cd infrastructure
$ cdk bootstrap
 ```

then deploy.

```
$ cdk deploy
```

## Testing

 using httpie to make our HTTP requests from the command line.

 ```
$ python3 -m pip install httpie
$ http POST EndpointURL
```

## FAQ & Trouble Shots

-[FAQ & Trouble Shots](FAQ & Trouble Shots)