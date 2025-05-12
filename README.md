# Enhancing-SEO-through-OCR-and-Prompt-Engineering-Techniques

# OCR 및 프롬프트 엔지니어링을 활용한 검색엔진 최적화 프레임워크

본 저장소는 논문_“OCR 및 프롬프트 엔지니어링을 활용한 검색엔진 최적화 프레임워크”에 기반한 재현성 자료를 제공합니다. 본 프레임워크는 OCR 기술과 생성형 AI 프롬프트를 활용하여 상품 상세페이지 이미지를 SEO 최적화된 HTML로 자동 변환합니다.

## 저장소 구성

- `prompt_ko.md` : 논문에 사용된 프롬프트 원문
- `prompt_design_rationale.md` : 프롬프트 설계 근거 및 재현 가이드

## 실행 환경

본 연구는 OpenAI의 ChatGPT 모델을 활용하여 프롬프트 결과를 생성하였으며, 다음 환경에서 실행되었습니다:

- 모델 버전: ChatGPT (GPT-3.5 및 GPT-4)
- 접근 방식: ChatGPT Web UI (https://chat.openai.com)
- 사용 플랜: ChatGPT Free

## 실행 방법

1. prompt_ko.md의 “역할 설정”과 “상황 설정” 프롬프트 실행
2. “명령1” 프롬프트 실행 시, 이미지 소스 링크와 상품명을 기입하여 실행
3. “명령2” 프롬프트 실행 시, 상세 설명 부분에 OCR 결과를 삽입하여 실행


## 논문 정보

> 논문명: OCR 및 프롬프트 엔지니어링 기반 SEO 최적화 방안 연구: e커머스 상품 상세페이지 적용 사례
