# demo-n8n
通过docker-compose部署n8n，并使用nginx作为反向代理，使用https访问

## Usage
```bash
# generate certs
sh generate_cert.sh

# start services
docker compose up -d
```