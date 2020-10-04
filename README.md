# 머신러닝과 딥러닝 BASIC

## 학습 목표

- 머신러닝과 딥러닝의 기본적인 이해

## 학습 방식

- [edwith] 머신러닝과 딥러닝 BASIC 강의를 중심으로 진행
- PDF 에 마크업 도구를 이용해서 필기
- 실습은 실습 PDF 필기 및 Jupyter Notebook 으로 따라하며 진행

## 학습 자료

- 강의 슬라이드 (tf 1.x) - [[edwith] 머신러닝과 딥러닝 BASIC](https://www.edwith.org/others26/)
- 실습 슬라이드 (tf 1.x) - [시즌 1 - 딥러닝의 기본](http://hunkim.github.io/ml/)
  - 단, [텐서플로우로 시작하는 딥러닝 기초(tf 2.x)](https://www.edwith.org/boostcourse-dl-tensorflow)가 더 이해하기 좋을 경우 슬라이드를 대체해서 학습
- 실습 코드 (tf 2.x) - [Jupter Notebook](https://github.com/deeplearningzerotoall/TensorFlow/tree/master/tf_2.x)

## 파일명 및 링크

- 파일명은 [[edwith] 머신러닝과 딥러닝 BASIC](https://www.edwith.org/others26/) 의 강의 순서에 따라서 `0X-1`, `0X-2` 순으로 정리
  - 텐서플로우 구현 강의 관련 파일명은 `.pdf` 는 `0X-강의순서-1`, `.ipynb` 는 `0X-강의순서-2` 로 정리
- 텐서플로우 구현 강의의 `.pdf` 파일이 없을 경우, `.ipynb` 파일로 대신 링크
- 텐서플로우 구현 강의 관련 파일은 혼란을 피하기 위해 파일명 뒤에 `_Lab`을 추가

## PART-1 Basic ML

#### 01 - 머신러닝의 개념과 용어

- [기본적인 Machine Learning 의 용어와 개념 설명](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/01/01_Machine_Learning_Basic.pdf) ✅

#### 02 - Linear Regression 의 개념

- [Linear Regression 의 Hypothesis 와 cost](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/02/02-1_Linear_Regression.pdf) ✅
- [Tensorflow 로 간단한 Linear Regression 구현](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/02/02-2-1_Linear_Regression_Lab.pdf) ✅

#### 03 - Linear Regression cost 함수 최소화

- [Linear Regression 의 cost 최소화 알고리즘의 원리](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/03/03-1_Minimizing_Cost.pdf) ✅
- [TensorFlow로 Linear Regression 의 cost 최소화 구현](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/03/03-2-1_Minimizing_Cost_Lab.pdf) ✅

#### 04 - 여러 개의 입력(feature)의 Linear Regression

- [Multi-variable Linear Regression](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/04/04-1_Multi-variable_Linear_Regression.pdf) ✅
- [TensorFlow 로 Multi-variable Linear Regression 구현](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/04/04-2-1_Multi-variable_Linear_Regression_Lab.pdf) ✅

#### 05 - Logistic (Regression) Classification

- [Logistic Classification 의 가설 함수 정의](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/05/05-1_Logistic_Regression:Classification_Hypothesis_Function.pdf) ✅
- [Logistic Regression 의 cost 함수 설명](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/05/05-2_Logistic_Regression:Classification_Cost_Function.pdf) ✅
- [TensorFlow 로 Logistic Classification 구현](https://github.com/jum0/MachineLearningAndDeepLearningBasic/tree/master/Part-1_Basic_Machine_Learning/05/05-3-2_Logistic_Regression:Classification_Lab.ipynb) ✅

#### 06 - Softmax Regression (Multinomial Logistic Regression)

- Lec - Lec 06-1: Softmax Regression: 기본 개념 소개

  ​         Lec 06-2: Softmax Classifier 의 cost 함수

- Lab - Lab 06-1: Softmax classifier 를 TensorFlow 로 구현하기

  ​         Lab 06-2: Fancy Softmax classifier 를 TensorFlow 로 구현하기

#### 07 - ML의 실용과 몇 가지 팁

- Lec - Lab 07-1: Application & Tips: 학습률(Learning Rate)과 데이터 전처리(Data Preprocessing)

  ​         Lab 07-2-1: Application & Tips: 오버피팅(Overfitting) & Solutions

  ​         Lab 07-3-1: Application & Tips: Data & Learning

- Lab - Lab 07-2-2: Application & Tips: 학습률, 전처리, 오버피팅을 TensorFlow 로 실습

  ​         Lab 07-3-2: Application & Tips: 다양한 Dataset 으로 실습