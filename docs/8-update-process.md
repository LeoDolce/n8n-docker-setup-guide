# 8. Update Process

## Update Procedure

1. Stop the current container
2. Execute the docker run command again
3. Docker automatically downloads the latest image
4. Existing data remains preserved inside the volume

## Important

The persistent volume prevents workflow and credential loss during updates.