# Emotion-Detection
## 표정인식 기술을 이용한 이모지 매칭

## 팀 구성
|이름|전공|
|----|----|
|김수연|빅데이터 21|
|이연우|스마트IoT 21|
|주원교|빅데이터 21|

## 프로젝트 개요 
| |:angry:|:dizzy_face:|:fearful:|:smile:|:sob:|:open_mouth:|:neutral_face:|
|----|----|----|----|----|----|----|----|
|emotion|angry|disgust|scared|happy|sad|surprised|neutral|

opencv를 이용해 위의 7가지 감정을 인식하고, 이모지와 매칭해 사용자의 얼굴 부분에 합성되도록 구현한다.  
단순히 자신의 감정을 담은 이모지를 전송하는 것부터, 이모지를 제시하고 그에 맞는 표정을 지으면 통과하는 매칭 게임 등 다양한 방면에 활용될 것으로 기대한다.

## 진행 상황
kaggle 표정인식 데이터셋을 활용해 7가지 감정을 인식하도록 학습하고 웹캠으로 테스트까지 진행하였으며,
인식한 표정과 동일한 감정의 이모지를 사용자의 얼굴 부분에 합성되도록 구현할 예정이다.

## 개발 툴
Google Colab

## 사용 패키지
* tensorflow
* numpy
* opencv-python
* pandas
* keras

