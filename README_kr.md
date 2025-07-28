# Awesome Azure AI Foundry

**언어 선택 / Language Selection:**
- [English](README.md) | [中文](README_cn.md) | [한국어](README_kr.md) | [日本語](README_jp.md)

---

> ### Azure AI Foundry is **ALL** you need.

## 🚀 Azure AI Foundry란 무엇인가요?

Azure AI Foundry는 개발자와 조직이 정교한 AI 애플리케이션과 멀티 에이전트 시스템을 만들 수 있도록 지원하는 Microsoft의 통합 플랫폼입니다. 모델 커스터마이징, 콘텐츠 안전, 에이전트 AI 워크플로우, Azure 서비스와의 원활한 통합을 위한 엔터프라이즈급 도구를 제공합니다.

## 📋 여기에서 찾을 수 있는 것들

이 저장소는 다음과 같은 내용을 포함하는 Azure AI Foundry의 포괄적인 리소스 허브 역할을 합니다:

- **🤖 AI 에이전트 및 에이전트 앱**: 고객 서비스, 영업 분석, 연구, 제조 최적화를 포함한 다양한 비즈니스 시나리오를 위한 사전 구축 및 커스터마이징 가능한 에이전트
- **🧠 Azure OpenAI 통합**: Sora, 비디오 플레이그라운드, 모델 라우터, 파인 튜닝, 프롬프트 캐싱 및 배치 처리 기능에 대한 문서
- **🌐 에이전트 AI 솔루션**: 대화 마이닝, 멀티 에이전트 자동화, 콘텐츠 처리 및 적응형 RAG 구현을 위한 프로덕션 준비 솔루션 가속기
- **📄 문서 인텔리전스**: 콘텐츠 이해, 멀티모달 데이터 처리 및 지능형 문서 분석 도구
- **🛡️ 콘텐츠 안전**: PII 필터, 프롬프트 쉴드, 신뢰할 수 있는 AI 가이드라인을 포함한 엔터프라이즈급 보안 기능
- **� 모델 커스터마이징**: 텍스트 및 비전 모델 전반에 걸친 파인 튜닝, 디스틸레이션 및 최적화를 위한 포괄적인 도구
- **� 에이전트 검색 및 검색**: 멀티모달 지원 및 모델 컨텍스트 프로토콜(MCP) 구현을 통한 고급 검색 기능
- **🛠️ 개발 도구**: 간소화된 AI 개발을 위한 VS Code 확장, AI 툴킷 및 로컬 개발 리소스
- **🏠 Foundry 로컬**: Azure AI Foundry 기능을 로컬 환경으로 가져오는 도구
- **🔌 통합 솔루션**: 엔터프라이즈 환경에서 리소스와 에이전트를 연결하기 위한 템플릿 및 패턴
- **📚 학습 리소스**: AI Foundry 여정을 가속화하기 위한 워크샵, 실습 랩 및 초급자 과정

첫 번째 AI 에이전트를 구축하든 엔터프라이즈 AI 솔루션을 확장하든, 이 컬렉션은 Azure AI Foundry와 함께하는 여정을 가속화하는 데 도움이 될 것입니다.

---

