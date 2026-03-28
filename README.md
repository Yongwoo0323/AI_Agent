가상 AI 에이전트 제작 과정 (vscode 터미널로 진행)

# 1. 가상환경 생성 (라이브러리 꼬임 방지)
python -m venv venv

# 2. 가상환경 활성화
# Windows 기준:
.\venv\Scripts\activate
# Mac/Linux 기준:
source venv/bin/activate

# 3. 필수 라이브러리 설치
pip install langchain langchain-google-genai langchain-community chromadb pypdf