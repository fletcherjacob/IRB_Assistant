# THIS REPO IS A WORK IN PROGRESS AND MAY NOT FUNCTION AS INTENDED

# Generative AI for Institutional Review Board (IRB) Proposals

## To test in development environment (From The Working Directory)
Install required Python library requirements using the requirement.in file

`pip install -r requirements.in`

Run the Streamlit server

`streamlit run IRB_Assistant/main.py`

In this case, use `.streamlit/secrets.toml` for secrets


## To test with docker compose

`docker-compose up --build --force-recreate`

In this case, use `secrets/` and text files for secrets. The docker-compose.yml specifies all needed secrets.

# TODO
specify a data folder location in `.devcontainer/devcontainer.json`

# Documendation 

## Build
`python3 -m mkdocs build`

## Serve 
`python3 -m mkdocs serve`
