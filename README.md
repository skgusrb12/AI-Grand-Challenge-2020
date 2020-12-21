# 폭력 기반 한국어 텍스트 학습 및 분류 모델(2020 인공지능 그랜드 챌린지)

**본 프로젝트는 ETRI에서 제공된 한국어 korBERT 모델을 활용하여 폭력 기반 한국어 텍스트를 분류하는 다양한 분류 모델들을 제공합니다.**

본 개발자들이 참여한 [2020 인공지능 그랜드 챌린지](http://www.ai-challenge.kr/) 4차 대회는 인공지능 기술을 활용하여 다양한 지역사회의 국민생활 및 사회현안을 대응하는 과제입니다. 
그중 음성인지 트랙은 음성 클립에서 위협상황을 검출하고 해당 위협 상황을 구분하는 것이 목표로 하고 있습니다. 아래의 표는 본 대회에서 정의한 4가지의 폭력 Class이며 아래의 4가지 폭력 Class 외에 비폭력 Class가 추가되어 총 5개 Class의 폭력 또는 비폭력을 분류하는 것이 주된 목적입니다.

<p align="center"><img src="./img/문제 정의.png"  width="500" height="270"></p>
<p align="center"><b>< 음성인지 분류대상 정의 ></b><p align="center">

**추가적으로, 본 개발자들은 ETRI에서 작성된 사용협약서에 준수하여 pretrained 모델 및 정보에 관한 내용은 공개하지 않는다.** 해당 프로젝트에서 활용한 ETRI 형태소 분석기, 토큰화를 사용하시려면 다음 [링크](https://aiopen.etri.re.kr/key_main.php)에서 서약서를 작성 후 키와 코드를 다운받은 후, 제공된 분류 모델들을 적용하여 분석한다.




## 분류 모델

## Requirements

Python 3.7

Pytorch == 1.5.0

boto3

botocore

tqdm

requests

## Results

**아래의 결과는 2020 인공지능 그랜드 챌린지 4차 대회 음성인지 트랙에서 본 팀에 대한 결과이며, 테스트 결과는 제공되지 않았습니다.**

결과는 Macro-F1 score에 의해 평가되었으며 아래와 같이 정의한다.



| Model || Macro F1-Score |
| ----- || ----- |
| MLP || 0.15 |
| CNN || 0.15 |
