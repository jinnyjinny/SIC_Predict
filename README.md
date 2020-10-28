# Attention based ConvLSTM for SIC Prediction

[Introduction] 
- 위성에서 관측하는 마이크로파 세기 신호를 변환해서 목표 타겟 변수인 SIC(Sea Ice Concentration)을 측정한다.

1) SIC을 측정한다는 의미는 위성에서 측정한 각 그리드 셀에서 해빙의 면적 비율을 구하는 것을 말한다. 예를 들면 100% 이면 all ice, 50% 이면 half ice 라고 할 수 있다. 

2) 각 파장에서 물체에 따라 흡수/반사하는 정도/세기가 다르다. 그 정도/세기를 경험 함수에 넣은 후 추출된 산출 변수를 가공한 매트릭스를 데이터로 한다. 

3) 해당 연구의 목적은 형체 움직임을 확인하는 것이다. 정량적인 판단을 목적으로 하지 않는다. 참고로 정량적 평가는 Ice motion vector, drift, Ice pattern recognition을 사용하는 것이 용이하다.

[연구 목적]
- Attention based ConvLSTM for SIC Prediction

[Application]
- 머신러닝 기법 중 딥러닝 알고리즘의 ConvLSTM 을 활용한다. 
- 특정 공간을 집중하는 Attention module 을 모델에 접목한다.

[수행 목록]
- ConvLSTM 논문을 코드로 구현하여 위성 SIC Data에 접목
- 논문에서 제시된 모델의 Return sequence, Kernel size 파라미터 조정 및 레이어 구성 변형
