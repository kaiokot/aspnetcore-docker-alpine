# ASP.NET Core Docker Sample

To run:

```console
docker build --pull -t aspnetapp-alpine .
docker run --name aspnetcore_sample_alpine --rm -it -p 8000:80 aspnetapp-alpine
```

The output should be:

```console
Hosting environment: Production
Content root path: /app
Now listening on: http://[::]:80
Application started. Press Ctrl+C to shut down.
```
To test:

```console
curl http://localhost:8000/
```





