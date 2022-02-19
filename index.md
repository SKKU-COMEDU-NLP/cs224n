---
title: CS224N 자연어처리 2021 겨울학기 공부 노트
layout: home
---

성균관대학교 컴퓨터교육과 학생들의 2022년 겨울 자연어 처리 스터디 입니다. 최신 버전 (2021 Winter)로 진행하였습니다.

## 참여자

- [최지원](https://jasonchoi.dev)
- [김보민](https://github.com/nimod7890)
- [김준영](https://github.com/junieberry)
- [신동수](https://github.com/zero-DS)
- [장지원](https://github.com/jiwon-center)
- [정소연](https://github.com/happysoy)
- [최재석](https://github.com/xy5787)
- [하유진](https://github.com/haujinnn)

## Lecture Note

|                                                                     강의 (Youtube)                                                                      |                  담당자                   |                                           노트                                            |   작성일   |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------: | :---------------------------------------------------------------------------------------: | :--------: |
|        [Lecture 1 - Introduction and Word Vectors](https://www.youtube.com/watch?v=rmVRLeJRkl4&list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ&index=1)         |      [최지원](https://jasonchoi.dev)      | [Link](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-05-Lecture-1.html) | 2022.01.05 |
|              [Lecture 2 - Neural Classifiers](https://www.youtube.com/watch?v=gqaHkPEZAew&list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ&index=2)              |      [최지원](https://jasonchoi.dev)      | [Link](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-05-Lecture-2.html) | 2022.01.05 |
|         [Lecture 3 - Backprop and Neural Networks](https://www.youtube.com/watch?v=X0Jw4kgaFlg&list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ&index=3)         |  [김보민](https://github.com/nimod7890)   | [Link](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-12-Lecture-3.html) | 2022.01.12 |
|              [Lecture 4 - Dependency Parsing](https://www.youtube.com/watch?v=PSGIodTN3KE&list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ&index=4)              |   [정소연](https://github.com/happysoy)   | [Link](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-12-Lecture-4.html) | 2022.01.12 |
|           [Lecture 5 - Language Models and RNNs](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=5)           |    [최재석](https://github.com/xy5787)    | [Link](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-19-Lecture-5.html) | 2022.01.19 |
|             [Lecture 6 - Simple and LSTM RNNs](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=6)             |   [신동수](https://github.com/zero-DS)    | [Link](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-19-Lecture-6.html) | 2022.01.19 |
|       [Lecture 7 - Translation, Seq2Seq, Attention](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=7)        |   [하유진](https://github.com/haujinnn)   | [Link](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-26-Lecture-7.html) | 2022.01.26 |
|        [Lecture 8 - Final Projects; Practical Tips](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=8)        |                                           |                                           Skip                                            |            |
|       [Lecture 9 - Self- Attention and Transformers](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=9)       |  [김준영](https://github.com/junieberry)  | [Line](https://skku-comedu-nlp.github.io/cs224n/lecture%20note/2022-01-26-Lecture-9.html) | 2022.01.26 |
|        [Lecture 10 - Transformers and Pretraining](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=10)        |      [최지원](https://jasonchoi.dev)      |                                           Link                                            | 2022.02.02 |
|             [Lecture 11 - Question Answering](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=11)             | [장지원](https://github.com/jiwon-center) |                                           Link                                            | 2022.02.02 |
|        [Lecture 12 - Natural Language Generation](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=12)         |  [김준영](https://github.com/junieberry)  |                                           Link                                            | 2022.02.09 |
|           [Lecture 13 - Coreference Resolution](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=13)           |   [신동수](https://github.com/zero-DS)    |                                           Link                                            | 2022.02.09 |
|        [Lecture 14 - T5 and Large Language Models](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=14)        |    [최재석](https://github.com/xy5787)    |                                           Link                                            | 2022.02.16 |
|      [Lecture 15 - Add Knowledge to Language Models](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=15)      |   [정소연](https://github.com/happysoy)   |                                           Link                                            | 2022.02.16 |
|      [Lecture 16 - Social & Ethical Considerations](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=16)       |                                           |                                           Skip                                            |            |
|       [Lecture 17 - Model Analysis and Explanation](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=17)       |   [하유진](https://github.com/haujinnn)   |                                           Link                                            | 2022.02.23 |
|       [Lecture 18 - Future of NLP + Deep Learning](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=18)        |      [최지원](https://jasonchoi.dev)      |                                           Link                                            | 2022.02.23 |
|      [Lecture 19 - Low Resource Machine Translation](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=19)      |  [김보민](https://github.com/nimod7890)   |                                           Link                                            | 2022.03.02 |
| [Lecture 20 - BERT and Other Pre-trained Language Models](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=20) | [장지원](https://github.com/jiwon-center) |                                           Link                                            | 2022.03.02 |

## Writing Guide

1. \_posts 폴더에 마크다운 문법으로 작성
2. 이미지는 assets 폴더에 넣고 Link (Typora, MarkText 등을 사용하면 Ctrl + C, V나 Drag & Drop으로 바로 연동 가능)
3. 수식은 달러 두개 사이에 작성 **달러 한개 아님**
4. TeX 문법에 익숙하지 않다면 톡방에 바로 물어보거나 [링크](https://zetawiki.com/wiki/TeX_%EB%AC%B8%EB%B2%95) 참조
5. H1에 **볼드 표시** 할것

## Contributing Guide

1. 작성 담당자는 Repository에 직접 Commit & Push
2. 자기거 쓰고 index.md랑 README.md도 수정 바람
3. 본인 파트가 아닌데 수정하고 싶을 경우 Pull Request를 날리거나 귀찮다면(....) 톡방에다 알려주기
