Скачайте контейнер:
docker pull tensorflow/tensorflow:nightly-py3-jupyter

Используйте:
docker run -it --rm -v $(realpath ~):/tf/notebooks -p 8888:8888 -p 6006:6006 tensorflow/tensorflow:nightly-py3-jupyter
