# 🛰️ AI·개발 오픈소스 카탈로그

> **Trendchaser(AI/개발 트렌드 카톡방)** 큐레이션 + 직접 저장한 도구를 합쳐, GitHub 오픈소스 **240개**를 용도별로 정리했습니다.
>
> 🔥 = 트렌드방과 저장소 **양쪽에서 걸린 강한 신호** (23개) · ⭐ 스타는 GitHub API 기준 · 📅 마지막 업데이트(YYYY-MM) · 🗄️ 아카이브됨

*생성일 2026-07-12 · 총 240개 · 대분류 8개*

## 📑 목차
- **1. 🤖 AI 에이전트 · 코딩 하네스** (59)
  - 코딩 에이전트·하네스 (16)
  - 에이전트 스킬·플러그인 팩 (16)
  - 멀티·오케스트레이션 프레임워크 (17)
  - 에이전트 메모리·컨텍스트 (5)
  - 관측·거버넌스·패키지 (5)
- **2. 🔌 MCP 서버 · SDK** (12)
  - MCP 서버 (11)
  - MCP SDK (1)
- **3. 🧠 LLM 추론 · 서빙 · 모델** (26)
  - 로컬 추론·서빙 (10)
  - 모델·프레임워크·SDK (8)
  - 라우팅·게이트웨이·비용 (4)
  - 음성·TTS (4)
- **4. 🔍 RAG · 검색 · 문서 · 크롤링** (21)
  - 웹 크롤링·브라우저 자동화 (6)
  - 문서 변환·파싱·검색 (5)
  - 코드검색·지식그래프 (7)
  - RAG·리서치 플랫폼 (3)
- **5. 🛠️ 개발도구 · DevEx · 시스템** (27)
  - 보안 (3)
  - 런타임·언어·인프라 (14)
  - 터미널·에디터·Git (7)
  - 맥 유틸리티 (3)
- **6. 💼 도메인 특화 앱** (64)
  - 주식·투자·금융 (10)
  - 영상·이미지·미디어 (11)
  - 로보틱스·과학·기타 (9)
  - 법률·세무·규정(한국) (8)
  - UI·디자인 시스템 (10)
  - 콘텐츠·마케팅·SEO (8)
  - 생산성·지식관리 (8)
- **7. 📚 학습 · 연구 · 리소스** (11)
  - 큐레이션 리스트 (2)
  - 튜토리얼·학습 (5)
  - 학술·연구 에이전트 (4)
- **8. 🧩 기타 · 커뮤니티** (20)
  - 기타 (20)

---

## 1. 🤖 AI 에이전트 · 코딩 하네스  ·  59개

