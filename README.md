# Streamlit Object Detection with WEBRTC and YOLOv5

> [🚧 WARNING 🚧] This is still under construction 👷‍♀️👷

## Introduction

This is an example modified from [streamlit-webrtc](https://github.com/whitphx/streamlit-webrtc)'s [**Real time object detection (sendrecv)**](https://github.com/whitphx/streamlit-webrtc/blob/2c63c17c3843213f5b3ed007724cb7d95d1f9b5f/app.py#L297) example with some little modifications:

* Change the model from Caffe to PyTorch ([YOLOv5](https://github.com/ultralytics/yolov5))
* Remove the prediciton confidence filter

Thank [Yuichiro Tachibana (Tsuchiya) (whitphx)](https://github.com/whitphx) again for the wonderful component and example

## Usage

```bash
pip install -r requirements.txt
streamlit run app.py
```

## TODO

* Add another example to use RTSP stream as source, take RTSP as [**"Consuming media files on server-side and streaming it to browser (recvonly)"**](https://github.com/whitphx/streamlit-webrtc/blob/2c63c17c3843213f5b3ed007724cb7d95d1f9b5f/app.py#L441) example's parameter of the [MediaPlayer()](https://github.com/whitphx/streamlit-webrtc/blob/2c63c17c3843213f5b3ed007724cb7d95d1f9b5f/app.py#L472) function.
