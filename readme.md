# Alchemy-TF

This is going to be my #AlchemyFriends card-detector.
It's based on [TF.OBJD](https://github.com/PascalS86/my-tensorflow-object_detection-pkg)

The current sources show the running sample from (https://pythonprogramming.net/video-tensorflow-object-detection-api-tutorial/?completed=/introduction-use-tensorflow-object-detection-api-tutorial/)

I followed the installation for tensorflow with pip. I also use tensorflow 1.4 currently.

To make it run the same way, i did, do the following (tested with windows 10):
* Ensure you installed python 3.6.x (I used 3.6.8)
* install virtualenv
```
python3 -m pip install virtualenv
```
* create a virtualenv
```
virtualenv --system-site-packages -p python3 ./venv
```
* activate the virtualenv
```
.\venv\Scripts\activate

```
* install tensorflow
```
pip install --upgrade tensorflow
```
* install opencv
```
pip install --upgrade opencv
```

that's basically it. if you cloned this repos, and followed those instructions, you should have your own object detection first shot.

