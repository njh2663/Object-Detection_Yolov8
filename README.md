## Object-Detection_Yolov8

AI Hub의 객체 인식용 한국형 비전 데이터셋  
(https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71452)  
전체 데이터셋을 학습하기에는 시간적 제약이 있어 4개 클래스(apple, banana, bowl, dumbbell)만 추출하여 Yolov8 모델에 10 epoch으로 학습함    

학습에 사용하지 않은 IMG_0058403_apple(apple).jpg에 대한 객체 탐지 결과는 다음과 같음  



실행 환경은 다음과 같으며, 데이터는 파일 용량 제한으로 인해 업로드하지 않음
- python 3.8.6  
- cuda 11.8  
- requirements.txt
