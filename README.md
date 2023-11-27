# roboflow-yolov7

![Untitled (38)](https://github.com/chaewonS/roboflow-yolov7/assets/81732426/8fe9d046-d57e-42a1-96e7-4cfce94574cd)

- yolov7 다운로드
``` git clone https://github.com/WongKinYiu/yolov7.git ```  
``` pip install -r requirements.txt ```
- yaml 파일 설정 (yolov7/data/)
    - coco.yaml
    - 파일 위치, 객체 숫자, 이름 변경
- config 파일 설정 (yolov7/cfg/training/)
    - 객체 숫자 변경
- yolov7 가중치 다운로드
- 훈련
    - 최적 가중치가 저장됨 (runs/train/yolov7/weights/best.pt)
- 모델 테스트
    - detect.py
    - 테스트 완료 이미지 저장됨 (runs/detect/expx/test.jpeg)
