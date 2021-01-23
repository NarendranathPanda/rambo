rambo is simple web application project which will render a html page

docker command

```
docker build -t narenp/rambo:latest .
docker push narenp/rambo:latest
docker run -d -p 5000:3000 --name rambo narenp/rambo:latest
```
