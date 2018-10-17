## Adaptive Learning 

#### Adaptive Learning: A Tale of Two Contexts, Charles et al., 2017
두 대학(UCF, CTU)에서 사용하는 LMS 시스템을 이용해 Adaptive Learning 환경 분석을 함. 두 대학간 학습환경을 분석하고 실험대상인 표본집단을 잘 비교했다. 어댑티브 러닝이 실제 오프라인 대학에서 적용하고자 하는 연구들도 진행되고 있다고 설명하는데 참조 가능하다.

#### Recommendation System for Adaptive Learning, Yunxiao et al., 2018
MOOC 시스템에서 어댑티브러닝을 위한 추천 시스템을 구현하는 방법을 제안했으며, 학습자 평가모델, 학습 모델, 추천 전략을 설계해 추천시스템의 구조를 제안했다. 시스템인 Plain Vanilla System I, II 와 적용 가능한 여러 예시 알고리즘 들을 제안했다. 예시를 Gittins Index를 활용했다는 점이 인상적이다. 

#### The Knewton Platform : A General-Purpose Adaptive Learning Infrastructure, Keven W., et al. 2015
뉴튼에서 정리한 백서. 어뎁티브 러닝에 대한 훌륭한 기술설명이다. IRT (Item Response Theory) 에 대해서도 잘 나온다.

#### An Online adaptive learning environment for critical-thinking-infused English literacy instruction, Ya-Ting C.Y. et al., 2014
어댑티브러닝 환경이 고급 영어를 학습하는데 좋은 어플리케이션인지 실험함. 이때 토익을 함께 활용했음. 토익도 영어 실력 향상에 도움이 된다는데 참조로 활용 가능

## Student Modeling

#### Open Social Student Modeling for Personalized Learning
OSM/OSSM 소셜하게 학습자를 모델링하는 방법(peer review with online)

#### Tracking Behavioral Patterns among Students in an Online Educational System, EDM 2018
MOOC에서 사용자들의 행동패턴 데이터를 NMF를 사용해 학생의 성취도를 측정하고, 과목별로 성과가 어떻게 차이나는지 알아본다.

#### Data-Driven Approach Towards a Personalized Curriculum
Performance Prediction을 통해 최근에 들은 코스에 대한 성취도를 측정했고, 측정된 성취도를 활용해 코스간 유사도 그래프를 만들었다. 만들어진 유사도 그래프를 이용해 유저에게 맞춤형 커리큘럼을 추천한다.
 - Student Performance Prediction by Discovering Inter-Activity Relations
   - 이 논문 또한 학습활동간의 유사도를 통해 사용자의 퍼포먼스를 예측했다. 이곳에서 사용한 데이터는 코딩학습컨텐츠였고 이를 통해 학생 퍼포먼스가 낮은 코스를 추천해줄 수 있다. 위 논문은 추천방법이 결과라면 이 논문은 학생 퍼포먼스를 예측하는데 초점이 맞추어져 있다.

#### Towards a Model-Free Estimate of the Limits to Student Modeling Accuracy
학습자를 모델링하는데, 이 모델은 사용자가 다음 문제를 맞출지 틀릴지 예측할 수 있는 모델을 만든다. 이러한 예측 정확도를 높일 수 있는 모델을 딥러닝 기반 기술(LSTM)을 활용해 예측하는데, 이 방법의 초점은 틀릴만한 문제를 맞추도록 전환하는데 있다. 이러한 방식에 지식을 활용하면 도메인간 연결성이 너무 떨어지는 문제가 있다. (하나의 MOOC 시스템에는 여러 도메인의 과목들이 있으며, 이는 상호작용을 하는데, 도메인 지식은 이를 해치는 문제중 하나이다.)

Next-item-correct prediction problem 을 정의하고 이를 해결할 수 있는 학습자 모델 제안

## Finding Trajectory

#### Finding trajectory on Multi-choice question answering space
객관식 문항 공간에서 이상적인 Trajectory를 찾는 문제
 - Filtered Time Series Analyses of Student Problem-Solving Behaviors in Game-based Learning
   - 게임기반 학습환경(Crystal Island)에서 Trajectory를 찾는 연구


