---
layout: post
title: "Coursera Practical Machine Learning 리뷰"
date: 2016-01-11
comments: true
tags: Coursera MOOC Data_Science
archive: true
---

 Coursera의 Data Science Specialization 8번째 과목 'Practical Machine Learning' 수강 리뷰입니다.

 작년 4월부터 시작해서 한달에 한과목씩 수료하던 Coursera의 Data Science 과정도 막바지에 이르렀네요. 대체 언제 끝나나 하던 지루함도 이제 얼른 끝내고 싶은 조바심으로 바뀌었습니다. 이 과정을 수료하는 중간에 여러 사이트에서 더 좋은 온라인 강의들도 많이 알게 되어서 이걸 포기하고 다른 수업으로 갈아탈까 하는 마음도 있었습니다. 하지만, 과목당 49$ 정도의 적지 않은 돈을 몇개월 투자한 덕분에 끝까지 수료하기로 맘을 먹게 되었습니다 ㅎㅎ 의지가 약한 분들에게는 수료증이 수료증 이상의 값을 할 수 있다고 봅니다.

Practical Machine Learning 후기를 본격적으로 시작하겠습니다.

![](https://lh3.googleusercontent.com/RrbdYlLG-m--afxqmlRifT41TXc07JbyaOlet7xtxb2BLh_NkodXyQLaRMQNvJ02r710fiHrVG7z6xK_EL-yiD7mb3PIDZKQl7Qz-G1IjwhH93owWfkUGZERWFnp9sxhV0ZZ_zmvT2kbgpSAqJ9Dm0N9Xh7BhhZRorRBrhOEHw3v82noZZPSJsGrRUbjhQmEnjT4iAlJmqzWhgmkrqDehSjuH6bhzJy8CwATGw-arp71v1WDlqbpjHNnKum1yfij-E7QNcwYnAtxAawpBmfPfo7uAuB0ByDhBtbwZweM7qVxBdAZ3EmtPZ9UbmzKk84PL6oVqz4eexVHoAWpltUVgeXSWMMQV2TPvbeZf8ZQeQaMtlRSK3KyeMk0be8wW6RXN2-FjWhp9tTJgaLxF1n-d4BPkiJ-naiey2YceFgwqSBGTybxssBSQKsYBbV-qRysEsT0ZT6UN1eB9wtYjoPC1puDJ_vR7lLaoQjn9xAof5-kFTSA68I70eoJEMLKsYGfLIlYAIxrSuHIszwZkR4mIe2KEgJtyPg4Lze3qAY7RJdWLBV18fJTiX-r7myzDXH0XozY=w442-h137-no)


 이번 과목의 강사는 Jeff Leak 입니다. Exploratory Data Analysis 과목에서 말이 엄청 빠르고 과제 설명이 불친절해서 엄청 힘들었던 기억이 나네요. 이번에도 말이 빠른건 마찬가지입니다. 다만 과제는 밑에서 다루겠지만 이번에는 작성해야할 리포트와 알고리즘에 대해 자세히 설명해 준 덕분에 과제하기는 수월했습니다.

 머신러닝에 대해서 조금이라도 알고 계신 분들은 아시겠지만 이 분야에서 학습해야할 내용이 엄청나게 많습니다. 알고리즘도 많고 알고리즘과 R코드를 1달안에 전부 가르치는 것은 사실 불가능한 일이겠죠. 그래서 Coursera의 이 과목도 필수적인 알고리즘을 R코드와 소개하고 적용하는 장면을 보여주고 자세한 내용은 어디를 참고하라는 식으로 링크를 알려주는 수준입니다.

 동영상 클립도 이전의 다른 과목들에 비해 많기도 하고 다루는 내용들도 많다보니 밀리면 진도를 나가기가 굉장히 힘듭니다. 시간을 정해서 매일 조금씩 진도를 나가는 것을 추천합니다.

 퀴즈도 어렵습니다 ㅠㅠ Statistical Inference보다는 덜 어렵지만 어렵긴 합니다만 주마다 한두 문제는 까다로운게 나왔습니다. 주로 데이터셋과 기본 R코드를 주고 어떤 알고리즘으로 모델을 만든 후 test set의 예측률을 맞추는 문제들입니다. 하라는 데로 하면 대부분 결과가 나옵니다.

 Project 과제는 하나의 주제로 2가지를 수행하는 방식입니다. 첫번째는 classification 해야 하는 데이터셋을 주고 Machine Learning 알고리즘을 만드는 작업을 리포트로 작성해서 제출해야 합니다. 두번째는 위에서 만든 알고리즘으로 testset을 classification해서 정답을 맞춰야 합니다. testset에는 정답지는 없고 웹으로 결과를 제출해서 맞은 개수대로 점수를 얻는 방식입니다. class가 몇개 안되서 여러번 찍으면 맞출 수도 있겠지만 제출 한도가 2회입니다.

 Project를 하면서 컬럼이 160개가 되는 데이터셋은 처음 다뤄봤습니다. 데이터셋이 커지면 작업이 힘든 것 중에 하나가 데이터를 확인하고 살펴보는 과정이 힘듭니다. EDA 작업이 지난할 뿐더러 각 컬럼이 무엇을 의미하는지 체크하는데 시간이 오래 걸립니다(데이터의 내용 파악은 영어이기도 하고 결국 포기;;). 데이터셋으로 학습시키는 연산도 오래 걸려서 모델 선택도 오래 걸렸습니다. 저는 PCA로 차원 축소해서 연산 시간을 줄이고자 했는데, 토론 게시판의 다른 학습자들은 160개 전부 모델링으로 돌리는 것 같았습니다.
 저는 결과적으로 모델 정확도는 20개의 테스트셋 문제 중에 17개만 맞췄습니다. 토론 게시판에 일부는 다 맞춘 사람도 있었는데 Ensemble을 썼다고 하네요(kaggle도 그렇고 classification 기법의 대세는 ensemble인 듯..)

 이 수업 이전에는 단순히 알고리즘 몇개만 알고 활용하는 수준이였는데, 이 과목을 통해서 좀 더 포괄적으로 다양한 기법들을 알 수 있게 되었습니다(caret 패키지의 다양한 활용도와 함께~). 힘들었지만 재미를 느낄 수 있는 과목이였습니다.