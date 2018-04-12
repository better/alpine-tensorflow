Alpine Tensorflow
-----------------

... because Tensorflow is a pain to install on Alpine. This is mostly based on [https://github.com/tatsushid/docker-alpine-py3-tensorflow-jupyter](https://github.com/tatsushid/docker-alpine-py3-tensorflow-jupyter) with a few changes to make it work on Alpine 3.7 and Tensorflow 1.7.0

How to install
--------------

By far the easiest way to install this is to use the pre-built binary wheel hosted on Github.

```
pip3 install https://github.com/better/alpine-tensorflow/releases/download/alpine3.7-tensorflow1.7.0/tensorflow-1.7.0-cp36-cp36m-linux_x86_64.whl
```

If you want to compile it yourself, use the Dockerfile. Note that it can take many hours.
