## rag-chatbot-guide

이 저장소는 RAG(Retrieval-Augmented Generation) 기반 AI 챗봇 개발을 위한 실습 가이드입니다.
Jupyter Notebook 및 Python 파일로 단계별 RAG 구현과 최적화 전략을 따라 할 수 있도록 구성되어 있습니다.

---

## ✨ 강의 목표

✅ LLM & RAG 기본 원리 이해
✅ 다양한 모델 및 임베딩 실습
✅ Streamlit으로 챗봇 인터페이스 구축
✅ RAG 최적화 전략까지 심화 학습

---

## 📂 전체 강의 자료 파일 리스트

### 🔹 환경 및 기본

* 01.실습 환경 설정 및 기본 LLM 테스트.ipynb
* 02.다양한 LLM 모델 테스트.ipynb
* 03.텍스트 데이터 로드 및 전처리.ipynb

### 🔹 임베딩 및 인덱싱

* 04.텍스트 분할(Chunking), 임베딩, 인덱싱 개념.ipynb
* 05.임베딩 생성 및 벡터 인덱싱 (E5 모델).ipynb
* 06.임베딩 생성 및 벡터 인덱싱 (Ko-SBERT).ipynb
* 07.임베딩 생성 및 벡터 저장 (OpenAI).ipynb
* 08.임베딩 모델 비교 및 선택 가이드.ipynb
* 09.FAISS 인덱스 구조 및 저장 방식.ipynb
* 10.FAISS vs ChromaDB 비교.ipynb

### 🔹 검색 및 검색 품질

* 11.유사 문서 검색 및 유사도 출력 실습.ipynb
* 13.내 문서 기반 RAG 챗봇 완성하기.ipynb
* 14.Chunking 전략 고도화.ipynb
* 15.Hybrid Search.ipynb

### 🔹 고급 전략 및 최적화

* 16.응답 속도 최적화 전략.ipynb
* 17.Streamlit UI 구성하기 (간단한 챗봇 인터페이스 제작).ipynb
* 18.RAG 챗봇 실전 구현 마무리.ipynb
* 19.RAG 챗봇, 실무에 쓰려면 어떤 기능이 더 필요할까?.ipynb
* 20.RAG 챗봇의 품질을 높이는 고급 전략.ipynb
* 21.실제 운영 단계에서 챗봇을 어떻게 관리할까?.ipynb

### 🔹 Python 앱 및 데이터

* streamlit\_app.py
* kr\_constitution.txt

---

* **Python 앱**

  * `streamlit_app.py`

* **데이터**

  * `kr_constitution.txt`

---

## 💻 사용 방법

1️⃣ 저장소 클론:

```bash
git clone https://github.com/mintiecloud/rag-chatbot-guide.git
```

2️⃣ Jupyter Notebook 또는 Colab에서 `.ipynb` 파일 로드

3️⃣ Streamlit 앱 실행:

```bash
streamlit run streamlit_app.py
```

---

## 📝 참고

* 본 강의 자료는 교육 및 실습 목적으로 제작되었습니다.
* 질문 및 피드백은 [이슈](https://github.com/mintiecloud/rag-chatbot-guide/issues)를 통해 남겨주세요.

---
