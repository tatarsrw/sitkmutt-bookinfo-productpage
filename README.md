## Bookinfo Application for Workshop
Product page service has been developed on Python

# Prerequisite

* Python 3.8

```bash
pip install -r requirements.txt
python productpage.py 9080
```

# How to run with Docker

```bash
# Build Docker Image for product service
docker build -t productpage .

# Run product service on port 8083
docker run -d --name productpage -p 8083:8083 productpage
```
* Test with path /productpage and /health

# How to run with Docker Compose

```bash
docker-compose up
```

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)