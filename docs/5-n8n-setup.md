# 5. n8n Container Setup

## Run n8n Container

Execute the command below:

```bash
docker run -it --rm \
  -p 5678:5678 \
  -v n8n_data:/home/node/.n8n \
  n8nio/n8n
What This Command Does
Exposes port 5678
Enables persistent storage
Downloads the official n8n image automatically
Starts the n8n container