Machine Learning
=============
> Created by Jeongkyu Kim  
git.md, jupyter.ipynb, python  

<img src="https://user-images.githubusercontent.com/66001539/117562702-e3234d00-b0db-11eb-914a-4dbd0a04fab6.png" width="600px" height="300px" title="px(픽셀) 크기 설정" alt="Image_machine"></img><br/>  
*What is machine learning? (머신 러닝)*
-------------
> 머신 러닝은 명시적인 프로그래밍을 통해서가 아닌 데이터로부터 시스템을 학습할 수 있는 AI의 한 형태입니다. 그러나 머신 러닝은 단순한 프로세스가 아닙니다. 알고리즘을 통해 학습 데이터를 수집한 후 해당 데이터를 기반으로 더 정확한 모델을 생성할 수 있습니다. 머신 러닝 모델은 데이터를 이용하여 머신 러닝 알고리즘을 트레이닝시킬 때 생성되는 출력입니다. 학습을 마친 후 모델에 입력 내용을 제공하면 결과물을 받게 됩니다. 예를 들면, 예측 알고리즘에서는 예측 모델이 생성됩니다. 그런 다음 예측 모델에 데이터를 제공하면 해당 모델을 학습한 데이터를 기반으로 예측 정보를 받게 됩니다.  

*머신 러닝의 반복 학습*
-------------
> 머신 러닝을 사용하면 모델을 배치하기 전에 데이터 세트를 기반으로 학습할 수 있습니다. 일부 머신 러닝 모델은 온라인에서 이루어지며 지속적입니다. 온라인 모델의 이러한 반복적인 프로세스를 통해 데이터 요소 사이에서 이루어지는 연결 유형이 개선됩니다. 이러한 패턴과 연관성은 그 복잡성과 크기로 인해 사용자가 간과하기 쉽습니다. 모델을 학습한 후에는 모델을 실시간으로 사용하여 데이터로부터 학습할 수 있습니다. 머신 러닝에 포함되는 학습 과정 및 자동화로 인해 정확도가 향상됩니다.  

*머신 러닝에 대한 접근법*
-------------
> 예측 모형의 정확도를 향상시키려면 머신 러닝 기술이 필요합니다. 다루고 있는 비즈니스 문제의 특성에 따라 데이터 유형 및 용량을 기반으로 다양한 접근법이 있습니다.  

*Supervised learning (지도 학습)*
-------------
> 지도 학습은 일반적으로 구축된 데이터 세트와 해당 데이터를 분류하는 방식에 대한 확실한 이해를 바탕으로 시작됩니다. 지도 학습은 분석 프로세스에 적용할 수 있도록 데이터에서 패턴을 찾기 위한 방식입니다. 이러한 데이터에는 데이터의 의미를 정의하는 분류된 기능이 있습니다. 예를 들면, 이미지 또는 작성된 설명을 기반으로 수백만 마리의 동물을 구별하는 머신 러닝 애플리케이션을 만들 수 있습니다.  

*Unsupervised learning (비지도 학습)*
-------------
> 비지도 학습은 문제에 엄청난 양의 분류되지 않은 데이터가 필요한 경우 사용됩니다. 예를 들면, Twitter, Instagram, Snapchat과 같은 소셜 미디어 애플리케이션에는 모두 대규모의 분류되지 않은 데이터가 있습니다. 이러한 데이터에 숨겨진 의미를 이해하려면 발견된 패턴 또는 클러스터를 기반으로 데이터를 분류하는 알고리즘이 필요합니다. 자율 학습은 반복적인 프로세스를 수행하고, 사용자 개입 없이 데이터를 분석합니다. 이 방식은 이메일 스팸 탐지 기술에 사용되고 있습니다. 합법적인 이메일과 스팸 메일에는 너무 많은 변수가 있어 분석가가 원치 않는 대량의 이메일에 태그를 지정하기 어렵습니다. 그 대신에 클러스터링 및 연관을 기반으로 하는 머신 러닝 분류기가 원치 않는 이메일을 식별하기 위해 적용됩니다.  

*Reinforcement learning (강화 학습)*
-------------
> 강화 학습은 행동 학습 모델입니다. 알고리즘에 데이터 분석에서 얻은 피드백이 접목되어 사용자에게 최적의 결과를 안내합니다. 강화 학습은 다른 유형의 감독 학습과 다릅니다. 샘플 데이터 세트를 사용하여 시스템을 학습하지 않기 때문입니다. 대신 시행착오를 통해 시스템을 학습합니다. 따라서 일련의 성공적인 의사결정을 통해 프로세스가 강화되는데, 문제를 언제든 가장 효과적으로 해결하기 때문입니다.  

*Deep learning (딥 러닝)*
-------------
> 딥 러닝은 데이터로부터 반복적으로 학습할 수 있도록 연속된 계층에 신경망을 통합하는 특정 머신 러닝 방법론입니다. 딥 러닝은 비정형 데이터로부터 패턴을 학습할 때 특히 유용합니다. 딥 러닝 복합 신경망은 인간의 두뇌가 어떻게 작동하는지를 에뮬레이션하기 위해 설계되었습니다. 따라서 컴퓨터는 잘못 정의된 추상과 문제점을 처리하도록 트레이닝을 받을 수 있습니다. 평균 5세의 어린이는 교사의 얼굴과 건널목 안전 지킴이 얼굴의 차이를 쉽게 인식할 수 있습니다. 그러나 컴퓨터에서는 누가 누구인지 알아내기 위해 많은 작업을 수행해야 합니다. 신경망과 딥 러닝은 흔히 이미지 인식, 음성, 컴퓨터 비전 애플리케이션에 사용됩니다.


[IBM_Example_URL](https://www.ibm.com/kr-ko/analytics/machine-learning?p1=Search&p4=43700052658044404&p5=e&gclid=CjwKCAjw7diEBhB-EiwAskVi1yKXEyBOHmWSVyWV_9KBln8r-eFt6RrIeJY0xY6pJ-iF2IKjIjuXLxoC9X4QAvD_BwE&gclsrc=aw.ds)  
