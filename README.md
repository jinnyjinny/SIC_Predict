# SIC_Predict
Geophysical variable retrieval 

[연구 목적]
위성에서 관측하는 (빛을 쏘는게 아님) 마이크로파 세기 신호를 변환해서 sea ice concentration (목표 타겟 변수) 을 측정한다.

1)	여기서 sea ice concentration을 측정한다는 의미는 위성에서 측정한 각 그리드 셀에서 해빙의 면적 비율을 구하는 것을 말한다. 예를 들면 100% 이면 all ice, 50% 이면 half ice 라고 할 수 있다. 

2)	각 파장에서 물체에 따라 흡수/반사하는 정도/세기가 다르다. 그 정도/세기를 경험 함수에 넣은 후 추출된 산출 변수를 가공한 매트릭스를 데이터로 한다. 

3)	움직임은 형체의 확인 정도이지 정량적인 판단이 불가능하다. (ice motion vector, drift, ice pattern recognition을 사용하는 것이 더 용이)

4) 




