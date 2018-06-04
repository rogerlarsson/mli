# mli
Machine learning docker image, 
based on Anaconda3-5.2.0, but uses newer Python 3.6, adds tensorflow, keras, ipdb, nano

# instructions
```
$ docker build -t mli .
$ docker run -it --rm mli:latest bash
$ docker run -it --rm -p 8888:8888 mli:latest bash -c "jupyter notebook --notebook-dir=/app --ip='*' --port=8888 --no-browser --allow-root"
```

