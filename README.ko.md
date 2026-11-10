# ![Awesome Claude Skills](assets/header.svg)

> [English](README.md) | 한국어

지금 하려는 일에 딱 맞는 스킬을 찾아보세요. [Claude Code](https://code.claude.com/docs/en/skills),
[Claude.ai와 API][anthropic-install]에서 쓸 수 있는 스킬을 모아 둔 커뮤니티 목록입니다.

**[스킬 둘러보기](#browse-skills)** · [처음이신가요?](#new-here) · [첫 스킬 설치하기](#quick-start) ·
[컬렉션](#skill-collections) · [기여하기](CONTRIBUTING.ko.md)

<a id="new-here"></a>

## 처음이신가요? 먼저 읽어 보세요

### 스킬은 무엇일까요

요리를 처음 해 보는 사람에게는 레시피 카드가 큰 도움이 됩니다. 재료와 순서가 적혀 있으니, 누가 만들어도 비슷한 맛이 나지요. 스킬은 Claude에게 건네는 레시피 카드라고 생각하면 쉽습니다.

Claude는 똑똑하지만 처음 하는 일에는 서툴 수 있습니다. 그래서 "PDF 양식은 이렇게 채워" 또는 "테스트를 먼저 쓰고 코드를 만들어" 같은 요령을 미리 적어 두고, Claude가 그대로 따르게 합니다. 그 요령을 담은 폴더가 바로 스킬입니다. 폴더 안에는 사용 설명서인 `SKILL.md` 파일이 들어 있고, 필요하면 프로그램(스크립트)이나 자료도 함께 들어 있습니다. Claude는 일과 관련이 있다고 판단하면 스킬을 스스로 꺼내 쓰며, 사용자가 직접 불러올 수도 있습니다.

### 이 목록은 이렇게 쓰세요

1. 아래 표에서 하려는 일과 비슷한 스킬을 찾습니다.
2. 스킬 이름을 눌러 원본 저장소(프로젝트 파일을 모아 둔 온라인 보관함)로 이동합니다.
3. 거기에 적힌 설치 안내를 읽고, 안내대로 설치한 뒤 Claude에게 일을 시킵니다.

> **꼭 기억하세요.** 이 목록에 올라 있다고 해서 안전하다고 검증된 것은 아닙니다. 설치하기 전에 원본 저장소의 설명과 코드를 직접 읽어 보세요. 읽어도 잘 모르겠다면 선생님이나 선배, 보호자에게 함께 봐 달라고 부탁하는 편이 좋습니다.

### 낯선 말 풀이

표 안에 처음 보는 말이 나오면 여기로 돌아와 찾아보세요.

| 용어 | 쉬운 뜻 |
| --- | --- |
| Claude | Anthropic이 만든 AI 도우미입니다. |
| Claude Code | 터미널에서 코딩을 맡길 수 있는 Claude입니다. |
| Claude.ai | 웹사이트에서 대화하며 쓰는 Claude입니다. |
| 스킬 | Claude에게 일하는 요령을 알려 주는 레시피 카드(폴더)입니다. |
| `SKILL.md` | 스킬의 사용 설명서 파일입니다. |
| 플러그인 | 프로그램에 기능을 덧붙이는 꾸러미입니다. |
| 터미널 | 글자로 명령을 입력하는 창입니다. |
| 저장소(repository) | 프로젝트 파일과 고친 기록을 모아 두는 온라인 보관함입니다. 이 목록의 링크는 대부분 GitHub 저장소로 이어집니다. |
| 프롬프트 | Claude에게 건네는 말, 곧 요청문입니다. |
| API | 프로그램끼리 대화하는 창구입니다. |
| MCP | Claude가 다른 서비스나 도구와 이어지는 통로입니다. (Model Context Protocol) |
| CLI | 글자로 명령을 내려 쓰는 프로그램입니다. |
| 에이전트 | 스스로 판단하며 일을 이어서 해 나가는 AI입니다. |
| 서브에이전트 | 일을 나누어 맡는 보조 AI입니다. |
| PR(풀 리퀘스트) | "제가 고친 코드를 합쳐 주세요" 하고 올리는 요청입니다. |
| diff | 바뀐 부분만 나란히 비교해 보여 주는 화면입니다. |
| 테스트 | 코드가 제대로 움직이는지 확인하는 검사입니다. |
| 디버깅 | 오류(버그)의 원인을 찾아 고치는 일입니다. |
| 리팩터링 | 하는 일은 그대로 두고 코드를 깔끔하게 정리하는 일입니다. |
| CI | 코드를 올릴 때마다 자동으로 검사해 주는 장치입니다. |
| 훅 | 정해진 순간에 저절로 실행되는 동작입니다. |
| 컨텍스트 | Claude가 지금 기억하고 있는 대화 내용입니다. |
| 라이선스 | 소프트웨어를 써도 되는 조건을 적어 둔 허락 문서입니다. 스킬마다 조건이 다르니 꼭 확인하세요. |

### 사례로 이해하기

대표 스킬 일곱 가지를 학교생활에 빗대어 소개합니다. "이렇게 말해 보세요"는 이해를 돕기 위한 예시 문장일 뿐이며, 실제로 스킬을 부르는 방법은 스킬마다 다릅니다. 설치 안내를 먼저 확인하세요.

#### 사례 1. 동아리 신청서 PDF 세 장을 한 파일로 합치기 — [pdf][pdf]

- **이럴 때**: 신청서 PDF가 세 개로 흩어져 있어서 한 번에 제출하고 싶을 때
- **이렇게 말해 보세요**: "이 PDF 세 개를 하나로 합쳐 줘."
- **스킬이 하는 일**: 텍스트와 표를 뽑아내고, PDF를 합치고, 양식 칸을 채웁니다.
- **확인하는 법**: 합쳐진 파일을 열어 쪽수와 순서가 맞는지 직접 넘겨 봅니다.

#### 사례 2. 모둠 보고서를 Word로 만들고 고친 흔적 남기기 — [docx][docx]

- **이럴 때**: 친구들과 돌려 보는 보고서에서 누가 어디를 고쳤는지 보이게 하고 싶을 때
- **이렇게 말해 보세요**: "이 내용으로 보고서 Word 파일을 만들어 줘. 고친 곳은 변경 추적으로 남겨 줘."
- **스킬이 하는 일**: 변경 추적과 주석(옆에 다는 메모)을 지원하며 Word 문서를 만들고 고칩니다.
- **확인하는 법**: Word에서 파일을 열어 검토 탭에 고친 흔적과 메모가 보이는지 봅니다.

#### 사례 3. 게임 점수 계산을 시험 문제부터 만들고 짜기 — [test-driven-development][tdd]

- **비유**: 시험 문제와 정답지를 먼저 만들어 두고, 그 문제를 풀 수 있게 공부하는 방식입니다.
- **이럴 때**: 점수 계산이 틀릴까 봐 걱정되는 게임을 만들 때
- **이렇게 말해 보세요**: "점수 계산 기능을 테스트부터 만들어 줘."
- **스킬이 하는 일**: ① 일부러 실패하는 테스트를 먼저 쓰고, ② 그 테스트가 통과하도록 코드를 만든 뒤, ③ 코드를 깔끔하게 정리합니다.
- **확인하는 법**: 처음에 테스트가 실패했다가 마지막에 모두 통과하는지 봅니다.

#### 사례 4. 계속 실패하는 테스트의 원인부터 찾기 — [systematic-debugging][debugging]

- **비유**: 병원에서는 약부터 주지 않고 어디가 왜 아픈지 진찰부터 합니다.
- **이럴 때**: 테스트가 자꾸 실패하는데 어디가 문제인지 모를 때
- **이렇게 말해 보세요**: "이 테스트가 왜 실패하는지, 고치기 전에 원인부터 조사해 줘."
- **스킬이 하는 일**: 수정을 시도하기 전에 버그의 원인부터 조사합니다.
- **확인하는 법**: 원인 설명이 실제 오류 메시지와 맞아떨어지는지 살펴봅니다.

#### 사례 5. 숙제 내기 전에 검산하기 — [verification-before-completion][verification]

- **비유**: 숙제를 내기 전에 답을 한 번 더 맞춰 보는 습관입니다.
- **이럴 때**: Claude가 "다 했어요"라고 했지만 정말 맞는지 믿기 어려울 때
- **이렇게 말해 보세요**: "끝났다고 하기 전에 점검을 직접 실행하고 결과를 보여 줘."
- **스킬이 하는 일**: 작업이 끝났다고 말하기 전에 점검을 실행하고, 그 출력을 확인합니다.
- **확인하는 법**: 점검을 실제로 실행한 결과가 화면에 남아 있는지 봅니다.

#### 사례 6. 만들기 전에 생각 정리하고 계획 세우기 — [brainstorming][brainstorming], [writing-plans][writing-plans]

- **비유**: 여행을 떠나기 전에 가고 싶은 곳을 먼저 정리하고, 그다음에 날짜별 일정표를 짜는 것과 같습니다.
- **이럴 때**: 무엇을 만들지 막막하거나, 일이 너무 커서 어디서부터 해야 할지 모를 때
- **이렇게 말해 보세요**: "만들기 전에 필요한 것과 선택지를 같이 정리해 줘." 그다음에 "정리한 내용을 단계별 계획으로 나눠 줘."
- **스킬이 하는 일**: brainstorming은 구현에 들어가기 전에 요구 사항과 설계 선택지를 정리하고, writing-plans는 명세(만들 것을 적은 글)를 구현 단계로 나눕니다.
- **확인하는 법**: 계획의 각 단계가 한 번에 끝낼 수 있을 만큼 작게 나뉘었는지 봅니다.

#### 사례 7. 매주 하는 일을 나만의 스킬로 만들기 — [skill-creator][creator]

- **이럴 때**: 매주 같은 형식으로 보고서를 쓰는 것처럼, 반복되는 일이 있을 때
- **이렇게 말해 보세요**: "매주 하는 이 작업을 스킬로 만들어 줘."
- **스킬이 하는 일**: 반복 작업을 스킬로 바꾸는 일을 돕습니다.
- **확인하는 법**: 새로 만든 스킬 폴더에 `SKILL.md`가 있는지, 같은 일을 시켰을 때 같은 방식으로 하는지 봅니다.
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
| [cue-omni-reader](https://github.com/sensedeal/cue-skills/tree/main/cue-omni-reader) | Cue Omni Reader MCP(Claude가 다른 서비스와 연결되는 통로) 서비스로 문서와 웹 자료를 글자로 바꿉니다. |
| [docx][docx] | Word 문서를 만들고 고칩니다. 고친 곳을 표시하고 메모(주석)도 남깁니다. |
| [equalang](https://github.com/equalang/equalang-skill) | Equalang으로 파일을 번역하고, 녹음한 말을 글로 옮겨 적습니다. API 키(프로그램끼리 대화하는 창구를 쓰는 열쇠)와 크레딧(이용권)이 필요합니다. |
| [humanpen](https://github.com/humanpen/humanpen-skill) | 유료 HumanPen API(프로그램끼리 대화하는 창구)로 파일 속 인용문을 다시 쓰고, 번역하고, 줄이고, 글투를 바꿉니다. |
| [mubu-integration](https://github.com/liuboacean/mubu-integration) | 비공식 API(프로그램끼리 대화하는 창구)로 Mubu의 개요와 Markdown 글을 가져오고, 내보내고, 정리합니다. |
| [pdf][pdf] | PDF에서 글자와 표를 뽑아내고, PDF 여러 개를 하나로 합치고, 양식을 채웁니다. |
| [pptx][pptx] | PowerPoint 발표 자료를 만들고, 고치고, 살펴봅니다. |
| [rtl-slides](https://github.com/darajoukar/reveal-rtl/tree/main/plugins/reveal-rtl/skills/rtl-slides) | 페르시아어·아랍어처럼 오른쪽에서 왼쪽으로 쓰는 글로 reveal.js 발표 자료를 만듭니다. 그 나라식 숫자와 날짜(잘랄리·히즈리)를 쓰고 PDF/PNG로도 내보냅니다. |
| [translate-book](https://github.com/kcy4334-lgtm/translate-book-arxiv) | 논문과 책을 번역합니다. LaTeX 원본에서 출발해 arXiv 논문의 수식과 표를 그대로 지킵니다. |
| [xlsx][xlsx] | 수식과 서식이 들어간 스프레드시트(엑셀 표)를 만들고 고칩니다. |

<a id="-testing--quality"></a>
<a id="testing--quality"></a>

### 테스트·품질

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [aeo-check](https://github.com/pchewlo/aeo-check/tree/main/.claude/skills/aeo-check) | AI 검색과 에이전트(스스로 일하는 AI)를 가로막는 것이 있는지 사이트 코드나 실제 주소(URL)를 점검합니다. 프레임워크 순서대로 고친 뒤 다시 실행해 확인합니다. |
| [agent-qa-authoring](https://github.com/vostride/agent-qa/tree/main/skills/agent-qa-authoring) | agent-qa 테스트와 ID를 쓰고 올바른지 확인합니다. 원본 라이선스가 경쟁 목적의 사용을 제한합니다. |
| [align](https://github.com/ggrigo/align/tree/main/skills/align) | 만들어진 주장을 보고 받은 의견을 HTML 양식으로 모으고, 고친 내용은 보관해 두었다가 나중에 다시 봅니다. |
| [benchmark-yylo](https://github.com/yylo-dev/yylo-skills/tree/main/skills/benchmark-yylo) | 다시 쓸 수 있는 시험 사례를 준비하고, 모델과 하니스(AI를 돌리는 틀)를 견주어 보며, 남겨 둔 결과를 따로 평가합니다. |
| [checkup](https://github.com/agentvitals/checkup/tree/main/checkup) | 인터넷의 점검 도구(프로브)를 돌려 서버가 매긴 점수를 받아 옵니다. 전체 모드는 승인된 대화 기록을 올립니다. |
| [clousd](https://github.com/Clousd-Android/clousd-sdk/tree/main/skills/clousd) | 클라우드 휴대폰(인터넷에 있는 가상 휴대폰)에서 Android 앱을 시험합니다. 평범한 말로 일을 시키거나 화면을 한 단계씩 직접 조작합니다. |
| [crosscheck](https://github.com/moveju112/skill_verify/tree/main/skills/crosscheck) | Claude와 Codex가 따로 분석한 결과를 견주고, 서로 맞추고, 끝난 작업이 맞는지 확인합니다. |
| [design-fidelity-verify](https://github.com/jeltehomminga/figma-design-skills/tree/main/skills/design-fidelity-verify) | 실행 중인 앱에서 잰 값을 Figma 디자인 설명서와 견줍니다. |
| [fresh-review](https://github.com/roman-s8o/workflow-pack-free/tree/main/.claude/skills/fresh-review) | 대화를 본 적 없는 에이전트가 완료 조건에 맞춰 코드나 계획을 살펴보고, 지적마다 이름표를 붙입니다. |
| [ironloop](https://github.com/edouard-claude/ironloop/tree/main/skills/engineering/ironloop) | Rust 작업을 계획합니다. 명세(설계 설명서), 테스트, 모의 실행, 승인된 보안 점검 순서로 진행합니다. |
| [never-again](https://github.com/malaysherasia-ai/claude-never-again/tree/main/skills/never-again) | 고친 버그를 반드시 지키게 하는 훅(특정 순간에 자동으로 실행되는 동작)이나 짧은 교훈으로 남겨 다음 작업에 씁니다. |
| [pdp-audit](https://github.com/llizell/pdp-audit) | 온라인 쇼핑몰의 상품 페이지를 컴퓨터·모바일 증거와 우선순위를 매긴 사용성 문제로 점검합니다. |
| [playwright-expert](https://github.com/jeffallan/claude-skills/tree/main/skills/playwright-expert) | Playwright로 하는 브라우저 테스트를 쓰고 고칩니다. 픽스처(테스트 준비물), 페이지 객체, 화면 비교, CI(코드를 올릴 때 자동으로 검사하는 장치) 연동을 갖췄습니다. |
| [prove-it-ran](https://github.com/agentkitco/agentkit-dev-skills/tree/main/skills/prove-it-ran) | 작업이 끝났다고 말하기 전에, 테스트와 빌드(프로그램 만들기)가 실제로 실행됐고 바뀐 부분을 다뤘다는 증거를 보여 줍니다. |
| [sim (interview-sim)](https://github.com/chrisjacksonn/interview-sim/tree/main/skills/sim) | 스크립트가 관리하는 타이머와 숨겨진 테스트 채점으로 시간제한이 있는 코딩 면접을 연습합니다. |
| [test-checklist](https://github.com/Ifeanyiejindu/qarunbook/tree/main/plugins/qarunbook/skills/test-checklist) | 앱 코드를 보고 기기별 단계와 기대 결과가 적힌 QA(품질 확인) 계획을 만듭니다. |
| [test-driven-development][tdd] | 실패하는 테스트를 먼저 쓰고, 변경 내용을 만든 뒤, 리팩터링(겉모습은 그대로 두고 코드를 깔끔하게 정리하기)합니다. |
| [test-master](https://github.com/jeffallan/claude-skills/tree/main/skills/test-master) | 단위·통합·성능·보안 테스트를 계획하고 만듭니다. 코드를 테스트가 얼마나 덮는지와 결함 분석도 함께 봅니다. |
| [webapp-testing][webapp-testing] | Playwright로 내 컴퓨터의 웹 앱을 실행해 보고 동작을 살펴봅니다. |
| [what-could-break](https://github.com/stas4000/what-could-break/tree/main/what-could-break) | 변경이 쓰이는 곳, 저장된 데이터, 겹치는 규칙에 미치는 영향을 따라가 보고, 핵심 가정이 맞는지 확인할 점검을 구체적으로 설계합니다. |
| [wreck-it](https://github.com/miyannishar/wreck-it/tree/main/skills/wreck-it) | 실제 사용자나 카오스 몽키(일부러 마구 눌러 보는 방식)처럼 내 컴퓨터의 웹 앱을 시험하고, 다시 나타나는 버그를 스크린샷, 소스 위치, 회귀 테스트(고친 버그가 다시 생기는지 보는 시험)와 함께 알려 줍니다. |

<a id="-debugging--troubleshooting"></a>
<a id="debugging--troubleshooting"></a>

### 디버깅·문제 해결

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [agenttrace-session-audit](https://github.com/luoyuctl/agenttrace) | 에이전트 작업 기록(세션)의 비용, 토큰(AI가 쓰는 글자 양), 실패, 걸린 시간을 살펴봅니다. |
| [debugging-wizard](https://github.com/jeffallan/claude-skills/tree/main/skills/debugging-wizard) | 실패를 다시 일으켜 보고, 추측을 확인하고, 진짜 원인을 찾고, 고친 것이 맞는지 확인합니다. |
| [solidping-monitoring](https://github.com/fclairamb/solidping-plugin/tree/main/skills/solidping-monitoring) | SolidPing MCP 서버(Claude가 다른 서비스와 연결되는 통로)로 서버가 살아 있는지 보는 점검이 왜 실패하는지 찾고, 사고(인시던트) 기록을 읽고, 점검을 추가합니다. |
| [systematic-debugging][debugging] | 고치려고 하기 전에 버그의 원인부터 조사합니다. |
| [verification-before-completion][verification] | 작업을 끝냈다고 하기 전에 점검을 실행하고 그 결과를 확인합니다. |

<a id="-collaboration--workflow"></a>
<a id="collaboration--workflow"></a>

### 협업·워크플로

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [a2ui-ask](https://github.com/YuniqueUnic/a2ui-ask) | 브라우저 양식과 JSON 응답 파일로 사용자의 입력을 정해진 형식으로 받습니다. |
| [ai-agency-os-starter](https://github.com/CalebAnderson-Coder/ai-agency-os-starter) | 고객마다 말투, 주장, 일의 범위를 따로 관리합니다. 돈을 받지 못하는 일을 하기 전에는 고객 요청이 SOW(일의 범위를 적은 계약서)에 맞는지 대조합니다. |
| [ai-code-review-triage](https://github.com/laulauraluo/ai-code-review-triage/tree/main/skills/ai-code-review-triage) | AI가 쓴 PR(코드를 고쳐 달라고 올리는 요청)을 세 단계로 살펴봅니다. 새 컨텍스트(Claude가 기억하는 대화 내용)에서 버그 찾기, 컨텍스트 점검(단위, 이력, 호출자), 범위를 정한 승인입니다. |
| [ai-meeting](https://github.com/bin1874/ai-meeting-skill/tree/main/ai-meeting) | CLI(글자로 명령을 입력하는 도구) 에이전트와 정해진 형식으로 제안을 검토합니다. 라운드가 바뀌어도 각 에이전트의 세션이 이어집니다. |
| [ax-extract-workflow](https://github.com/Necmttn/ax) | 내 컴퓨터에 남은 ax 세션 기록으로, 출시된 기능이 어떤 순서로 만들어졌는지 다시 그려 냅니다. |
| [before-you-build](https://github.com/bin1874/before-you-build-skill) | 제품이나 기능을 만들기 전에 찾는 사람이 있는지, 어떻게 퍼뜨릴지, 범위, 실패할 위험을 점검합니다. |
| [brainstorming][brainstorming] | 만들기 전에 필요한 것과 설계 선택지를 정리합니다. |
| [breather](https://github.com/ilandahan/breather/tree/main/skills/breather) | 작업한 시간과 글로 적은 인수인계를 바탕으로 세션을 멈추기 좋은 때를 제안합니다. |
| [call-me](https://github.com/radres/call-me/tree/main/skill) | 사용자의 iPhone으로 전화하거나 문자를 보내 질문하고 보고하며, 답장대로 움직입니다. 유료 /call-me iPhone 앱이 필요합니다. |
| [clueless](https://github.com/ADanMan/clueless/tree/main/skills/clueless) | 사용자에게 더 안내가 필요할 때, 가정과 되돌릴 수 없는 단계, 빠진 검토를 짚어 줍니다. |
| [communication-protocol-setup](https://github.com/cez0060405/communication-protocol-setup) | 어시스턴트와 소통하는 방식을 정해 두고, 다시 쓸 수 있는 약속(프로토콜)으로 내보냅니다. |
| [cooper-email](https://github.com/cooper-email/cooper-email/tree/main/skills/cooper-email) | Cooper Email MCP(Claude가 다른 서비스와 연결되는 통로) 또는 HTTP로 에이전트 자신의 받은편지함에서 메일을 보내고, 읽고, 찾으며, 답장이나 인증 코드를 기다립니다. |
| [delegate](https://github.com/aayushpokhrel1/delegation-pipeline/tree/master/skills/delegate) | 정확하게 적은 코딩 작업을 작업자에게 맡기고, 그 diff(바뀐 부분 비교)와 테스트를 살펴봅니다. |
| [dialog-tree](https://github.com/ikotelkin/claude-skills/tree/main/skills/dialog-tree) | 대화가 갈라지는 길을 대화형 대화 나무로 따라갑니다. |
| [executing-plans][executing-plans] | 중간에 확인하는 지점을 두고 구현 계획을 실행합니다. |
| [fabling](https://github.com/gncdev/fabling/tree/main/fabling) | 일의 크기에 맞춰 조사, 눈으로 하는 점검, 작업 마무리용 작업 방식을 적용합니다. |
| [finishing-a-development-branch][finishing] | 끝낸 작업을 어떻게 합칠지 정하고 브랜치(작업 갈래)를 정리합니다. |
| [forward-deployed-selling](https://github.com/vonarmen-wq/forward-deployed-selling) | 기업에 파는 영업에서 알아보기, 관련된 사람들 분석, 거래가 될지 판단, 고객 관리 계획을 틀에 맞춰 정리합니다. |
| [golden-frijoles](https://github.com/danybgoode/golden-frijoles) | 아이디어를 목표와 확인 날짜가 있는 베팅(시도)으로 바꿉니다. 플래그와 A/B 테스트(두 가지를 비교하는 시험) 뒤에서 내보내고, 각 베팅이 성과를 냈는지 알려 줍니다. |
| [guashuai / junshi](https://github.com/DENGYUFAN0/guashuai-junshi/tree/main/adapters/claude-code/skills) | 모델 등급을 조율하는 총괄이 되거나, 가끔 부르는 전문가 조언자 역할을 합니다. |
| [guided-goal](https://github.com/luchasarie/guided-goal/tree/main/skills/guided-goal) | 일을 시작하기 전에 막연한 생각을 성공 기준, 확인 방법, 한계선, 멈출 조건이 담긴 완료 약속으로 바꿉니다. |
| [karpathy-guidelines](https://github.com/swarmclawai/andrej-karpathy-skills/tree/main/skills/karpathy-guidelines) | 가정을 드러내고, 코드 변경을 작게 하고, 만들기 전에 확인 기준을 정합니다. |
| [kgai knowledge-graph](https://github.com/kgaidev/kgai) | kgai CLI(글자로 명령을 입력하는 도구)로 프로젝트의 결정과 분야 지식을 이어진 그래프에 담습니다. |
| [least-cost-capable](https://github.com/kanibal-studio/least-cost-capable) | 일에 필요한 능력이 있는 모델 가운데 정해 둔 비용 등급이 가장 낮은 모델을 고릅니다. |
| [mindpalace](https://github.com/aashutosh396/mindpalace-skill) | 자료, 프로젝트 안내, 기록, 런북(작업 순서 안내서)을 중심으로 내 컴퓨터의 지식 저장소를 정리합니다. |
| [OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) | 기록된 에이전트 실행을 살펴보고, Orca MCP(Claude가 다른 서비스와 연결되는 통로)로 재생하거나 갈라 냅니다(포크). |
| [orchestrating-subagents](https://github.com/PapiScholz/symphony/tree/main/skills/orchestrating-subagents) | 맡긴 일에 쓸 모델 등급을 고르고, 일을 나눠 보내는 비용과 걸린 시간을 살펴봅니다. |
| [planning-with-files](https://github.com/OthmanAdi/planning-with-files/tree/master/skills/planning-with-files) | 긴 작업이나 컨텍스트(Claude가 기억하는 대화 내용)가 초기화돼도 계획, 알아낸 것, 진행 상황을 이어 갑니다. |
| [pr-review](https://github.com/priyank766/OpenSource-SKILL) | PR(코드를 고쳐 달라고 올리는 요청) 리뷰에서 바로 고칠 만한 지적만 남기고 나머지는 걸러 냅니다. |
| [product-decision-agent](https://github.com/atdy/maoxuan-product-agent/tree/main/product-decision-agent) | 제품의 우선순위, 성장 문제, 납품 제약을 중국어로 살펴봅니다. |
| [product-manager-skills](https://github.com/Digidai/product-manager-skills) | PRD(제품 설명서)를 비평하고, SaaS(인터넷으로 쓰는 소프트웨어) 지표를 진단하고, 로드맵(앞으로의 계획표)을 세우고, 디스커버리(고객 알아보기)를 진행합니다. 원본 라이선스는 CC BY-NC-SA 4.0입니다. |
| [punchcard](https://github.com/Maksim-Burtsev/punchcard/tree/master/skills/punchcard) | 코드 변경을 모듈 경계, 의존성(서로 기대는 관계), 데이터 모델, 오류 경로 관점에서 살펴봅니다. |
| [puzzle-activity-planner](https://github.com/fruitwyatt/puzzle-activity-planner) | 시간, 난이도, 준비 단계, 인쇄용 퍼즐 도구 링크가 있는 퍼즐 활동을 계획합니다. |
| [receiving-code-review][receiving-review] | 리뷰로 받은 의견을 따져 보고, 요청받은 변경을 처리합니다. |
| [requesting-code-review][requesting-review] | 작업을 이어가거나 합치기 전에 리뷰를 요청합니다. |
| [Satori](https://github.com/MetcalfSolutions/Satori) | 감정, 관계, 삶의 목적을 돌아보는 대화를 이끌되, 전문 상담의 선은 넘지 않습니다. |
| [session-handoff](https://github.com/alapha888/session-handoff-kit) | 세션을 정해진 방식으로 넘기기 위해 SKILL.md 약속(프로토콜), 컨텍스트(Claude가 기억하는 대화 내용) 정리 점검표, 인수인계 노트 양식을 코딩 에이전트에게 주는 도구 모음입니다. |
| [shipreel](https://github.com/theBstar/shipreel/tree/main/plugins/shipreel/skills/shipreel) | 다이어그램, 코드 화면, 선택 사항인 앱 녹화를 넣어 PR 설명을 말로 들려주는 영상을 만듭니다. |
| [simple-man](https://github.com/Maksim-Burtsev/simple-man/tree/master/skills/simple-man) | 찾은 것, 수정, 점검, 꼭 필요한 사실은 남기고 에이전트의 답변을 줄입니다. |
| [slop-post](https://github.com/useslop/claude-plugins/tree/main/plugins/slop/skills/slop-post) | 세션에서 모델, 도구, 커밋(변경 저장 기록) 영수증이 붙은 비공개 Slop 초안을 만듭니다. |
| [tlgr](https://github.com/tlgrcli/tlgr/tree/main/plugin/skills/tlgr) | JSON CLI(글자로 명령을 입력하는 도구)로 개인 Telegram 계정의 글을 읽고, 찾고, 관리합니다. |
| [unpaid-intern](https://github.com/kevinmmiddleton/unpaid-intern/tree/main/skills/unpaid-intern) | 회의 녹취록, 문서, 티켓을 내가 가진 일반 파일 형태의 아침 요약, 회의 준비, 뒤처리 할 일로 바꿉니다. |
| [using-git-worktrees][worktrees] | 서로 다른 개발 작업마다 따로 떨어진 체크아웃(작업용 복사본)에서 일합니다. |
| [using-lwc](https://github.com/JanYork/llm-wiki-cli/tree/main/skills/using-lwc) | LWC 위키와 그래프 도구로 출처가 있는 프로젝트 지식을 떠올리고 보관합니다. |
| [wise-men-flash](https://github.com/Ali-expandings/wise-men-flash) | 어려운 결정을 서브에이전트(일을 나눠 맡는 보조 Claude) 셋에게 맡깁니다. 그중 하나는 일부러 반대하는 역할이고, 가장 센 반론이 남은 확인된 메모 한 장을 받습니다. |
| [workflow-design](https://github.com/ghorbanies/workflow-design) | 일의 진행 단계를 모델로 만들고, 가드(조건 검사)를 시험하고, 단계 전환 기록을 분석하며, 안전하게 흐름을 바꾸는 계획을 세웁니다. |
| [working-memory](https://github.com/ikotelkin/claude-skills/tree/main/skills/working-memory) | 컨텍스트(Claude가 기억하는 대화 내용)가 압축돼도 크기가 제한된 작업 체크포인트(중간 저장)를 지킵니다. |
| [writing-plans][writing-plans] | 명세를 만들기 단계로 나눕니다. |

<a id="️-development--architecture"></a>
<a id="development--architecture"></a>

### 개발 및 아키텍처

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [anti-slop-design](https://github.com/wwewtech/anti-slop-design/tree/main/skills/anti-slop-design) | 화면(UI)의 글자 모양, 색 값, 눌렀을 때의 반응, 누구나 쓸 수 있게 하는 배려(접근성)를 살펴보고 다듬습니다. |
| [anti-ui-slop](https://github.com/uizze/uizze/tree/main/skills/anti-ui-slop) | 제품에 맞는 화면 구성을 정리하고, 필요한 화면 상태를 빠짐없이 챙기고, 완성된 화면을 검토합니다. |
| [api-designer](https://github.com/jeffallan/claude-skills/tree/main/skills/api-designer) | REST·GraphQL(프로그램끼리 대화하는 방식)의 약속을 설계합니다. 자원 모델, OpenAPI 명세(사용법 설명서), 검증까지 갖춥니다. |
| [aria-icons](https://github.com/LeulAria/Aria-Icons/tree/main/skills) | 무료로 공개된(오픈소스) SVG 아이콘 약 140만 개를 검색해 SVG나 React/Vue/Svelte/Solid 컴포넌트(화면 부품)로 넣어 줍니다. |
| [AuraKit](https://github.com/smorky850612/Aurakit/tree/main/skills/aura) | 상태 스냅샷(그때그때의 상태 기록)과 선택형 로컬 훅(특정 순간에 자동으로 실행되는 동작)을 써서 빌드, 수정, 리뷰, 배포 모드를 조율합니다. |
| [auteur](https://github.com/agiwhitelist/auteur) | 직접 쓴 아트 디렉션(디자인 방향 설명)대로 웹사이트를 만들고, 디자인이 일관된지와 화면에 나온 결과를 점검합니다. |
| [birdview](https://github.com/Qiuner/birdview) | 아키텍처(전체 구조), 제약 조건, 계획된 변경 사항을 소스 근거와 이어서 정리합니다. |
| [brewpage-publish](https://github.com/kochetkov-ma/claude-brewcode/tree/main/skills/brewpage-publish) | 텍스트, Markdown, HTML, 파일, 폴더를 계정 없이 brewpage.app에 사이트로 올리고 공유 링크를 돌려줍니다. |
| [build-with-better-design](https://github.com/better-designs/better-design-plugin/tree/main/skills/build-with-better-design) | Better Design MCP(Claude가 다른 서비스와 연결되는 통로) 서비스로 디자인 시스템을 골라 설치합니다. |
| [building-blog](https://github.com/BuildShipGrowRepeat/nextjs-sanity-blog-skill/tree/main/skills/building-blog) | 프로젝트를 파악하고 구현 계획을 세운 뒤, SEO(검색 결과에 잘 나오게 하는 작업) 가이드에 맞춰 Next.js·Sanity 블로그를 추가합니다. |
| [clone-team](https://github.com/Varalix-Digitech-Solutions/clone-team/tree/main/skills/clone-team) | 에이전트 팀(일을 나눠 맡는 Claude들), 눈으로 하는 점검, 구조 메모를 써서 웹사이트 화면을 다시 만듭니다. |
| [cohesivity](https://github.com/cohesivity-org/cohesivity-plugin/tree/main/packages/claude/skills/cohesivity) | Cohesivity API와 MCP(Claude가 다른 서비스와 연결되는 통로)로 앱의 백엔드 서비스(눈에 안 보이는 서버 기능)를 준비하고 관리합니다. |
| [deacon-install](https://github.com/heydeacon/skills/tree/main/skills/deacon-install) | 사이트나 앱에 Deacon AI 지원 위젯(작은 도우미 창)을 넣고 로그인한 사용자 정보를 넘깁니다. 실제 페이지에서 위젯이 열리는지도 확인합니다. |
| [dropthehassle-publish](https://github.com/bosmdavid-gif/dropthehassle-skill/tree/main/skills/dropthehassle-publish) | 만들어 둔 정적 사이트(바뀌지 않는 웹페이지)를 DropTheHassle에 올리고 기존 백엔드와 연결합니다. |
| [easy-auto-research](https://github.com/wjc2830/Easy-AutoResearch-for-DeepLearning/tree/main/easy-auto-research) | 버전 관리되는 코드와 계속 남는 진행 기록으로, 사람이 지켜보는 딥러닝 실험을 되풀이해 돌립니다. |
| [embedded-iot-mentor](https://github.com/mh-mansouri/embedded-iot-mentor/tree/main/embedded-iot-mentor) | 임베디드·IoT(작은 기계를 인터넷에 연결하는 기술) 프로젝트를 계획하고 하드웨어를 비교하며, 브레드보드(전자 부품을 꽂아 보는 판) 단계부터 펌웨어(기계 안의 프로그램)까지 안내합니다. |
| [EmblemAI Agent Wallet](https://github.com/EmblemCompany/Agent-skills/tree/main/skills/emblem-ai-agent-wallet) | EmblemAI CLI(글자로 명령을 입력하는 도구)로 지갑을 조회하고, 사용자가 분명히 확인한 거래만 준비합니다. |
| [enterprise-architect](https://github.com/rafalr100/enterprise-architect-skill/tree/main/skills/enterprise-architect) | 앞으로 만들 시스템의 구조(목표 아키텍처), 역량 맵, 의사결정 기록, 기술 로드맵(앞으로의 기술 계획표)을 계획합니다. |
| [erupt-admin](https://github.com/plinian/erupt-skill) | erupt 프레임워크, H2, CRUD(만들기·보기·고치기·지우기), 권한 모델로 Java 관리자 앱의 뼈대를 만듭니다. |
| [figma-design-extract](https://github.com/jeltehomminga/figma-design-skills/tree/main/skills/figma-design-extract) | Figma 값을 뽑아 프로젝트의 토큰(색·크기 같은 디자인 값)에 맞추고, 디자인 명세로 정리합니다. |
| [game-build-team](https://github.com/Varalix-Digitech-Solutions/game-build-team-skill/tree/main/skills/game-build-team) | 에이전트 역할, 헤드리스 테스트(화면 없이 하는 테스트), 눈으로 하는 리뷰, 이어서 할 수 있는 진행 기록으로 Godot 게임 기능을 만듭니다. |
| [impresario](https://github.com/Shushant17711/impresario) | 한 문장으로 주제에 맞는 콘셉트를 구상해 움직이는 웹사이트를 만들고, 스크린샷을 찍어 고칩니다. |
| [keyboard-shortcuts](https://github.com/nparashar150/claude-keyboard-shortcuts/tree/main/skills/keyboard-shortcuts) | 웹 앱의 단축키, 커맨드 팔레트(명령 검색창), 키보드 도움말을 점검하고 만듭니다. |
| [legacy-modernizer](https://github.com/jeffallan/claude-skills/tree/main/skills/legacy-modernizer) | 의존성 맵(무엇이 무엇에 기대는지 보여 주는 지도)과 동작 검증으로 단계별 이전 계획을 세우고, 오래된 시스템을 리팩터링(겉모습은 그대로 두고 코드를 깔끔하게 정리하기)합니다. |
| [light-cloud-deploy](https://github.com/light-cloud-com/skills/tree/main/skills/light-cloud-deploy) | 저장소나 내 컴퓨터 폴더를 Light Cloud에 배포하고(올려서 쓸 수 있게 하고) 데이터베이스를 추가합니다. 로그를 읽거나 롤백(이전 상태로 되돌리기)도 합니다. |
| [mcp-builder][mcp-builder] | 도구와 API(프로그램끼리 대화하는 창구)를 Claude에 연결하는 Model Context Protocol 서버를 만듭니다. |
| [multi-stack-mcp](https://github.com/VovikP/multi-stack-mcp) | 공유 토큰(디자인 값)을 바탕으로 Next.js, Flutter, WordPress, Vue용 첫 화면 큰 영역, 가격표, 기능 소개, 행동 유도 영역(CTA)을 만듭니다. |
| [nopekit](https://github.com/neuman/nopekit/tree/main/skills/nopekit) | CAD, 3D 프린팅, 구조, 열 분야의 물리 설계 주장을, 실패할 수 있음을 증명해야 통과하는 검사로 바꿉니다. |
| [pit-stop](https://github.com/Finn763/pit-stop) | 저장소에서 작은 유지보수 수정거리를 찾아 근거를 붙이고, 패치(고친 내용)를 리뷰합니다. |
| [postgres-pro](https://github.com/jeffallan/claude-skills/tree/main/skills/postgres-pro) | PostgreSQL 쿼리(데이터 요청), 복제, JSONB, 확장, 데이터베이스 유지보수를 분석합니다. |
| [regulex-plus](https://github.com/PipeDream941/regulex-plus) | CLI(글자로 명령을 입력하는 도구)로 JavaScript 정규식(글자 패턴 규칙)을 SVG, PNG, Mermaid 다이어그램(그림)으로 그립니다. |
| [scrollytelling-brand-site](https://github.com/abdelrhman2007/scrollytelling-brand-site/tree/main/skills/scrollytelling-brand-site) | 스크롤하면 이야기가 이어지는 회사 웹사이트를 만듭니다. WebGL을 쓴 3D 효과, 성능 한도, 화면 크기별 점검, 선택형 CMS(글을 관리하는 도구)를 갖춥니다. |
| [tastegate](https://github.com/stas4000/tastegate/tree/main/tastegate) | 디자인 브리프(요구 설명서)로 프런트엔드(화면 쪽 코드)를 만든 뒤, 내장 Playwright 브라우저 검사로 배치, 색 대비 같은 눈에 보이는 문제를 점검합니다. |
| [tree-ring-memory](https://github.com/TerminallyLazy/tree-ring-memory-skill) | Tree Ring Memory로 오래 유지되는 프로젝트 메모리(기억)를 불러오고, 저장하고, 검사하고, 지웁니다. |
| [unflat](https://github.com/merturl4576/unflat) | 범위를 제한한 CSS 처리로 웹 마케팅 페이지에 입체감을 더합니다. |
| [web-artifacts-builder][artifacts] | React, Tailwind CSS, shadcn/ui로 웹 아티팩트(웹 결과물)를 만듭니다. |

<a id="-security--performance"></a>
<a id="security--performance"></a>

### 보안 및 성능

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [16-eyes](https://github.com/kigiela/16-eyes/tree/main/skills/16-eyes) | 저장된 조사 관점과 의심하는 눈으로 하는 검증으로 저장소나 PR(코드를 고쳐 달라고 올리는 요청)의 diff(바뀐 부분 비교)를 감사합니다. |
| [awesome-bug-bounty](https://github.com/YangTech-gh/Awesome-Bug-Bounty/tree/main/skills/awesome-bug-bounty) | 범위 확인, 취약점(해킹당할 수 있는 약한 부분) 가이드, 보고서 템플릿으로 허가된 버그 바운티(약점을 찾으면 상금을 받는 제도) 조사를 계획합니다. |
| [cra-vulnerability-obligations](https://github.com/Ansvar-Systems/cra-vulnerability-obligations-skill) | Ansvar Gateway로 조항을 인용하며 CRA(유럽연합의 사이버 보안 법)가 적용되는 범위와 취약점 보고 의무 질문을 골라 정리합니다. |
| [deep-security-audit](https://github.com/ravindrakele/claude-skills/tree/main/plugins/deep-security-audit/skills/deep-security-audit) | 코드에서 공격받을 수 있는 부분을 파악하고, 약점 후보를 따로 확인하며 검토합니다. |
| [deep-security-check](https://github.com/give-jd/deep-security-check/tree/main/skills/deep-security-check) | 내 컴퓨터에서 코드 검사, 의존성(가져다 쓰는 외부 코드) 검사, 시크릿(비밀번호·열쇠) 스캔을 실행하고 그 근거와 범위를 보고합니다. |
| [gedik](https://github.com/onur-kesim/gedik/tree/main/skills/gedik) | 허가된 프로젝트 범위를 감사하고, 보안 발견 사항에 다시 확인할 수 있는 근거를 붙입니다. |
| [incident-reporting-navigator](https://github.com/Ansvar-Systems/incident-reporting-navigator-skill) | Ansvar Gateway로 EU 사고 통지 질문을 조항이 인용된 의무, 담당 기관, 기한과 이어 줍니다. |
| [regulatory-threat-model](https://github.com/Ansvar-Systems/regulatory-threat-model-skill) | Ansvar Gateway로 근거를 인용한 위협 모델(어떤 위험이 있는지 정리한 것)을 쓰고, 골라낸 EU 의무 항목을 검토합니다. |
| [SecHelix](https://github.com/omarmohelal/SecHelix/tree/main/skills/sechelix) | 허가된 내 컴퓨터의 코드에서 보안 문제를 찾아, 근거를 대고 반박해 보는 확인 단계를 거쳐 리뷰합니다. |
| [secure-code-guardian](https://github.com/jeffallan/claude-skills/tree/main/skills/secure-code-guardian) | 인증(누구인지 확인), 인가(무엇을 해도 되는지 확인), 입력 검증 같은 보안 코딩 장치를 구현합니다. |
| [security-reviewer](https://github.com/jeffallan/claude-skills/tree/main/skills/security-reviewer) | 코드와 인프라(서버 환경)의 보안 문제를 리뷰하고, 우선순위를 매긴 개선 방안을 작성합니다. |
| [unthrottled-route-check](https://github.com/edtrackai/ship-ready-skills/tree/main/skills/unthrottled-route-check) | 속도 제한 없이 OpenAI, Anthropic, Stripe Checkout을 호출하는 Next.js API 라우트(주소)를 찾아, 악용으로 요금이 폭증하기 전에 알려줍니다. |
| [wp-security-audit](https://github.com/mwstech/wp-security-audit-skill) | WordPress 설정, 플러그인 취약점, 해킹당한 흔적을 감사합니다. |

<a id="-documentation--automation"></a>
<a id="documentation--automation"></a>

### 문서화 및 자동화

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [brickwise](https://github.com/JCPetrelli/brickwise) | 코드베이스나 주제를 HTML 한 페이지의 움직이는 3D 브릭(블록) 모델로 설명합니다. |
| [code-documenter](https://github.com/jeffallan/claude-skills/tree/main/skills/code-documenter) | 독스트링(코드 안 설명글), API 명세, 문서 포털, 개발자 가이드를 작성합니다. |
| [devops-engineer](https://github.com/jeffallan/claude-skills/tree/main/skills/devops-engineer) | CI(코드를 올릴 때 자동으로 검사하는 장치)/CD(자동 배포), 컨테이너, 인프라 템플릿, 배포 점검, 롤백(되돌리기) 계획을 구성합니다. |
| [docs-to-book](https://github.com/EliaTolin/docs-to-book-skills/tree/main/docs-to-book) | 기술 문서를 웹에서 자동으로 읽어 와 Typst로 오프라인 PDF 책으로 엮고, 원하면 번역도 합니다. |
| [famulor-assistants-history](https://github.com/bekservice/Famulor-Skill/tree/main/claude-store/skills/famulor-assistants-history) | 제한된 MCP(Claude가 다른 서비스와 연결되는 통로) 프로필로 Famulor 어시스턴트 설정과 대화 기록을 읽습니다. |
| [linkedin-outreach](https://github.com/vanshyadav1408/Omentir/tree/main/plugins/omentir/skills/linkedin-outreach) | Omentir MCP로 잠재 고객을 조사하고, 아웃리치(먼저 연락하기) 메시지 초안을 쓰고, 캠페인을 살펴봅니다. |
| [llm-wiki](https://github.com/praneybehl/llm-wiki-plugin/tree/main/skills/llm-wiki) | 자료를 링크로 이어진 Markdown 위키로 정리하고, 출처를 밝혀 답하고, 세션끼리 내용이 맞는지 점검합니다. |
| [okf](https://github.com/mattjoyce/okf-skill/tree/master/skills/okf) | 링크로 이어진 Markdown 개념 파일 묶음인 Open Knowledge Format 번들을 작성하고 검증합니다. |
| [process-builder](https://github.com/Castaldo-Solutions/process-builder) | 프로세스 인터뷰 내용을 .drawio 파일의 BPMN 스윔레인 다이어그램(일을 맡은 사람별로 칸을 나눈 흐름도)으로 바꿉니다. |
| [project-planning-journaling](https://github.com/mh-mansouri/Project-Planning-Journaling/tree/main/project-planning-journaling) | 프로젝트 범위를 정하고, 결정 사항과 진행 상황, 남은 작업을 이어서 쓸 수 있는 일지로 관리합니다. |
| [readme-atlas](https://github.com/chromoany/readme-atlas) | 저장소의 근거를 바탕으로 프로젝트 README를 쓰고, 다시 쓰고, 리뷰하고, 번역합니다. 저장소가 뒷받침하지 못하는 주장은 뺍니다. |
| [swarmvault](https://github.com/swarmclawai/swarmvault/tree/main/skills/swarmvault) | 그래프 탐색, 검색, 리뷰, 선택형 모델 기반 종합 기능을 갖춘 내 컴퓨터의 Markdown 지식 저장소를 관리합니다. |
| [trace-my-code](https://github.com/kgohil/trace-my-code/tree/main/skills/trace-my-code) | 도메인 흐름, 아키텍처 메모, 재사용 패턴을 관리하고, 코드와 문서가 서로 맞지 않는 곳을 점검합니다. |

<a id="-media--content-creation"></a>
<a id="media--content-creation"></a>

### 미디어 및 콘텐츠 제작

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [3d-logo](https://github.com/hasuwini77/3d-logo-skill/tree/main/skills/3d-logo) | React Three Fiber로 회전하는 3D 로고 컴포넌트(화면 부품)를 만듭니다. |
| [algorithmic-art][algorithmic-art] | p5.js로 제너러티브 아트(규칙으로 만들어 내는 그림)를 만듭니다. |
| [bria-ai](https://github.com/Bria-AI/bria-skill/tree/dev/skills/bria-ai) | Bria API(프로그램끼리 대화하는 창구)로 이미지를 만들고 고치며 배경을 지웁니다. |
| [canvas-design][canvas-design] | PNG와 PDF 파일로 시각 디자인을 만듭니다. |
| [cliptude-plan](https://github.com/cliptude/cliptude/tree/main/mcp_server/skills/cliptude-plan) | YouTube 다큐멘터리의 모든 샷(장면)을 계획한 뒤, Cliptude가 음성을 입히고 자료를 구해 렌더링(영상으로 완성)하게 합니다. |
| [collage-design](https://github.com/polgarp/collage-design) | 사용이 허가되었거나 직접 제공한 이미지로 콜라주 작품을 구성하고, 출처 표기 목록을 관리합니다. |
| [comment-to-dm-cta](https://github.com/commentkeyword/agent-toolkit/tree/main/skills/comment-to-dm-cta) | Instagram 릴스의 "댓글에 KEYWORD" CTA(행동 유도 문구)를 기획하고 CommentKeyword에서 자동 DM(개인 메시지)을 만듭니다. 계정과 API 토큰이 필요합니다. |
| [harmonic-mixing](https://github.com/songfinder-dev/songfinder-skills/tree/main/skills/harmonic-mixing) | 템포와 음악 키를 조회해 플레이리스트와 DJ 전환을 계획합니다. |
| [hitpost](https://github.com/Lihaila/hitpost-skill/tree/main/skills/hitpost) | 아이디어마다 X 글 또는 스레드 세 가지를 쓰고, X의 글자 수 계산 방식에 맞춰 길이를 검사하며 공유 링크도 함께 만듭니다. |
| [identify-song](https://github.com/songfinder-dev/songfinder-skills/tree/main/skills/identify-song) | Song Finder로 링크나 오디오 파일에서 곡을 찾아냅니다. |
| [kavel-image](https://github.com/hanshs474/kavel-image-skill) | 무료 사용량 안에서 Kavel의 API(프로그램끼리 대화하는 창구)로 이미지를 만듭니다. 익명으로 요청을 보낸 뒤 결과를 반복해서 확인하는 방식입니다. 사진 편집에는 Kavel API 키가 필요합니다. |
| [keyword-icons](https://github.com/ruthless-coder-ai/keyword-icons) | 단순한 SVG 아이콘 콘셉트를 여러 개 만들고, 투명 PNG로 렌더링한 결과를 작은 크기에서 확인합니다. |
| [ltx2-video](https://github.com/patraxo/ltx2-vidgen-skill/tree/main/skills/ltx2-video) | 내 Modal 계정에 배포한 LTX-2.3 백엔드로 텍스트, 이미지, 영상에서 클립(짧은 영상)을 만듭니다. |
| [make-faceless-video](https://github.com/airdropfi/autoshort-skills/tree/main/skills/make-faceless-video) | AutoShort 또는 StoryShort MCP 서버로 얼굴 없는 숏폼 영상을 초안 작성, 가격 확인, 렌더링(영상으로 완성)합니다. 크레딧이 있는 계정이 필요합니다. |
| [meshy-pose-rigging](https://github.com/rickyworld/rigmeshy-by-ricky/tree/master/meshy-pose-rigging) | 캐릭터 레퍼런스(참고 그림)를 준비하고 Meshy 자동 리깅(움직일 뼈대 넣기)과 내보내기 문제 해결을 진행합니다. |
| [pro-motion](https://github.com/jack-reson8/pro-motion/tree/main/plugins/pro-motion/skills/pro-motion) | 기획된 음악 트랙에 맞춰 편집한, 소리를 먼저 생각한 모션 그래픽 런칭·브랜드·TVC 영상을 코드로 MP4로 렌더링합니다. |
| [publishport](https://github.com/karuha-m/publishport-skill/tree/main/skills/publishport) | 내 PublishPort 브라우저 앱에 연결된 계정으로 글을 올리고, 여러 곳에 함께 올립니다. |
| [puzzlegenio](https://github.com/fruitwyatt/puzzlegenio-claude-skill) | 퍼즐 유형을 고르고, 인쇄용 퍼즐을 만드는 PuzzleGenio 브라우저 도구로 연결되는 값이 채워진 링크를 만듭니다. |
| [reels-setup](https://github.com/VishiATChoudhary/reels/tree/main/skills/reels-setup) | 노래의 드롭(분위기가 바뀌는 순간)에 맞춰 편집한 9:16 스토리 릴스를 만드는 Remotion 스튜디오를 설치하고 검증합니다. |
| [runapi-cli](https://github.com/runapi-ai/cli-skill/tree/main/skills/runapi-cli) | RunAPI CLI(글자로 명령을 입력하는 도구)로 미디어를 만들고 모델 작업을 실행합니다. 결제와 인증 설정이 필요합니다. |
| [ruxi-skill](https://github.com/swaylq/ruxi-skill) | 선택한 책의 장면과 출처가 연결된 선택지로 파일 하나짜리 비주얼 노벨(이야기 게임)을 만듭니다. |
| [screenbrowser](https://github.com/screenbrowser/skill/tree/main/skills/screenbrowser) | Screen Browser MCP(Claude가 다른 서비스와 연결되는 통로) 서비스로 내레이션(해설 목소리)이 들어간 웹 앱 튜토리얼을 만듭니다. |
| [seedance-25-prompting](https://github.com/gbeyrouti/seedance-prompting-claude-skill/tree/main/seedance-25-prompting) | Seedance 영상 프롬프트(AI에게 주는 지시문), 레퍼런스 역할, 오디오, 샷 타이밍을 쓰고 문제를 해결합니다. |
| [slack-gif-creator][slack-gif-creator] | Slack에 맞는 크기의 움직이는 GIF를 만듭니다. |
| [SocialClaw](https://github.com/ndesv21/socialclaw/tree/main/skill) | SocialClaw로 소셜 게시물을 예약하고 올립니다. 설정된 워크스페이스와 유효한 요금제가 필요합니다. |
| [table-sheet](https://github.com/netmobster/unstuck-games/tree/main/plugins/table-sheet) | D&D Beyond 캐릭터 시트를 플레이 가이드와 게임 시작 전 체크리스트로 바꿉니다. |
| [vox-director](https://github.com/Alisa0808/vox-director) | 유료 Atlas Cloud API와 내 컴퓨터의 ffmpeg로 내레이션(해설 목소리)이 들어간 콜라주 영상을 기획하고 조립합니다. |
| [watch-igaming](https://github.com/igamingsychov/watch-igaming) | 영상 링크나 내 컴퓨터의 화면 녹화를 스크립트와 장면 전환 프레임으로 검토하고, QA 표, UX 감사, 회의록을 만듭니다. |
| [youtube-transcript](https://github.com/tubeagentkit/youtube-transcript-skills/tree/main/skills/youtube-transcript) | YouTube Transcript API(프로그램끼리 대화하는 창구)로 자막, 영상 검색 결과, 재생목록을 가져옵니다. |

<a id="-data--analysis"></a>
<a id="data--analysis"></a>

### 데이터 및 분석

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [adhx](https://github.com/itsmemeworks/adhx/tree/main/skills/adhx) | ADHX API(프로그램끼리 대화하는 창구)로 X 게시물과 글을 정리된 JSON 형식으로 읽어옵니다. |
| [aligned-delivery](https://github.com/ahnbingbing/aligned-delivery) | 스프린트(짧은 개발 주기)와 전달 지표를 분석하고, 팀의 업무량을 진단하고, 완료 시점을 예측합니다. |
| [apify-account-mapping](https://github.com/johnisanerd/claude-skill-account-mapping/tree/main/apify-account-mapping) | 유료 Apify 액터(자동 수집 프로그램)로 목표 기업별로 지정한 직책을 지금 맡고 있는 사람을 파악합니다. |
| [apify-linkedin-post-engagement](https://github.com/johnisanerd/claude-skill-linkedin-post-engagement/tree/main/apify-linkedin-post-engagement) | 유료 Apify 데이터로 LinkedIn 게시물의 반응, 댓글, 공유 수를 비교합니다. |
| [apify-linkedin-posts-scraper](https://github.com/johnisanerd/claude-skill-linkedin-posts-scraper/tree/main/apify-linkedin-posts-scraper) | 유료 Apify 액터(자동 수집 프로그램)로 공개된 LinkedIn 게시물 기록을 모읍니다. |
| [apify-remote-startup-jobs](https://github.com/johnisanerd/claude-skill-remote-startup-jobs/tree/main/apify-remote-startup-jobs) | 유료 Apify 액터(자동 수집 프로그램)로 정리된 형태의 원격 근무 스타트업 채용 공고를 가져옵니다. |
| [apify-yc-startup-jobs](https://github.com/johnisanerd/claude-skill-yc-startup-jobs/tree/main/apify-yc-startup-jobs) | 유료 Apify 액터(자동 수집 프로그램)로 공개된 스타트업 연봉 및 지분 범위를 비교합니다. |
| [apify-youtube-transcript-api](https://github.com/johnisanerd/claude-skill-youtube-transcript-api/tree/main/apify-youtube-transcript-api) | 유료 Apify 액터(자동 수집 프로그램)로 YouTube 자막과 자막 형식을 가져옵니다. |
| [apify-youtube-transcripts-llm-training-data](https://github.com/johnisanerd/claude-skill-youtube-transcripts-llm-training-data/tree/main/apify-youtube-transcripts-llm-training-data) | 출처 정보, 언어 정책, 오류 걸러내기, 유료 Apify 사용량을 갖춘 자막 데이터셋(자료 묶음)을 만듭니다. |
| [apitube-news-api](https://github.com/apitube/news-api-skills/tree/main/skills/apitube-news-api) | APITube로 뉴스를 검색하고 걸러내며, API 인증, 페이지 나누기, 오류 처리도 함께 다룹니다. |
| [claude-ecom](https://github.com/takechanman1228/claude-ecom) | 온라인 쇼핑몰 주문 CSV(표 파일)에서 매출, 다시 사는 비율, 이익 마진 패턴을 살펴봅니다. |
| [claude-persona](https://github.com/takechanman1228/claude-persona/tree/main/skills/persona) | 가상의 사람들로 이루어진 패널과 콘셉트 인터뷰를 흉내 내고, 탐색을 위한 조사로 주제와 비교 결과를 요약합니다. |
| [converly](https://github.com/converlyio/converly-agent) | Converly 전환 흐름(방문자가 구매·가입으로 이어지는 과정)을 설정하고, 테스트 이벤트와 전달된 전환을 확인합니다. |
| [datawebot](https://github.com/datawebot/datawebot-mcp/tree/main/skills/datawebot) | 호스팅된 datawebot MCP(Claude가 다른 서비스와 연결되는 통로) 서버로 온라인 쇼핑몰의 상품과 판매자별 가격을 직접 링크와 함께 찾습니다. |
| [formo-analytics](https://github.com/getformo/cli/tree/main/skills/formo-analytics) | MCP, CLI, REST(Claude 연결 통로, 명령 도구, 프로그램 대화 방식)로 Formo의 제품 및 온체인 분석 데이터를 조회합니다. |
| [invoice-winning-numbers](https://github.com/tahodev/baodao-skill/tree/main/invoice-winning-numbers) | 공식 출처에서 기간별 대만 영수증 당첨 번호를 조회합니다. |
| [market-mirror](https://github.com/DarkWorldCoder/market-mirror/tree/main/plugin/skills/market-mirror) | 광고, 가격, 영업 멘트를 가상의 구매자에게 시험해 보고, 진행·보완·중단 판정 보고서를 받습니다. |
| [octav-api](https://github.com/Octav-Labs/octav-api-skill) | API 키로 지갑 잔액, 내역, DeFi 포지션을 연동합니다. 일부 에이전트 엔드포인트는 x402 결제도 지원합니다. |
| [pandas-pro](https://github.com/jeffallan/claude-skills/tree/main/skills/pandas-pro) | pandas DataFrame과 시계열 데이터를 정리하고, 합치고, 모으고, 바꿉니다. |
| [polymarket-tennis](https://github.com/livetennisapi/polymarket-tennis/tree/main/skills/polymarket-tennis) | 시장 가격을 실시간 경기 점수와 합쳐서 보기만 하는 테니스 시장 감시기를 만듭니다. |
| [pvr-inox-radar](https://github.com/karanb192/pvr-inox-radar/tree/main/skills/pvr-inox-radar) | 인도 PVR INOX의 상영 시간표를 나란히 앉을 수 있는 좌석 수와 이동 시간 추정치와 함께 정리합니다. |
| [shopify-review-triage](https://github.com/alfredtech2026/shopify-app-review-brief/tree/main/docs/skills/shopify-review-triage) | 제공받은 Shopify 리뷰를 출처가 연결된 장애, 불편, 가격, 기능 요청으로 분류합니다. |
| [site-traffic-teardown](https://github.com/zhuyansen/site-traffic-teardown/tree/main/skills/site-traffic-teardown) | 사이트의 경쟁사를 찾아 트래픽, 채널 구성, 키워드, 백링크, DR을 비교하고 성장 기회 세 가지를 짚어줍니다. AIsa 유료 데이터를 사용합니다. |
| [sql-pro](https://github.com/jeffallan/claude-skills/tree/main/skills/sql-pro) | SQL 쿼리(데이터 요청)를 쓰고 최적화하며, 실행 계획을 살펴보고, 데이터베이스 방언(종류별 문법 차이)을 비교합니다. |
| [weread-trial-card-list](https://github.com/C-s-salute/weread-trial-card-list) | WeRead 카테고리·순위 페이지를 자동으로 읽어 체험 카드로 읽을 수 있는 도서 목록을 중복 없이 만들고 HTML과 Excel로 내보냅니다. |
| [youtube-full](https://github.com/ZeroPointRepo/youtube-skills/tree/main/skills/youtube-full) | TranscriptAPI로 YouTube 자막, 검색 결과, 채널 데이터, 재생목록을 가져옵니다. API 키가 필요합니다. |

<a id="-finance--tax"></a>
<a id="finance--tax"></a>

### 금융 및 세무

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [file-itr](https://github.com/shivprime94/file-itr) | 인도 소득세 신고 포털을 단계별로 안내받으며 따라갑니다. |
| [furusato-nozei](https://github.com/tahodev/kurashi-skill/tree/main/furusato-nozei) | 전제 조건을 밝히고 공식 출처에 근거해 일본 고향납세 기부 한도를 추정합니다. |
| [ipo-offer-document-review](https://github.com/parinshahAIbuilder/ipo-offer-document-review) | 인도 IPO 공모 서류(DRHP/RHP)를 SEBI ICDR, LODR, Companies Act, Ind AS에 비추어 공시 누락이 없는지 리뷰합니다. |
| [itr-wala](https://github.com/karanb192/itr-wala) | 문서에서 내용을 뽑고 Python으로 계산해 인도 소득세 신고서를 준비합니다. |
| [open-finance-skills](https://github.com/levelcfo/open-finance-skills) | 20개의 재무 스킬로 중소기업의 월말 결산, 은행 대사, 13주 현금 예측, 1099 신고 준비 상태를 리뷰합니다. |
| [simmer-tennis-live-gate](https://github.com/livetennisapi/simmer-tennis-live-gate) | 주문은 넣지 않고, 모의(시뮬레이션) 테니스 시장에 들어가는 것을 실시간 경기 상태에 따라 허용하거나 막습니다. |
| [stipend](https://github.com/stipend-sh/stipend) | 지출 정책을 정할 수 있는, 직접 보관하는 USDC 지갑과 x402 결제를 관리합니다. |
| [stock-analysis](https://github.com/AlenSarangSatheesh/Indian-Stocks-Fundamental-Analysis-SKILL/tree/main/stock-analysis) | 1차 공시 자료, 업종 비교, 회계 품질 점검으로 상장 기업을 분석합니다. |
| [verify-polish-company](https://github.com/bartosz-kuc/skanfirmy-mcp/tree/main/skill) | 폴란드 기업의 등록 정보, VAT 상태, 은행 계좌, EU VAT 번호를 조회합니다. |

<a id="️-writing--research"></a>
<a id="writing--research"></a>
### 글쓰기 & 리서치

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [ai-tell-detector](https://github.com/aragossa/ai-tell-detector/tree/main/en/ai-tell-detector) | 영어나 러시아어로 쓴 초안에서 흔히 보이는 뻔한 글쓰기 버릇을 찾고, 고칠 방법을 정확히 알려 줍니다. |
| [berlin-job-search](https://github.com/umutyesildal/berlin-job-search/tree/main/skills/berlin-job-search) | 베를린과 독일의 구인 사이트를 찾아봅니다. 독일어 실력과 블루카드(독일에서 일하기 위한 비자) 조건도 확인합니다. 없는 경력은 지어내지 않고 Lebenslauf(독일식 이력서)나 영어 이력서 초안을 씁니다. |
| [brand-guidelines][brand-guidelines] | Anthropic의 브랜드 색깔과 글씨체를 아티팩트(Claude가 만든 결과물)에 입힙니다. |
| [business-name-fit](https://github.com/Elham-Farajnejad/business-name-fit) | 가게나 회사 이름이 여러 나라, 여러 언어, 목표 시장에서 어떻게 받아들여질지 살펴봅니다. |
| [buyer-eval-skill](https://github.com/salespeak-ai/buyer-eval-skill) | 업체의 주장, 서로 맞지 않는 점, 답이 없는 질문, 구매 조건을 확인해서 기업용 소프트웨어(B2B) 판매 업체를 평가합니다. |
| [check-blindspot](https://github.com/AlexanderCato/check-blindspot) | 내가 믿는 내용을 증거와 맞대어 봅니다. 찬성과 반대 양쪽 입장에서 따져 보고, 결론을 뒤집을 만한 핵심 사실을 짚고, 지나친 자신감을 지적합니다. |
| [diasporic-intelligence](https://github.com/MinistaJazz/diasporic-intelligence/tree/main/skills/diasporic-intelligence) | 문화와 조상(혈통) 이야기를 다루는 글에 출처 표기 방법과 동의를 받는 틀을 적용합니다. |
| [fact-check-x-complete](https://github.com/ASI2030/Fact-Check-X/tree/main/skills/fact-check-x-complete) | AI의 답과 인용을 모아 작은 주장 하나하나로 나누어 견줍니다. 확인하는 동안 증거도 보관합니다. |
| [feynman-pdf](https://github.com/TadTheFisherman/feynman-it) | 쉬운 비유를 넣고 완성된 쪽을 점검하면서, 그림이 들어간 PDF 설명서를 만듭니다. |
| [goethecoach](https://github.com/janosszaboaipm-design/goethecoach-claude-skill/tree/main/goethecoach) | 채점 기준에 맞춘 피드백으로 괴테 시험의 쓰기, 읽기, 말하기를 연습합니다. |
| [grill](https://github.com/mtangoz/grill/tree/main/skills/grill) | 다른 AI 모델의 힘을 빌려 결정을 꼼꼼히 따져 봅니다. 의문을 풀어 줄 테스트도 알려 줍니다. |
| [grounded](https://github.com/jostelzer/grounded/tree/main/skills/grounded) | 실시간으로 출처를 찾고 인용이 맞는지 확인한 뒤, 과학 논문을 정리한 글의 초안을 씁니다. |
| [humanize-chinese](https://github.com/swaylq/humanize-chinese) | 문장을 다시 쓰고, 표현을 정리하고, 내 컴퓨터에서 점검해 중국어 글을 다듬습니다. 비상업 라이선스(돈 버는 용도로는 쓸 수 없는 라이선스)입니다. |
| [humanize-pro](https://github.com/msdanyg/humanize-pro) | 저장해 둔 문체 프로필과 글을 올리는 곳의 규칙에 맞춰 글을 고쳐 쓰거나 점검합니다. |
| [humanizer-ru](https://github.com/ilyautov/humanizer-ru) | 사실, 문체, 건드리면 안 되는 글은 그대로 두고 읽는 사람에 맞게 러시아어 글을 다듬습니다. |
| [humanizer-zh-tw](https://github.com/nagameTW/formosa-humanizer) | 번체 중국어(대만에서 쓰는 중국어) 글에서 AI가 쓴 티가 나는 버릇을 없앱니다. 중국 본토 용어는 대만 표현으로 바꾸고, 문장부호는 넓은 모양(전각) 그대로 둡니다. |
| [humanizing-writing](https://github.com/AshwinSathian/humanize-writing-skill) | 틀에 박힌 구조, 군더더기, 약한 주장, 반복되는 글쓰기 버릇을 고칩니다. |
| [internal-comms][internal-comms] | 소식 알림이나 뉴스레터처럼 회사 안에서 돌려 보는 글의 초안을 씁니다. |
| [jd-decoder](https://github.com/landedjobs/ai-job-hunt-os/tree/main/skills/jd-decoder) | 지원하기 전에 채용 공고를 읽고 실제로 필요한 조건, 월급 단서, 가짜 공고일 위험을 알아냅니다. |
| [kochab](https://github.com/btmoriarty/kochab/tree/main/skills/kochab) | 이력서를 바탕으로 맞춤 초안을 쓰고, 면접을 준비하고, 지원 현황을 관리하면서 구직 활동을 이끕니다. |
| [niubiskill](https://github.com/nathanskill/niubiskill/tree/main/skills/niubiskill) | 사업 아이디어를 살펴보고, 분명한 근거와 가정을 따져서 돈이 될지 다음에 시험해 볼 방법을 고릅니다. |
| [no-slop](https://github.com/Byk3y/no-slop) | 출처를 흐리게 쓰기, 광고 같은 말투, 같은 구조 반복처럼 흔한 글쓰기 버릇이 있는지 글을 살펴봅니다. |
| [prospeak](https://github.com/giorgiozamboni/prospeak) | 영어와 이탈리아어의 말투 조절 기능으로 이미 쓴 글을 전문가 독자에게 맞게 고쳐 씁니다. |
| [publora-post-ideas](https://github.com/publora-team/publora-post-ideas/tree/main/skills/publora-post-ideas) | 소셜 미디어 게시물을 쓰는 방향 세 가지 중 하나를 고르게 하고, 고른 방향으로 초안을 씁니다. |
| [reading-analysis](https://github.com/shenquan520/reading-analysis) | 영어 시험의 지문, 보기, 자주 나오는 오답 유형을 분석합니다. 비상업 라이선스(돈 버는 용도로는 쓸 수 없는 라이선스)입니다. |
| [renwei](https://github.com/dbhosbu-dotcom/renwei) | 중국어 원고의 문장 짜임, 장마다의 흐름, 사실이 서로 맞는지, 뻔한 문장을 다듬습니다. |
| [resume-claim-guard](https://github.com/korey2028-prog/resume-claim-guard) | 지원자에게 먼저 질문해 확인된 사실 정리표를 확정하고, 그다음 채용 공고에 맞춰 이력서를 고칩니다. |
| [resume-studio](https://github.com/Sidgit11/resume-studio) | 경력을 보여 주는 자료를 관리하고, 없는 내용은 지어내지 않으면서 맡을 일의 조건에 맞게 이력서를 고칩니다. |
| [sales-framework](https://github.com/KudoMetrics-Techologies-Private-Limited/sales-framework/tree/main/skills/sales-framework) | 널리 알려진 설득 방법에 맞춰 판매 문구, 소개 발표(피치), 반대 의견에 답하는 말을 살펴봅니다. |
| [Say it plainly](https://github.com/adjustleads/provenskills-free-packs/tree/main/plain-writing/say-it-plainly) | 주장은 바꾸지 않고 읽는 사람이 이해하기 쉽게 글을 고쳐 씁니다. 비상업 라이선스(돈 버는 용도로는 쓸 수 없는 라이선스)입니다. |
| [seo-translator](https://github.com/Skillproofdev/seo-translator) | 키워드, 링크, 구조는 그대로 두고 시장마다 다른 말투에 맞게 내용을 현지화(그 나라에 맞게 바꾸기)합니다. |
| [signs-of-ai](https://github.com/peopleworks/SignsofAI) | 영어와 스페인어 글의 글쓰기 버릇을 다듬습니다. 선택해서 쓰는 분석 도구가 있으면 그 결과를 한계와 함께 풀이합니다. |
| [structured-gist](https://github.com/domattioli/structured-gist/tree/main/skills/structured-gist) | 설명과 진행 요약을 훑어보기 좋은 층층 개요로 정리합니다. |
| [swedish_mentor](https://github.com/mh-mansouri/help_with_swedish/tree/master/swedish_mentor) | 수준에 맞는 영상, 팟캐스트, 말하기 연습으로 스웨덴어 공부 계획을 짭니다. |
| [tldr](https://github.com/SurefireStudios/tldr/tree/main/skills/tldr) | 짧은 요약을 맨 앞에 두되, 자세한 내용과 중요한 주의사항은 그대로 남깁니다. |
| [trade-show-prep](https://github.com/DataOrigin/trade-show-prep-skill/tree/main/skills/trade-show-prep) | 기업끼리 거래하는 전시회(B2B) 참가를 계획합니다. 만나자는 요청 글 초안을 쓰고, 부스에 찾아온 사람 중 가능성 있는 사람을 고르고, 나중에 보낼 연락 문구를 씁니다. |
| [unslop](https://github.com/MohamedAbdallah-14/unslop/tree/main/skills/unslop) | 기술 내용은 그대로 두고, 반복되는 AI식 글쓰기 버릇이 사라지도록 글을 고쳐 씁니다. |
| [upwork-job-hunter](https://github.com/droopboop/flconsole-upwork-mcp/tree/main/skills/upwork-job-hunter) | flconsole MCP 서버(Claude가 다른 서비스와 연결되는 통로)로 Upwork의 새 일감을 살펴봅니다. 맞는 일감을 골라 검토할 제안서 초안을 씁니다. |
| [zh-tw-humanizer](https://github.com/acchuang/zh-tw-humanizer) | 대만 용어와 건드리면 안 되는 사실 규칙을 지키면서 번체 중국어 글을 다듬습니다. |

<a id="-meta-skills"></a>
<a id="meta-skills"></a>

### 메타 스킬

| 스킬 | 이럴 때 쓰세요 |
| --- | --- |
| [CERA Project Memory](https://github.com/miketepUR/cera-reasoning-harness) | 프로젝트 대화 기록의 지도를 보존하고, 다음 대화에서 함께 쓸 공유 목차를 정리합니다. |
| [claude-memory-manager](https://github.com/jau123/claude-memory-manager) | 정리 규칙, 업데이트 안내서, 목차 크기 점검으로 Claude Code의 자동 기억(메모리)을 정돈합니다. |
| [danshari-skill](https://github.com/swaylq/danshari-skill) | 설치된 스킬을 점검하고, 사용자가 허락하면 겹치는 스킬을 되돌릴 방법과 함께 보관해 둡니다. |
| [emulo](https://github.com/ohad6k/emulo/tree/main/.agents/skills/emulo) | 살펴볼 범위와 비용을 허락받은 뒤, 내 컴퓨터에 저장된 에이전트 대화 기록을 분석해 나의 작업 습관 프로필을 만듭니다. |
| [feedback](https://github.com/luchasarie/feedback-loop/tree/main/skills/feedback) | 에이전트에게 느낀 불만을 근거가 있는 개선 계획으로 바꿉니다. 허락하기 전에는 아무것도 바꾸지 않습니다. |
| [prime-worker](https://github.com/alperiox/prime-worker) | 여러 번 주고받아야 하는 작업을 내 컴퓨터에서 계속 돌아가는 prime-agent 작업자에게 맡깁니다. |
| [reap (skillreaper)](https://github.com/thousandflowers/skillreaper/tree/main/plugins/skillreaper/skills/reap) | 내 컴퓨터의 에이전트 대화 기록에서 쓰이지 않는 컨텍스트(Claude가 기억하고 있는 대화 내용)가 얼마나 되는지 재고, 되돌릴 수 있는 정리 작업을 살펴봅니다. |
| [rule-architect](https://github.com/moveju112/rule-architect) | 공유 목차와 프로그램별 시작점을 갖춘, 조각으로 나뉜 프로젝트 규칙을 만듭니다. |
| [sijiao-skill](https://github.com/swaylq/sijiao-skill) | 조사한 내용으로 수업, 연습 문제, 간격을 두고 하는 복습을 짜서, 학습 상태를 기억하는 공부 선생님을 만듭니다. |
| [skill-creator][creator] | 스킬을 만들고, 평가하고, 설명을 다듬습니다. |
| [skill-freshness](https://github.com/kvozianov/skill-freshness) | Claude Code, Codex, Cursor 같은 여러 에이전트의 스킬 중 고장 난 것, 오래된 것, 겹치는 것, 이미 내장된 것을 출처와 함께 점검합니다. |
| [skill-skill](https://github.com/jack-reson8/skill-skill/tree/main/plugins/skill-skill/skills/skill-skill) | 결과를 실제로 바꾸는 스킬을 쓰고, Agent Skills 규격에 맞는지 검사(린트)한 뒤 건강 점수를 매깁니다. |
| [skill-tuner](https://github.com/DENGYUFAN0/skill-forge/tree/main/skill-tuner) | 작게 기준선을 재고, 한 부분에 집중해 고치고, 되돌릴지 판단하는 과정을 거쳐 설치된 스킬을 다듬습니다. |
| [subagent-driven-development][subagents] | 계획을 나눠 맡긴 작업과 검토 단계로 쪼개어 만듭니다. |
| [task-observer](https://github.com/rebelytics/one-skill-to-rule-them-all) | 일하다 겪은 불편을 기록하고, 다시 쓸 스킬을 어떻게 바꾸면 좋을지 검토할 수 있는 제안을 냅니다. |
| [template-skill][template] | 가장 간단한 `SKILL.md` 틀로 스킬 만들기를 시작합니다. |
| [whetstone](https://github.com/TbusOS/whetstone) | 일하며 얻은 교훈을 근거와 중복 검사를 갖춘, 검토할 수 있는 스킬 제안으로 정리합니다. |
| [writing-skills][writing-skills] | 배포하기 전에 스킬 지침을 쓰고 시험해 봅니다. |

[카테고리로 돌아가기 ↑](#browse-skills)

<a id="skill-collections"></a>

## 스킬 컬렉션

관련 스킬 묶음이 필요할 때 이 저장소들을 둘러보세요.

| 컬렉션 | 주요 내용 |
| --- | --- |
| [Anthropic skills](https://github.com/anthropics/skills) | 문서 다루기, 디자인, 개발, 스킬 예제를 다룹니다. |
| [Superpowers](https://github.com/obra/superpowers) | 계획, 테스트, 오류 찾기(디버깅), 개발 순서(워크플로)를 다룹니다. |
| [adologyai/content-intelligence-plugin](https://github.com/adologyai/content-intelligence-plugin) | Adology가 운영하는 MCP(Claude가 다른 서비스와 연결되는 통로) 도구로 경쟁사 광고 조사, 브랜드 추적, 보는 사람 분석을 합니다. |
| [Affiliate Skills](https://github.com/Affitor/affiliate-skills) | 제휴 마케팅(남의 상품을 소개하고 대가를 받는 홍보)의 조사, 콘텐츠, 유통, 분석을 다룹니다. |
| [Agent Skills English Productivity Pack](https://github.com/alapha888/agent-skills-en) | 회의록, 글 다듬기, 조사, 코드 검토, 커밋 메시지를 다룹니다. |
| [agent-pilot-skills](https://github.com/babyGao/agent-pilot-skills) | 여러 AI 모델의 서로 검토하기, 동시에 조사하기, 밖으로 보내는 영업, 일러스트, 중국 플랫폼에서 일하는 순서를 다룹니다. |
| [agentsvc.io skills](https://github.com/agentsvc/skills) | 유료 agentsvc.io API(프로그램끼리 대화하는 창구)로 음성을 글로 바꾸고, 웹 페이지를 Markdown으로 바꾸고, 이메일을 확인하고, 토큰 안전성을 점검하고, 문서에서 글을 뽑습니다. |
| [AI sales skills](https://github.com/Marchenko-sales/ai-sales-skills) | 러시아어로 회사 조사, 영업 대상인지 판단하기, 업무용 접촉(아웃리치) 순서를 다룹니다. |
| [aigent-OS](https://github.com/wrg32786/aigent-os) | 계속 이어지는 볼트(보관함) 기억, 작업 시간 루틴, 일 맡기기, 훅(특정 순간에 자동으로 실행되는 동작), 내 컴퓨터에서 하는 관리 순서를 다룹니다. |
| [Baodao skills](https://github.com/tahodev/baodao-skill) | 대만 공공 서비스의 영수증(인보이스), 날씨, 경보, 교통, 공공 데이터 조회를 다룹니다. |
| [ChatCrystal](https://github.com/ZengLiangYi/ChatCrystal/tree/main/skills) | 코딩 작업에 쓸 내 컴퓨터 기억 불러오기와 기록 다시 쓰기를 다룹니다. |
| [Chisanan232/requirement-zero](https://github.com/Chisanan232/requirement-zero) | 요구사항이 정말 필요한지 따져 보고, 기존 코드가 유지 비용만큼 값어치를 하는지 점검합니다. |
| [claude-fable-5-skills](https://github.com/kpab/claude-fable-5-skills) | 노력 수준 조정, 작업 범위 관리, 서브에이전트(일을 나눠 맡는 보조 Claude) 오케스트레이션(여러 작업을 순서에 맞게 조율하기)을 다룹니다. |
| [Cogny Marketing Skills](https://github.com/cognyai/claude-code-marketing-skills) | 마케팅 점검과 광고 문구 쓰기를 다룹니다. 실시간으로 계정과 연결하려면 Cogny 구독이 필요합니다. |
| [Cowork Tasks](https://github.com/sabbah13/cowork-tasks) | 허락받은 Cowork 연결 도구에서 내 컴퓨터의 작업 보드를 만들고 분류합니다. 우선순위 정하기와 보드 검토 스킬도 들어 있습니다. |
| [CreatorSkills Free Skills](https://github.com/calebvbi/creatorskills-free-skills) | 블로그 개요, 짧은 영상 대본, 방송 정리 노트, 챕터, 뉴스레터 기획, 소셜 미디어 문구를 다룹니다. |
| [dbhq-uk/marketplace](https://github.com/dbhq-uk/marketplace) | 원격 진단, 코드 찾기, 저장소 점검, 조사, 글쓰기, 업무 서비스 연결을 다룹니다. |
| [Design Engineer Skills](https://github.com/modeinspect/design-engineer-skills) | 저장소 설정, 부품(컴포넌트)이 미치는 영향 분석, 눈으로 하는 품질 확인, 검토하기 쉬운 화면 PR(코드를 고쳐 달라고 올리는 요청), PR의 디자인 검토, 디자이너를 위한 디자인 시스템 점수 매기기를 다룹니다. |
| [DurdeuVlad/persona-write](https://github.com/DurdeuVlad/persona-write) | 인물 설정에 맞춘 초안 쓰기와 다시 쓰기, 견본 글에서 문체 뽑아내기, 따로 하는 검토를 다룹니다. |
| [E-commerce skills](https://github.com/mardab96/ecommerce-claude-skills) | 가게 데이터로 결제 과정, 상품 설명, 이익, 재고, 재구매율, 분쟁을 점검합니다. |
| [Growth Cab GTM Skills](https://github.com/federicodon/growthcab-gtm-skills) | 메일 보내는 도메인 점검, 영업 첫 메일 평가, 잠재 고객 목록 검사, 미팅 성과 비교를 다룹니다. |
| [iOS agents and skills](https://github.com/apexbymanish/claude-ai-agents-ios) | Swift/iOS 개발, 테스트, 접근성(누구나 쓰기 쉬운 설계), 속도, 보안, 출시 전 점검을 다룹니다. |
| [Kudosity skills](https://github.com/kudosity/skills) | Kudosity로 문자(SMS), MMS, WhatsApp, RCS, 연락처 목록, 발송 결과를 알려 주는 웹훅(결과를 자동으로 알려 주는 연결)을 다룹니다. |
| [Kurashi skills](https://github.com/tahodev/kurashi-skill) | 일본 공공 서비스의 날씨, 경보, 공휴일, 세금, 도서관 조회를 다룹니다. |
| [leechen298/Code2Skill](https://github.com/leechen298/Code2Skill) | 소스 코드에서 에이전트 도구를 뽑아내고, 만들어진 작업 순서와 소스에 충실한지를 따로 검토합니다. |
| [Lesile-Yin/agent-skills](https://github.com/Lesile-Yin/agent-skills) | 프롬프트 엔지니어링(AI에게 지시문 잘 쓰기), 여러 관점 검토, 토큰 예산, PowerPoint 일괄 자동화를 다룹니다. |
| [Linked API Skills](https://github.com/Linked-API/linkedin-skills) | Linked API로 LinkedIn 프로필과 잠재 고객 흐름을 읽고 관리합니다. 로그인 정보(자격 증명) 설정이 필요합니다. |
| [Mamba Labs Skills](https://github.com/mambalabsdev/mamba-labs-skills) | 잠재 고객 조사, CRM(고객 정보 관리) 운영, 이메일 도착률, 새 시장에 나가는 순서를 다룹니다. 일부는 Apify를 사용합니다. |
| [MarchTalk/ai-content-skills](https://github.com/MarchTalk/ai-content-skills) | 중국어 개념 분석, 대화 초안 정리, 출처에 바탕을 둔 콘텐츠 검토를 다룹니다. |
| [Marketing Skills](https://github.com/coreyhaines31/marketingskills) | SEO(검색 결과에 잘 나오게 하는 작업), 광고 문구 쓰기, 이메일, 가격 정하기, 광고, 분석을 다룹니다. |
| [mblode/agent-skills](https://github.com/mblode/agent-skills) | UI, 글씨 모양, 개발자 사용 경험, 문서 쓰기, 검토, 출시 순서를 다룹니다. |
| [minxnnu-cloud/make-new-things](https://github.com/minxnnu-cloud/make-new-things) | Claude와 Codex 사이의 시각 자료 넘겨주기, 대표 장면 승인, 다시 하기 횟수 제한, 스킬 폴더 맞추기를 다룹니다. |
| [Nero1688/claude-academic-skills](https://github.com/Nero1688/claude-academic-skills) | 학술 계획, 문헌 점검, 연구 방법, 같은 결과를 다시 얻는 순서를 다룹니다. 라이선스가 섞여 있습니다. |
| [noizai/skills](https://github.com/noizai/skills) | 글을 소리로 바꾸는 더빙과 보조 목소리 설정을 다룹니다. |
| [NotFair](https://github.com/nowork-studio/notfair-plugin) | 서비스별 MCP 연결로 SEO(검색 결과에 잘 나오게 하는 작업), 검색 노출, 광고, 분석 순서를 다룹니다. |
| [Novu skills](https://github.com/novuhq/skills) | Novu 알림 순서, 받은 알림함, 환경설정, 호스팅 에이전트 채널을 만듭니다. |
| [Ontoly skills](https://github.com/0xsarwagya/ontoly/tree/main/skills) | Ontoly 그래프 증거에 바탕을 둔 설계 구조, 서로 기대는 관계(의존성), 코드 정리(리팩터링), 문서 쓰기 순서를 다룹니다. |
| [Pathmode](https://github.com/pathmodeio/claude-plugin) | 제품 아이디어를 의도 명세로 바꾸고, 가정이 맞는지 따져 묻고, 실제로 만든 증거를 확인합니다. |
| [prompt-to-asset](https://github.com/MohamedAbdallah-14/prompt-to-asset) | CLI(글자로 명령을 입력하는 도구)와 MCP 서버로 이미지 요청서를 나누어 맡기고, 소프트웨어용 자료를 만들고, 플랫폼별 묶음으로 내보냅니다. |
| [RouterBase Agent Skills](https://github.com/zenlee123/routerbase-agent-skills) | RouterBase 게이트웨이를 연결하고, 모델을 고르고, 미디어 생성 API 작업을 처리합니다. RouterBase 키가 필요합니다. |
| [Sequenzy skills](https://github.com/Sequenzy/skills) | Sequenzy CLI(글자로 명령을 입력하는 도구)나 MCP 서버로 고객 여정에 따른 메일, 캠페인, 거래 확인 이메일 업무를 합니다. Sequenzy 계정이 필요합니다. |
| [Shipwise](https://github.com/harmansidhudev/shipwise) | 검증, 디자인, 설계, 품질, 보안, 운영 전반에 걸쳐 웹앱 출시를 계획하고 검토합니다. |
| [sjh9714/skill-receipts](https://github.com/sjh9714/skill-receipts) | 채택한 이유와 기각한 이유가 공개된, 코드 범위를 제한하고 문제를 먼저 재현해 보는 작은 스킬을 다룹니다. |
| [suede-creator-skills](https://github.com/JasonColapietro/suede-creator-skills) | 코드 품질, 디자인, 마케팅, 출시를 다룹니다. |
| [superseo-skills](https://github.com/inhouseseo/superseo-skills) | SEO(검색 결과에 잘 나오게 하는 작업) 점검, 콘텐츠 쓰기, 링크 만들기를 다룹니다. |
| [Vibe Coding Rules skills](https://github.com/getvibekits/vibe-coding-rules/tree/main/skills) | 오류 설명, 페이지 추가, 커밋, 바뀐 내용 검토, 디자인 규칙 적용, 데이터베이스 변경 막기, SEO 점검을 다룹니다. |
| [Wondel.ai Skills](https://github.com/wondelai/skills) | 책과 스타일 가이드에서 가져온 제품, UX, 마케팅, 소프트웨어 방법론을 적용합니다. |
| [YouTube Skills](https://github.com/sergebulaev/youtube-skills) | YouTube 제목, 설명, 오프닝 훅(맨 앞의 눈길 끌기), 썸네일 요청서, 업로드 계획의 초안을 씁니다. Publora로 올리는 것은 선택 사항입니다. |
| [YYLO skills](https://github.com/yylo-dev/yylo-skills) | YYLO CLI(글자로 명령을 입력하는 도구)로 작업, 아티팩트, 성능 비교(벤치마크), 계속 이어지는 작업 기록을 관리합니다. |

<a id="how-to-install-skills"></a>
<a id="quick-start"></a>

## 빠른 시작

Anthropic이 만든 문서 스킬로 첫 설치를 해 봅시다. 설치는 Claude Code에서 터미널(글자로 명령을 입력하는 창)로 합니다.

**1단계.** Claude Code를 쓰는 터미널을 엽니다.

**2단계.** 아래 두 줄을 한 줄씩 입력합니다.

```bash
claude plugin marketplace add anthropics/skills
claude plugin install document-skills@anthropic-agent-skills
```

- 첫 줄은 Anthropic의 스킬 모음(마켓플레이스, 쉽게 말해 스킬 가게)을 등록하는 명령입니다.
- 둘째 줄은 그 가게에서 문서 스킬 꾸러미를 골라 설치하는 명령입니다.

**3단계.** PDF 파일을 하나 준비해서 Claude에게 건네고, 양식 칸(이름이나 날짜를 적는 빈칸)을 뽑아 달라고 요청하세요.

**4단계.** Claude가 뽑아 준 결과를 원본 파일과 나란히 놓고 비교해 보세요. 빠지거나 틀린 칸이 없는지 확인하는 과정입니다.

설치가 잘 안 되면 [Anthropic 설치 가이드][anthropic-install]를 읽어 보세요.

<details>
<summary><strong>다른 컬렉션, 단독 스킬, 업데이트</strong></summary>

각 원본 저장소에 적힌 설치 안내를 따르세요. 컬렉션은 플러그인(기능 꾸러미)으로 나오기도 하고 폴더 하나씩 나오기도 하며, 둘 다 되는 곳도 있습니다. 같은 컬렉션은 설치 방법을 하나만 골라 쓰세요.

스킬 하나만 따로 설치할 때는 폴더를 알맞은 자리에 넣습니다.

- 나만 쓸 때: `~/.claude/skills/<skill-name>/` (내 컴퓨터의 사용자 폴더 안에 있는 `.claude/skills` 폴더)
- 한 프로젝트에서만 쓸 때: `.claude/skills/<skill-name>/` (그 프로젝트 폴더 안에 있는 `.claude/skills` 폴더)

`SKILL.md`와 함께 들어 있는 다른 파일도 같은 폴더에 두어야 합니다. 자세한 설명은 [Claude Code 스킬 가이드][skill-guide]를 참고하세요.

플러그인으로 설치했다면 [플러그인 업데이트 가이드][plugin-updates]를 따라 새 버전으로 바꾸고, 단독 폴더는 원본 저장소의 업데이트 안내를 따르세요.
이 목록 저장소를 내려받는다고 해서 여기 나온 스킬이 설치되는 것은 아닙니다.

</details>

<a id="faq"></a>

## 자주 묻는 질문

<a id="what-are-skills"></a>

<details>
<summary><strong>스킬이란 무엇인가요?</strong></summary>

스킬은 Claude에게 일하는 요령을 알려 주는 레시피 카드입니다. 요령을 적은 `SKILL.md` 파일이 들어 있고, 필요하면 프로그램(스크립트)이나 자료도 함께 담깁니다. 일과 관련이 있으면 Claude가 스스로 불러 쓰고, 사용자가 직접 부를 수도 있습니다. 더 알고 싶다면 [스킬 가이드][skill-guide]를 읽어 보세요.

</details>

<details>
<summary><strong>모든 스킬이 모든 Claude 앱에서 동작하나요?</strong></summary>

그렇지 않을 수 있습니다. 스킬의 형식은 같지만, 쓸 수 있는 도구와 설치하는 방법은 앱마다 다릅니다. 예를 들어 Claude Code용 플러그인은 Claude.ai나 API에 저절로 설치되지 않습니다. 각 스킬의 원본 저장소에서 어떤 환경을 지원하는지 확인하고, Claude.ai나 API에서는 [Anthropic의 별도 설치 방법][anthropic-install]을 따르세요.

</details>

<a id="skills-vs-mcp-vs-system-prompts"></a>

<details>
<summary><strong>스킬, MCP, 프로젝트 지침 중 무엇을 써야 하나요?</strong></summary>

하려는 일에 맞는 것을 고르면 됩니다.

| 필요한 것 | 사용할 것 | 쉽게 말하면 |
| --- | --- | --- |
| 반복되는 작업이나 일하는 순서 | [스킬][skill-guide] | 일하는 방법이 적힌 레시피 카드 |
| 외부 서비스나 도구 접근 | [Model Context Protocol (MCP)][mcp-guide] | 다른 서비스로 가는 통로 |
| 프로젝트에 대해 Claude가 읽는 규칙 | [프로젝트 지침][memory-guide] | 교실 벽에 붙여 둔 규칙표 |

</details>

<details>
<summary><strong>목록의 스킬은 테스트나 감사를 거쳤나요?</strong></summary>

아닙니다. 이 목록은 커뮤니티가 함께 만든 디렉터리일 뿐, 안전을 보증하는 인증 제도가 아닙니다. 설치하기 전에 원본 저장소의 설명과 코드를 직접 읽으세요. 처음에는 결과를 눈으로 쉽게 확인할 수 있는 작업부터 시켜 보는 편이 안전합니다. 깨진 링크나 잘못된 설명을 발견하면 [이슈][suggest]로 알려 주세요.

</details>

<details>
<summary><strong>스킬을 직접 만들거나 기여할 수 있나요?</strong></summary>

네, 가능합니다. 직접 만들 때는 [skill-creator][creator]나 [템플릿][template]으로 시작하세요. 이 목록에 스킬을 추가하고 싶다면 [기여 가이드](CONTRIBUTING.ko.md)를 따르면 됩니다.

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
- [Simon Willison이 Claude Skills를 다룬 글][simon-skills]
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