### 코딩 에이전트·하네스

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
| 🔥 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 137.5k | Python | 2026-07 | 터미널에서 코드베이스를 이해하고 작업하는 앤트로픽 공식 코딩 에이전트 |
| 🔥 | [github/spec-kit](https://github.com/github/spec-kit) | 119.7k | Python | 2026-07 | 스펙 주도 개발(SDD)을 시작하게 돕는 GitHub 공식 툴킷 |
| 🔥 | [openai/codex](https://github.com/openai/codex) | 97.3k | Rust | 2026-07 | 터미널에서 도는 OpenAI의 경량 코딩 에이전트 |
|  | [openhands/openhands](https://github.com/OpenHands/OpenHands) | 80.5k | Python | 2026-07 | 목표만 던지면 코드 작성부터 PR까지 자동 수행하는 AI 개발 에이전트 |
|  | [aaif-goose/goose](https://github.com/aaif-goose/goose) | 51.1k | Rust | 2026-07 | 설치·실행·수정·테스트까지 하는 확장형 오픈소스 AI 에이전트(Block 제작) |
|  | [hmbown/codewhale](https://github.com/Hmbown/CodeWhale) | 39.7k | Rust | 2026-07 | 커뮤니티 주도 오픈소스 에이전트 하네스(구 deepseek-tui) |
|  | [continuedev/continue](https://github.com/continuedev/continue) | 34.8k | TypeScript | 2026-07 | 오픈소스 코딩 에이전트(IDE·CLI) |
|  | [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) | 27.8k | JavaScript | 2026-07 | Claude Code에서 Codex로 코드리뷰·작업 위임 |
|  | [xiaomimimo/mimo-code](https://github.com/XiaomiMiMo/MiMo-Code) | 11.8k | TypeScript | 2026-07 | 샤오미 MiMo 모델·에이전트 공진화 코딩 CLI |
|  | [1jehuang/jcode](https://github.com/1jehuang/jcode) | 8.3k | Rust | 2026-07 | 경량 코딩 에이전트 하네스 |
|  | [aattaran/deepclaude](https://github.com/aattaran/deepclaude) | 2.2k | JavaScript | 2026-05 | Claude Code 에이전트 루프를 DeepSeek·OpenRouter 등 백엔드로 구동 |
|  | [first-fluke/oh-my-agent](https://github.com/first-fluke/oh-my-agent) | 1.2k | TypeScript | 2026-07 | 벤더 독립적·프로젝트별 스킬/워크플로우 에이전트 하네스 |
|  | [kstost/cokacdir](https://github.com/kstost/cokacdir) | 352 | Rust | 2026-07 | 코드 에이전트 관련 CLI 유틸(코각코) |
|  | [dgk-dev/dgk-gpt](https://github.com/dgk-dev/dgk-gpt) | 51 | JavaScript | 2026-03 | 스킬·AGENTS.md·MCP 기본값 포함한 안전한 Codex CLI 셋업 설치기 |
|  | [project820/gjc-multivendor-setup-guide](https://github.com/project820/gjc-multivendor-setup-guide) | 29 | Shell | 2026-07 | 5구독 멀티벤더(Codex·Opus·LLM Council) 코딩 셋업 통합 가이드 |
|  | [yong076/divecode](https://github.com/yong076/divecode) | 0 | Shell | 2026-05 | 바이브코딩의 반대편 — 스펙부터 꼼꼼히 짚는 디테일 우선 코딩 스킬셋 |

### 에이전트 스킬·플러그인 팩

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [obra/superpowers](https://github.com/obra/superpowers) | 252.7k | Shell | 2026-07 | 에이전틱 스킬 프레임워크 + 개발방법론(Claude Code) |
| 🔥 | [affaan-m/ecc](https://github.com/affaan-m/ECC) | 228.7k | JavaScript | 2026-07 | 스킬·본능·메모리·보안을 묶은 에이전트 하네스 성능 최적화(Everything Claude Code) |
| 🔥 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | 191.0k | - | 2026-04 | 카파시의 LLM 통찰을 담은 CLAUDE.md 한 파일 |
|  | [mattpocock/skills](https://github.com/mattpocock/skills) | 166.2k | Shell | 2026-07 | Matt Pocock의 실전 엔지니어용 Claude 스킬 모음 |
|  | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 77.4k | JavaScript | 2026-07 | Addy Osmani의 프로덕션급 코딩 에이전트 스킬 모음 |
|  | [vercel-labs/skills](https://github.com/vercel-labs/skills) | 25.9k | TypeScript | 2026-07 | Vercel의 오픈 에이전트 스킬 도구(npx skills) |
|  | [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | 22.5k | Python | 2026-07 | 지식노동자용 Claude Cowork 오픈소스 플러그인 모음 |
|  | [muratcankoylan/agent-skills-for-context-engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) | 17.1k | Python | 2026-07 | 컨텍스트 엔지니어링·멀티에이전트용 종합 스킬 모음 |
|  | [composiohq/awesome-codex-skills](https://github.com/ComposioHQ/awesome-codex-skills) | 14.9k | Python | 2026-05 | Codex CLI·API 워크플로우 자동화용 실전 스킬 큐레이션 |
|  | [google/skills](https://github.com/google/skills) | 14.5k | Python | 2026-07 | 구글 제품·기술용 공식 Agent Skills |
|  | [google/agents-cli](https://github.com/google/agents-cli) | 5.0k | Python | 2026-07 | 코딩 어시스턴트를 에이전트 제작 전문가로 만드는 구글 CLI·스킬 |
|  | [nvidia/skills](https://github.com/NVIDIA/skills) | 2.4k | Python | 2026-07 | NVIDIA 공개 Verified Agent Skills |
|  | [modu-ai/cowork-plugins](https://github.com/modu-ai/cowork-plugins) | 252 | HTML | 2026-06 | 한국 실무 도메인(세무·법률·HR·마케팅) Claude Cowork 플러그인 마켓 |
|  | [alexzio00/sovereign-skills](https://github.com/AlexZio00/sovereign-skills) | 114 | Python | 2026-07 | 셋업·스코프·리뷰·보안 등 프로덕션급 코딩 에이전트 스킬 18종 |
|  | [hostingglobal-tech/claude-code-os](https://github.com/Hostingglobal-Tech/claude-code-os) | 103 | Shell | 2026-06 | Claude Code가 OS인 부팅형 LiveCD |
|  | [vyvhouse/oh-my-destructor](https://github.com/vyvhouse/oh-my-destructor) | 29 | Shell | 2026-06 | Oh My Claude Code 안전 제거 도구 |

### 멀티·오케스트레이션 프레임워크

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
| 🔥 | [nousresearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 213.4k | Python | 2026-07 | 함께 성장하는 개인 에이전트(Nous Research Hermes) |
| 🔥 | [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | 130.6k | Shell | 2026-07 | 144명+ AI 전문가를 팀으로 고용하는 AI 에이전시 오픈소스 |
| 🔥 | [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 76.8k | Python | 2026-07 | 바이트댄스가 공개한 장기 리서치·코딩·창작 슈퍼에이전트 하네스 |
|  | [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 64.1k | TypeScript | 2026-07 | 자율 멀티에이전트 스웜을 배치·조율하는 메타 하네스 |
|  | [hkuds/cli-anything](https://github.com/HKUDS/CLI-Anything) | 45.2k | Python | 2026-07 | 모든 소프트웨어를 에이전트 네이티브로 만드는 CLI-Hub |
|  | [multica-ai/multica](https://github.com/multica-ai/multica) | 39.9k | Go | 2026-07 | 코딩 에이전트를 팀원처럼 관리하는 오픈소스 매니지드 에이전트 플랫폼 |
| 🔥 | [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | 34.7k | Rust | 2026-07 | 내 삶의 로컬 메모리를 쌓는 개인 초지능 오케스트레이터 |
|  | [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | 27.8k | Python | 2026-07 | OpenAI의 경량 멀티에이전트 워크플로우 프레임워크 |
|  | [nesquena/hermes-webui](https://github.com/nesquena/hermes-webui) | 15.9k | Python | 2026-07 | Hermes 에이전트를 웹·모바일에서 쓰는 WebUI |
|  | [fathah/hermes-desktop](https://github.com/fathah/hermes-desktop) | 13.3k | TypeScript | 2026-07 | Hermes 에이전트 데스크톱 컴패니언 앱 |
|  | [q00/ouroboros](https://github.com/Q00/ouroboros) | 4.9k | Python | 2026-07 | 프롬프트 대신 스펙으로 구동하는 Agent OS |
|  | [strukto-ai/mirage](https://github.com/strukto-ai/mirage) | 3.3k | TypeScript | 2026-07 | AI 에이전트용 통합 가상 파일시스템 |
|  | [google/ax](https://github.com/google/ax) | 1.8k | Go | 2026-07 | 구글 오픈소스 분산 에이전트 런타임 |
|  | [salomondiei08/oh-my-hermes](https://github.com/Salomondiei08/oh-my-hermes) | 691 | Shell | 2026-07 | Hermes 에이전트로 앱을 빌드·배포·운영하는 워크플로우 레이어 |
|  | [aronprins/paperclip-desktop](https://github.com/aronprins/paperclip-desktop) | 551 | TypeScript | 2026-07 | AI 에이전트 플랫폼 Paperclip을 앱처럼 쓰는 비공식 데스크톱 래퍼 |
|  | [agentlas-ai/agentlas-os](https://github.com/agentlas-ai/Agentlas-OS) | 134 | Python | 2026-07 | 전문 에이전트를 허브에 두고 작업별 임시 오케스트레이터를 띄우는 Agent OS |
|  | [chrisryugj/hermes-dashboard](https://github.com/chrisryugj/hermes-dashboard) | 33 | HTML | 2026-04 | Hermes 게이트웨이 웹 대시보드(설정·MCP·크론·모델 관리) |

### 에이전트 메모리·컨텍스트

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
| 🔥 | [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) | 58.6k | Python | 2026-07 | LLM 도달 전 출력·로그·RAG 청크를 압축해 토큰 60~95% 절감 |
|  | [getzep/graphiti](https://github.com/getzep/graphiti) | 28.6k | Python | 2026-07 | AI 에이전트용 실시간 지식그래프 메모리(Zep) |
| 🔥 | [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory) | 25.0k | TypeScript | 2026-07 | 벤치마크 기반 1위 코딩 에이전트 영구 메모리 |
|  | [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | 18.3k | Python | 2026-07 | 대화 저장을 넘어 '학습'하는 에이전트 메모리 |
|  | [jung-wan-kim/memory-bank](https://github.com/jung-wan-kim/memory-bank) | 129 | TypeScript | 2026-07 | RAG·온톨로지로 Claude Code 컨텍스트 관리 |

### 관측·거버넌스·패키지

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [panniantong/agent-reach](https://github.com/Panniantong/Agent-Reach) | 55.1k | Python | 2026-07 | 트위터·레딧·유튜브·깃허브를 읽고 검색하는 에이전트의 '눈' |
|  | [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 51.6k | Python | 2026-07 | 레딧·X·유튜브·HN을 훑어 최근 30일 트렌드를 합성하는 에이전트 스킬 |
|  | [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | 4.8k | Python | 2026-07 | AI 에이전트 거버넌스(정책·제로트러스트·샌드박싱) 툴킷 |
|  | [microsoft/apm](https://github.com/microsoft/apm) | 3.2k | Python | 2026-07 | MS의 에이전트 패키지 매니저 |
|  | [taewooopark/agent-blackbox](https://github.com/TaewoooPark/Agent-Blackbox) | 47 | TypeScript | 2026-06 | 코딩 에이전트용 로컬 플라이트 레코더 — 실행을 세션맵으로 리플레이 |

---

## 2. 🔌 MCP 서버 · SDK  ·  12개

### MCP 서버

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
| 🔥 | [chromedevtools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | 46.7k | TypeScript | 2026-07 | 코딩 에이전트에 Chrome DevTools의 '눈'을 달아주는 MCP |
|  | [czlonkowski/n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | 22.3k | TypeScript | 2026-07 | Claude로 n8n 워크플로우를 만들어주는 MCP |
|  | [excalidraw/excalidraw-mcp](https://github.com/excalidraw/excalidraw-mcp) | 4.9k | TypeScript | 2026-03 | Excalidraw 공식 MCP — 아키텍처·흐름도 작성 |
|  | [chrisryugj/korean-law-mcp](https://github.com/chrisryugj/korean-law-mcp) | 2.2k | TypeScript | 2026-07 | 법제처 국가법령정보 MCP — 법령·판례·인용 환각 검증 |
|  | [syedazharmbnr1/claude-chatgpt-mcp](https://github.com/syedazharmbnr1/claude-chatgpt-mcp) | 794 | JavaScript | 2025-11 | 맥 ChatGPT 데스크톱 앱을 Claude에서 제어하는 MCP |
|  | [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) | 613 | Python | 2025-05 | 수학 애니메이션 Manim MCP 서버 |
|  | [harimxchoi/google-surf-mcp](https://github.com/HarimxChoi/google-surf-mcp) | 263 | TypeScript | 2026-07 | 검색+fetch+논문추출을 하나로 대체하는 구글 검색 MCP |
|  | [mdn/mcp](https://github.com/mdn/mcp) | 163 | JavaScript | 2026-07 | MDN 웹 문서 MCP 서버(프로토타입) |
|  | [emceekim/korea-finance-mcp](https://github.com/emceeKim/korea-finance-mcp) | 53 | TypeScript | 2026-07 | 자본시장법 준수 한국 금융 MCP(ECOS·실거래가·DART 등 15툴) |
|  | [hueflowstudio/hueflow-sketchup-mcp](https://github.com/hueflowstudio/hueflow-sketchup-mcp) | 8 | Ruby | 2026-04 | SketchUp을 Claude에 연결하는 한국어 MCP |
|  | [taewooopark/trendchaser-mcp](https://github.com/TaewoooPark/Trendchaser-mcp) | 3 | JavaScript | 2026-06 | Trendchaser AI/개발 트렌드 피드를 LLM에 노출하는 읽기전용 MCP |

### MCP SDK

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) | 23.6k | Python | 2026-07 | MCP 서버·클라이언트 공식 파이썬 SDK |

---

## 3. 🧠 LLM 추론 · 서빙 · 모델  ·  26개

### 로컬 추론·서빙

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [ollama/ollama](https://github.com/ollama/ollama) | 176.0k | Go | 2026-07 | 로컬에서 Qwen·Gemma·DeepSeek 등 모델을 손쉽게 구동 |
|  | [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) | 120.1k | C++ | 2026-07 | C/C++ LLM 추론 엔진 |
|  | [vllm-project/vllm](https://github.com/vllm-project/vllm) | 86.0k | Python | 2026-07 | 고처리량·메모리 효율 LLM 추론·서빙 엔진 |
|  | [sgl-project/sglang](https://github.com/sgl-project/sglang) | 30.2k | Python | 2026-07 | 대규모·멀티모달 모델 고성능 서빙 프레임워크 |
|  | [andyyyy64/whichllm](https://github.com/Andyyyy64/whichllm) | 5.8k | Python | 2026-07 | 내 하드웨어에서 실제로 잘 도는 로컬 LLM을 랭킹 |
|  | [raullenchai/rapid-mlx](https://github.com/raullenchai/Rapid-MLX) | 3.3k | Python | 2026-07 | 애플 실리콘용 초고속 로컬 AI 엔진(Ollama 대비 4.2배) |
|  | [cactus-compute/needle](https://github.com/cactus-compute/needle) | 2.7k | Python | 2026-07 | 초소형 기기에서 도는 26M 함수호출 모델 |
|  | [tsotchke/gpt2-basic](https://github.com/tsotchke/gpt2-basic) | 33 | Python | 2026-05 | BASIC/DOS(486)에서 도는 QEMU 검증 트랜스포머 런타임 |
|  | [furiosa-ai/async-opd](https://github.com/furiosa-ai/async-opd) | 22 | Python | 2026-06 | 퓨리오사AI 비동기 추론 관련(async-opd) |
|  | [taewooopark/drift](https://github.com/TaewoooPark/DRIFT) | 16 | Python | 2026-07 | 맥(MPS)+윈도우(CUDA)에 걸쳐 하나의 LLM을 이기종 파이프라인 추론 |

### 모델·프레임워크·SDK

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [huggingface/transformers](https://github.com/huggingface/transformers) | 162.5k | Python | 2026-07 | 최신 ML 모델 정의 프레임워크(허깅페이스) |
|  | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 141.6k | Python | 2026-07 | 에이전트 엔지니어링 플랫폼(LangChain) |
|  | [openai/openai-python](https://github.com/openai/openai-python) | 31.3k | Python | 2026-07 | OpenAI API 공식 파이썬 라이브러리 |
|  | [google-research/timesfm](https://github.com/google-research/timesfm) | 26.8k | Python | 2026-07 | 구글의 시계열 파운데이션 모델(TimesFM) |
|  | [robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map) | 10.5k | Python | 2026-07 | 스트리밍 데이터로 3D 장면을 복원하는 피드포워드 파운데이션 모델 |
|  | [huggingface/accelerate](https://github.com/huggingface/accelerate) | 9.8k | Python | 2026-07 | PyTorch 모델 분산 학습·실행 간편화 |
|  | [anthropics/anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python) | 3.7k | Python | 2026-07 | 앤트로픽 공식 파이썬 SDK |
|  | [mistralai/client-python](https://github.com/mistralai/client-python) | 755 | Python | 2026-07 | Mistral AI 플랫폼 파이썬 클라이언트 |

### 라우팅·게이트웨이·비용

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [cheahjs/free-llm-api-resources](https://github.com/cheahjs/free-llm-api-resources) | 26.9k | Python | 2026-07 | API로 쓰는 무료 LLM 추론 리소스 목록 |
| 🔥 | [decolua/9router](https://github.com/decolua/9router) | 21.8k | JavaScript | 2026-07 | Claude·Codex·Cursor 등을 무료 모델에 연결하는 AI 게이트웨이 |
| 🗄️ | [tensorzero/tensorzero](https://github.com/tensorzero/tensorzero) | 11.7k | Rust | 2026-06 | LLM 게이트웨이·관측·평가·최적화를 묶은 오픈소스 LLMOps(아카이브) |
|  | [automazeio/vibeproxy](https://github.com/automazeio/vibeproxy) | 3.2k | Swift | 2026-07 | Claude·ChatGPT 구독을 API키 없이 코딩툴에 쓰는 맥 메뉴바 앱 |

### 음성·TTS

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [microsoft/vibevoice](https://github.com/microsoft/VibeVoice) | 50.0k | Python | 2026-07 | MS의 오픈소스 프론티어 음성 AI |
|  | [openbmb/voxcpm](https://github.com/OpenBMB/VoxCPM) | 33.2k | Python | 2026-07 | 토크나이저 없는 다국어 TTS·음성복제(VoxCPM2) |
|  | [supertone-inc/supertonic](https://github.com/supertone-inc/supertonic) | 13.0k | Swift | 2026-06 | 슈퍼톤의 온디바이스 다국어 초고속 TTS(ONNX) |
|  | [dograh-hq/dograh](https://github.com/dograh-hq/dograh) | 4.8k | Python | 2026-07 | Vapi·Retell 대체 셀프호스팅 음성 AI 플랫폼 |

---

## 4. 🔍 RAG · 검색 · 문서 · 크롤링  ·  21개

### 웹 크롤링·브라우저 자동화

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) | 72.4k | Python | 2026-07 | LLM 친화적 오픈소스 웹 크롤러·스크래퍼 |
| 🔥 | [d4vinci/scrapling](https://github.com/D4Vinci/Scrapling) | 69.2k | Python | 2026-07 | 단일요청부터 대규모 크롤까지 처리하는 적응형 스크래핑 프레임워크 |
|  | [cloakhq/cloakbrowser](https://github.com/CloakHQ/CloakBrowser) | 28.1k | Python | 2026-07 | 모든 봇탐지를 통과하는 스텔스 크로미움(Playwright 대체) |
| 🔥 | [browserbase/skills](https://github.com/browserbase/skills) | 3.6k | JavaScript | 2026-07 | 웹 접근용 Browserbase 공식 에이전트 스킬(CAPTCHA·프록시) |
|  | [tamnd/kage](https://github.com/tamnd/kage) | 2.7k | Go | 2026-07 | JS 제거하고 웹사이트를 오프라인 열람용으로 미러링 |
|  | [lidge-jun/agbrowse](https://github.com/lidge-jun/agbrowse) | 200 | JavaScript | 2026-07 | MCP 토큰 부담 없는 AI 에이전트용 브라우저 자동화 툴킷 |

### 문서 변환·파싱·검색

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
| 🔥 | [microsoft/markitdown](https://github.com/microsoft/markitdown) | 165.0k | Python | 2026-06 | 워드·엑셀 등 오피스 문서를 마크다운으로 변환(MS) |
|  | [teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py) | 17.6k | Python | 2026-07 | 구글 NotebookLM 비공식 파이썬 API·에이전트 스킬 |
|  | [chrisryugj/kordoc](https://github.com/chrisryugj/kordoc) | 1.4k | TypeScript | 2026-07 | HWP·HWPX·PDF·오피스 → 마크다운(신구대조·양식채우기·MCP) |
|  | [chrisryugj/docufinder](https://github.com/chrisryugj/Docufinder) | 429 | Rust | 2026-07 | HWPX·PDF·오피스 수천 건 본문을 1초에 로컬 검색 |
|  | [seunghan91/mdm-desktop](https://github.com/seunghan91/mdm-desktop) | 36 | - | 2026-04 | HWP·PDF·DOCX → 마크다운 데스크톱 변환기 |

### 코드검색·지식그래프

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [graphify-labs/graphify](https://github.com/Graphify-Labs/graphify) | 82.7k | Python | 2026-07 | 폴더를 쿼리 가능한 코드 지식으로 만드는 코딩 어시스턴트 스킬 |
| 🔥 | [egonex-ai/understand-anything](https://github.com/Egonex-AI/Understand-Anything) | 73.4k | TypeScript | 2026-07 | 코드·문서를 탐색 가능한 인터랙티브 지식그래프로 변환 |
| 🔥 | [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph) | 59.3k | TypeScript | 2026-07 | 코드 변경 시 자동 동기화되는 사전 인덱싱 코드 지식그래프 |
| 🔥 | [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | 19.5k | Python | 2026-06 | MCP·CLI용 로컬 코드 인텔리전스 그래프 |
|  | [ryancodrai/turbovec](https://github.com/RyanCodrai/turbovec) | 12.7k | Python | 2026-06 | TurboQuant 기반 Rust 벡터 인덱스(파이썬 바인딩) |
|  | [minishlab/semble](https://github.com/MinishLab/semble) | 5.6k | Python | 2026-07 | grep+read 대비 토큰 98% 절감하는 에이전트용 코드 검색 |
|  | [johunsang/semble_rs](https://github.com/johunsang/semble_rs) | 136 | Rust | 2026-06 | Rust 하이브리드(BM25+시맨틱) AI 에이전트용 코드 검색 |

### RAG·리서치 플랫폼

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx) | 30.8k | Python | 2026-07 | 슬랙·드라이브·깃허브 50여 소스 연결 사내 AI 챗봇 플랫폼 |
|  | [vibrantlabsai/ragas](https://github.com/vibrantlabsai/ragas) | 14.8k | Python | 2026-02 | LLM 앱·RAG 응답 품질 평가 툴 |
|  | [learningcircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research) | 8.7k | Python | 2026-07 | 로컬·클라우드 LLM로 도는 딥리서치(SimpleQA 95%) |

---

## 5. 🛠️ 개발도구 · DevEx · 시스템  ·  27개

### 보안

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [soxoj/maigret](https://github.com/soxoj/maigret) | 35.3k | Python | 2026-07 | 유저네임으로 3000+ 사이트에서 신상 수집 OSINT |
|  | [bigbodycobain/shadowbroker](https://github.com/BigBodyCobain/Shadowbroker) | 9.7k | Python | 2026-07 | 전용기·자산 추적 등 글로벌 OSINT 도구 |
|  | [anthropics/defending-code-reference-harness](https://github.com/anthropics/defending-code-reference-harness) | 6.4k | Python | 2026-07 | 위협모델링·스캔·패치·자율스캔 하네스(앤트로픽 보안) |

### 런타임·언어·인프라

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [golang/go](https://github.com/golang/go) | 135.4k | Go | 2026-07 | Go 프로그래밍 언어 |
|  | [oven-sh/bun](https://github.com/oven-sh/bun) | 94.6k | Rust | 2026-07 | 초고속 올인원 자바스크립트 런타임·번들러(Bun) |
|  | [syncthing/syncthing](https://github.com/syncthing/syncthing) | 86.3k | Go | 2026-07 | 오픈소스 P2P 지속 파일 동기화 |
|  | [apple/container](https://github.com/apple/container) | 47.6k | Swift | 2026-07 | 맥에서 경량 VM으로 리눅스 컨테이너 실행(Apple) |
|  | [valvesoftware/gamenetworkingsockets](https://github.com/ValveSoftware/GameNetworkingSockets) | 9.8k | C++ | 2026-06 | UDP 신뢰·비신뢰 메시지 P2P 네트워킹(Valve) |
|  | [rsyncproject/rsync](https://github.com/RsyncProject/rsync) | 5.0k | C | 2026-06 | 빠른 증분 파일 전송 유틸(rsync) |
|  | [microsoft/coreutils](https://github.com/microsoft/coreutils) | 4.7k | Rust | 2026-06 | 윈도우용 coreutils 패키징(MS) |
|  | [microsoft/pg_durable](https://github.com/microsoft/pg_durable) | 2.5k | Rust | 2026-07 | PostgreSQL 인-DB 내구 실행(durable execution) |
|  | [c0dejedi/nbd-vram](https://github.com/c0deJedi/nbd-vram) | 503 | Shell | 2026-07 | NVIDIA GPU VRAM을 리눅스 스왑으로 사용 |
|  | [fractalfir/crustc](https://github.com/FractalFir/crustc) | 461 | C | 2026-07 | rustc 전체를 C로 번역한 프로젝트 |
|  | [tech4bot/rk3562deb](https://github.com/tech4bot/rk3562deb) | 387 | C | 2026-06 | RK3562 보드용 데비안 관련 |
|  | [nishantjoshi00/sidekick](https://github.com/NishantJoshi00/sidekick) | 30 | Rust | 2026-06 | sidekick(Rust 유틸) |
|  | [stemps/treehouse](https://github.com/stemps/treehouse) | 18 | Go | 2026-06 | treehouse(Go 유틸) |
|  | [hostingglobal-tech/vke-scaleout-bmt](https://github.com/Hostingglobal-Tech/vke-scaleout-bmt) | 1 | Shell | 2026-06 | Vultr Kubernetes 스케일아웃 부하 벤치마크 |

### 터미널·에디터·Git

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [microsoft/vscode](https://github.com/microsoft/vscode) | 187.5k | TypeScript | 2026-07 | Visual Studio Code |
| 🔥 | [warpdotdev/warp](https://github.com/warpdotdev/warp) | 63.1k | Rust | 2026-07 | 터미널에서 태어난 에이전틱 개발환경 Warp(오픈소스 전환) |
|  | [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty) | 58.0k | Zig | 2026-07 | 빠른 크로스플랫폼 GPU 가속 터미널 에뮬레이터 |
|  | [sourcegit-scm/sourcegit](https://github.com/sourcegit-scm/sourcegit) | 5.5k | C# | 2026-07 | 무료 크로스플랫폼 Git GUI 클라이언트 |
|  | [helvesec/rmux](https://github.com/Helvesec/rmux) | 2.4k | Rust | 2026-07 | 타입드 SDK로 어떤 CLI·TUI든 코드로 구동하는 Rust 멀티플렉서 |
|  | [duanebester/gooey](https://github.com/duanebester/gooey) | 570 | Zig | 2026-07 | GPU 렌더링 하이브리드 UI 프레임워크(Zig) |
|  | [betive37/autolimit](https://github.com/betive37/autolimit) | 2 | Python | 2026-07 | 인터랙티브 CLI용 터미널 독립 PTY 래퍼 |

### 맥 유틸리티

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [tw93/mole](https://github.com/tw93/Mole) | 58.7k | Shell | 2026-07 | 터미널에서 맥을 청소·제거·분석·모니터링 |
|  | [darrylmorley/whatcable](https://github.com/darrylmorley/whatcable) | 6.4k | Swift | 2026-07 | 꽂힌 USB-C 케이블의 실제 성능을 알려주는 맥 메뉴바 앱 |
|  | [h5nam/mq-dir](https://github.com/h5nam/mq-dir) | 67 | Swift | 2026-07 | 4분할 네이티브 맥 파일 매니저(Q-Dir 대안) |

---

## 6. 💼 도메인 특화 앱  ·  64개

### 주식·투자·금융

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
| 🔥 | [tauricresearch/tradingagents](https://github.com/TauricResearch/TradingAgents) | 92.5k | Python | 2026-07 | 멀티에이전트 LLM 금융 트레이딩 프레임워크 |
|  | [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | 61.2k | Python | 2026-07 | 애널리스트·리스크·PM 역할 AI 헤지펀드 팀 |
|  | [virattt/dexter](https://github.com/virattt/dexter) | 27.4k | TypeScript | 2026-07 | 심층 금융 리서치 자율 에이전트 |
|  | [ranaroussi/yfinance](https://github.com/ranaroussi/yfinance) | 24.7k | Python | 2026-07 | 야후 파이낸스에서 시세 데이터 가져오는 파이썬 라이브러리 |
| 🔥 | [hkuds/ai-trader](https://github.com/HKUDS/AI-Trader) | 20.7k | Python | 2026-06 | 100% 완전자동 에이전트 네이티브 트레이딩 |
|  | [hkuds/vibe-trading](https://github.com/HKUDS/Vibe-Trading) | 20.0k | Python | 2026-07 | 개인용 바이브 트레이딩 에이전트 |
|  | [ai4finance-foundation/finrobot](https://github.com/AI4Finance-Foundation/FinRobot) | 7.5k | Jupyter Notebook | 2026-07 | LLM 금융분석 오픈소스 AI 에이전트 플랫폼(FinRobot) |
|  | [the-swarm-corporation/autohedge](https://github.com/The-Swarm-Corporation/AutoHedge) | 3.8k | Python | 2026-05 | 스웜 지능 기반 자율 헤지펀드 구축 |
|  | [eddmpython/dartlab](https://github.com/eddmpython/dartlab) | 197 | Python | 2026-07 | 한국 DART+SEC EDGAR 공시를 구조화 파이썬 데이터로 |
|  | [junghoonghae/smartstore-cli](https://github.com/JungHoonGhae/smartstore-cli) | 22 | Go | 2026-03 | 네이버 스마트스토어 셀러센터 데이터 접근 CLI |

### 영상·이미지·미디어

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
| 🗄️ | [siddharthvaddem/openscreen](https://github.com/siddharthvaddem/openscreen) | 39.3k | TypeScript | 2026-06 | 워터마크 없는 무료 오픈소스 화면 녹화(아카이브) |
|  | [calesthio/openmontage](https://github.com/calesthio/OpenMontage) | 37.3k | Python | 2026-07 | 500+ 스킬을 가진 세계 최초 에이전틱 영상 제작 시스템 |
|  | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 34.4k | TypeScript | 2026-07 | HTML을 쓰면 영상으로 렌더(HeyGen, 에이전트용) |
|  | [ath-maas/pixelle-video](https://github.com/ATH-MaaS/Pixelle-Video) | 25.2k | Python | 2026-06 | AI 완전자동 숏폼 영상 엔진 |
|  | [browser-use/video-use](https://github.com/browser-use/video-use) | 16.7k | Python | 2026-07 | 코딩 에이전트로 영상을 편집 |
| 🔥 | [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro) | 10.3k | Swift | 2026-07 | AI를 위한 맥OS 영상 편집기 |
|  | [parthjadhav/app-store-screenshots](https://github.com/ParthJadhav/app-store-screenshots) | 6.0k | TypeScript | 2026-07 | AI로 앱스토어 스크린샷 엔드투엔드 제작 |
|  | [augani/openreel-video](https://github.com/Augani/openreel-video) | 3.9k | TypeScript | 2026-06 | 브라우저 기반 오픈소스 CapCut 대안 영상편집기 |
|  | [nomadamas/god-tibo-imagen](https://github.com/NomaDamas/god-tibo-imagen) | 152 | JavaScript | 2026-06 | Codex 구독으로 GPT image 2.0을 쓰는 패키지 |
|  | [okdalto/siljangnim](https://github.com/okdalto/siljangnim) | 23 | JavaScript | 2026-04 | 자연어로 미디어아트 씬을 만드는 실시간 그래픽 툴 |
|  | [kyejin1991/audio-mastering](https://github.com/kyejin1991/AUDIO-MASTERING) | 2 | Python | 2026-05 | 유튜브용 AI 오디오 마스터링 |

### 로보틱스·과학·기타

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [librepods-org/librepods](https://github.com/librepods-org/librepods) | 28.9k | Kotlin | 2026-06 | 애플 생태계에서 해방된 에어팟(안드로이드·리눅스) |
|  | [fulu-foundation/orcaslicer-bambulab](https://github.com/FULU-Foundation/OrcaSlicer-bambulab) | 7.0k | C++ | 2026-07 | OrcaSlicer 뱀부랩 3D 프린팅 슬라이서 |
|  | [nvlabs/gr00t-wholebodycontrol](https://github.com/NVlabs/GR00T-WholeBodyControl) | 2.9k | Python | 2026-07 | 휴머노이드 전신 제어(GR00T WBC, NVIDIA) |
|  | [synthetic-sciences/openscience](https://github.com/synthetic-sciences/openscience) | 2.2k | TypeScript | 2026-07 | 과학 연구용 오픈소스 AI 워크벤치 |
|  | [ammaarreshi/generals-mac-ios-ipad](https://github.com/ammaarreshi/Generals-Mac-iOS-iPad) | 1.4k | C++ | 2026-07 | 커맨드앤컨커 제너럴을 맥·아이폰에서 네이티브 구동 |
|  | [robinostlund/homeassistant-volkswagencarnet](https://github.com/robinostlund/homeassistant-volkswagencarnet) | 663 | Python | 2026-07 | 폭스바겐 Carnet 홈어시스턴트 컴포넌트 |
|  | [sander110419/lightroom-cc-on-linux](https://github.com/sander110419/lightroom-cc-on-linux) | 192 | C | 2026-05 | Wine으로 리눅스에서 어도비 라이트룸 CC 실행 |
|  | [taewooopark/maglab](https://github.com/TaewoooPark/MagLab) | 9 | Python | 2026-06 | 자성·스핀트로닉스 연구용 AI-for-Science 하네스 |
|  | [taewooopark/minecraft-26.1-cobblemon-ralph](https://github.com/TaewoooPark/minecraft-26.1-cobblemon-ralph) | 1 | Shell | 2026-05 | Ralph 자율루프로 마인크래프트 코블몬 모드 포팅 |

### 법률·세무·규정(한국)

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [anthropics/financial-services](https://github.com/anthropics/financial-services) | 33.4k | Python | 2026-06 | 금융 서비스용 Claude 리소스 |
|  | [anthropics/claude-for-legal](https://github.com/anthropics/claude-for-legal) | 8.7k | Python | 2026-07 | 법률 워크플로우용 Claude 플러그인 모음 |
|  | [kimlawtech/korean-privacy-terms](https://github.com/kimlawtech/korean-privacy-terms) | 283 | Go Template | 2026-05 | 한국 법령 기반 개인정보처리방침·약관 자동 생성 스킬 |
|  | [kimlawtech/korean-jangbu-for](https://github.com/kimlawtech/korean-jangbu-for) | 71 | Python | 2026-04 | 1인 법인·프리랜서용 장부·세무 CSV 자동 생성 스킬 |
|  | [jurisupport/jurisupport-plugins](https://github.com/jurisupport/jurisupport-plugins) | 48 | Shell | 2026-06 | 한국 변호사용 사건폴더 통독·준비서면 초안 Claude Code 패키지 |
|  | [kimlawtech/korean-contracts](https://github.com/kimlawtech/korean-contracts) | 47 | Go Template | 2026-04 | 한국 사업자용 9종 계약서 자동 생성 스킬(+MCP) |
|  | [charliehotel/oh-my-hermes-for-legal-researcher](https://github.com/charliehotel/oh-my-hermes-for-legal-researcher) | 8 | - | 2026-05 | 미국 법률 리서치(법령·판례) Hermes 스킬 |
|  | [hostingglobal-tech/business-receipt-sdk](https://github.com/Hostingglobal-Tech/business-receipt-sdk) | 2 | Python | 2025-10 | 팝빌 세금계산서 일괄발행·국세청 전송 자동화 |

### UI·디자인 시스템

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [nexu-io/open-design](https://github.com/nexu-io/open-design) | 77.4k | TypeScript | 2026-07 | 로컬 우선 오픈소스 Claude Design 대안 데스크톱 앱 |
|  | [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers) | 66.4k | - | 2026-05 | 개발자용 디자인·UI 리소스 큐레이션 |
|  | [google-labs-code/design.md](https://github.com/google-labs-code/design.md) | 25.7k | TypeScript | 2026-07 | 코딩 에이전트에 비주얼 아이덴티티를 주는 DESIGN.md 규격 |
|  | [cocoon-ai/architecture-diagram-generator](https://github.com/Cocoon-AI/architecture-diagram-generator) | 6.4k | HTML | 2026-05 | 다크테마 시스템 아키텍처 다이어그램을 HTML/SVG로 생성 |
|  | [zerostaticthemes/square-ui](https://github.com/zerostaticthemes/square-ui) | 5.9k | TypeScript | 2026-06 | shadcn/ui 기반 아름다운 오픈소스 레이아웃 모음 |
|  | [coleam00/excalidraw-diagram-skill](https://github.com/coleam00/excalidraw-diagram-skill) | 4.1k | Python | 2026-03 | Claude로 Excalidraw 다이어그램을 생성하는 스킬 |
|  | [nomadamas/slides-grab](https://github.com/NomaDamas/slides-grab) | 1.1k | HTML | 2026-07 | Claude Code/Codex용 슬라이드 생성 하네스·에디터·린터 |
|  | [himomohi/airtranslate](https://github.com/himomohi/AirTranslate) | 356 | Swift | 2026-07 | 맥 시스템 오디오를 실시간 전사·번역하는 앱 |
|  | [nlook-service/design-from-code](https://github.com/nlook-service/design-from-code) | 17 | Shell | 2026-06 | 실제 소스코드에서 충실한 HTML 목업으로 디자인 반복 |
|  | [ashmoonori-afk/design-claude-burnguard](https://github.com/ashmoonori-afk/Design-Claude-Burnguard) | 13 | TypeScript | 2026-04 | Claude 디자인 토큰 소모를 로컬로 막는 BurnGuard |

### 콘텐츠·마케팅·SEO

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [yikart/aitoearn](https://github.com/yikart/AiToEarn) | 23.6k | TypeScript | 2026-07 | 여러 플랫폼 자동 퍼블리싱으로 AI 수익화 |
|  | [zubair-trabzada/geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude) | 8.9k | Python | 2026-05 | AI 검색 최적화(GEO) 우선 SEO 스킬 |
|  | [op7418/guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) | 4.9k | HTML | 2026-07 | 샤오홍슈 캐러셀·위챗 커버를 만드는 카드화 스킬 |
|  | [nowork-studio/notfair](https://github.com/nowork-studio/NotFair) | 3.1k | TypeScript | 2026-07 | SEO·GEO·구글/메타 광고 분석 Claude Code 마케팅 스킬팩 |
|  | [revfactory/webtoon-harness](https://github.com/revfactory/webtoon-harness) | 274 | HTML | 2026-06 | 27개 AI 에이전트 팀이 웹툰 한 회차를 제작하는 하네스 |
|  | [sero12journey/synopsis-to-scenario](https://github.com/sero12journey/synopsis-to-scenario) | 117 | Python | 2026-07 | 시놉시스 → 장편 시나리오 전환 멀티에이전트 워크플로우 |
|  | [daewooki/naver-bc-automation](https://github.com/Daewooki/naver-bc-automation) | 97 | TypeScript | 2026-02 | 네이버 브랜드커넥트 상품 리뷰를 블로그에 자동 포스팅 |
|  | [nomadamas/geobench](https://github.com/NomaDamas/geobench) | 59 | TypeScript | 2026-06 | GEO 벤치마크 — Profound·Semrush 오픈소스 대안 |

### 생산성·지식관리

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [zakirullin/files.md](https://github.com/zakirullin/files.md) | 3.8k | Go | 2026-07 | 조용히 사고하는 .md 파일 노트 앱(AI 친화) |
|  | [johnfkoo951/cmds-system-files](https://github.com/johnfkoo951/cmds-system-files) | 216 | HTML | 2026-07 | 1만 노트 옵시디언 볼트를 떠받치는 지식 아키텍처 규칙 |
|  | [jo-duchan/tapflow](https://github.com/jo-duchan/tapflow) | 157 | TypeScript | 2026-07 | 팀 전체를 위한 셀프호스팅 iOS·안드로이드 시뮬레이터 스트리밍 |
|  | [team-attention/openclone](https://github.com/team-attention/openclone) | 125 | TypeScript | 2026-05 | 실제 인물을 학습한 AI 클론과 대화 |
|  | [koul777/clickguide-local-private](https://github.com/koul777/clickguide-local-private) | 38 | TypeScript | 2026-07 | 브라우저 클릭을 기록해 업무 매뉴얼을 만드는 크롬 확장 |
|  | [sodam-ai/sodam-wikimate](https://github.com/sodam-ai/SoDam-WikiMate) | 32 | JavaScript | 2026-07 | 흩어진 자료를 옵시디언에 정리·연결·색인하는 Claude 플러그인 |
|  | [petercha90/link-bookmark](https://github.com/PeterCha90/link-bookmark) | 13 | Python | 2026-06 | 채팅 채널의 안읽은 링크를 북마크하는 Hermes 스킬 |
|  | [digireal-k/digireal-public](https://github.com/digireal-k/digireal-public) | 12 | Python | 2026-07 | 라즈베리파이5 기반 숙박업소 무인 관제 솔루션 |

---

## 7. 📚 학습 · 연구 · 리소스  ·  11개

### 큐레이션 리스트

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [public-apis/public-apis](https://github.com/public-apis/public-apis) | 449.2k | Python | 2026-06 | 32만+ 무료 공개 API 모음 |
|  | [alternbits/awesome-cuda-books](https://github.com/alternbits/awesome-cuda-books) | 936 | - | 2026-05 | 최고의 CUDA 프로그래밍 책 큐레이션 |

### 튜토리얼·학습

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | 38.0k | Python | 2026-06 | 밑바닥부터 배우는 AI 엔지니어링 |
|  | [devenjarvis/lathe](https://github.com/devenjarvis/lathe) | 1.6k | Go | 2026-06 | LLM 스킬로 실습형 멀티파트 기술 튜토리얼 생성 |
|  | [fivetaku/vibe-sunsang](https://github.com/fivetaku/vibe-sunsang) | 169 | Python | 2026-07 | 바이브코더용 AI 멘토 — 대화분석·멘토링·성장 리포트 |
|  | [optimeta/paideia](https://github.com/OPTIMETA/PAIDEIA) | 90 | Python | 2026-07 | 로컬에서 시험 준비를 돕는 Claude Code 플러그인 |
|  | [optimeta/paideia-codex](https://github.com/OPTIMETA/PAIDEIA-codex) | 25 | Python | 2026-06 | Paideia의 Codex 플러그인 버전 |

### 학술·연구 에이전트

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | 37.4k | Python | 2026-07 | 연구→작성→리뷰→수정 학술 연구 Claude 스킬 |
|  | [richard-kim-79/archora-skills](https://github.com/richard-kim-79/archora-skills) | 42 | - | 2026-05 | 가설생성·동료평가 등 학술 연구 에이전트 스킬 9종 |
|  | [taewooopark/scholar-megasearch](https://github.com/TaewoooPark/scholar-megasearch) | 19 | Python | 2026-07 | 20+ 학술DB에 서브에이전트를 뿌리는 대규모 문헌검색 스킬 |
|  | [taewooopark/scholar-lab-radar](https://github.com/TaewoooPark/scholar-lab-radar) | 18 | Python | 2026-07 | OpenAlex로 연구실 N년치 논문을 시계열 지식그래프화 |

---

## 8. 🧩 기타 · 커뮤니티  ·  20개

### 기타

| | 레포 | ⭐ | 언어 | 업데이트 | 설명 |
|---|---|--:|---|---|---|
|  | [xai-org/x-algorithm](https://github.com/xai-org/x-algorithm) | 26.4k | Rust | 2026-05 | X(트위터) For You 피드 추천 알고리즘 |
|  | [epoko77-ai/im-not-ai](https://github.com/epoko77-ai/im-not-ai) | 3.7k | Python | 2026-06 | AI 티 제거 한국어 윤문 스킬 |
|  | [vexa-ai/vexa](https://github.com/Vexa-ai/vexa) | 2.4k | Python | 2026-07 | Google Meet·Teams·Zoom 자동 녹취 API(봇 자동참여) |
|  | [stripe/link-cli](https://github.com/stripe/link-cli) | 610 | TypeScript | 2026-07 | 에이전트가 승인 하에 결제하게 하는 Stripe Link CLI |
|  | [fbsamples/threads_api](https://github.com/fbsamples/threads_api) | 287 | JavaScript | 2026-03 | Meta Threads API 샘플 앱 |
|  | [itssosunny/im-not-strange-ai](https://github.com/itssosunny/im-not-strange-ai) | 138 | Python | 2026-06 | im-not-ai 영감 한국어 AI 윤문·교정 플러그인 |
|  | [nomadamas/katok](https://github.com/NomaDamas/katok) | 120 | Rust | 2026-07 | 카카오톡 전체를 에이전트가 검색(BM25+벡터) |
|  | [bssm-oss/kakao-talk-auto-bot](https://github.com/bssm-oss/kakao-talk-auto-bot) | 74 | Kotlin | 2026-06 | 선택한 방에 AI 자동답장 보내는 안드로이드 앱 |
|  | [johunsang/tauri-dev-screen-cli](https://github.com/johunsang/tauri-dev-screen-cli) | 28 | JavaScript | 2026-05 | MCP 없이 Tauri 개발화면을 검사·조작하는 CLI |
|  | [sapsaldog/supabase-naver-oidc-proxy](https://github.com/sapsaldog/supabase-naver-oidc-proxy) | 17 | TypeScript | 2026-04 | 네이버 로그인을 OIDC로 변환하는 Supabase Edge 프록시 |
|  | [3svs/simsa](https://github.com/3SVS/simsa) | 16 | TypeScript | 2026-07 | AI가 만든 소프트웨어의 수용(스펙 검증) 레이어 Simsa |
|  | [bssm-oss/kakao-talk-auto-bot-mac](https://github.com/bssm-oss/kakao-talk-auto-bot-mac) | 8 | Swift | 2026-05 | 맥 접근성 API로 카카오톡을 제어하는 CLI·메뉴바 |
|  | [redhatinsights/javascript-clients](https://github.com/RedHatInsights/javascript-clients) | 7 | TypeScript | 2026-07 | Swagger API용 자바스크립트 클라이언트 |
|  | [taewooopark/trendchaser](https://github.com/TaewoooPark/Trendchaser) | 6 | - | 2026-07 | 하루 3회 카톡으로 오는 AI 시그널 브리프(이 방의 원천) |
|  | [hwemo-chung/threads-analytics](https://github.com/Hwemo-Chung/threads-analytics) | 5 | Python | 2026-04 | Meta Threads 게시물 수집·인사이트·엑셀 리포트 |
|  | [taewooopark/claude-korean-translator](https://github.com/TaewoooPark/claude-korean-translator) | 3 | JavaScript | 2026-06 | claude.ai 한↔영 자동 번역 크롬 확장(BYOK) |
|  | [jjunsss/momo](https://github.com/jjunsss/MOMO) | 2 | Python | 2026-05 | 긴 줌 녹화를 근거파일 포함 마크다운 회의록으로 |
|  | [jjj06960-hash/telegram-codex-bridge](https://github.com/jjj06960-hash/telegram-codex-bridge) | 1 | Python | 2026-05 | 텔레그램-Codex 브리지 |
|  | [kimminchul/anticard](https://github.com/kimminchul/anticard) | 0 | TypeScript | 2026-06 | 한국인 결제(anticard) 관련 |
|  | [simdorei/telegram-cli-gate](https://github.com/simdorei/telegram-cli-gate) | 0 | Python | 2026-05 | Codex CLI·셸 작업용 텔레그램 롱폴 게이트 |

---

## 🔥 부록 — 양쪽에서 걸린 강한 신호

트렌드방 언급 + 직접 저장 둘 다 된 레포. 언급수 순.

| 언급 | 레포 | ⭐ | 분류 |
|--:|---|--:|---|
| 12x | [openai/codex](https://github.com/openai/codex) | 97.3k | 🤖 AI 에이전트 · 코딩 하네스 › 코딩 에이전트·하네스 |
| 10x | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 137.5k | 🤖 AI 에이전트 · 코딩 하네스 › 코딩 에이전트·하네스 |
| 3x | [egonex-ai/understand-anything](https://github.com/Egonex-AI/Understand-Anything) | 73.4k | 🔍 RAG · 검색 · 문서 · 크롤링 › 코드검색·지식그래프 |
| 2x | [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) | 58.6k | 🤖 AI 에이전트 · 코딩 하네스 › 에이전트 메모리·컨텍스트 |
| 2x | [nousresearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 213.4k | 🤖 AI 에이전트 · 코딩 하네스 › 멀티·오케스트레이션 프레임워크 |
| 2x | [tauricresearch/tradingagents](https://github.com/TauricResearch/TradingAgents) | 92.5k | 💼 도메인 특화 앱 › 주식·투자·금융 |
| 2x | [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | 34.7k | 🤖 AI 에이전트 · 코딩 하네스 › 멀티·오케스트레이션 프레임워크 |
| 2x | [warpdotdev/warp](https://github.com/warpdotdev/warp) | 63.1k | 🛠️ 개발도구 · DevEx · 시스템 › 터미널·에디터·Git |
| 1x | [affaan-m/ecc](https://github.com/affaan-m/ECC) | 228.7k | 🤖 AI 에이전트 · 코딩 하네스 › 에이전트 스킬·플러그인 팩 |
| 1x | [browserbase/skills](https://github.com/browserbase/skills) | 3.6k | 🔍 RAG · 검색 · 문서 · 크롤링 › 웹 크롤링·브라우저 자동화 |
| 1x | [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 76.8k | 🤖 AI 에이전트 · 코딩 하네스 › 멀티·오케스트레이션 프레임워크 |
| 1x | [chromedevtools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | 46.7k | 🔌 MCP 서버 · SDK › MCP 서버 |
| 1x | [colbymchenry/codegraph](https://github.com/colbymchenry/codegraph) | 59.3k | 🔍 RAG · 검색 · 문서 · 크롤링 › 코드검색·지식그래프 |
| 1x | [d4vinci/scrapling](https://github.com/D4Vinci/Scrapling) | 69.2k | 🔍 RAG · 검색 · 문서 · 크롤링 › 웹 크롤링·브라우저 자동화 |
| 1x | [decolua/9router](https://github.com/decolua/9router) | 21.8k | 🧠 LLM 추론 · 서빙 · 모델 › 라우팅·게이트웨이·비용 |
| 1x | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | 191.0k | 🤖 AI 에이전트 · 코딩 하네스 › 에이전트 스킬·플러그인 팩 |
| 1x | [github/spec-kit](https://github.com/github/spec-kit) | 119.7k | 🤖 AI 에이전트 · 코딩 하네스 › 코딩 에이전트·하네스 |
| 1x | [hkuds/ai-trader](https://github.com/HKUDS/AI-Trader) | 20.7k | 💼 도메인 특화 앱 › 주식·투자·금융 |
| 1x | [microsoft/markitdown](https://github.com/microsoft/markitdown) | 165.0k | 🔍 RAG · 검색 · 문서 · 크롤링 › 문서 변환·파싱·검색 |
| 1x | [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | 130.6k | 🤖 AI 에이전트 · 코딩 하네스 › 멀티·오케스트레이션 프레임워크 |
| 1x | [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro) | 10.3k | 💼 도메인 특화 앱 › 영상·이미지·미디어 |
| 1x | [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory) | 25.0k | 🤖 AI 에이전트 · 코딩 하네스 › 에이전트 메모리·컨텍스트 |
| 1x | [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph) | 19.5k | 🔍 RAG · 검색 · 문서 · 크롤링 › 코드검색·지식그래프 |

---
*이 카탈로그는 카톡 대화 내보내기와 개인 저장 아카이브를 병합·정규화하여 자동 생성되었습니다.*