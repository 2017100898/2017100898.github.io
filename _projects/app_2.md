---
layout: page
title: "사용자 경험 평가 대시보드 MIND"
description: 사용자 경혐 평가를 위한 멀티모달 데이터 분석 대시보드 개발
img: assets/img/dashboard_gif.GIF
importance: 2
category: web/app
---



### 소개
- 사용자의 실시간 뇌파 데이터와 웹캠 기반 비디오 데이터를 이용해 사용자 경험 (UX)을 통합적으로 평가 및 시각화 하는 대시보드 개발
- 인원: 5명 (**대시보드 개발** 담당)
- 개발기간: 2023.07 ~ 2023.10

### 기술 스택
- Python
- Streamlit
- JavaScript

### 기여
- 여러 모달리티의 데이터를 실시간으로 처리할 수 있도록 Flask 백엔드 구조 설계 및 Streamlit을 활용한 대시보드 구축
- JavaScript (ChartJS)을 이용하여, 실시간으로 입력되는 사용자의 뇌파 데이터 시각화
- 웹캠 기반 실시간 비디오의 감정 인식 시각화 알고리즘 개발
- 분산 되어 있던 뇌파 집중도 분석 모델 + 웹캠 기반 감정 인식 모델 + 집중도, 감정, 사용자의 포즈를 condition으로 설정하는 캐릭터 생성 모델을 통합하여 하나의 서비스로 구현

### 논문
- **A Multimodal Interactive Dashboard for User Experience Evaluation**  
Junhyeok Lee, Hyejeong Jo, **Hye Won Park**, Minjae Kim, Yeonwoo Kim, Tae-Seong Kim, Won Hee Lee  
International Conference on Computer Science and its Applications (CSA), 2023.

- **[Developing an Integrated Dashboard to Analyze Multimodal Data for User Experience Evaluation](https://ieeexplore.ieee.org/document/10326366)**  
Hyejeong Jo, Junhyeok Lee, **Hye Won Park**, Minjae Kim, Yeonwoo Kim, Won Hee Lee  
International Conference on Consumer Electronics Asia (ICCE-Asia), 2023.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dashboard_gif.GIF" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="caption">
    대시보드 시연 장면
</div>
