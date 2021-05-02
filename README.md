# MedQuad_MemN
Medical QA Memory Network Model


### MZ 인공지능 해커톤 대회 - 의료용어 QA 시스템 구축

memory network 모델을 통해 의료 용어 QA 시스템 구축한다.

- colab 환경에서 json 파일 형태의 의료용 데이터셋을 배열 형태로 로드.
- 토큰화된 데이터셋을 Okt(Open Korean Text) 형태소 분석기를 사용하여 전처리.
- 단어, 문장 단위로 워드 벡터화
- memory network 모델 생성.
- 개별 본문이 아닌 전체 본문에서 Answer를 도출해 정확도가 낮은 문제 발생.
- 모델을 각 본문마다 생성하여 배치하도록 해결 요망.
