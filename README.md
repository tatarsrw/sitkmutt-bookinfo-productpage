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
# Build Docker Image for products service
docker build -t products .

# Run products service on port 8083
docker run -d --name products -p 8082:9080 products
```
* Test with path /products/1 and /health

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)