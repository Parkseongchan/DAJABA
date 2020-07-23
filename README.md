 # DAJABA
  FPGA를 이용한 High speed processing 지능형 CCTV

  팀 번호 : 34

  팀 원 : 201524464 박종욱, 201524423 김문석, 201424456 박성찬

------------------------------------------------

File Tree: 

```
yolov3-tf2
│  convert.py                                             
│  detect_video.py
│  requirements.txt
├─checkpoints
├─data
│      action.names
│      yolov3-tiny.weights      
└─yolov3_tf2
    │  dataset.py
    │  models.py
    │  utils.py
    │  __init__.py
    └──────────────
```

<br>

convert.py  				::       *.weights을 모델에 맞게 변환 

<br>

detect_video.py 		::       Action Detector

<br>

requirements.txt	   ::       Python 요구 패키지 

<br>

data							 ::       행동 태그 및  weights 저장 폴더

<br>

yolov3_tf2				  ::        Yolo 모델 

<br>