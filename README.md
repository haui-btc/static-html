# static-html

## Docker commands

```bash
docker build -t static-html .
```
```bash
docker run -it -d -p 8082:80 satic-html
```
```bash
docker-compose build
```
```bash
docker-compose up -d
```

Once you have the docker container up and running. You can rebuild image and recreate your container any time by running these two commands.

For example, you have make a change your site. Just run these two commands on terminal.
```bash
docker-compose build
docker-compose up -d
```
This will rebuild the docker image and recreate the docker container as showing in the screenshot: