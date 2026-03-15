# 📊 GitHub Analyze LLM

> **내 GitHub 저장소 코드를 이해하고 대화할 수 있는 맞춤형 AI 어시스턴트**

![Python](https://img.shields.io/badge/Python_3.11.9-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-d97757?style=for-the-badge&logo=anthropic&logoColor=white) ![Voyage AI](https://img.shields.io/badge/Voyage_AI-5E43CE?style=for-the-badge&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub_API-181717?style=for-the-badge&logo=GitHub&logoColor=white)

본인의 GitHub 계정을 연동하여, 직접 참여하고 기여한 프로젝트의 소스 코드를 바탕으로 LLM(대형 언어 모델)과 대화할 수 있는 프로젝트입니다. 내 코드를 가장 잘 이해하는 나만의 AI 협업 프로그래머를 구상해 보세요!

## ✨ 주요 기능 (Key Features)

* **저장소 연동**: 내 GitHub 계정과 연동하여 참여한 Repository 목록을 손쉽게 불러옵니다.
* **코드 기반 대화**: 선택한 Repository의 코드를 분석하여, 내 프로젝트의 구조와 로직에 대해 AI와 자연스럽게 질의응답할 수 있습니다.

## 🎯 세부 기능 (Detailed Features)

* **Repository 탐색 및 설정**: 
  * 본인이 참여하거나 소유한 Repository 목록 가져오기
  * LLM 분석의 타겟(Target)이 될 Repository 선택 및 환경 설정
* **AI 컨텍스트(Context) 구축**: 
  * 대상 Repository의 소스코드 및 문서 내용 수집/파싱
  * 파싱된 데이터를 LLM이 이해하기 쉬운 형태로 처리하여 주입
* **스마트 인터랙션**: 
  * 프로젝트 아키텍처 질문, 특정 함수 로직 검토, 리팩토링 제안 등 내 코드 기반의 맞춤형 대화 생성

## 🚀 빠른 시작 (Quick Start)

```bash
# 1. 저장소 클론
git clone https://github.com/Properks/Github-analyze-llm.git
cd Github-analyze-llm

# 2. 파이썬 3.11 가상 환경 생성 및 활성화
python3.11 -m venv .venv
source .venv/bin/activate  # (Windows: .venv\Scripts\activate)

# 3. Jupyter 커널(ipykernel) 패키지 설치
pip install --upgrade pip
pip install ipykernel

# 4. 환경 변수(.env) 설정 파일 생성 및 설정
# GITHUB_TOKEN=your_github_personal_access_token
# OPENAI_API_KEY=your_openai_api_key
```
