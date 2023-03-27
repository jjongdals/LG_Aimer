#  LG_Aimer AI Hackathon
 스마트 공장 제품 품질분류 시스템 개발 🏭
------
### 1. Environment

Jupyter notebook
GPU서버를 할당받았음

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

#### 1-1. gpu 사용하고 있는지 확인하기

```nvidia-smi```
gpu 사용현황 및 CUDA 버전이 표시


--------
### 2. Prerequisite💻

최적화된 모델을 사용하기 위해 미리 다운

#### 2-1. catboost 설치

``` !pip install catboost```

####  2-2. autogluon 설치

``` !pip install autogluon```

#### 2-3. lightgbm 설치
```!pip install lightgbm```

lightgbm은 설치되어 있을 수도 있으니 확인한 후 설치를 진행하면 된다.

#### 2-4. train data, test data
데이터는 회사 내부 데이터라 공개 불가능

---------

### 3. License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
