A simple Python weather API wrapper for educational purpose.


Build:

```
docker build -t weather:v1 .
```

Run:

```
docker run -dit --rm -p 5000:5000 --name weather weather:v1
```

You can also run it using Docker Compose:
```
docker-compose up
```

Test:

```
curl http://0.0.0.0:5000/london/uk/
```
