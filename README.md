# python-upload
```
git clone https://github.com/paichayon321/python-upload.git
cd python-upload
docker build -t test .
docker run -d -p 8989:8989 test
docker run --name uploader -d -p 8989:8989 -v ${PWD}:/usr/src/app/uploads
```

