layout: post
title: "Coursera Exploratory Data Analysis/Reproducible Research 리뷰"
date: 2015-11-13
comments: true
tags: Coursera MOOC Data_Science
archive: true
---

 이 리뷰를 쓰는 시점은 11월로 위 과목들을 모두 듣고 난 후에 한번에 쓰게 되었다. 기억이 조금 희미해 지는 시점이기도 해서 상세한 후기가 되지는 못할 것 같다.

![](https://lh3.googleusercontent.com/QvxAPDmogXCCBJtNBYPwwBC9vVxGAMTEWpk7ns8hWUjSc4mFGDYXDC2h44rQRdXh7DPNi7OupwZQAepaajj87crAwX6RVdZVog8t8tHMsZsK9zrZboEqKEgLPvfdYOgQBqItlCdYMnJe0OCzYjdL69h0DLaNItLS_jJquZqQ7fd3yeFbJ7sIVnI21OMNJAfcXDLdxBx-DVbWtBDxcFexUTJNk2vqeahddWXJg_R16m7Ypv6DZ7kiQPoQ6b63-Ta5Xk8qU6uW5Uap6xZqzfHsXUNdg-T5_-Jv4qbzHhK4E6xMVjLSRpnEeNObAaVfb6G7199DRXublpKAu8LZGd7IJbWDAAnPE4ne3dBysncX861-i5mNKzG09p-erJUaE_KPbITT6ysg6mSuUez1ItdbokzIjGDj2xxDRckwaT0wl6rC-cvq-G73LMFi8gQXf0S478MH156hNlRAJbgTx_arx0PJeNSjoB6GWnBZA-Ri9lAGMjwksz745J-GktYQMJuvprxy424rg5tGcDgYtrM4T0_QTjkcgjkK665gNM41Ths=w442-h137-no)

1. Exploratory Data Analysis

 일명 EDA 라고 불리는 탐색적 데이터 분석에 대해서 학습하는 과목이다. 실제 본 분석에 앞서서 주어진 데이터의 생김새를 살펴보는 과정이다. 지난 번 강의(Getting and Cleaning Data)에 빠져 있었던 Roger Peng 교수가 다시 강사로 나왔다. 아시안계라서 그런지 발음도 영어 발음도 알아듣기 쉽고 Project과제에 대해서도 친절하게 안내해준 것이 참 맘에 든다 ㅎㅎ (심지어는 Project를 평가할 때에 점수를 깍는 것에 집중하지 말고 학습자에게 도움이 되는 조언을 하라는 것까지 Project 과제에 표시해 놓았다)

 강의 내용의 70%는 Plotting에 관한 내용이다. Plot은 데이터 분석의 최종 단계 ‘Visualization’에 사용된다고 생각하고 있었는데, 이번 강의를 들으면서 데이터를 탐색하고 살펴보는데 plot은 유용한 툴이라는 것을 알 수 있었다(물론, ‘EDA’단계와 ‘Visualization’단계에서 사용되는 plot과 기법은 조금 다를 것이다).

 Plotting 연습을 한참 하고 있을 무렵에 갑자기 PCA, KMEANS, Hierarchical 군집분석에 대한 내용이 나온 점이 조금 생뚱맞긴 했지만, 충분히 EDA에서 다룰 기법이라는 생각이 든다. 그리 어렵지 않게 Pass 할 수 있는 과목.

![](https://lh3.googleusercontent.com/8UgxP7ahYPnutlbjilq6xxqpdq8Plzid9tkNdOCxBCHs6D74lcYn7uofU8-rDKwwJpXD-UmgMyMUsT4ey7xdv9-XlcLmCqZE2LRx18MmIOAJZjMo10XhrLou2Icuwjl5sUFIONX6qJLyXC8S7mK5Qe2yoMj17kInOrvykY_V64j_6nP51lact2q9OqGitjgQE3qlyV-m4GPhBlb5yly3BgTKCDbT7tV6Ax_otbJoiQp0FsMSpvAsziU-0Vi2NDUj73qOpd5PhOL6uF7tQkVIar8y9CPNHvNclfUt8-LXVXjJho3BKsw-9p-RgCRUV4mIKPZO2K58xbSgwMovfjlKqzctXJb7Fx2GQGUQ0yxEcR4CtvF5PcRm1rjz4lpvT5jhhPyhY03yjV_G86FMMj7pz1Vao2ueCnv3OP2uxpbEAe3-lZ2cTnLN1OlKoyAG95T1hW_tvv2Vrwuu80DVR_iZncgYUxMnINOcTvyx_fbJLrQo0FMBFnyP0d4QJZ-jg6edYfhn8brDPWsRfypdAkC2NP_UlIiDKia06omuAkqxzJU=w442-h137-no)

2. Reproducible Research

 IT분야에서 오픈소스가 널리 사용되면서 내 작업과 연구물이 다른 사람에 의해서 더 개선되고 발전되는 경우들이 많아졌다. 데이터 과학 분야도 마찬가지로 이러한 개방성이 발전의 큰 디딤돌이 되었다(R이라는 언어와 수많은 Package들을 보아도). 내 작업과 연구결과가 더 널리 활용되기 위해서는 재현가능해야 한다는 큰 개념이 있는데, 이러한 개념과 적용 방법을 배우는 과목이다.

 과목의 주 내용은 Reproducible Research의 개념과 R의 'knitr' 패키지를 이용해 리포트를 만들고 웹에 퍼블리싱 하는 방법들이다. Reproducible Research는 실행이 어려운 것이지 개념은 한 번 들으면 알 수 있는 부분이기 때문에, 실제로 학습하는 내용은 'knitr' 패키지와 R Markdown 사용법이 전부라고 해도 과언이 아니다. 처음에는 신기해 하면서
즐겁게 배웠지만 나중에 개인적으로 'knitr'과 관련된 자료를 검색해보니, 강의에서 알려주는 몇가지 방법들은 일부분에 지나지 않았다. knitr로 리포트를 만드는 데 사용되는 함수들도 강의에서 언급되지 않은 것들도 많았고, Reproducible Research를 위한 R 패키지에는 knitr과 함께 다른 패키지들도 활용되고 있었다.

 Specialized Certificate를 노리는 것이 아니라면 웹에서 knitr과 Markdown을 학습하는 것이 더 나을 것 같다. 물론 Reproducible Research 개념도 중요하다고 생각되기 때문에 별도로 자료를 읽고 연습할 필요가 있다고 생각된다.