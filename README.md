# Bookinfo Product Page Service

Product page service has been developed on Ruby

## License

MIT License

## How to run

```bash
pip install -r requirements.txt
python productpage.py 8083
```

## How to run with Docker

```bash
# Build Docker Image for product page service
docker build -t productpage .

# Run product page service on port 8081
docker run -d --name product pag -p 8083:8083 productpage
```

## How to run with Docker Compose

```bash
docker-compose up
```

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
