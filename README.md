# ai-study-sourcecode
공개SW전문교육 인공지능(심화) 과정 소스 정리

## 실행 환경
- Google Colab - 클라우드 기반의 무료 Jupyter Notebook 개발 환경이다. (내부적으로는 Colab/Google Drive/Docker/Linux/Google Cloud 로 이루어져 있다.

## 라이브러리
- Tensorflow
- Keras : pytorch, tensorflow 등등의 학습 도구들을 API처럼 편하게 사용할 수 있게 도와주는 라이브러리인데, 현재는 Keras와, Tensorflow 내부의 Keras가 따로 있다.
(Keras : 2.4.3버전, TF(2.3.0) 내부의 Keras 버전은 1.18.5, TF가 업데이트되면 Keras도 같이 업데이트 된다.)

## 실행 방법
1. 나의 구글 드라이브에 실행할 ipynb파일을 적절한 디렉토리에 올린다.
2. 올린 파일을 Google Colab에서 접근 가능하다.(내 구글 드라이브를 마운트해야함)
> 내 구글 드라이브를 마운트하는 이유 : Colab 세션이 자기맘대로 끊기기 때문에, 연산하다가 멈추면 진행사항을 저장할 공간이 필요해서
