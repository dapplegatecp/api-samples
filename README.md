# api-samples
Sample code using the NetCloud Manager API for key use cases

# How To Try

## Setup a python virtual environment

    python3 -m venv .venv
    . .venv/bin/activate
    pip install -r requirements.txt

## Setup your keys in your environment

You need to create API keys in NCM to use these scripts so they can
access your NCM account. To make them available to the script, set
them in the environment, for example:

    export X_CP_API_ID=b89a24a3
    export X_CP_API_KEY=4b1d77fe271241b1cfafab993ef0891d
    export X_ECM_API_ID=c71b3e68-33f5-4e69-9853-14989700f204
    export X_ECM_API_KEY=f1ca6cd41f326c00e23322795c063068274caa30

(These are not valid keys, get your own from the NCM site!)

## Running the examples

Remember to enter your virtual environment again if you are in a new terminal
and to export your keys (see above).

    . .venv/bin/activate

Enter the `examples` directory:

    cd examples

Run the example scripts. They will provide usage information if you use the
--help option. For instance:

    ./location_tracking.py --help

Specific examples are described below.

### Getting GPS data for a router for the last day

### Getting GPS data for all routers in your account for the last day
