# Simple Python Flask Dockerized Application#

Build the image using the following command

```bash
$ docker build -t kyamajir123/travisdocker:latest .
```

Run the Docker container using the command shown below.

```bash
$ docker run --name firstImage --platform linux/amd64  -p 8000:8000 kyamajir123/travisdocker:latest 
```

The application will be accessible at http://localhost:8000/ 
