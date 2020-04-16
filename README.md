# python-upload
```
git clone https://github.com/paichayon321/python-upload.git
cd python-upload
docker build -t paichayon/uploader:1 .
docker push paichayon/uploader:1
docker run -d -p 8989:8989 paichayon/uploader:1
docker run --name uploader -d -p 8989:8989 -v ${PWD}:/usr/src/app/uploads  paichayon/uploader:1
```

