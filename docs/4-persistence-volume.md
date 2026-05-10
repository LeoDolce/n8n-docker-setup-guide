## Objective

The Docker volume guarantees that workflows and credentials remain saved even after restarting or updating the container.

## Create Volume

Run the command below in CMD or PowerShell:

```bash
docker volume create n8n_data
Expected Result

Docker will create a persistent volume called:

n8n_data