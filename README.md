# PaperReview

2022년 4월부터 조사한 논문들을 간략하게 정리하기 위한 노트로 작성하는 페이지입니다. **Action Recognition**(비디오 클립 분류), **3D Object Detection**(객체 종류, 크기 그리고 위치 파악), and **Segmentation**(객체가 시각 내에서 존재하는 영역 파악) 관련 논문 토픽을 정리하고 있으며, [project](https://github.com/users/jinsoo9595/projects/1)에 정리하고 있습니다. 아래에는 논문의 핵심 모델 또는 개념을 정리해뒀습니다.


## Action Recognition (CNN based Temporal Design)
### Video 데이터 특징 정리
- Video = Spatial(공간) + Temporal(시간) 특징을 지님
    - Video에서 spatial
        - 비디오에 묘사된 장면과 물체에 대한 정보를 학습
    - Video에서 temporal 
        - 비디오 클립에 확인되는 motion에 대한 정보를 학습
        
- 딥러닝 기반 방법론에 따른 temporal(시간) 정보 분석 이점 및 단점
  ![image](https://user-images.githubusercontent.com/60027558/181400811-1b6df12b-7343-47d3-b33d-25730a7df279.png)

### Model   
- [2016] [TSN](https://github.com/jinsoo9595/PaperReview/issues/1), Temporal Segment Networks: Towards Good Practices for Deep Action Recognition
- [2017] [R(2+1)D](https://github.com/jinsoo9595/PaperReview/issues/3), A Closer Look at Spatiotemporal Convolutions for Action Recognition
- [2018] [TRN](https://github.com/jinsoo9595/PaperReview/issues/2), Temporal Relational Reasoning in Videos 

## 3D Object Detection
- 

## Segmentation
- 