## Azure OpenAI

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [Sora 비디오 릴](https://youtu.be/x6Oj2wbrLcU) | Sora 기능을 보여주는 비디오 |
| [Azure AI Foundry 비디오 플레이그라운드](https://youtu.be/V29lwzWPwTE) | 비디오 플레이그라운드 기능 연습 |
| [VS Code용 비디오 플레이그라운드](https://youtu.be/79zzSMY1nh4) | 비디오 플레이그라운드와 VS Code 간의 통합 데모 |
| [모델 라우터 비디오](https://1drv.ms/v/c/d17313624f8feacf/EZYbJdl1bQtDsqombEEnFTsBQL8GtVIU4FEiyaQxP9srsQ?e=8uT0CS) | Azure OpenAI 모델 라우터 기능 시연 |
| [프로비저닝된 처리량 문서](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/spillover-traffic-management) | 프로비저닝된 배포를 위한 스필오버 트래픽 관리 가이드 |
| [파인 튜닝 가이드](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/fine-tuning?context=%2Fazure%2Fai-foundry%2Fcontext%2Fcontext&tabs=azure-openai&pivots=programming-language-studio) | 포괄적인 파인 튜닝 문서 |
| [프롬프트 캐싱 문서](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/prompt-caching) | 프롬프트 캐싱 구현 가이드 |
| [배치 API 문서](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/batch?tabs=global-batch%2Cstandard-input%2Cpython-secure&pivots=ai-foundry-portal) | Azure OpenAI 배치 API 문서 |


## Azure AI Foundry에서의 에이전트 AI

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [프로덕션에서 AI 애플리케이션 배포](https://github.com/microsoft/Deploy-Your-AI-Application-In-Production) | vNet에서 AI Foundry를 안전하게 배포, 프로덕션 준비 완료 |
| [대화 지식 마이닝 솔루션 가속기](https://github.com/microsoft/Conversation-Knowledge-Mining-Solution-Accelerator) | 대화 데이터 마이닝, 주제 추출, 인사이트 |
| [멀티 에이전트 커스텀 자동화 엔진 솔루션 가속기](https://github.com/microsoft/Multi-Agent-Custom-Automation-Engine-Solution-Accelerator) | 멀티 에이전트 자동화, 복잡한 비즈니스 오케스트레이션 |
| [콘텐츠 처리 솔루션 가속기](https://github.com/microsoft/content-processing-solution-accelerator) | 멀티모달 콘텐츠 추출 |
| [적응형 RAG 워크벤치](https://github.com/Azure-Samples/adaptive-rag-workbench) | 엔터프라이즈 AI 애플리케이션을 위한 3가지 고급 검색 증강 생성(RAG) 패턴을 시연하는 포괄적인 Microsoft 솔루션 가속기 |
| [멀티모달 모델 및 에이전트와의 상호작용](https://github.com/microsoft/Build25-LAB324) | Azure AI Foundry에서 멀티모달 모델 및 에이전트와의 상호작용을 위한 Build 2025 랩 콘텐츠 |
| [SK와 AI Foundry를 사용한 .NET 에이전트 앱](https://github.com/Azure-Samples/app-service-agentic-semantic-kernel-ai-foundry-agent) | Azure AI Foundry 에이전트와 Semantic Kernel 에이전트를 모두 통합하는 현대적인 .NET 웹 애플리케이션 |

## Azure AI 문서 인텔리전스 및 콘텐츠 이해

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [Azure 콘텐츠 이해 일반 샘플](https://github.com/Azure-Samples/azure-ai-content-understanding-python) | 콘텐츠 이해 프리뷰 API를 위한 즉시 사용 가능한 Python 샘플 |
| [Azure 검색과 콘텐츠 이해](https://github.com/Azure-Samples/azure-ai-search-with-content-understanding-python) | Azure 검색과 콘텐츠 이해를 결합한 통합 샘플 |
| [Azure 콘텐츠 이해와 OpenAI](https://github.com/Azure-Samples/azure-ai-content-understanding-with-azure-openai-python) | 콘텐츠 이해와 Azure OpenAI 통합을 시연하는 샘플 |
| [문서 인텔리전스 문서](https://learn.microsoft.com/azure/ai-services/document-intelligence) | Azure AI 문서 인텔리전스 공식 문서 |
| [콘텐츠 이해 문서](https://learn.microsoft.com/azure/ai-services/content-understanding/) | Azure AI 콘텐츠 이해 공식 문서 |
| [멀티모달 데이터 처리 비디오 시리즈](https://learn.microsoft.com/en-us/shows/multimodal-data-processing-with-azure-ai-content-understanding/) | 멀티모달 데이터 처리에 대한 교육용 비디오 시리즈 |
| [콘텐츠 이해 학습 경로](https://learn.microsoft.com/training/modules/analyze-content-ai/) | Azure AI로 콘텐츠 분석을 위한 교육 모듈 |
| [배치 API 문서](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/concept-batch-analysis?view=doc-intel-4.0.0) | 문서 인텔리전스 배치 API 가이드 |
| [문서 인텔리전스 스튜디오](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/studio-overview?view=doc-intel-4.0.0&tabs=di-studio) | 문서 인텔리전스 스튜디오 인터페이스 개요 |


## Azure AI Foundry 콘텐츠 안전

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [개인 식별 정보(PII) 필터](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/content-filter-personal-information?branch=release-build-ai-foundry) | 콘텐츠 안전 필터에서 PII 감지 및 차단에 대한 문서 |
| [콘텐츠 필터 프롬프트 쉴드](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/content-filter-prompt-shields?branch=release-build-ai-foundry) | 프롬프트 주입 보호에 대한 문서 |
| [프롬프트의 문서 임베딩](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/content-filter-document-embedding?branch=release-build-ai-foundry) | 문서 보안을 위한 XPIA 스포트라이팅 문서 |
| [요청 수준 콘텐츠 필터](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/content-filters#specify-a-content-filtering-configuration-at-request-time-preview) | API 요청 시 콘텐츠 필터 구성 가이드 |
| [신뢰할 수 있는 AI 개요](https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-use-of-ai-overview?branch=release-build-ai-foundry-non-FDP-features) | Azure AI Foundry에서 신뢰할 수 있는 AI에 대한 포괄적인 가이드 |


## Azure AI 모델 커스터마이징

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [E2E 디스틸레이션](https://github.com/microsoft/Build25-LAB329) | 엔드투엔드 디스틸레이션 실습 랩 |
| [o4-mini RFT](https://github.com/azure-ai-foundry/build-2025-demos/tree/main/Azure%20AI%20Model%20Customization/MSBuildRFTDemo) | o4-mini 모델을 위한 책임감 있는 파인 튜닝 데모 |
| [4.1을 사용한 비전 파인 튜닝](https://github.com/Azure/gen-cv/tree/main/vision-fine-tuning) | 비전 모델 파인 튜닝 샘플 |
| [RAFT 샘플](https://github.com/Azure-Samples/azure-openai-raft/tree/main) | 검색 증강 파인 튜닝 구현 |
| [파인 튜닝 문서](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/fine-tuning?context=%2Fazure%2Fai-foundry%2Fcontext%2Fcontext&tabs=azure-openai&pivots=programming-language-studio) | 공식 파인 튜닝 가이드 |
| [파인 튜닝 고려사항](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/fine-tuning-considerations?context=%2Fazure%2Fai-foundry%2Fcontext%2Fcontext) | 파인 튜닝 결정을 위한 모범 사례 |
| [모델 및 토큰 문서](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models?tabs=global-standard%2Cstandard-chat-completions) | 모델 및 토큰 사용에 대한 포괄적인 가이드 |


## Azure AI 검색 에이전트 검색

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [에이전트 검색 데모](https://capps-backend-pqyf4g35p3evg.redpebble-3e83d98f.eastus2.azurecontainerapps.io/) | 에이전트 검색 기능의 라이브 시연 |
| [멀티모달 데모](https://mmapp-nq6bj36spgzzs.azurewebsites.net/) | 라이브 멀티모달 검색 시연 |
| [에이전트 검색 샘플](https://github.com/Azure-Samples/azure-search-openai-demo) | 에이전트 검색 구현을 위한 코드 샘플 |
| [멀티모달 샘플](https://aka.ms/AIsearch-multimodal) | 멀티모달 검색 구현 샘플 |
| [Azure MCP](https://github.com/Azure/azure-mcp) | Azure용 모델 컨텍스트 프로토콜 구현 |
| [Foundry MCP](https://github.com/azure-ai-foundry/mcp-foundry) | Foundry 전용 모델 컨텍스트 프로토콜 구현 |
| [에이전트 서비스 및 원격 MCP](https://github.com/Azure-Samples/foundry-agent-service-remote-mcp-python) | Azure AI Foundry 에이전트 서비스 클라이언트를 쉽게 실행하고 Azure Functions 원격 MCP를 사용하여 사용자 정의 원격 MCP 서버를 클라우드에 추가하는 빠른 시작 템플릿 |
| [멀티모달용 샘플 PDF](https://github.com/Azure-Samples/azure-ai-search-multimodal-sample/blob/main/data/2024-State-of-AI-Change-Readiness-eBook.pdf) | 멀티모달 검색 테스트를 위한 샘플 문서 |
| [에이전트 검색 문서](https://learn.microsoft.com/en-us/azure/search/search-agentic-retrieval-concept) | 에이전트 검색에 대한 개념 가이드 |
| [에이전트 검색 빠른 시작](https://learn.microsoft.com/en-us/azure/search/search-get-started-agentic-retrieval?pivots=python) | 에이전트 검색 빠른 시작 가이드 |
| [에이전트 간 검색 가이드](https://learn.microsoft.com/en-us/azure/search/search-agentic-retrieval-how-to-pipeline) | 에이전트 간 검색 솔루션 구축 |
| [멀티모달 검색 문서](https://learn.microsoft.com/en-us/azure/search/multimodal-search-overview) | 멀티모달 검색에 대한 포괄적인 가이드 |


## Azure 오픈소스 AI 도구

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [Visual Studio Code용 AI 툴킷](https://marketplace.visualstudio.com/items?itemName=ms-windows-ai-studio.windows-ai-studio) | AI 툴킷은 에이전트 개발을 간소화하는 Visual Studio Code용 강력한 확장입니다 |
| [Visual Studio Code용 Azure AI Foundry](https://marketplace.visualstudio.com/items?itemName=TeamsDevApp.vscode-ai-foundry) | 번역 데모를 위한 프라이빗 iOS 앱 |
| [Microsoft 문서 번역](https://github.com/MicrosoftTranslator/DocumentTranslation) | 로컬 파일이나 네트워크 파일을 다양한 형식으로 100개 이상의 언어로 번역 |
| [Microsoft MarkItDown](https://github.com/microsoft/markitdown) | LLM 및 관련 텍스트 분석 파이프라인에서 사용하기 위해 다양한 파일을 마크다운으로 변환하는 경량 Python 유틸리티 |


## AML을 사용한 기본 모델에서 추론 모델로

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [GRPO 훈련 데모 비디오](https://www.youtube.com/watch?v=YOm_IQt3YWw) | 지시 모델을 추론 모델로 훈련하는 비디오 시연 |
| [Azure ML GRPO 예제](https://github.com/Azure/azureml-examples/tree/main/sdk/python/jobs/grpo) | Azure ML의 그룹 상대 정책 최적화를 위한 코드 예제 |


## Azure AI Foundry 로컬

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [Foundry Local](https://github.com/microsoft/Foundry-Local) | Foundry Local은 Azure 구독 없이도 Azure AI Foundry의 강력한 기능을 로컬 장치로 가져옵니다 |


## Azure AI Foundry 통합

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [AI Foundry 연결](https://github.com/Azure-Samples/AI-Foundry-Connections) | AI Foundry에서 리소스와 에이전트를 연결하기 위한 통합 샘플 및 템플릿 |
| [AI 게이트웨이](https://github.com/Azure-Samples/AI-Gateway) | Azure API 관리 및 AI Foundry를 사용한 생성형 AI 게이트웨이 패턴을 위한 실험적 랩 |


## Azure AI Foundry 워크샵 및 샘플

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [Azure AI Foundry 워크샵](https://github.com/Azure/ai-foundry-workshop) | Azure AI Foundry 위에서 지능형 앱과 AI 에이전트를 구축하는 과정을 안내하는 실습 워크샵 |
| [Azure AI 여행 에이전트 with Llamaindex.TS and MCP](https://github.com/Azure-Samples/azure-ai-travel-agents) | AI 여행 에이전트는 여러 AI 에이전트를 활용하여 여행사 운영을 향상시키는 강력한 엔터프라이즈 애플리케이션입니다. 이 애플리케이션은 LlamaIndex.TS가 여러 AI 에이전트를 오케스트레이션하여 직원들이 고객 문의를 처리하고, 목적지 추천을 제공하며, 여행 일정을 계획하는 것을 지원하는 방법을 보여줍니다. |
| [JS AI 빌드어톤](https://github.com/Azure-Samples/JS-AI-Build-a-thon?tab=readme-ov-file) | JS/TS 개발자가 Azure AI Foundry에서 AI 앱을 구축하고 AI 기술, 도구 및 프레임워크에 대한 더 깊은 이해를 얻을 수 있는 9개의 독특한 실습 퀘스트. |
| [Azure AI Foundry를 사용한 에이전트 시작하기](https://github.com/Azure-Samples/get-started-with-ai-agents) | 에이전트는 Azure AI 에이전트 서비스를 활용하고 업로드된 파일에서 지식 검색을 위해 파일 검색을 활용하여 인용이 포함된 응답을 생성할 수 있습니다. 솔루션에는 더 쉬운 문제 해결과 최적화된 성능을 보장하기 위한 추적 기능이 있는 내장 모니터링 기능도 포함되어 있습니다. |
| [RAG Time: RAG 마스터링을 위한 궁극의 가이드](https://github.com/microsoft/rag-time) | RAG Time으로 RAG를 마스터하세요! 검색 증강 생성으로 더 스마트한 AI 애플리케이션을 구축하는 방법을 배우세요. 이 리포지토리에는 초보자에서 RAG 전문가가 되기 위해 필요한 모든 것—단계별 가이드, 라이브 코딩 샘플, 전문가 인사이트가 포함되어 있습니다! |
| [RAG 채팅 앱 with Azure OpenAI and Azure AI Search (Python)](https://github.com/Azure-Samples/azure-search-openai-demo) | 이 솔루션은 RAG(검색 증강 생성)를 사용하여 자신의 문서에서 ChatGPT와 같은 프론트엔드 경험을 만듭니다. GPT 모델에 액세스하기 위해 Azure OpenAI 서비스를 사용하고, 데이터 인덱싱 및 검색을 위해 Azure AI Search를 사용합니다. |

## Microsoft 초급자 과정

| 저장소/링크 | 설명 |
|-----------------|-------------|
| [생성형 AI 초급자 과정](https://github.com/microsoft/generative-ai-for-beginners) | 21개 레슨의 포괄적인 과정으로 생성형 AI 애플리케이션 구축의 기초를 학습하세요 |
| [AI 에이전트 초급자 과정](https://github.com/microsoft/ai-agents-for-beginners) | 이 과정은 AI 에이전트 구축의 기초를 다루는 11개의 레슨으로 구성되어 있습니다. 각 레슨은 고유한 주제를 다루므로 어디서든 시작할 수 있습니다! |
| [MCP 초급자 과정](https://github.com/microsoft/mcp-for-beginners) | AI 개발자, 시스템 아키텍트 또는 소프트웨어 엔지니어이든 관계없이, 이 가이드는 MCP 기초와 구현 전략을 마스터하기 위한 포괄적인 리소스입니다. |
