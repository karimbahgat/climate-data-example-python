# DHIS2 Climate Data Connector Example for Python

Work in progress... 

## Secrets

Any secrets and environment variables should be put inside a .env file in the root folder. This file is not tracked by git. 

## Running locally

Create a conda env:

```
>>> conda create python=3.13 -n climate-data-example-python
```

Install dependencies:

```
>>> conda activate climate-data-example-python
>>> pip install -r requirements.txts
```

Run the fastapi server:

```
>>> uvicorn main:app --host 0.0.0.0 --port 7000
```

## Running as a docker container

Run docker compose:

```
docker-compose up --build
```

Test that the fastapi server is up and running: 

- Go to http://localhost:7000. 
