# MinIO Deployment Documentation
## Docker Command Used
```bash
docker run -d \
  -p 9000:9000 \
  -p 9001:9001 \
  --name minio-server \
  -e "MINIO_ROOT_USER=cloudadmin" \
  -e "MINIO_ROOT_PASSWORD=CloudNova2026" \
  quay.io/minio/minio server /data --console-address ":9001"

## Web Console Port
The MinIO Web Console was accessed using port 9001.
Bucket Created
* Bucket Name: client-photos
## Explanation of the -e Flags (Environment Variables)
The -e flags are used to set environment variables inside the Docker container when it starts.
* MINIO_ROOT_USER=cloudadmin
This sets the username (Access Key) that will be used to log in to the MinIO console.
* MINIO_ROOT_PASSWORD=CloudNova2026
This sets the password (Secret Key) for the root user.
By using these environment variables, we defined our own login credentials instead of relying on the default ones. This makes the deployment more secure and customized for our needs.
