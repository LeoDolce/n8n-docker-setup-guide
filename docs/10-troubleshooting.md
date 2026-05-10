# 10. Troubleshooting

## Docker Engine not running

Open Docker Desktop and wait until the following message appears:

Docker Engine Running

---

## Port 5678 already in use

Verify whether another application is already using port 5678.

---

## Volume not persisting

Validate if the volume mapping is correct:

```bash
-v n8n_data:/home/node/.n8n