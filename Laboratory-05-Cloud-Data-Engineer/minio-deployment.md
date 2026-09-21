
## Note on the Image Source

The lab instructions use the image `minio/minio` from Docker Hub. When I ran it, Docker returned `pull access denied for minio/minio, repository does not exist`, because MinIO no longer publishes its images to Docker Hub. I pulled the same image from MinIO's official Quay registry instead (`quay.io/minio/minio`). Only the registry prefix changed; the ports, environment variables, and startup arguments are identical.
