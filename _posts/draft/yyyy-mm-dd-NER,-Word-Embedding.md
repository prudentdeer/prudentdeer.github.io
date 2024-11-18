---
title: NER, Word Embedding
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
published: false
#tags: []
#pin: false
#math: false
#mermaid: false
#image:
#  path: /commons/devices-mockup.png
#  lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
#  alt: Responsive rendering of Chirpy theme on multiple devices.
---

<div class="post-wrap">
  <div class="para">
    <div class="para-title">
      I. NER (Named Entity Recognition, 개체명 인식)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NER, Word Embedding의 정의
        </div>
        <div class="para-cntnt">
            텍스트에서 사전 정의된 카테고리에 속한 개체명 찾아 특정 의미 가진 단어 인식하는 과정
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NER, Word Embedding
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NER, Word Embedding의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NER,-Word-Embedding.png" alt="NER, Word Embedding">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NER, Word Embedding의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          활용
  정보검색(Information Retrieval), 질의응답(Question Answering), 챗봇

Word Embedding 
개념
  단어 간 유사도 파악위해 저차원의 실수 벡터로 매핑하여 의미적으로 비슷한 단어를 가깝게 배치
종류
  word2vec - CBOW(Continuous Bag of Words)와 Skip-Gram 두 가지 방식
  gloVe - 기존의 카운트 기반의 LSA(Latent Semantic Analysis)와 예측 기반
  FASTTEXT - 원래 단어를 부분단어(subword)의 벡터들로 표현한다는 점을 제외하고는 Word2Vec과 거의 유사

        </div>
      </div>
    </div>
  </div>

  <div class="refr-wrap">
    <div class="refr-title">
        참고자료
    </div>
    <ol class="refr-list">
    <!--    <li>(나현식, 최대선) <a target="_blank" href="https://scienceon.kisti.re.kr/commons/util/originalView.do?cn=JAKO202225948430499&oCn=JAKO202225948430499&dbt=JAKO&journal=NJOU00291864">메타버스 보안 위협 요소 및 대응 방안 검토</a></li>-->
    <!--    <li>(M. Uddin, S. Manickam, H. Ullah, M. Obaidat and A. Dandoush) <a target="_blank" href="https://ieeexplore.ieee.org/abstract/document/10138386">Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</a></li>-->
    </ol>
  </div>
</div>
