# ML-Study

## 교재
[머신 러닝 교과서 with 파이썬, 사이킷런, 텐서플로](https://ridibooks.com/v2/Detail?id=754026320)

<details>
  <summary>목차</summary>
  <p>

  #### 1장 컴퓨터는 데이터에서 배운다
  1. 데이터를 지식으로 바꾸는 지능적인 시스템 구축
  2. 머신 러닝의 세 가지 종류
  3. 기본 용어와 표기법 소개
  4. 머신 러닝 시스템 구축 로드맵
  5. 머신 러닝을 위한 파이썬
  6. 요약

  #### 2장 간단한 분류 알고리즘 훈련
  1. 인공 뉴런: 초기 머신 러닝의 간단한 역사
  2. 파이썬으로 퍼셉트론 학습 알고리즘 구현
  3. 적응형 선형 뉴런과 학습의 수렴
  4. 요약

  #### 3장 사이킷런을 타고 떠나는 머신 러닝 분류 모델 투어
  1. 분류 알고리즘 선택
  2. 사이킷런 첫걸음: 퍼셉트론 훈련
  3. 로지스틱 회귀를 사용한 클래스 확률 모델링
  4. 서포트 벡터 머신을 사용한 최대 마진 분류
  5. 커널 SVM을 사용하여 비선형 문제 풀기
  6. 결정 트리 학습
  7. k-최근접 이웃: 게으른 학습 알고리즘
  8. 요약

  #### 4장 좋은 훈련 세트 만들기: 데이터 전처리
  1. 누락된 데이터 다루기
  2. 범주형 데이터 다루기
  3. 데이터셋을 훈련 세트와 테스트 세트로 나누기
  4. 특성 스케일 맞추기
  5. 유용한 특성 선택
  6. 랜덤 포레스트의 특성 중요도 사용
  7. 요약

  #### 5장 차원 축소를 사용한 데이터 압축
  1. 주성분 분석을 통한 비지도 차원 축소
  2. 선형 판별 분석을 통한 지도 방식의 데이터 압축
  3. 커널 PCA를 사용하여 비선형 매핑
  4. 요약

  #### 6장 모델 평가와 하이퍼파라미터 튜닝의 모범 사례
  1. 파이프라인을 사용한 효율적인 워크플로
  2. k-겹 교차 검증을 사용한 모델 성능 평가
  3. 학습 곡선과 검증 곡선을 사용한 알고리즘 디버깅
  4. 그리드 서치를 사용한 머신 러닝 모델 세부 튜닝
  5. 여러 가지 성능 평가 지표
  6. 불균형한 클래스 다루기
  7. 요약

  #### 7장 다양한 모델을 결합한 앙상블 학습
  1. 앙상블 학습
  2. 다수결 투표를 사용한 분류 앙상블
  3. 배깅: 부트스트랩 샘플링을 통한 분류 앙상블
  4. 약한 학습기를 이용한 에이다부스트
  5. 요약

  #### 8장 감성 분석에 머신 러닝 적용
  1. 텍스트 처리용 IMDb 영화 리뷰 데이터 준비
  2. BoW 모델 소개
  3. 문서 분류를 위한 로지스틱 회귀 모델 훈련
  4. 대용량 데이터 처리: 온라인 알고리즘과 외부 메모리 학습
  5. 잠재 디리클레 할당을 사용한 토픽 모델링
  6. 요약

  #### 9장 웹 애플리케이션에 머신 러닝 모델 내장
  1. 학습된 사이킷런 추정기 저장
  2. 데이터를 저장하기 위해 SQLite 데이터베이스 설정
  3. 플라스크 웹 애플리케이션 개발
  4. 영화 리뷰 분류기를 웹 애플리케이션으로 만들기
  5. 공개 서버에 웹 애플리케이션 배포
  6. 요약

  #### 10장 회귀 분석으로 연속적 타깃 변수 예측
  1. 선형 회귀
  2. 주택 데이터셋 탐색
  3. 최소 제곱 선형 회귀 모델 구현
  4. RANSAC을 사용하여 안정된 회귀 모델 훈련
  5. 선형 회귀 모델의 성능 평가
  6. 회귀에 규제 적용
  7. 선형 회귀 모델을 다항 회귀로 변환
  8. 랜덤 포레스트를 사용하여 비선형 관계 다루기
  9. 요약

  #### 11장 레이블되지 않은 데이터 다루기: 군집 분석
  1. k-평균 알고리즘을 사용하여 유사한 객체 그룹핑
  2. 계층적인 트리로 클러스터 조직화
  3. DBSCAN을 사용하여 밀집도가 높은 지역 찾기
  4. 요약

  #### 12장 다층 인공 신경망을 밑바닥부터 구현
  1. 인공 신경망으로 복잡한 함수 모델링
  2. 손글씨 숫자 분류
  3. 인공 신경망 훈련
  4. 신경망의 수렴
  5. 신경망 구현에 관한 몇 가지 첨언
  6. 요약

  #### 13장 텐서플로를 사용하여 신경망 훈련
  1. 고성능 머신 러닝 라이브러리 텐서플로
  2. tf.keras API로 다층 신경망 훈련
  3. 다층 신경망의 활성화 함수 선택
  4. 요약

  #### 14장 텐서플로의 구조 자세히 알아보기
  1. 텐서플로의 주요 특징
  2. 텐서플로의 랭크와 텐서
  3. 텐서를 다차원 배열로 변환
  4. 텐서플로의 계산 그래프 이해
  5. 텐서플로의 변수
  6. tf.keras API 자세히 배우기
  7. 계산 그래프 시각화
  8. 요약

  #### 15장 심층 합성곱 신경망으로 이미지 분류
  1. 합성곱 신경망의 구성 요소
  2. 기본 구성 요소를 사용하여 심층 합성곱 신경망 구성
  3. 텐서플로를 사용하여 심층 합성곱 신경망 구현
  4. 요약

  #### 16장 순환 신경망으로 시퀀스 데이터 모델링
  1. 시퀀스 데이터 소개
  2. 시퀀스 모델링을 위한 RNN
  3. 텐서플로의 tf.keras API로 시퀀스 모델링을 위한 다층 RNN 구현
  4. 첫 번째 프로젝트: 다층 RNN으로 IMDb 영화 리뷰의 감성 분석 수행
  5. 두 번째 프로젝트: 텐서플로로 글자 단위 언어 모델 구현
  6. 전체 요약

  #### 부록 A 윈도에 아나콘다, 사이킷런, 텐서플로 설치
  1. 아나콘다 설치
  2. 사이킷런, 텐서플로 설치
  3. 예제 노트북 실행
  4. 주피터 노트북 뷰어와 구글 코랩 사용
  </p>
</details>

## 스터디 방식
1. 주 설명: 해당 주의 챕터 위주 설명
2. 부 설명: 이전까지의 내용 요약 설명
3. 실습 진행: 해당 주의 실습 진행 및 코드리뷰

## 자료 저장
https://github.com/deveb/ML-Study

## 사용할 IDE (예제 코드 구현)
Jupyter notebook or Colab

## 관련 강의
- http://hunkim.github.io/ml/
- https://www.coursera.org/learn/machine-learning
