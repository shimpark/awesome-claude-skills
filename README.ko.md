# ![Awesome Claude Skills](assets/header.svg)

> [English](README.md) | 한국어

지금 하려는 작업에 맞는 스킬을 찾아보세요. [Claude Code](https://code.claude.com/docs/en/skills),
[Claude.ai와 API][anthropic-install]를 위한 커뮤니티 디렉터리입니다.

**[스킬 둘러보기](#browse-skills)** · [첫 스킬 설치하기](#quick-start) ·
[컬렉션](#skill-collections) · [기여하기](CONTRIBUTING.ko.md)

<a id="featured-skills"></a>
<a id="pick-a-starting-point"></a>

## 어디서 시작할까요

| 해야 할 일 | 추천 스킬 |
| --- | --- |
| PDF에서 표 추출하기 | [pdf][pdf] |
| 테스트가 계속 실패하는 이유 찾기 | [systematic-debugging][debugging] |
| 테스트부터 작성하며 기능 만들기 | [test-driven-development][tdd] |
| Word 문서 만들기 | [docx][docx] |
| 반복 작업을 스킬로 만들기 | [skill-creator][creator] |

<a id="browse-skills"></a>

## 스킬 둘러보기

| 코드 | 제작 | 업무 |
| --- | --- | --- |
| [테스트](#testing--quality) | [파일](#document--file-processing) | [협업·워크플로](#collaboration--workflow) |
| [디버깅](#debugging--troubleshooting) | [미디어](#media--content-creation) | [데이터](#data--analysis) |
| [앱 개발](#development--architecture) | [글쓰기](#writing--research) | [재무·세무](#finance--tax) |
| [보안](#security--performance) | [스킬](#meta-skills) | [자동화](#documentation--automation) |

스킬 이름을 누르면 원본 저장소로 이동합니다. 스킬을 켜기 전에 그곳의 설치 안내를 먼저 읽으세요.
목록에 있다고 해서 보안 검증을 거친 것은 아닙니다. 검색은 **Cmd+F** 또는 **Ctrl+F**를 사용하세요.

<a id="skill-categories"></a>
<a id="-document--file-processing"></a>
<a id="document--file-processing"></a>

### 문서·파일 처리

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [cue-omni-reader](https://github.com/sensedeal/cue-skills/tree/main/cue-omni-reader) | Cue Omni Reader MCP 서비스로 문서와 웹 자료를 텍스트로 변환합니다. |
| [docx][docx] | 변경 추적과 주석을 지원하며 Word 문서를 만들고 편집합니다. |
| [equalang](https://github.com/equalang/equalang-skill) | API 키와 크레딧으로 Equalang을 통해 파일을 번역하거나 녹음을 받아 적습니다. |
| [humanpen](https://github.com/humanpen/humanpen-skill) | 유료 HumanPen API로 파일 속 인용문을 다시 쓰고, 번역하고, 줄이고, 문체를 바꿉니다. |
| [mubu-integration](https://github.com/liuboacean/mubu-integration) | 비공식 API로 Mubu 개요와 Markdown을 가져오고, 내보내고, 정리합니다. |
| [pdf][pdf] | 텍스트와 표를 추출하고, PDF를 합치고, 양식을 채웁니다. |
| [pptx][pptx] | PowerPoint 프레젠테이션을 만들고, 편집하고, 살펴봅니다. |
| [rtl-slides](https://github.com/darajoukar/reveal-rtl/tree/main/plugins/reveal-rtl/skills/rtl-slides) | 현지화된 숫자, 잘랄리·히즈리 날짜, PDF/PNG 내보내기를 갖춘 오른쪽에서 왼쪽 방향(페르시아어·아랍어) reveal.js 프레젠테이션을 만듭니다. |
| [translate-book](https://github.com/kcy4334-lgtm/translate-book-arxiv) | arXiv 수식과 표를 보존하는 LaTeX 원본 경로로 논문과 책을 번역합니다. |
| [xlsx][xlsx] | 수식과 서식을 갖춘 스프레드시트를 만들고 편집합니다. |

<a id="-testing--quality"></a>
<a id="testing--quality"></a>

### 테스트·품질

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [aeo-check](https://github.com/pchewlo/aeo-check/tree/main/.claude/skills/aeo-check) | AI 검색과 에이전트를 막는 요소가 있는지 사이트 코드나 실제 URL을 점검하고, 프레임워크 순서대로 고친 뒤 다시 실행해 확인합니다. |
| [agent-qa-authoring](https://github.com/vostride/agent-qa/tree/main/skills/agent-qa-authoring) | agent-qa 테스트와 ID를 작성하고 검증합니다. 원본 라이선스가 경쟁 목적의 사용을 제한합니다. |
| [align](https://github.com/ggrigo/align/tree/main/skills/align) | 생성된 주장에 대한 구조화된 피드백을 HTML 양식으로 받고, 수정 내용을 보관해 나중에 검토합니다. |
| [benchmark-yylo](https://github.com/yylo-dev/yylo-skills/tree/main/skills/benchmark-yylo) | 재사용 가능한 케이스를 준비하고, 모델과 하니스를 비교하며, 보존된 출력을 독립적으로 평가합니다. |
| [checkup](https://github.com/agentvitals/checkup/tree/main/checkup) | 호스팅된 프로브를 실행하고 서버가 채점한 결과를 가져옵니다. 전체 모드는 승인된 대화 로그를 업로드합니다. |
| [clousd](https://github.com/Clousd-Android/clousd-sdk/tree/main/skills/clousd) | 클라우드 휴대폰에서 Android 앱을 테스트합니다. 평범한 말로 작업을 실행하거나 화면을 한 단계씩 조작합니다. |
| [crosscheck](https://github.com/moveju112/skill_verify/tree/main/skills/crosscheck) | Claude와 Codex의 독립적인 분석을 비교하고, 결과를 조율하며, 완료된 작업을 검증합니다. |
| [design-fidelity-verify](https://github.com/jeltehomminga/figma-design-skills/tree/main/skills/design-fidelity-verify) | 실행 중인 앱에서 측정한 값을 Figma 디자인 명세와 비교합니다. |
| [fresh-review](https://github.com/roman-s8o/workflow-pack-free/tree/main/.claude/skills/fresh-review) | 대화를 본 적 없는 에이전트가 인수 기준에 맞춰 코드나 계획을 검토하고, 각 지적 사항에 라벨을 붙입니다. |
| [ironloop](https://github.com/edouard-claude/ironloop/tree/main/skills/engineering/ironloop) | 명세, 테스트, 시뮬레이션, 승인된 보안 점검을 거쳐 Rust 작업을 계획합니다. |
| [never-again](https://github.com/malaysherasia-ai/claude-never-again/tree/main/skills/never-again) | 고친 버그를 강제 가능한 훅이나 짧은 교훈으로 남겨 다음 세션에 활용합니다. |
| [pdp-audit](https://github.com/llizell/pdp-audit) | 데스크톱·모바일 증거와 우선순위를 매긴 UX 지적 사항으로 이커머스 상품 페이지를 감사합니다. |
| [playwright-expert](https://github.com/jeffallan/claude-skills/tree/main/skills/playwright-expert) | 픽스처, 페이지 객체, 시각 검사, CI 연동을 갖춘 Playwright 브라우저 테스트를 작성하고 디버깅합니다. |
| [prove-it-ran](https://github.com/agentkitco/agentkit-dev-skills/tree/main/skills/prove-it-ran) | 작업을 끝냈다고 하기 전에 테스트와 빌드가 실제로 실행됐고 변경 사항을 다뤘다는 증거를 보여 줍니다. |
| [sim (interview-sim)](https://github.com/chrisjacksonn/interview-sim/tree/main/skills/sim) | 스크립트가 관리하는 타이머와 숨겨진 테스트 채점으로 시간제한 코딩 면접을 연습합니다. |
| [test-checklist](https://github.com/Ifeanyiejindu/qarunbook/tree/main/plugins/qarunbook/skills/test-checklist) | 앱 코드에서 플랫폼별 단계와 기대 결과가 담긴 QA 계획을 도출합니다. |
| [test-driven-development][tdd] | 실패하는 테스트를 먼저 작성하고, 변경을 구현한 뒤, 리팩터링합니다. |
| [test-master](https://github.com/jeffallan/claude-skills/tree/main/skills/test-master) | 커버리지와 결함 분석을 곁들여 단위·통합·성능·보안 테스트를 계획하고 구현합니다. |
| [webapp-testing][webapp-testing] | Playwright로 로컬 웹 앱을 실행해 보고 동작을 살펴봅니다. |
| [what-could-break](https://github.com/stas4000/what-could-break/tree/main/what-could-break) | 변경이 사용처, 저장된 데이터, 중복된 규칙에 미치는 영향을 추적하고, 핵심 가정을 검증할 구체적인 점검을 설계합니다. |
| [wreck-it](https://github.com/miyannishar/wreck-it/tree/main/skills/wreck-it) | 실제 사용자와 카오스 몽키처럼 로컬 웹 앱을 테스트하고, 재현된 버그를 스크린샷, 소스 위치, 회귀 테스트와 함께 보고합니다. |

<a id="-debugging--troubleshooting"></a>
<a id="debugging--troubleshooting"></a>

### 디버깅·문제 해결

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [agenttrace-session-audit](https://github.com/luoyuctl/agenttrace) | 에이전트 세션의 비용, 토큰, 실패, 지연 시간을 살펴봅니다. |
| [debugging-wizard](https://github.com/jeffallan/claude-skills/tree/main/skills/debugging-wizard) | 실패를 재현하고, 가설을 검증하고, 근본 원인을 찾고, 수정을 확인합니다. |
| [solidping-monitoring](https://github.com/fclairamb/solidping-plugin/tree/main/skills/solidping-monitoring) | SolidPing MCP 서버로 가동 시간 점검이 실패하는 이유를 찾고, 인시던트를 읽고, 점검을 추가합니다. |
| [systematic-debugging][debugging] | 수정을 시도하기 전에 버그의 원인부터 조사합니다. |
| [verification-before-completion][verification] | 작업을 끝냈다고 하기 전에 점검을 실행하고 그 출력을 확인합니다. |

<a id="-collaboration--workflow"></a>
<a id="collaboration--workflow"></a>

### 협업·워크플로

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [a2ui-ask](https://github.com/YuniqueUnic/a2ui-ask) | 브라우저 양식과 JSON 응답 파일로 구조화된 사용자 입력을 받습니다. |
| [ai-agency-os-starter](https://github.com/CalebAnderson-Coder/ai-agency-os-starter) | 고객별 어조, 주장, 범위를 분리해 관리하고, 비용이 청구되지 않는 작업을 하기 전에 고객 요청을 SOW와 대조합니다. |
| [ai-code-review-triage](https://github.com/laulauraluo/ai-code-review-triage/tree/main/skills/ai-code-review-triage) | AI가 작성한 PR을 세 단계로 검토합니다. 새 컨텍스트에서 버그 찾기, 컨텍스트 점검(단위, 이력, 호출자), 범위를 정한 승인입니다. |
| [ai-meeting](https://github.com/bin1874/ai-meeting-skill/tree/main/ai-meeting) | CLI 에이전트와 구조화된 제안 리뷰를 진행하고, 라운드 사이에도 각 에이전트 세션을 유지합니다. |
| [ax-extract-workflow](https://github.com/Necmttn/ax) | 로컬 ax 세션 이력에서 출시된 기능의 워크플로를 재구성합니다. |
| [before-you-build](https://github.com/bin1874/before-you-build-skill) | 제품이나 기능을 만들기 전에 수요, 유통, 범위, 실패 위험을 점검합니다. |
| [brainstorming][brainstorming] | 구현에 들어가기 전에 요구 사항과 설계 선택지를 정리합니다. |
| [breather](https://github.com/ilandahan/breather/tree/main/skills/breather) | 작업 시간 맥락과 서면 인수인계를 곁들여 세션을 멈출 만한 지점을 제안합니다. |
| [call-me](https://github.com/radres/call-me/tree/main/skill) | 사용자의 iPhone에 전화나 문자로 질문하거나 보고하고, 답장에 따라 행동합니다. 유료 /call-me iPhone 앱이 필요합니다. |
| [clueless](https://github.com/ADanMan/clueless/tree/main/skills/clueless) | 사용자에게 추가 안내가 필요할 때 가정, 되돌릴 수 없는 단계, 검토 공백을 짚어 줍니다. |
| [communication-protocol-setup](https://github.com/cez0060405/communication-protocol-setup) | 어시스턴트와의 소통 방식에 합의하고 재사용할 수 있는 프로토콜로 내보냅니다. |
| [cooper-email](https://github.com/cooper-email/cooper-email/tree/main/skills/cooper-email) | Cooper Email MCP 또는 HTTP로 에이전트 자신의 받은편지함에서 메일을 보내고, 읽고, 검색하며, 답장이나 인증 코드를 기다립니다. |
| [delegate](https://github.com/aayushpokhrel1/delegation-pipeline/tree/master/skills/delegate) | 정확히 명세한 코딩 작업을 작업자에게 맡기고, 그 diff와 테스트를 검토합니다. |
| [dialog-tree](https://github.com/ikotelkin/claude-skills/tree/main/skills/dialog-tree) | 대화 분기를 대화형 대화 트리로 추적합니다. |
| [executing-plans][executing-plans] | 검토 지점을 두고 구현 계획을 실행합니다. |
| [fabling](https://github.com/gncdev/fabling/tree/main/fabling) | 작업 규모에 맞는 조사, 시각 점검, 작업 완료를 위한 작업 프로필을 적용합니다. |
| [finishing-a-development-branch][finishing] | 끝낸 작업을 어떻게 통합할지 정하고 브랜치를 정리합니다. |
| [forward-deployed-selling](https://github.com/vonarmen-wq/forward-deployed-selling) | 엔터프라이즈 영업의 탐색, 이해관계자 분석, 딜 적격 판단, 어카운트 플랜을 구조화합니다. |
| [golden-frijoles](https://github.com/danybgoode/golden-frijoles) | 아이디어를 목표와 확인 날짜가 있는 베팅으로 바꾸고, 플래그와 A/B 테스트 뒤에서 출시하며, 각 베팅이 성과를 냈는지 보고합니다. |
| [guashuai / junshi](https://github.com/DENGYUFAN0/guashuai-junshi/tree/main/adapters/claude-code/skills) | 오케스트레이터 또는 가끔 부르는 전문가 조언자로 모델 등급을 조율합니다. |
| [guided-goal](https://github.com/luchasarie/guided-goal/tree/main/skills/guided-goal) | 작업을 시작하기 전에 막연한 의도를 성공 기준, 검증 방법, 경계, 중단 조건이 담긴 완료 계약으로 바꿉니다. |
| [karpathy-guidelines](https://github.com/swarmclawai/andrej-karpathy-skills/tree/main/skills/karpathy-guidelines) | 가정을 드러내고, 코드 변경을 작게 유지하며, 구현에 앞서 점검 기준을 정합니다. |
| [kgai knowledge-graph](https://github.com/kgaidev/kgai) | kgai CLI로 프로젝트 결정과 도메인 지식을 연결된 그래프에 담습니다. |
| [least-cost-capable](https://github.com/kanibal-studio/least-cost-capable) | 작업에 필요한 능력을 갖춘 모델 중에서 선언된 비용 등급이 가장 낮은 모델을 고릅니다. |
| [mindpalace](https://github.com/aashutosh396/mindpalace-skill) | 자료, 프로젝트 포인터, 로그, 런북을 중심으로 로컬 지식 저장소를 정리합니다. |
| [OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) | 기록된 에이전트 실행을 살펴보고 Orca MCP로 재생하거나 포크합니다. |
| [orchestrating-subagents](https://github.com/PapiScholz/symphony/tree/main/skills/orchestrating-subagents) | 위임한 작업에 쓸 모델 등급을 고르고, 디스패치 비용과 소요 시간을 검토합니다. |
| [planning-with-files](https://github.com/OthmanAdi/planning-with-files/tree/master/skills/planning-with-files) | 긴 작업과 컨텍스트 초기화를 넘어 계획, 발견 사항, 진행 상황을 유지합니다. |
| [pr-review](https://github.com/priyank766/OpenSource-SKILL) | 풀 리퀘스트 리뷰를 바로 조치할 수 있는 지적 사항만 남도록 걸러냅니다. |
| [product-decision-agent](https://github.com/atdy/maoxuan-product-agent/tree/main/product-decision-agent) | 제품 우선순위, 성장 문제, 납품 제약을 중국어로 검토합니다. |
| [product-manager-skills](https://github.com/Digidai/product-manager-skills) | PRD를 비평하고, SaaS 지표를 진단하고, 로드맵을 세우고, 디스커버리를 진행합니다. 원본 라이선스는 CC BY-NC-SA 4.0입니다. |
| [punchcard](https://github.com/Maksim-Burtsev/punchcard/tree/master/skills/punchcard) | 코드 변경을 모듈 경계, 의존성, 데이터 모델, 오류 경로 관점에서 검토합니다. |
| [puzzle-activity-planner](https://github.com/fruitwyatt/puzzle-activity-planner) | 시간, 난이도, 준비 단계, 인쇄용 퍼즐 도구 링크를 갖춘 퍼즐 기반 활동을 계획합니다. |
| [receiving-code-review][receiving-review] | 리뷰 피드백을 평가하고 요청받은 변경을 처리합니다. |
| [requesting-code-review][requesting-review] | 작업을 진행하거나 병합하기 전에 리뷰를 요청합니다. |
| [Satori](https://github.com/MetcalfSolutions/Satori) | 감정, 관계, 삶의 목적에 대한 성찰적 대화를 이끌되, 전문 상담의 경계를 지킵니다. |
| [session-handoff](https://github.com/alapha888/session-handoff-kit) | 구조화된 세션 전환을 위한 SKILL.md 프로토콜, 컨텍스트 위생 체크리스트, 인수인계 노트 템플릿을 코딩 에이전트에게 제공하는 도구 모음입니다. |
| [shipreel](https://github.com/theBstar/shipreel/tree/main/plugins/shipreel/skills/shipreel) | 다이어그램, 코드 패널, 선택적 앱 녹화를 넣은 내레이션 PR 설명 영상을 만듭니다. |
| [simple-man](https://github.com/Maksim-Burtsev/simple-man/tree/master/skills/simple-man) | 발견 사항, 수정, 점검, 꼭 필요한 사실은 유지한 채 에이전트의 답변을 줄입니다. |
| [slop-post](https://github.com/useslop/claude-plugins/tree/main/plugins/slop/skills/slop-post) | 세션에서 모델, 도구, 커밋 영수증이 붙은 비공개 Slop 초안을 만듭니다. |
| [tlgr](https://github.com/tlgrcli/tlgr/tree/main/plugin/skills/tlgr) | JSON CLI로 개인 Telegram 계정을 읽고, 검색하고, 관리합니다. |
| [unpaid-intern](https://github.com/kevinmmiddleton/unpaid-intern/tree/main/skills/unpaid-intern) | 회의 녹취록, 문서, 티켓을 내가 소유한 일반 파일 형태의 아침 브리핑, 회의 준비, 후속 조치로 바꿉니다. |
| [using-git-worktrees][worktrees] | 별개의 개발 작업마다 격리된 체크아웃에서 작업합니다. |
| [using-lwc](https://github.com/JanYork/llm-wiki-cli/tree/main/skills/using-lwc) | LWC 위키와 그래프 도구로 출처가 있는 프로젝트 지식을 떠올리고 보존합니다. |
| [wise-men-flash](https://github.com/Ali-expandings/wise-men-flash) | 어려운 결정을 서브에이전트 셋(그중 하나는 악마의 변호인)에게 맡기고, 가장 강력한 반론이 남은 검증된 메모 한 장을 받습니다. |
| [workflow-design](https://github.com/ghorbanies/workflow-design) | 워크플로 상태를 모델링하고, 가드를 테스트하고, 전환 로그를 분석하고, 안전한 흐름 변경을 계획합니다. |
| [working-memory](https://github.com/ikotelkin/claude-skills/tree/main/skills/working-memory) | 컨텍스트 압축을 넘어 제한된 크기의 작업 체크포인트를 보존합니다. |
| [writing-plans][writing-plans] | 명세를 구현 단계로 나눕니다. |

<a id="️-development--architecture"></a>
<a id="development--architecture"></a>

### 개발 및 아키텍처

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [anti-slop-design](https://github.com/wwewtech/anti-slop-design/tree/main/skills/anti-slop-design) | UI 타이포그래피, 색상 토큰, 인터랙션, 접근성을 리뷰하고 다듬습니다. |
| [anti-ui-slop](https://github.com/uizze/uizze/tree/main/skills/anti-ui-slop) | 제품에 맞는 UI 결정을 정리하고, 필요한 상태를 빠짐없이 다루며, 렌더링된 화면을 리뷰합니다. |
| [api-designer](https://github.com/jeffallan/claude-skills/tree/main/skills/api-designer) | 리소스 모델, OpenAPI 명세, 검증을 갖춘 REST·GraphQL 계약을 설계합니다. |
| [aria-icons](https://github.com/LeulAria/Aria-Icons/tree/main/skills) | 약 140만 개의 오픈소스 SVG 아이콘을 검색해 SVG나 React/Vue/Svelte/Solid 컴포넌트로 추가합니다. |
| [AuraKit](https://github.com/smorky850612/Aurakit/tree/main/skills/aura) | 상태 스냅샷과 선택적 로컬 훅으로 빌드, 수정, 리뷰, 배포 모드를 조율합니다. |
| [auteur](https://github.com/agiwhitelist/auteur) | 작성한 아트 디렉션에 따라 웹사이트를 만들고 디자인 일관성과 렌더링 결과를 점검합니다. |
| [birdview](https://github.com/Qiuner/birdview) | 아키텍처, 제약 조건, 계획된 변경 사항을 소스 근거와 연결해 정리합니다. |
| [brewpage-publish](https://github.com/kochetkov-ma/claude-brewcode/tree/main/skills/brewpage-publish) | 텍스트, Markdown, HTML, 파일, 폴더를 계정 없이 brewpage.app에 사이트로 게시하고 공유 링크를 돌려줍니다. |
| [build-with-better-design](https://github.com/better-designs/better-design-plugin/tree/main/skills/build-with-better-design) | Better Design MCP 서비스로 디자인 시스템을 골라 설치합니다. |
| [building-blog](https://github.com/BuildShipGrowRepeat/nextjs-sanity-blog-skill/tree/main/skills/building-blog) | 프로젝트 파악, 구현 계획, SEO 가이드와 함께 Next.js·Sanity 블로그를 추가합니다. |
| [clone-team](https://github.com/Varalix-Digitech-Solutions/clone-team/tree/main/skills/clone-team) | 에이전트 팀, 시각 점검, 아키텍처 메모로 웹사이트 인터페이스를 다시 만듭니다. |
| [cohesivity](https://github.com/cohesivity-org/cohesivity-plugin/tree/main/packages/claude/skills/cohesivity) | Cohesivity API와 MCP로 애플리케이션 백엔드 서비스를 프로비저닝하고 관리합니다. |
| [deacon-install](https://github.com/heydeacon/skills/tree/main/skills/deacon-install) | 사이트나 앱에 Deacon AI 지원 위젯을 추가하고 로그인한 사용자를 전달하며, 실제 페이지에서 위젯이 로드되는지 확인합니다. |
| [dropthehassle-publish](https://github.com/bosmdavid-gif/dropthehassle-skill/tree/main/skills/dropthehassle-publish) | 빌드한 정적 사이트를 DropTheHassle로 게시하고 기존 백엔드와 연결합니다. |
| [easy-auto-research](https://github.com/wjc2830/Easy-AutoResearch-for-DeepLearning/tree/main/easy-auto-research) | 버전 관리되는 코드와 지속되는 진행 기록으로 감독형 딥러닝 실험 루프를 돌립니다. |
| [embedded-iot-mentor](https://github.com/mh-mansouri/embedded-iot-mentor/tree/main/embedded-iot-mentor) | 임베디드·IoT 프로젝트를 계획하고 하드웨어를 비교하며 브레드보드 단계부터 펌웨어까지 안내합니다. |
| [EmblemAI Agent Wallet](https://github.com/EmblemCompany/Agent-skills/tree/main/skills/emblem-ai-agent-wallet) | EmblemAI CLI로 지갑을 조회하고, 명시적으로 확인받은 거래를 준비합니다. |
| [enterprise-architect](https://github.com/rafalr100/enterprise-architect-skill/tree/main/skills/enterprise-architect) | 목표 아키텍처, 역량 맵, 의사결정 기록, 기술 로드맵을 계획합니다. |
| [erupt-admin](https://github.com/plinian/erupt-skill) | erupt 프레임워크, H2, CRUD, 권한 모델로 Java 관리자 앱의 뼈대를 만듭니다. |
| [figma-design-extract](https://github.com/jeltehomminga/figma-design-skills/tree/main/skills/figma-design-extract) | Figma 값을 추출해 프로젝트 토큰에 대응시킨 디자인 명세로 정리합니다. |
| [game-build-team](https://github.com/Varalix-Digitech-Solutions/game-build-team-skill/tree/main/skills/game-build-team) | 에이전트 역할, 헤드리스 테스트, 시각 리뷰, 이어서 할 수 있는 진행 기록으로 Godot 게임 기능을 만듭니다. |
| [impresario](https://github.com/Shushant17711/impresario) | 한 문장으로 주제에 맞는 콘셉트를 구상해 애니메이션 웹사이트를 만들고, 스크린샷을 찍어 수정합니다. |
| [keyboard-shortcuts](https://github.com/nparashar150/claude-keyboard-shortcuts/tree/main/skills/keyboard-shortcuts) | 웹 앱의 단축키, 커맨드 팔레트, 키보드 도움말을 점검하고 구현합니다. |
| [legacy-modernizer](https://github.com/jeffallan/claude-skills/tree/main/skills/legacy-modernizer) | 의존성 맵과 동작 검증으로 단계적 마이그레이션을 계획하고 레거시 시스템을 리팩터링합니다. |
| [light-cloud-deploy](https://github.com/light-cloud-com/skills/tree/main/skills/light-cloud-deploy) | 저장소나 로컬 폴더를 Light Cloud에 배포하고 데이터베이스를 추가하며 로그를 읽거나 롤백합니다. |
| [mcp-builder][mcp-builder] | 도구와 API를 Claude에 연결하는 Model Context Protocol 서버를 만듭니다. |
| [multi-stack-mcp](https://github.com/VovikP/multi-stack-mcp) | 공유 토큰을 바탕으로 Next.js, Flutter, WordPress, Vue용 히어로, 가격, 기능, CTA 섹션을 생성합니다. |
| [nopekit](https://github.com/neuman/nopekit/tree/main/skills/nopekit) | CAD, 3D 프린팅, 구조, 열 분야의 물리 설계 주장을, 실패할 수 있음을 증명해야 통과하는 검사로 바꿉니다. |
| [pit-stop](https://github.com/Finn763/pit-stop) | 저장소의 작은 유지보수 수정 사항을 찾아 근거로 뒷받침하고 패치를 리뷰합니다. |
| [postgres-pro](https://github.com/jeffallan/claude-skills/tree/main/skills/postgres-pro) | PostgreSQL 쿼리, 복제, JSONB, 확장, 데이터베이스 유지보수를 분석합니다. |
| [regulex-plus](https://github.com/PipeDream941/regulex-plus) | CLI로 JavaScript 정규식을 SVG, PNG, Mermaid 다이어그램으로 그립니다. |
| [scrollytelling-brand-site](https://github.com/abdelrhman2007/scrollytelling-brand-site/tree/main/skills/scrollytelling-brand-site) | WebGL 스크롤 연동 3D, 성능 예산, 반응형 QA, 선택형 CMS를 갖춘 스크롤 스토리텔링 회사 웹사이트를 만듭니다. |
| [tastegate](https://github.com/stas4000/tastegate/tree/main/tastegate) | 디자인 브리프로 프런트엔드를 만든 뒤, 내장 Playwright 브라우저 게이트로 레이아웃, 대비 등 눈에 보이는 결함을 점검합니다. |
| [tree-ring-memory](https://github.com/TerminallyLazy/tree-ring-memory-skill) | Tree Ring Memory로 오래 유지되는 프로젝트 메모리를 불러오고, 저장하고, 감사하고, 지웁니다. |
| [unflat](https://github.com/merturl4576/unflat) | 범위를 제한한 CSS 처리로 웹 마케팅 페이지에 시각적 깊이를 더합니다. |
| [web-artifacts-builder][artifacts] | React, Tailwind CSS, shadcn/ui로 웹 아티팩트를 만듭니다. |

<a id="-security--performance"></a>
<a id="security--performance"></a>

### 보안 및 성능

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [16-eyes](https://github.com/kigiela/16-eyes/tree/main/skills/16-eyes) | 저장된 조사 관점과 회의적 검증으로 저장소나 PR diff를 감사합니다. |
| [awesome-bug-bounty](https://github.com/YangTech-gh/Awesome-Bug-Bounty/tree/main/skills/awesome-bug-bounty) | 범위 확인, 취약점 가이드, 보고서 템플릿으로 허가된 버그 바운티 조사를 계획합니다. |
| [cra-vulnerability-obligations](https://github.com/Ansvar-Systems/cra-vulnerability-obligations-skill) | Ansvar Gateway를 통해 조항을 인용하며 CRA 적용 범위와 취약점 보고 의무 질문을 선별합니다. |
| [deep-security-audit](https://github.com/ravindrakele/claude-skills/tree/main/plugins/deep-security-audit/skills/deep-security-audit) | 코드의 공격 표면을 파악하고 후보 취약점을 독립적으로 검증하며 리뷰합니다. |
| [deep-security-check](https://github.com/give-jd/deep-security-check/tree/main/skills/deep-security-check) | 로컬에서 정적 코드, 의존성, 시크릿 스캔을 실행하고 그 근거와 범위를 보고합니다. |
| [gedik](https://github.com/onur-kesim/gedik/tree/main/skills/gedik) | 허가된 프로젝트 범위를 감사하고 보안 발견 사항에 재현 가능한 근거를 첨부합니다. |
| [incident-reporting-navigator](https://github.com/Ansvar-Systems/incident-reporting-navigator-skill) | Ansvar Gateway를 통해 EU 사고 통지 질문을 조항이 인용된 의무, 담당 기관, 기한과 연결합니다. |
| [regulatory-threat-model](https://github.com/Ansvar-Systems/regulatory-threat-model-skill) | Ansvar Gateway를 통해 근거가 인용된 위협 모델과 선별된 EU 의무 항목 검토를 작성합니다. |
| [SecHelix](https://github.com/omarmohelal/SecHelix/tree/main/skills/sechelix) | 허가된 로컬 코드의 보안 문제를 근거와 반박 검증 단계를 거쳐 리뷰합니다. |
| [secure-code-guardian](https://github.com/jeffallan/claude-skills/tree/main/skills/secure-code-guardian) | 인증, 인가, 입력 검증 등 보안 코딩 통제를 구현합니다. |
| [security-reviewer](https://github.com/jeffallan/claude-skills/tree/main/skills/security-reviewer) | 코드와 인프라의 보안 문제를 리뷰하고 우선순위가 매겨진 개선 방안을 작성합니다. |
| [unthrottled-route-check](https://github.com/edtrackai/ship-ready-skills/tree/main/skills/unthrottled-route-check) | 속도 제한 없이 OpenAI, Anthropic, Stripe Checkout을 호출하는 Next.js API 라우트를 찾아, 악용으로 요금이 폭증하기 전에 알려줍니다. |
| [wp-security-audit](https://github.com/mwstech/wp-security-audit-skill) | WordPress 설정, 플러그인 취약점, 침해 징후를 감사합니다. |

<a id="-documentation--automation"></a>
<a id="documentation--automation"></a>

### 문서화 및 자동화

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [brickwise](https://github.com/JCPetrelli/brickwise) | 코드베이스나 주제를 HTML 한 페이지의 인터랙티브 3D 브릭 모델로 설명합니다. |
| [code-documenter](https://github.com/jeffallan/claude-skills/tree/main/skills/code-documenter) | 독스트링, API 명세, 문서 포털, 개발자 가이드를 작성합니다. |
| [devops-engineer](https://github.com/jeffallan/claude-skills/tree/main/skills/devops-engineer) | CI/CD, 컨테이너, 인프라 템플릿, 배포 점검, 롤백 계획을 구성합니다. |
| [docs-to-book](https://github.com/EliaTolin/docs-to-book-skills/tree/main/docs-to-book) | 기술 문서를 크롤링해 Typst로 오프라인 PDF 책으로 엮고, 원하면 번역도 합니다. |
| [famulor-assistants-history](https://github.com/bekservice/Famulor-Skill/tree/main/claude-store/skills/famulor-assistants-history) | 제한된 MCP 프로필로 Famulor 어시스턴트 설정과 상호작용 기록을 읽습니다. |
| [linkedin-outreach](https://github.com/vanshyadav1408/Omentir/tree/main/plugins/omentir/skills/linkedin-outreach) | Omentir MCP로 잠재 고객을 조사하고, 아웃리치 메시지 초안을 쓰며, 캠페인을 살펴봅니다. |
| [llm-wiki](https://github.com/praneybehl/llm-wiki-plugin/tree/main/skills/llm-wiki) | 자료를 링크로 연결된 Markdown 위키로 정리하고, 출처를 인용해 답하며, 세션 간 일관성을 점검합니다. |
| [okf](https://github.com/mattjoyce/okf-skill/tree/master/skills/okf) | 링크로 연결된 Markdown 개념 파일 묶음인 Open Knowledge Format 번들을 작성하고 검증합니다. |
| [process-builder](https://github.com/Castaldo-Solutions/process-builder) | 프로세스 인터뷰를 .drawio 파일의 BPMN 스윔레인 다이어그램으로 바꿉니다. |
| [project-planning-journaling](https://github.com/mh-mansouri/Project-Planning-Journaling/tree/main/project-planning-journaling) | 프로젝트 범위를 정하고, 결정 사항과 진행 상황, 남은 작업을 이어서 쓸 수 있는 일지로 관리합니다. |
| [readme-atlas](https://github.com/chromoany/readme-atlas) | 저장소의 근거를 바탕으로 프로젝트 README를 작성, 재작성, 리뷰, 번역하고 저장소가 뒷받침하지 못하는 주장은 뺍니다. |
| [swarmvault](https://github.com/swarmclawai/swarmvault/tree/main/skills/swarmvault) | 그래프 탐색, 검색, 리뷰, 선택형 모델 기반 종합 기능을 갖춘 로컬 Markdown 지식 저장소를 관리합니다. |
| [trace-my-code](https://github.com/kgohil/trace-my-code/tree/main/skills/trace-my-code) | 도메인 흐름, 아키텍처 메모, 재사용 패턴을 관리하고 코드와 문서의 어긋남을 점검합니다. |

<a id="-media--content-creation"></a>
<a id="media--content-creation"></a>

### 미디어 및 콘텐츠 제작

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [3d-logo](https://github.com/hasuwini77/3d-logo-skill/tree/main/skills/3d-logo) | React Three Fiber로 회전하는 3D 로고 컴포넌트를 만듭니다. |
| [algorithmic-art][algorithmic-art] | p5.js로 제너러티브 아트를 만듭니다. |
| [bria-ai](https://github.com/Bria-AI/bria-skill/tree/dev/skills/bria-ai) | Bria API로 이미지를 생성·편집하고 배경을 제거합니다. |
| [canvas-design][canvas-design] | PNG와 PDF 파일로 시각 디자인을 만듭니다. |
| [cliptude-plan](https://github.com/cliptude/cliptude/tree/main/mcp_server/skills/cliptude-plan) | YouTube 다큐멘터리의 모든 샷을 계획한 뒤, Cliptude가 음성을 입히고 자료를 구해 렌더링하게 합니다. |
| [collage-design](https://github.com/polgarp/collage-design) | 사용이 허가되었거나 직접 제공한 이미지로 콜라주 작품을 구성하고 출처 표기 목록을 관리합니다. |
| [comment-to-dm-cta](https://github.com/commentkeyword/agent-toolkit/tree/main/skills/comment-to-dm-cta) | Instagram 릴스의 "댓글에 KEYWORD" CTA를 기획하고 CommentKeyword에서 자동 DM을 만듭니다. 계정과 API 토큰이 필요합니다. |
| [harmonic-mixing](https://github.com/songfinder-dev/songfinder-skills/tree/main/skills/harmonic-mixing) | 템포와 음악 키를 조회해 플레이리스트와 DJ 전환을 계획합니다. |
| [hitpost](https://github.com/Lihaila/hitpost-skill/tree/main/skills/hitpost) | 아이디어마다 X 글 또는 스레드 세 가지를 X의 글자 수 계산 방식에 맞춰 길이를 검사하고 공유 링크와 함께 작성합니다. |
| [identify-song](https://github.com/songfinder-dev/songfinder-skills/tree/main/skills/identify-song) | Song Finder로 링크나 오디오 파일에서 곡을 찾아냅니다. |
| [kavel-image](https://github.com/hanshs474/kavel-image-skill) | 무료 사용량 안에서 Kavel의 익명 제출 후 폴링 방식 API로 이미지를 생성합니다. 사진 편집에는 Kavel API 키가 필요합니다. |
| [keyword-icons](https://github.com/ruthless-coder-ai/keyword-icons) | 단순한 SVG 아이콘 콘셉트를 여러 개 만들고, 투명 PNG로 렌더링한 결과를 작은 크기에서 확인합니다. |
| [ltx2-video](https://github.com/patraxo/ltx2-vidgen-skill/tree/main/skills/ltx2-video) | 사용자의 Modal 계정에 배포한 LTX-2.3 백엔드로 텍스트, 이미지, 영상에서 클립을 생성합니다. |
| [make-faceless-video](https://github.com/airdropfi/autoshort-skills/tree/main/skills/make-faceless-video) | AutoShort 또는 StoryShort MCP 서버로 얼굴 없는 숏폼 영상을 초안 작성, 가격 확인, 렌더링합니다. 크레딧이 있는 계정이 필요합니다. |
| [meshy-pose-rigging](https://github.com/rickyworld/rigmeshy-by-ricky/tree/master/meshy-pose-rigging) | 캐릭터 레퍼런스를 준비하고 Meshy 자동 리깅과 내보내기 문제 해결을 진행합니다. |
| [pro-motion](https://github.com/jack-reson8/pro-motion/tree/main/plugins/pro-motion/skills/pro-motion) | 기획된 음악 트랙에 맞춰 편집한, 오디오 우선 모션 그래픽 런칭·브랜드·TVC 영상을 코드로 MP4로 렌더링합니다. |
| [publishport](https://github.com/karuha-m/publishport-skill/tree/main/skills/publishport) | 사용자의 PublishPort 브라우저 앱에 연결된 계정으로 게시하고 교차 게시합니다. |
| [puzzlegenio](https://github.com/fruitwyatt/puzzlegenio-claude-skill) | 퍼즐 유형을 고르고, 인쇄용 퍼즐을 만드는 PuzzleGenio 브라우저 도구로 연결되는 값이 채워진 링크를 만듭니다. |
| [reels-setup](https://github.com/VishiATChoudhary/reels/tree/main/skills/reels-setup) | 노래의 드롭에 맞춰 편집한 9:16 스토리 릴스를 만드는 Remotion 스튜디오를 설치하고 검증합니다. |
| [runapi-cli](https://github.com/runapi-ai/cli-skill/tree/main/skills/runapi-cli) | RunAPI CLI로 미디어를 생성하고 모델 작업을 실행합니다. 결제와 인증 설정이 필요합니다. |
| [ruxi-skill](https://github.com/swaylq/ruxi-skill) | 선택한 책의 장면과 출처가 연결된 선택지로 단일 파일 비주얼 노벨을 만듭니다. |
| [screenbrowser](https://github.com/screenbrowser/skill/tree/main/skills/screenbrowser) | Screen Browser MCP 서비스로 내레이션이 들어간 웹 앱 튜토리얼을 제작합니다. |
| [seedance-25-prompting](https://github.com/gbeyrouti/seedance-prompting-claude-skill/tree/main/seedance-25-prompting) | Seedance 영상 프롬프트, 레퍼런스 역할, 오디오, 샷 타이밍을 작성하고 문제를 해결합니다. |
| [slack-gif-creator][slack-gif-creator] | Slack에 맞는 크기의 애니메이션 GIF를 만듭니다. |
| [SocialClaw](https://github.com/ndesv21/socialclaw/tree/main/skill) | SocialClaw로 소셜 게시물을 예약하고 게시합니다. 설정된 워크스페이스와 유효한 요금제가 필요합니다. |
| [table-sheet](https://github.com/netmobster/unstuck-games/tree/main/plugins/table-sheet) | D&D Beyond 캐릭터 시트를 플레이 가이드와 세션 전 체크리스트로 바꿉니다. |
| [vox-director](https://github.com/Alisa0808/vox-director) | 유료 Atlas Cloud API와 로컬 ffmpeg로 내레이션이 들어간 콜라주 영상을 기획하고 조립합니다. |
| [watch-igaming](https://github.com/igamingsychov/watch-igaming) | 영상 링크나 로컬 화면 녹화를 스크립트와 장면 전환 프레임으로 검토하고 QA 표, UX 감사, 회의록을 만듭니다. |
| [youtube-transcript](https://github.com/tubeagentkit/youtube-transcript-skills/tree/main/skills/youtube-transcript) | YouTube Transcript API로 자막, 영상 검색 결과, 재생목록을 가져옵니다. |

<a id="-data--analysis"></a>
<a id="data--analysis"></a>

### 데이터 및 분석

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [adhx](https://github.com/itsmemeworks/adhx/tree/main/skills/adhx) | ADHX API로 X 게시물과 글을 구조화된 JSON으로 읽어옵니다. |
| [aligned-delivery](https://github.com/ahnbingbing/aligned-delivery) | 스프린트와 전달 지표를 분석하고, 팀의 업무량을 진단하며, 완료 시점을 예측합니다. |
| [apify-account-mapping](https://github.com/johnisanerd/claude-skill-account-mapping/tree/main/apify-account-mapping) | 유료 Apify 액터로 목표 기업별로 지정한 직책을 현재 맡고 있는 사람을 파악합니다. |
| [apify-linkedin-post-engagement](https://github.com/johnisanerd/claude-skill-linkedin-post-engagement/tree/main/apify-linkedin-post-engagement) | 유료 Apify 데이터로 LinkedIn 게시물의 반응, 댓글, 공유 수를 비교합니다. |
| [apify-linkedin-posts-scraper](https://github.com/johnisanerd/claude-skill-linkedin-posts-scraper/tree/main/apify-linkedin-posts-scraper) | 유료 Apify 액터로 공개 LinkedIn 게시물 기록을 수집합니다. |
| [apify-remote-startup-jobs](https://github.com/johnisanerd/claude-skill-remote-startup-jobs/tree/main/apify-remote-startup-jobs) | 유료 Apify 액터로 구조화된 원격 스타트업 채용 공고를 가져옵니다. |
| [apify-yc-startup-jobs](https://github.com/johnisanerd/claude-skill-yc-startup-jobs/tree/main/apify-yc-startup-jobs) | 유료 Apify 액터로 공개된 스타트업 연봉 및 지분 범위를 비교합니다. |
| [apify-youtube-transcript-api](https://github.com/johnisanerd/claude-skill-youtube-transcript-api/tree/main/apify-youtube-transcript-api) | 유료 Apify 액터로 YouTube 자막과 자막 형식을 가져옵니다. |
| [apify-youtube-transcripts-llm-training-data](https://github.com/johnisanerd/claude-skill-youtube-transcripts-llm-training-data/tree/main/apify-youtube-transcripts-llm-training-data) | 출처 정보, 언어 정책, 오류 필터링, 유료 Apify 사용량을 갖춘 자막 데이터셋을 구축합니다. |
| [apitube-news-api](https://github.com/apitube/news-api-skills/tree/main/skills/apitube-news-api) | APITube로 뉴스를 검색하고 필터링하며, API 인증, 페이지네이션, 오류 처리를 함께 다룹니다. |
| [claude-ecom](https://github.com/takechanman1228/claude-ecom) | 이커머스 주문 CSV에서 매출, 재구매, 마진 패턴을 살펴봅니다. |
| [claude-persona](https://github.com/takechanman1228/claude-persona/tree/main/skills/persona) | 페르소나 패널과 콘셉트 인터뷰를 시뮬레이션하고, 탐색적 리서치를 위해 주제와 비교 결과를 요약합니다. |
| [converly](https://github.com/converlyio/converly-agent) | Converly 전환 흐름을 설정하고 테스트 이벤트와 전달된 전환을 확인합니다. |
| [datawebot](https://github.com/datawebot/datawebot-mcp/tree/main/skills/datawebot) | 호스팅된 datawebot MCP 서버로 온라인 쇼핑몰의 상품과 판매자별 가격을 직접 링크와 함께 찾습니다. |
| [formo-analytics](https://github.com/getformo/cli/tree/main/skills/formo-analytics) | MCP, CLI, REST로 Formo의 제품 및 온체인 분석 데이터를 조회합니다. |
| [invoice-winning-numbers](https://github.com/tahodev/baodao-skill/tree/main/invoice-winning-numbers) | 공식 출처에서 기간별 대만 영수증 당첨 번호를 조회합니다. |
| [market-mirror](https://github.com/DarkWorldCoder/market-mirror/tree/main/plugin/skills/market-mirror) | 광고, 가격, 영업 멘트를 가상의 구매자에게 시험해 보고 진행·보완·중단 판정 보고서를 받습니다. |
| [octav-api](https://github.com/Octav-Labs/octav-api-skill) | API 키로 지갑 잔액, 내역, DeFi 포지션을 연동합니다. 일부 에이전트 엔드포인트는 x402 결제도 지원합니다. |
| [pandas-pro](https://github.com/jeffallan/claude-skills/tree/main/skills/pandas-pro) | pandas DataFrame과 시계열 데이터를 정제, 조인, 집계, 변환합니다. |
| [polymarket-tennis](https://github.com/livetennisapi/polymarket-tennis/tree/main/skills/polymarket-tennis) | 시장 가격을 실시간 경기 점수와 결합해 관찰 전용 테니스 시장 감시기를 만듭니다. |
| [pvr-inox-radar](https://github.com/karanb192/pvr-inox-radar/tree/main/skills/pvr-inox-radar) | 인도 PVR INOX의 상영 시간표를 나란히 앉을 수 있는 좌석 수와 이동 시간 추정치와 함께 정리합니다. |
| [shopify-review-triage](https://github.com/alfredtech2026/shopify-app-review-brief/tree/main/docs/skills/shopify-review-triage) | 제공받은 Shopify 리뷰를 출처가 연결된 장애, 불편, 가격, 기능 요청으로 분류합니다. |
| [site-traffic-teardown](https://github.com/zhuyansen/site-traffic-teardown/tree/main/skills/site-traffic-teardown) | 사이트의 경쟁사를 찾아 트래픽, 채널 구성, 키워드, 백링크, DR을 비교하고 성장 기회 세 가지를 짚어줍니다. AIsa 유료 데이터를 사용합니다. |
| [sql-pro](https://github.com/jeffallan/claude-skills/tree/main/skills/sql-pro) | SQL 쿼리를 작성·최적화하고, 실행 계획을 살펴보며, 데이터베이스 방언을 비교합니다. |
| [weread-trial-card-list](https://github.com/C-s-salute/weread-trial-card-list) | WeRead 카테고리·순위 페이지를 스크랩해 체험 카드로 읽을 수 있는 도서 목록을 중복 없이 만들고 HTML과 Excel로 내보냅니다. |
| [youtube-full](https://github.com/ZeroPointRepo/youtube-skills/tree/main/skills/youtube-full) | TranscriptAPI로 YouTube 자막, 검색 결과, 채널 데이터, 재생목록을 가져옵니다. API 키가 필요합니다. |

<a id="-finance--tax"></a>
<a id="finance--tax"></a>

### 금융 및 세무

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [file-itr](https://github.com/shivprime94/file-itr) | 인도 소득세 신고 포털을 단계별로 안내받으며 따라갑니다. |
| [furusato-nozei](https://github.com/tahodev/kurashi-skill/tree/main/furusato-nozei) | 전제 조건을 밝히고 공식 출처에 근거해 일본 고향납세 기부 한도를 추정합니다. |
| [ipo-offer-document-review](https://github.com/parinshahAIbuilder/ipo-offer-document-review) | 인도 IPO 공모 서류(DRHP/RHP)를 SEBI ICDR, LODR, Companies Act, Ind AS에 비추어 공시 누락이 없는지 리뷰합니다. |
| [itr-wala](https://github.com/karanb192/itr-wala) | 문서 추출과 Python 계산으로 인도 소득세 신고서를 준비합니다. |
| [open-finance-skills](https://github.com/levelcfo/open-finance-skills) | 20개의 재무 스킬로 중소기업의 월말 결산, 은행 대사, 13주 현금 예측, 1099 신고 준비 상태를 리뷰합니다. |
| [simmer-tennis-live-gate](https://github.com/livetennisapi/simmer-tennis-live-gate) | 주문은 넣지 않고, 시뮬레이션 테니스 시장 진입을 실시간 경기 상태에 따라 허용하거나 막습니다. |
| [stipend](https://github.com/stipend-sh/stipend) | 지출 정책을 설정할 수 있는, 직접 보관하는 USDC 지갑과 x402 결제를 관리합니다. |
| [stock-analysis](https://github.com/AlenSarangSatheesh/Indian-Stocks-Fundamental-Analysis-SKILL/tree/main/stock-analysis) | 1차 공시 자료, 업종 비교, 회계 품질 점검으로 상장 기업을 분석합니다. |
| [verify-polish-company](https://github.com/bartosz-kuc/skanfirmy-mcp/tree/main/skill) | 폴란드 기업의 등록 정보, VAT 상태, 은행 계좌, EU VAT 번호를 조회합니다. |

<a id="️-writing--research"></a>
<a id="writing--research"></a>

### 글쓰기 & 리서치

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [ai-tell-detector](https://github.com/aragossa/ai-tell-detector/tree/main/en/ai-tell-detector) | 영어 또는 러시아어 초안에서 흔한 상투적 글쓰기 패턴을 점검하고 정확한 수정안을 제안합니다. |
| [berlin-job-search](https://github.com/umutyesildal/berlin-job-search/tree/main/skills/berlin-job-search) | 베를린과 독일의 구인 사이트를 검색하고, 독일어 및 블루카드 요건을 확인하며, 없는 경력을 지어내지 않고 Lebenslauf 또는 영문 CV 초안을 작성합니다. |
| [brand-guidelines][brand-guidelines] | Anthropic의 브랜드 색상과 타이포그래피를 아티팩트에 적용합니다. |
| [business-name-fit](https://github.com/Elham-Farajnejad/business-name-fit) | 사업체 이름이 여러 문화권, 언어, 목표 시장에서 어떻게 받아들여질지 평가합니다. |
| [buyer-eval-skill](https://github.com/salespeak-ai/buyer-eval-skill) | 주장, 모순점, 답변되지 않은 질문, 구매 요건을 확인해 B2B 소프트웨어 공급업체를 평가합니다. |
| [check-blindspot](https://github.com/AlexanderCato/check-blindspot) | 믿고 있는 내용을 증거와 대조합니다. 양쪽 입장에서 논증하고, 결론을 가릴 결정적 사실을 짚어 내며, 과신을 지적합니다. |
| [diasporic-intelligence](https://github.com/MinistaJazz/diasporic-intelligence/tree/main/skills/diasporic-intelligence) | 문화 및 혈통 지식을 다루는 글에 출처 표기와 동의 프레임워크를 적용합니다. |
| [fact-check-x-complete](https://github.com/ASI2030/Fact-Check-X/tree/main/skills/fact-check-x-complete) | AI 답변과 인용을 수집하고 세부 주장 단위로 비교하며, 검증하는 동안 증거를 보존합니다. |
| [feynman-pdf](https://github.com/TadTheFisherman/feynman-it) | 쉬운 비유와 렌더링된 페이지 점검을 곁들여 삽화가 있는 PDF 해설서를 만듭니다. |
| [goethecoach](https://github.com/janosszaboaipm-design/goethecoach-claude-skill/tree/main/goethecoach) | 채점 기준에 따른 피드백으로 괴테 시험의 쓰기, 읽기, 말하기를 연습합니다. |
| [grill](https://github.com/mtangoz/grill/tree/main/skills/grill) | 외부 모델로 결정을 따져 보고, 의문을 가려 줄 테스트를 제시합니다. |
| [grounded](https://github.com/jostelzer/grounded/tree/main/skills/grounded) | 실시간 출처 탐색과 인용 검증을 거쳐 과학 문헌 리뷰 초안을 작성합니다. |
| [humanize-chinese](https://github.com/swaylq/humanize-chinese) | 문장 재작성, 표현 정리, 로컬 점검으로 중국어 글을 다듬습니다. 비상업 라이선스입니다. |
| [humanize-pro](https://github.com/msdanyg/humanize-pro) | 저장해 둔 문체 프로필과 게시 채널 규칙에 맞춰 글을 고쳐 쓰거나 점검합니다. |
| [humanizer-ru](https://github.com/ilyautov/humanizer-ru) | 사실, 문체, 보호 대상 텍스트는 그대로 두고 독자에 맞게 러시아어 글을 다듬습니다. |
| [humanizer-zh-tw](https://github.com/nagameTW/formosa-humanizer) | 번체 중국어 글에서 AI 특유의 글쓰기 패턴을 없애고, 중국 본토 용어를 대만식 표현으로 바꾸며, 전각 문장부호를 유지합니다. |
| [humanizing-writing](https://github.com/AshwinSathian/humanize-writing-skill) | 틀에 박힌 구조, 군더더기, 약한 주장, 반복되는 글쓰기 패턴을 손봅니다. |
| [internal-comms][internal-comms] | 업데이트 공지, 뉴스레터 등 사내 커뮤니케이션 문서의 초안을 작성합니다. |
| [jd-decoder](https://github.com/landedjobs/ai-job-hunt-os/tree/main/skills/jd-decoder) | 지원하기 전에 채용 공고에서 실제 요건, 급여 단서, 유령 공고 위험을 읽어 냅니다. |
| [kochab](https://github.com/btmoriarty/kochab/tree/main/skills/kochab) | 이력서를 바탕으로 맞춤 초안 작성, 면접 준비, 지원 현황 관리까지 구직 활동을 진행합니다. |
| [niubiskill](https://github.com/nathanskill/niubiskill/tree/main/skills/niubiskill) | 사업 아이디어를 검토하고, 명시적인 근거와 가정을 바탕으로 다음 수익화 테스트를 고릅니다. |
| [no-slop](https://github.com/Byk3y/no-slop) | 모호한 출처 표기, 홍보성 표현, 반복되는 구조 등 흔한 글쓰기 패턴이 있는지 글을 검토합니다. |
| [prospeak](https://github.com/giorgiozamboni/prospeak) | 영어와 이탈리아어의 어투 조절 기능으로 기존 글을 전문가 독자에 맞게 고쳐 씁니다. |
| [publora-post-ideas](https://github.com/publora-team/publora-post-ideas/tree/main/skills/publora-post-ideas) | 소셜 게시물의 접근 방향 세 가지 중 하나를 고르게 한 뒤, 선택한 방향으로 초안을 작성합니다. |
| [reading-analysis](https://github.com/shenquan520/reading-analysis) | 영어 시험 지문, 선택지, 반복되는 오답 유형을 분석합니다. 비상업 라이선스입니다. |
| [renwei](https://github.com/dbhosbu-dotcom/renwei) | 중국어 원고의 구문, 장 단위 리듬, 사실 일관성, 상투적인 문장을 다듬습니다. |
| [resume-claim-guard](https://github.com/korey2028-prog/resume-claim-guard) | 지원자를 인터뷰해 검증된 사실 정리표를 먼저 확정한 뒤, 채용 공고에 맞춰 이력서를 고칩니다. |
| [resume-studio](https://github.com/Sidgit11/resume-studio) | 경력 증거 자료를 관리하고, 없는 내용을 지어내지 않으면서 직무 요건에 맞게 이력서를 고칩니다. |
| [sales-framework](https://github.com/KudoMetrics-Techologies-Private-Limited/sales-framework/tree/main/skills/sales-framework) | 공개된 설득 프레임워크에 따라 영업 문구, 피치, 반론 대응을 검토합니다. |
| [Say it plainly](https://github.com/adjustleads/provenskills-free-packs/tree/main/plain-writing/say-it-plainly) | 주장은 바꾸지 않고 독자가 이해하기 쉽게 글을 고쳐 씁니다. 비상업 라이선스입니다. |
| [seo-translator](https://github.com/Skillproofdev/seo-translator) | 키워드, 링크, 구조는 유지하면서 시장별 어투에 맞춰 콘텐츠를 현지화합니다. |
| [signs-of-ai](https://github.com/peopleworks/SignsofAI) | 영어와 스페인어 글의 글쓰기 패턴을 다듬고, 선택적으로 사용하는 분석 도구의 결과를 한계와 함께 해석합니다. |
| [structured-gist](https://github.com/domattioli/structured-gist/tree/main/skills/structured-gist) | 설명과 진행 요약을 훑어보기 좋은 중첩 개요 형태로 정리합니다. |
| [swedish_mentor](https://github.com/mh-mansouri/help_with_swedish/tree/master/swedish_mentor) | 수준에 맞는 영상, 팟캐스트, 말하기 연습으로 스웨덴어 학습 계획을 짭니다. |
| [tldr](https://github.com/SurefireStudios/tldr/tree/main/skills/tldr) | 짧은 요약을 맨 앞에 두면서 전체 세부 내용과 중요한 주의사항은 그대로 보존합니다. |
| [trade-show-prep](https://github.com/DataOrigin/trade-show-prep-skill/tree/main/skills/trade-show-prep) | B2B 전시회 참가를 계획하고, 미팅 요청 초안을 쓰고, 부스 방문 리드를 선별하고, 후속 연락 문구를 작성합니다. |
| [unslop](https://github.com/MohamedAbdallah-14/unslop/tree/main/skills/unslop) | 기술 내용은 보존하면서 반복되는 AI 글쓰기 패턴이 없어지도록 글을 고쳐 씁니다. |
| [upwork-job-hunter](https://github.com/droopboop/flconsole-upwork-mcp/tree/main/skills/upwork-job-hunter) | flconsole MCP 서버로 Upwork의 새 일감을 확인하고, 맞는 건을 추려 검토용 제안서 초안을 작성합니다. |
| [zh-tw-humanizer](https://github.com/acchuang/zh-tw-humanizer) | 대만 용어와 보호 대상 사실 규칙을 지키며 번체 중국어 글을 다듬습니다. |

<a id="-meta-skills"></a>
<a id="meta-skills"></a>

### 메타 스킬

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [CERA Project Memory](https://github.com/miketepUR/cera-reasoning-harness) | 프로젝트 세션 맵을 보존하고, 이후 대화에서 쓸 공유 인덱스를 정리합니다. |
| [claude-memory-manager](https://github.com/jau123/claude-memory-manager) | 배치 규칙, 업데이트 가이드, 인덱스 크기 점검으로 Claude Code 자동 메모리를 정리합니다. |
| [danshari-skill](https://github.com/swaylq/danshari-skill) | 설치된 스킬을 점검하고, 사용자가 승인하면 중복된 스킬을 복원 경로와 함께 보관 처리합니다. |
| [emulo](https://github.com/ohad6k/emulo/tree/main/.agents/skills/emulo) | 범위와 비용을 승인한 뒤, 로컬 에이전트 세션 기록을 분석해 개인 작업 프로필을 만듭니다. |
| [feedback](https://github.com/luchasarie/feedback-loop/tree/main/skills/feedback) | 에이전트에 대한 불만을 근거 기반의 개선 계획으로 바꿉니다. 승인하기 전까지는 아무것도 바꾸지 않습니다. |
| [prime-worker](https://github.com/alperiox/prime-worker) | 여러 턴이 걸리는 작업을 지속되는 로컬 prime-agent 워커 세션에 맡깁니다. |
| [reap (skillreaper)](https://github.com/thousandflowers/skillreaper/tree/main/plugins/skillreaper/skills/reap) | 로컬 에이전트 대화 기록에서 쓰이지 않는 로드된 컨텍스트를 측정하고, 되돌릴 수 있는 정리 작업을 검토합니다. |
| [rule-architect](https://github.com/moveju112/rule-architect) | 공유 인덱스와 런타임별 진입점을 갖춘 모듈식 프로젝트 규칙을 생성합니다. |
| [sijiao-skill](https://github.com/swaylq/sijiao-skill) | 조사한 내용을 바탕으로 한 수업, 연습 문제, 간격 복습을 갖춘 상태 유지형 학습 튜터를 만듭니다. |
| [skill-creator][creator] | 스킬을 만들고, 평가하고, 설명을 다듬습니다. |
| [skill-freshness](https://github.com/kvozianov/skill-freshness) | Claude Code, Codex, Cursor 등 여러 에이전트의 스킬 중 고장 났거나, 오래됐거나, 중복되거나, 이미 내장된 것을 출처와 함께 점검합니다. |
| [skill-skill](https://github.com/jack-reson8/skill-skill/tree/main/plugins/skill-skill/skills/skill-skill) | 출력을 실제로 바꾸는 스킬을 작성하고, Agent Skills 사양에 맞춰 린트한 뒤 상태 점수를 매깁니다. |
| [skill-tuner](https://github.com/DENGYUFAN0/skill-forge/tree/main/skill-tuner) | 작은 기준선 측정, 집중된 수정, 롤백 판단을 거쳐 설치된 스킬을 다듬습니다. |
| [subagent-driven-development][subagents] | 계획을 위임된 작업과 리뷰 단계로 나눠 구현합니다. |
| [task-observer](https://github.com/rebelytics/one-skill-to-rule-them-all) | 작업 중 겪는 마찰을 기록하고, 재사용 스킬에 대한 검토 가능한 변경안을 제안합니다. |
| [template-skill][template] | 최소한의 `SKILL.md` 템플릿으로 스킬을 시작합니다. |
| [whetstone](https://github.com/TbusOS/whetstone) | 세션에서 얻은 교훈을 근거와 중복 검사를 갖춘, 검토 가능한 스킬 제안으로 정리합니다. |
| [writing-skills][writing-skills] | 배포하기 전에 스킬 지침을 작성하고 테스트합니다. |

[카테고리로 돌아가기 ↑](#browse-skills)

<a id="skill-collections"></a>

## 스킬 컬렉션

관련 스킬 묶음이 필요할 때 이 저장소들을 둘러보세요.

| 컬렉션 | 주요 내용 |
| --- | --- |
| [Anthropic skills](https://github.com/anthropics/skills) | 문서 처리, 디자인, 개발, 스킬 예제를 다룹니다. |
| [Superpowers](https://github.com/obra/superpowers) | 계획, 테스트, 디버깅, 개발 워크플로를 다룹니다. |
| [adologyai/content-intelligence-plugin](https://github.com/adologyai/content-intelligence-plugin) | Adology 호스팅 MCP 도구로 경쟁사 광고 리서치, 브랜드 추적, 오디언스 분석을 합니다. |
| [Affiliate Skills](https://github.com/Affitor/affiliate-skills) | 제휴 마케팅의 리서치, 콘텐츠, 유통, 분석을 다룹니다. |
| [Agent Skills English Productivity Pack](https://github.com/alapha888/agent-skills-en) | 회의록, 교정, 리서치, 코드 리뷰, 커밋 메시지를 다룹니다. |
| [agent-pilot-skills](https://github.com/babyGao/agent-pilot-skills) | 교차 모델 리뷰, 병렬 리서치, 아웃바운드 영업, 일러스트, 중국 플랫폼 워크플로를 다룹니다. |
| [agentsvc.io skills](https://github.com/agentsvc/skills) | 유료 agentsvc.io API로 음성의 텍스트 변환, 웹 페이지의 Markdown 변환, 이메일 확인, 토큰 안전성 점검, 문서 텍스트 추출을 합니다. |
| [AI sales skills](https://github.com/Marchenko-sales/ai-sales-skills) | 러시아어로 기업 조사, 영업 적격성 판단, 비즈니스 아웃리치 워크플로를 다룹니다. |
| [aigent-OS](https://github.com/wrg32786/aigent-os) | 지속되는 볼트 메모리, 세션 루틴, 위임, 훅, 로컬 유지보수 워크플로를 다룹니다. |
| [Baodao skills](https://github.com/tahodev/baodao-skill) | 대만 공공 서비스의 인보이스, 날씨, 경보, 교통, 공공 데이터 조회를 다룹니다. |
| [ChatCrystal](https://github.com/ZengLiangYi/ChatCrystal/tree/main/skills) | 코딩 세션을 위한 로컬 메모리 불러오기와 기록 되쓰기를 다룹니다. |
| [Chisanan232/requirement-zero](https://github.com/Chisanan232/requirement-zero) | 요구사항이 정말 필요한지 검토하고, 기존 코드가 유지 비용만큼의 가치를 하는지 점검합니다. |
| [claude-fable-5-skills](https://github.com/kpab/claude-fable-5-skills) | 노력 수준 조정, 작업 범위 통제, 서브에이전트 오케스트레이션을 다룹니다. |
| [Cogny Marketing Skills](https://github.com/cognyai/claude-code-marketing-skills) | 마케팅 감사와 카피라이팅을 다룹니다. 실시간 계정 연동에는 Cogny 구독이 필요합니다. |
| [Cowork Tasks](https://github.com/sabbah13/cowork-tasks) | 승인된 Cowork 커넥터에서 로컬 작업 보드를 만들고 분류합니다. 우선순위 지정과 보드 리뷰 스킬을 포함합니다. |
| [CreatorSkills Free Skills](https://github.com/calebvbi/creatorskills-free-skills) | 블로그 개요, 숏폼 영상 대본, 쇼 노트, 챕터, 뉴스레터 기획, 소셜 카피를 다룹니다. |
| [dbhq-uk/marketplace](https://github.com/dbhq-uk/marketplace) | 원격 진단, 코드 검색, 저장소 점검, 리서치, 글쓰기, 업무 서비스 연동을 다룹니다. |
| [Design Engineer Skills](https://github.com/modeinspect/design-engineer-skills) | 저장소 설정, 컴포넌트 영향 분석, 시각 QA, 리뷰하기 좋은 UI 풀 리퀘스트, PR의 디자인 리뷰, 디자이너를 위한 디자인 시스템 점수 매기기를 다룹니다. |
| [DurdeuVlad/persona-write](https://github.com/DurdeuVlad/persona-write) | 페르소나 기반 초안 작성과 재작성, 샘플 기반 문체 추출, 독립 리뷰를 다룹니다. |
| [E-commerce skills](https://github.com/mardab96/ecommerce-claude-skills) | 스토어 데이터로 결제 과정, 상품 콘텐츠, 마진, 재고, 재구매율, 분쟁을 점검합니다. |
| [Growth Cab GTM Skills](https://github.com/federicodon/growthcab-gtm-skills) | 발송 도메인 점검, 콜드 이메일 평가, 리드 목록 QA, 미팅 벤치마크를 다룹니다. |
| [iOS agents and skills](https://github.com/apexbymanish/claude-ai-agents-ios) | Swift/iOS 구현, 테스트, 접근성, 성능, 보안, 릴리스 점검을 다룹니다. |
| [Kudosity skills](https://github.com/kudosity/skills) | Kudosity를 통한 SMS, MMS, WhatsApp, RCS, 연락처 목록, 발송 결과 웹훅을 다룹니다. |
| [Kurashi skills](https://github.com/tahodev/kurashi-skill) | 일본 공공 서비스의 날씨, 경보, 공휴일, 세금, 도서관 조회를 다룹니다. |
| [leechen298/Code2Skill](https://github.com/leechen298/Code2Skill) | 소스 기반 에이전트 도구를 추출하고, 생성된 워크플로와 소스 충실도를 독립적으로 리뷰합니다. |
| [Lesile-Yin/agent-skills](https://github.com/Lesile-Yin/agent-skills) | 프롬프트 엔지니어링, 다관점 리뷰, 토큰 예산, PowerPoint 일괄 자동화를 다룹니다. |
| [Linked API Skills](https://github.com/Linked-API/linkedin-skills) | Linked API로 LinkedIn 프로필과 리드 파이프라인을 읽고 관리합니다. 자격 증명 설정이 필요합니다. |
| [Mamba Labs Skills](https://github.com/mambalabsdev/mamba-labs-skills) | 잠재 고객 리서치, CRM 운영, 이메일 전달률, 시장 진출 워크플로를 다룹니다. 일부는 Apify를 사용합니다. |
| [MarchTalk/ai-content-skills](https://github.com/MarchTalk/ai-content-skills) | 중국어 개념 분석, 대화의 초안 정리, 출처 기반 콘텐츠 리뷰를 다룹니다. |
| [Marketing Skills](https://github.com/coreyhaines31/marketingskills) | SEO, 카피라이팅, 이메일, 가격 책정, 광고, 분석을 다룹니다. |
| [mblode/agent-skills](https://github.com/mblode/agent-skills) | UI, 타이포그래피, 개발자 경험, 문서화, 리뷰, 릴리스 워크플로를 다룹니다. |
| [minxnnu-cloud/make-new-things](https://github.com/minxnnu-cloud/make-new-things) | Claude/Codex 시각 자료 인수인계, 대표 프레임 승인, 재작업 한도, 스킬 트리 동기화를 다룹니다. |
| [Nero1688/claude-academic-skills](https://github.com/Nero1688/claude-academic-skills) | 학술 계획, 문헌 점검, 연구 방법, 재현 워크플로를 다룹니다. 라이선스가 섞여 있습니다. |
| [noizai/skills](https://github.com/noizai/skills) | 텍스트 음성 변환 더빙과 보조 음성 프리셋을 다룹니다. |
| [NotFair](https://github.com/nowork-studio/notfair-plugin) | 서비스별 MCP 연동으로 SEO, 검색 노출, 광고, 분석 워크플로를 다룹니다. |
| [Novu skills](https://github.com/novuhq/skills) | Novu 알림 워크플로, 인박스, 환경설정, 호스팅 에이전트 채널을 구축합니다. |
| [Ontoly skills](https://github.com/0xsarwagya/ontoly/tree/main/skills) | Ontoly 그래프 증거에 근거한 아키텍처, 의존성, 리팩터링, 문서화 워크플로를 다룹니다. |
| [Pathmode](https://github.com/pathmodeio/claude-plugin) | 제품 아이디어를 의도 명세로 바꾸고, 가정에 이의를 제기하며, 구현 증거를 검증합니다. |
| [prompt-to-asset](https://github.com/MohamedAbdallah-14/prompt-to-asset) | CLI와 MCP 서버로 이미지 브리프를 분배하고, 소프트웨어 에셋을 만들고, 플랫폼별 번들을 내보냅니다. |
| [RouterBase Agent Skills](https://github.com/zenlee123/routerbase-agent-skills) | RouterBase 게이트웨이를 연동하고, 모델을 고르고, 미디어 생성 API 작업을 처리합니다. RouterBase 키가 필요합니다. |
| [Sequenzy skills](https://github.com/Sequenzy/skills) | Sequenzy CLI 또는 MCP 서버로 라이프사이클, 캠페인, 트랜잭션 이메일 업무를 수행합니다. Sequenzy 계정이 필요합니다. |
| [Shipwise](https://github.com/harmansidhudev/shipwise) | 검증, 디자인, 아키텍처, 품질, 보안, 운영 전반에 걸쳐 웹앱 출시를 계획하고 리뷰합니다. |
| [sjh9714/skill-receipts](https://github.com/sjh9714/skill-receipts) | 채택 및 기각 근거가 공개된, 코드 범위 제한과 재현 우선 방식의 작은 스킬을 다룹니다. |
| [suede-creator-skills](https://github.com/JasonColapietro/suede-creator-skills) | 코드 품질, 디자인, 마케팅, 출시를 다룹니다. |
| [superseo-skills](https://github.com/inhouseseo/superseo-skills) | SEO 감사, 콘텐츠 작성, 링크 빌딩을 다룹니다. |
| [Vibe Coding Rules skills](https://github.com/getvibekits/vibe-coding-rules/tree/main/skills) | 오류 설명, 페이지 추가, 커밋, 변경 사항 리뷰, 디자인 규칙 적용, 데이터베이스 변경 방지, SEO 점검을 다룹니다. |
| [Wondel.ai Skills](https://github.com/wondelai/skills) | 출간된 도서와 스타일 가이드에서 가져온 제품, UX, 마케팅, 소프트웨어 프레임워크를 적용합니다. |
| [YouTube Skills](https://github.com/sergebulaev/youtube-skills) | YouTube 제목, 설명, 오프닝 훅, 썸네일 브리프, 업로드 계획의 초안을 작성합니다. Publora 게시는 선택 사항입니다. |
| [YYLO skills](https://github.com/yylo-dev/yylo-skills) | YYLO CLI로 작업, 아티팩트, 벤치마크, 지속되는 작업 기록을 관리합니다. |

<a id="how-to-install-skills"></a>
<a id="quick-start"></a>

## 빠른 시작

Claude Code에서 터미널로 Anthropic의 문서 스킬을 설치합니다.

```bash
claude plugin marketplace add anthropics/skills
claude plugin install document-skills@anthropic-agent-skills
```

PDF를 제공한 뒤 Claude에게 양식 필드를 추출해 달라고 요청하세요. 결과를 원본 파일과 비교해 보세요. [Anthropic 설치 가이드를 읽어 보세요][anthropic-install].

<details>
<summary><strong>다른 컬렉션, 단독 스킬, 업데이트</strong></summary>

각 소스 저장소의 설치 가이드를 따르세요. 컬렉션은 플러그인, 개별 폴더, 또는 둘 다로 제공될 수 있습니다. 컬렉션마다 설치 방법을 하나만 고르세요.

단독 Claude Code 스킬은 개인용이면 `~/.claude/skills/<skill-name>/`에, 한 프로젝트에서만 쓰려면 `.claude/skills/<skill-name>/`에 해당 폴더를 넣습니다. `SKILL.md`와 지원 파일은 함께 두어야 합니다. [Claude Code 스킬 가이드][skill-guide]를 참고하세요.

플러그인으로 설치했다면 [플러그인 업데이트 가이드][plugin-updates]를 따르세요.
단독 폴더는 소스 저장소의 업데이트 안내를 따르세요.
이 디렉터리를 클론한다고 해서 나열된 스킬이 설치되지는 않습니다.

</details>

<a id="faq"></a>

## 자주 묻는 질문

<a id="what-are-skills"></a>

<details>
<summary><strong>스킬이란 무엇인가요?</strong></summary>

스킬은 `SKILL.md`에 작성한 지침과, 선택 사항인 스크립트·리소스를 담은
폴더입니다. Claude는 작업과 관련이 있을 때 스킬을 불러오며, 직접 호출할 수도
있습니다. [스킬 가이드][skill-guide]를 참고하세요.

</details>

<details>
<summary><strong>모든 스킬이 모든 Claude 앱에서 동작하나요?</strong></summary>

형식은 공통이지만 사용할 수 있는 도구와 설치 방법은 호스트마다 다릅니다. Claude Code
플러그인은 Claude.ai나 API에 저절로 설치되지 않습니다. 해당 출처가 지원하는 환경과
[Anthropic의 별도 설치 경로][anthropic-install]를 확인하세요.

</details>

<a id="skills-vs-mcp-vs-system-prompts"></a>

<details>
<summary><strong>스킬, MCP, 프로젝트 지침 중 무엇을 써야 하나요?</strong></summary>

| 필요한 것 | 사용할 것 |
| --- | --- |
| 반복되는 작업이나 워크플로 | [스킬][skill-guide] |
| 외부 서비스나 도구 접근 | [Model Context Protocol (MCP)][mcp-guide] |
| 프로젝트에 대해 Claude가 읽는 규칙 | [프로젝트 지침][memory-guide] |

</details>

<details>
<summary><strong>목록의 스킬은 테스트나 감사를 거쳤나요?</strong></summary>

이 목록은 커뮤니티 디렉터리이며 인증 프로그램이 아닙니다. 출처의 지침과 스크립트를
직접 읽고, 결과를 확인할 수 있는 작업에 먼저 적용해 보세요. 깨진 링크나 잘못된
설명은 [이슈][suggest]로 알려 주세요.

</details>

<details>
<summary><strong>스킬을 직접 만들거나 기여할 수 있나요?</strong></summary>

[skill-creator][creator] 또는 [템플릿][template]으로 시작하세요. 목록에 항목을
추가하려면 [기여 가이드](CONTRIBUTING.ko.md)를 따르세요.

</details>

<a id="skill-ideas"></a>

## 스킬 아이디어

여기 있는 것은 기여를 기다리는 요청이며, 설치할 수 있는 스킬이 아닙니다.
구현을 알고 계신가요? [출처를 제안해 주세요][suggest].

<details>
<summary><strong>분류별 아이디어 보기</strong></summary>

| 분류 | 출처를 기다리는 아이디어 |
| --- | --- |
| 테스트 | e2e-testing-skill, snapshot-testing |
| 디버깅 | performance-profiling |
| 개발 | api-development, database-migration, refactoring-patterns |
| 보안 및 성능 | security-review, dependency-audit, performance-optimization, load-testing |
| 문서화 | documentation-generator, changelog-automation, ci-cd-integration |
| 미디어 | video-editing-helper |
| 데이터 | data-visualization, sql-query-builder, csv-processing |
| 글쓰기 | research-assistant, technical-writing |

</details>

<details>
<summary><strong>이전 버전 목록에 있던 항목을 찾고 계신가요?</strong></summary>

일부 항목은 이제 다른 스킬 안에 들어 있거나 이름이 바뀌었습니다.

| 이전 항목 | 현재 출처 |
| --- | --- |
| artifacts-builder | [web-artifacts-builder][artifacts] |
| condition-based-waiting | [systematic-debugging의 보조 가이드][waiting] |
| defense-in-depth | [systematic-debugging의 보조 가이드][defense] |
| root-cause-tracing | [systematic-debugging의 보조 가이드][tracing] |
| testing-skills-with-subagents | [writing-skills의 보조 가이드][testing-skills] |
| testing-anti-patterns, sharing-skills | [현재 Superpowers 카탈로그][superpowers-catalog]에서 독립 스킬을 찾을 수 없습니다. |

</details>

<a id="resources"></a>

## 참고 자료

- [Claude Code 스킬 가이드][skill-guide]
- [Agent Skills 명세](https://agentskills.io/specification)
- [Anthropic이 Skills를 설계한 방식][skills-deep-dive]
- [Skills 발표 글](https://www.anthropic.com/news/skills)
- [Claude Skills에 대한 Simon Willison의 글][simon-skills]
- [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)
- [awesome-claude](https://github.com/alvinunreal/awesome-claude)
- [Claude Skills Hub](https://claudeskills.info/)
- [Claudebin](https://claudebin.com)과 그
  [소스](https://github.com/wunderlabs-dev/claudebin.com/)
- [AgentHub](https://myagenthub.cn): MCP 서버와 에이전트 스킬을 모은 중국어 디렉터리를
  제공합니다.
- [Hypit 영상 가이드](https://hypit.video/guides/how-to-clone-a-video/): 참고 형식을 바탕으로
  영상을 기획하고 렌더링하는 과정을 안내합니다.
-
  [awesome-claude-code-hooks](https://github.com/loqimean/awesome-claude-code-hooks):
  Claude Code 훅 워크플로를 모은 관련 디렉터리입니다.
- [500k.io Skills Bank](https://500k.io/skills): 스킬, MCP 서버, GPT, 에이전트 도구를
  모은 관련 디렉터리입니다.
- [PolySkill](https://polyskill.ai): 스킬 레지스트리와 CLI이며 [공개
  소스](https://github.com/MrSpacemann/polyskill)가 있습니다.
- [Claude Skills 中文市集](https://claudeskill.me): Claude 스킬과 플러그인에 관한
  중국어 튜토리얼을 읽을 수 있습니다.

<a id="contributors"></a>
<a id="contributing"></a>

## 기여하기

스킬을 추가하거나, 링크를 고치거나, 설명을 다듬어 주세요.
[기여 가이드](CONTRIBUTING.ko.md)를 읽은 뒤 풀 리퀘스트를 열면 됩니다.

[커뮤니티][contributors]의 기여로 만들어졌으며,
[Anthropic](https://github.com/anthropics/skills)과
[obra](https://github.com/obra/superpowers)의 스킬도 포함되어 있습니다.
관리자: [Karan Bansal](https://karanbansal.in) · [블로그][blog].

<a id="license"></a>

## 라이선스

[MIT](LICENSE) 라이선스는 이 디렉터리에 적용됩니다. 목록에 있는 각 스킬에는 별도의 라이선스가 있습니다.

[pdf]: https://github.com/anthropics/skills/tree/main/skills/pdf
[docx]: https://github.com/anthropics/skills/tree/main/skills/docx
[pptx]: https://github.com/anthropics/skills/tree/main/skills/pptx
[xlsx]: https://github.com/anthropics/skills/tree/main/skills/xlsx
[webapp-testing]: https://github.com/anthropics/skills/tree/main/skills/webapp-testing
[mcp-builder]: https://github.com/anthropics/skills/tree/main/skills/mcp-builder
[artifacts]: https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder
[algorithmic-art]: https://github.com/anthropics/skills/tree/main/skills/algorithmic-art
[canvas-design]: https://github.com/anthropics/skills/tree/main/skills/canvas-design
[slack-gif-creator]: https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator
[brand-guidelines]: https://github.com/anthropics/skills/tree/main/skills/brand-guidelines
[internal-comms]: https://github.com/anthropics/skills/tree/main/skills/internal-comms
[creator]: https://github.com/anthropics/skills/tree/main/skills/skill-creator
[template]: https://github.com/anthropics/skills/tree/main/template
[tdd]: https://github.com/obra/superpowers/tree/main/skills/test-driven-development
[debugging]: https://github.com/obra/superpowers/tree/main/skills/systematic-debugging
[verification]: https://github.com/obra/superpowers/tree/main/skills/verification-before-completion
[brainstorming]: https://github.com/obra/superpowers/tree/main/skills/brainstorming
[executing-plans]: https://github.com/obra/superpowers/tree/main/skills/executing-plans
[finishing]: https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch
[receiving-review]: https://github.com/obra/superpowers/tree/main/skills/receiving-code-review
[requesting-review]: https://github.com/obra/superpowers/tree/main/skills/requesting-code-review
[worktrees]: https://github.com/obra/superpowers/tree/main/skills/using-git-worktrees
[writing-plans]: https://github.com/obra/superpowers/tree/main/skills/writing-plans
[subagents]: https://github.com/obra/superpowers/tree/main/skills/subagent-driven-development
[writing-skills]: https://github.com/obra/superpowers/tree/main/skills/writing-skills
[waiting]: https://raw.githubusercontent.com/obra/superpowers/main/skills/systematic-debugging/condition-based-waiting.md
[defense]: https://raw.githubusercontent.com/obra/superpowers/main/skills/systematic-debugging/defense-in-depth.md
[tracing]: https://raw.githubusercontent.com/obra/superpowers/main/skills/systematic-debugging/root-cause-tracing.md
[testing-skills]: https://raw.githubusercontent.com/obra/superpowers/main/skills/writing-skills/references/testing-skills-with-subagents.md
[superpowers-catalog]: https://github.com/obra/superpowers/tree/main/skills
[anthropic-install]: https://github.com/anthropics/skills#try-in-claude-code-claudeai-and-the-api
[skill-guide]: https://code.claude.com/docs/en/skills
[plugin-updates]: https://code.claude.com/docs/en/discover-plugins#keep-plugins-updated
[mcp-guide]: https://code.claude.com/docs/en/mcp
[memory-guide]: https://code.claude.com/docs/en/memory
[skills-deep-dive]: https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills
[simon-skills]: https://simonwillison.net/2025/Oct/16/claude-skills/
[suggest]: https://github.com/karanb192/awesome-claude-skills/issues/new/choose
[contributors]: https://github.com/karanb192/awesome-claude-skills/graphs/contributors
[blog]: https://karanbansal.in/blog/
