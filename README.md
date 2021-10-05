## Prerequisite

* Python 3.8

```bash
pip install -r requirements.txt
python productpage.py 9080
```

## How to run with Docker

```bash
# Build Docker Image for productpage service
docker build -t image_productpage .

# Run productpage service on port 8083
docker run -d --name productpage -p 8083:8083 image_productpage 
```

## License

MIT License