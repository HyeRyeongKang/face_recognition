# 인공지능 얼굴 인식 프로그램 만들기
## 얼굴 인식
Face Detection(얼굴 탐지) : 사진에서 얼굴의 위치가 어디인지 알아내는 것

Face Tracking(얼굴 추적) : 동영상에서 얼굴 탐지를 한 번 하고 추적 알고리즘을 통해 따라다니게 하는 방법

*Face Recognition(얼굴 인식) : 사진을 이미 알고 있는 상태에서, 다른 사진에서 누가 그 얼굴인지 알아 내는 것 

### Needs:
1. dlib : Face detection + Face recognition
2. OpenCV : 이미지 작업
3. numpy : 행렬 연산
4. pyplot : 결과물 그리기

### 함수:
1. 얼굴을 찾는 함수(find_faces(img))
2. 얼굴을 인코딩 하는 함수(encode_faces(img, shapes))

### 수정 요구 사항:
1. 비디오에서 얼굴 인식 가능하게 하기
