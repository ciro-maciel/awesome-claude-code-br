# Awesome Claude Code BR

> Claude Code 한국어 자료: 문서, 강의, skills, 규칙, plugins, 브라질에서 만든 MCP 서버.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%EA%B5%AC%EB%8F%85-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgN2EyIDIgMCAwIDEgMiAtMmgxNGEyIDIgMCAwIDEgMiAydjEwYTIgMiAwIDAgMSAtMiAyaC0xNGEyIDIgMCAwIDEgLTIgLTJ2LTEwIiAvPiA8cGF0aCBkPSJNMyA3bDkgNmw5IC02IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/ccbr-cartas) [![후원하기](https://img.shields.io/badge/%ED%9B%84%EC%9B%90%ED%95%98%EA%B8%B0-%EC%BB%A4%ED%94%BC%20%ED%95%9C%20%EC%9E%94-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-apoie) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square&logo=youtube&logoColor=FF0000)](https://go.mymarketing.click/ccbr-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square&logo=instagram&logoColor=E4405F)](https://go.mymarketing.click/ccbr-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/ccbr-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square&logo=rss&logoColor=FFA500)](feed/ko.xml) ![33 항목](https://img.shields.io/badge/%ED%95%AD%EB%AA%A9-33-555555?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMuNSA1LjVsMS41IDEuNWwyLjUgLTIuNSIgLz4gPHBhdGggZD0iTTMuNSAxMS41bDEuNSAxLjVsMi41IC0yLjUiIC8%2BIDxwYXRoIGQ9Ik0zLjUgMTcuNWwxLjUgMS41bDIuNSAtMi41IiAvPiA8cGF0aCBkPSJNMTEgNmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxMmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxOGw5IDAiIC8%2BIDwvc3ZnPg%3D%3D)

[![Português](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/pt.svg)](README.md) [![English](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/en.svg)](README-en.md) [![Español](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/es.svg)](README-es.md) [![Français](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/fr.svg)](README-fr.md) [![Deutsch](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/de.svg)](README-de.md) [![Italiano](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/it.svg)](README-it.md) [![Русский](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ru.svg)](README-ru.md) [![中文](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/zh.svg)](README-zh.md) [![日本語](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ja.svg)](README-ja.md) [![한국어](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ko-on.svg)](README-ko.md) [![हिन्दी](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/hi.svg)](README-hi.md) [![العربية](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ar.svg)](README-ar.md) [![Bahasa Indonesia](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/id.svg)](README-id.md) [![Türkçe](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/tr.svg)](README-tr.md) [![Tiếng Việt](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/vi.svg)](README-vi.md)

Claude Code를 쓰면서 포르투갈어 자료를 찾거나 브라질을 아는 skills가 필요한 사람을 위한 목록입니다. CLT, ABNT, CNJ, Simples 등을 다룹니다. Anthropic이 공개한 자료로 시작해서 브라질 커뮤니티가 만든 것으로 이어집니다. 모든 저장소는 공개되어 있고 2026년에 활동이 있었습니다.

## 콘텐츠

- [공식](#공식)
- [포르투갈어로 배우기](#포르투갈어로-배우기)
- [규칙, 스택, 메모리](#규칙-스택-메모리)
- [법률 스킬](#법률-스킬)
- [글쓰기와 연구](#글쓰기와-연구)
- [영상, 모션, 사이트](#영상-모션-사이트)
- [주변 도구](#주변-도구)
- [다른 목록](#다른-목록)
- [라벨](#라벨)
- [기여 방법](#기여-방법)
- [다른 목록](#다른-목록)
- [Ciro Cesar Maciel이 만듦](#ciro-cesar-maciel이-만듦)
- [라이선스](#라이선스)

## 공식

Anthropic이 공개한 자료.

- [Documentação do Claude Code em português](https://go.mymarketing.click/ccbr-documentacao-do-claude-code-em-port) - 공식 문서의 번역본. `공식` `무료`
- [Claude Code no GitHub](https://go.mymarketing.click/ccbr-claude-code-no-github) - 이슈와 릴리스 노트가 있는 공식 저장소. `공식` `무료`
- [Skills da Anthropic](https://go.mymarketing.click/ccbr-skills-da-anthropic) - Anthropic이 공개한 예제 스킬과 문서 스킬. `공식` `오픈 소스`
- [Plugins oficiais](https://go.mymarketing.click/ccbr-plugins-oficiais) - Anthropic이 관리하는 플러그인 디렉터리. `공식` `오픈 소스`
- [Claude Code Action](https://go.mymarketing.click/ccbr-claude-code-action) - pull request와 issue를 위한 GitHub Actions의 Claude Code. `공식` `오픈 소스`
- [Anthropic Academy](https://go.mymarketing.click/ccbr-anthropic-academy) - Anthropic의 무료 강의, Claude Code 강의 포함. `공식` `무료`

## 포르투갈어로 배우기

포르투갈어, 2026년에도 활발히 관리 중.

- [claude-course](https://go.mymarketing.click/ccbr-claude-course) - 포르투갈어로 된 대화형 Claude Code 강의, 실습 위주. `오픈 소스` `무료`
- [claude-melhores-skills](https://go.mymarketing.click/ccbr-claude-melhores-skills) - 무엇을 설치할지와 이유를 정리한 포르투갈어 스킬 큐레이션. `오픈 소스` `무료`
- [Spec-Driven Development](https://go.mymarketing.click/ccbr-spec-driven-development) - AI 에이전트로 소프트웨어를 만드는 방법을 명세부터 다룬 오픈 북. `오픈 소스` `무료`
- [Construir com IA](https://go.mymarketing.click/ccbr-construir-com-ia) - O Novo Básico 시리즈 10권: 프로토타입에서 로그인, 데이터, 결제가 있는 실제 시스템까지. `유료` `작성자 제공`

## 규칙, 스택, 메모리

CLAUDE.md에 들어가는 내용과 그 주변.

- [CCM Stack](https://go.mymarketing.click/ccbr-ccm-stack) - 원칙, 알려진 실수를 막는 hook, 스킬, 음성을 담은 플러그인. 사용자별 설정 가능. `오픈 소스` `무료` `작성자 제공`
- [Regras para o CLAUDE.md](https://go.mymarketing.click/ccbr-regras-para-o-claude-md) - 실수에서 나온 규칙들, 에이전트의 CLAUDE.md에 바로 쓸 수 있음. `무료` `작성자 제공`
- [Agentes com cargo](https://go.mymarketing.click/ccbr-agentes-com-cargo) - 직책이 있는 에이전트, 프로젝트에 바로 넣어 쓸 수 있음. `무료` `작성자 제공`
- [Pedidos prontos](https://go.mymarketing.click/ccbr-pedidos-prontos) - AI에 바로 붙여넣는 프롬프트, 각각 테스트가 함께 있음. `무료` `작성자 제공`
- [claude-code-memory-setup](https://go.mymarketing.click/ccbr-claude-code-memory-setup) - Obsidian과 Graphify를 쓰는 Claude Code 영구 메모리, 세션당 토큰 절약. `오픈 소스` `무료`
- [cerebro-inevita](https://go.mymarketing.click/ccbr-cerebro-inevita) - 로컬 우선 방식의 비즈니스 세컨드 브레인, 이미 쓰는 에이전트에서 실행. `오픈 소스` `무료`
- [obsidian-master-kit](https://go.mymarketing.click/ccbr-obsidian-master-kit) - 빈 폴더를 정리된 Obsidian vault로 바꿔 주는 스킬. `오픈 소스` `무료`

## 법률 스킬

포르투갈어, 2026년에도 활발히 관리 중.

- [brasil-legal-skills](https://go.mymarketing.click/ccbr-brasil-legal-skills) - IRPF 안내, CLT 해지, CLT 또는 PJ, Simples Nacional, 은퇴. `오픈 소스` `무료`
- [jusmanizer](https://go.mymarketing.click/ccbr-jusmanizer) - 33개 패턴과 예시를 갖춘 포르투갈어 법률 문체 검토. `오픈 소스` `무료`
- [leis-mcp](https://go.mymarketing.click/ccbr-leis-mcp) - 브라질 법령을 검색하고 인용하는 MCP 서버. `오픈 소스` `무료`
- [skills-datajud-djen](https://go.mymarketing.click/ccbr-skills-datajud-djen) - CNJ, DataJud, DJEN 공개 API 관련 스킬. `오픈 소스` `무료`
- [labdados-skills](https://go.mymarketing.click/ccbr-labdados-skills) - 브라질 법학 실증 연구를 위한 스킬 마켓플레이스. `오픈 소스` `무료`

## 글쓰기와 연구

포르투갈어, 2026년에도 활발히 관리 중.

- [pesquisador-br-skill](https://go.mymarketing.click/ccbr-pesquisador-br-skill) - ABNT, Qualis CAPES, Lattes, SciELO, BDTD를 활용한 학술 연구. `오픈 소스` `무료`
- [portugues-tecnico-controlado](https://go.mymarketing.click/ccbr-portugues-tecnico-controlado) - ASD-STE100을 참고한 브라질 포르투갈어 통제 언어. `오픈 소스` `무료`
- [marketing-copy-conteudo](https://go.mymarketing.click/ccbr-marketing-copy-conteudo) - 마케팅, 카피, 콘텐츠 관련 포르투갈어 스킬 153개. `오픈 소스` `무료`

## 영상, 모션, 사이트

포르투갈어, 2026년에도 활발히 관리 중.

- [ai-motion-library](https://go.mymarketing.click/ccbr-ai-motion-library) - 애니메이션 효과 24개, 포르투갈어 이름과 AI에 요청할 용어 포함. `오픈 소스` `무료`
- [claude-video](https://go.mymarketing.click/ccbr-claude-video) - Claude Code의 모션 그래픽, 포르투갈어. `오픈 소스` `무료`
- [pipeline-de-sites](https://go.mymarketing.click/ccbr-pipeline-de-sites) - 사이트의 이미지와 영상을 만들고 적용하는 스킬. `오픈 소스` `무료`
- [editing-gameplay-montages](https://go.mymarketing.click/ccbr-editing-gameplay-montages) - 게임 클립과 음악 하나를 리듬에 맞춰 편집된 영상으로 바꿔 줍니다. `오픈 소스` `무료`

## 주변 도구

포르투갈어, 2026년에도 활발히 관리 중.

- [claudept2en](https://go.mymarketing.click/ccbr-claudept2en) - VS Code 확장 프로그램으로, Claude Code에 포르투갈어로 입력한 요청을 영어로 번역해 줍니다. `오픈 소스` `무료`
- [Sankhya Ajuda MCP](https://go.mymarketing.click/ccbr-sankhya-ajuda-mcp) - ERP Sankhya의 공개 도움말 자료를 위한 MCP 서버입니다. `오픈 소스` `무료`

## 다른 목록

포르투갈어, 2026년에도 활발히 관리 중.

- [awesome-claude-code](https://go.mymarketing.click/ccbr-awesome-claude-code) - Claude Code를 위한 명령, 파일, 워크플로 전 세계 목록을 영어로 정리했습니다. `무료`
- [Awesome MCP Brasil](https://go.mymarketing.click/ccbr-awesome-mcp-brasil) - 브라질 서비스를 위한 MCP 서버 모음입니다. `무료`

## 라벨

각 항목은 무엇인지 설명합니다. 옆의 라벨이 선택에 도움을 줍니다. 표준을 정하는 쪽에서 만든 경우 공식, 코드가 공개된 경우 오픈 소스, 사용 방식에 따라 무료 또는 유료, 연동 방식에 따라 API와 SDK로 표시합니다. "작성자 제공" 라벨이 붙은 항목은 Ciro Cesar Maciel이 만들었으며 다른 모든 항목과 같은 기준을 따릅니다.

## 기여 방법

빠진 것, 바뀐 것, 사라진 것을 알고 계신가요? 새 항목 양식으로 issue를 열거나 data/list.json을 수정하는 pull request를 보내 주세요. 각 언어의 README는 이 파일에서 자동으로 만들어집니다.

[CONTRIBUTING.md](CONTRIBUTING.md)

## 다른 목록

같은 형식으로 큐레이션한 목록들이며, 포르투갈어와 다른 14개 언어로 있습니다.

- [Awesome IA no trabalho](https://go.mymarketing.click/ccbr-lista-ia-no-trabalho) - 직업별 업무 AI: 어시스턴트, 개인정보, 규정, 그리고 AI가 쓴 내용을 확인할 공식 자료.
- [Awesome IA na advocacia](https://go.mymarketing.click/ccbr-lista-ia-advocacia) - 변호사를 위한 AI: 어시스턴트, 개인정보, 법률 분야와 사법부의 AI 규정, 그리고 확인할 공식 자료.
- [Awesome IA na contabilidade](https://go.mymarketing.click/ccbr-lista-ia-contabilidade) - 회계사를 위한 AI: 어시스턴트, 개인정보, CFC 규정, 그리고 Receita, eSocial, Simples의 확인용 자료.
- [Awesome IA na sala de aula](https://go.mymarketing.click/ccbr-lista-ia-sala-de-aula) - 교사를 위한 AI: 각 도구의 어shi스턴트, 최소 사용 연령과 개인정보, 그리고 확인할 교육 관련 규정.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/ccbr-lista-ia-atendimento-e-vendas) - 고객 응대와 판매를 하는 사람을 위한 AI: 어시스턴트, 개인정보, 소비자 권리, 그리고 카운터, 계산대, 전화 업무의 근로 규정.
- [Awesome IA no escritório](https://go.mymarketing.click/ccbr-lista-ia-escritorio) - 비서, 어시스턴트, 행정 보조를 위한 AI: 어시스턴트, 개인정보, 공문서 작성, 이메일로 오는 사기.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/ccbr-lista-ia-pequeno-negocio) - MEI와 소규모 사업자를 위한 AI: 어시스턴트, 개인정보, MEI와 Simples 규정, 소비자 및 LGPD 규정.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/ccbr-lista-ia-primeiro-trabalho) - 막 일을 시작하는 사람을 위한 AI: 어시스턴트, 개인정보, 구인 정보를 찾을 곳, 첫 직장의 권리, 가짜 채용 사기.
- [Awesome Pix](https://go.mymarketing.click/ccbr-lista-pix) - 연동하는 사람을 위한 Pix: 규정, API, SDK, 제공업체, 도구를 하나씩 확인했습니다.
- [Awesome MCP Brasil](https://go.mymarketing.click/ccbr-awesome-mcp-brasil) - 브라질 서비스를 위한 MCP 서버: 공공 데이터, CNPJ, 세무, 법률, 금융 시장, 상거래, 결제.
- [Awesome livros de IA](https://go.mymarketing.click/ccbr-lista-livros-ia) - 포르투갈어로 된 인공지능 책: 첫 사용부터 직업까지, 만드는 사람부터 토론까지.
- [Awesome ferramentas online](https://go.mymarketing.click/ccbr-lista-ferramentas-online) - 설치 없이 브라우저에서 열리는 무료 도구: 이미지, PDF, 텍스트, 코드, 사이트, 이메일, 동영상, 판매.
- [Awesome NF-e](https://go.mymarketing.click/ccbr-lista-nfe) - 연동하는 사람을 위한 전자 세금계산서(NF-e): 공식 포털, 언어별 라이브러리, 발급 API, MCP 서버.
- [Awesome APIs Brasil](https://go.mymarketing.click/ccbr-lista-apis-brasil) - 브라질 공개 API: CEP, CNPJ, Banco Central, IBGE, 입법부, 사법부, 공휴일, 공공 데이터.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/ccbr-lista-pagamentos-brasil) - 연동하는 사람을 위한 브라질 결제: 규정, 게이트웨이, 매입사, boleto, 구독, split, 사기 방지.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/ccbr-lista-open-finance-brasil) - Open Finance와 Open Insurance 브라질: 규정, 명세, 공개 데이터, 집계 서비스, 오픈소스 코드.
- [Awesome WhatsApp API](https://go.mymarketing.click/ccbr-lista-whatsapp-api) - WhatsApp 연동 개발자용: Meta 공식 API, 제공업체, 비공식 라이브러리, 각 방식의 위험.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/ccbr-lista-empresa-de-uma-pessoa) - AI 에이전트로 사업 전체를 운영하는 도구: 출시, 결제, 측정, 홍보, 검색 노출.

## Ciro Cesar Maciel이 만듦

제가 만든 것을 사용해 주시는 것도 이 목록을 지원하는 방법입니다.

이 목록이 시간을 아껴 줬다면, 커피 한 잔이 목록을 계속 관리하는 데 도움이 됩니다. 후원 금액은 직접 정할 수 있으며, Pix나 카드로 보낼 수 있습니다. [![후원하기](https://img.shields.io/badge/%ED%9B%84%EC%9B%90%ED%95%98%EA%B8%B0-%EC%BB%A4%ED%94%BC%20%ED%95%9C%20%EC%9E%94-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-apoie)

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiM2MEE1RkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE2IDE4YTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybTAgLTEyYTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybS03IDEyYTYgNiAwIDAgMSA2IC02YTYgNiAwIDAgMSAtNiAtNmE2IDYgMCAwIDEgLTYgNmE2IDYgMCAwIDEgNiA2IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/ccbr-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTlhMiAyIDAgMCAxIC0yIC0yIiAvPiA8cGF0aCBkPSJNNSAxM3YtMiIgLz4gPHBhdGggZD0iTTUgN2EyIDIgMCAwIDEgMiAtMiIgLz4gPHBhdGggZD0iTTExIDVoMiIgLz4gPHBhdGggZD0iTTE3IDVhMiAyIDAgMCAxIDIgMiIgLz4gPHBhdGggZD0iTTE5IDExdjIiIC8%2BIDxwYXRoIGQ9Ik0xOSAxN3Y0IiAvPiA8cGF0aCBkPSJNMjEgMTloLTQiIC8%2BIDxwYXRoIGQ9Ik0xMyAxOWgtMiIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/ccbr-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGODcxNzEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTkgNWEzIDMgMCAwIDEgMyAtM2EzIDMgMCAwIDEgMyAzdjVhMyAzIDAgMCAxIC0zIDNhMyAzIDAgMCAxIC0zIC0zbDAgLTUiIC8%2BIDxwYXRoIGQ9Ik01IDEwYTcgNyAwIDAgMCAxNCAwIiAvPiA8cGF0aCBkPSJNOCAyMWw4IDAiIC8%2BIDxwYXRoIGQ9Ik0xMiAxN2wwIDQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE1IDhhNSA1IDAgMCAxIDAgOCIgLz4gPHBhdGggZD0iTTE3LjcgNWE5IDkgMCAwIDEgMCAxNCIgLz4gPHBhdGggZD0iTTYgMTVoLTJhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDJsMy41IC00LjVhLjggLjggMCAwIDEgMS41IC41djE0YS44IC44IDAgMCAxIC0xLjUgLjVsLTMuNSAtNC41IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/ccbr-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBNzhCRkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTQgNWExIDEgMCAwIDEgMSAtMWg0YTEgMSAwIDAgMSAxIDF2NGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtNCIgLz4gPHBhdGggZD0iTTE0IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE1YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXY0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC00IiAvPiA8cGF0aCBkPSJNMTQgMTVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDRhMyAzIDAgMCAxIDMgM3Y4YTMgMyAwIDAgMSAtMyAzaC01bC01IDN2LTNoLTJhMyAzIDAgMCAxIC0zIC0zdi04YTMgMyAwIDAgMSAzIC0zaDEyIiAvPiA8cGF0aCBkPSJNOS41IDloLjAxIiAvPiA8cGF0aCBkPSJNMTQuNSA5aC4wMSIgLz4gPHBhdGggZD0iTTkuNSAxM2EzLjUgMy41IDAgMCAwIDUgMCIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/ccbr-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMkQzRUUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEyIDRsLTggNGw4IDRsOCAtNGwtOCAtNCIgLz4gPHBhdGggZD0iTTQgMTJsOCA0bDggLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE2bDggNGw4IC00IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/ccbr-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjkyM0MiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgNWExIDEgMCAwIDEgMSAtMWgyYTEgMSAwIDAgMSAxIDF2MTRhMSAxIDAgMCAxIC0xIDFoLTJhMSAxIDAgMCAxIC0xIC0xbDAgLTE0IiAvPiA8cGF0aCBkPSJNOSA1YTEgMSAwIDAgMSAxIC0xaDJhMSAxIDAgMCAxIDEgMXYxNGExIDEgMCAwIDEgLTEgMWgtMmExIDEgMCAwIDEgLTEgLTFsMCAtMTQiIC8%2BIDxwYXRoIGQ9Ik01IDhoNCIgLz4gPHBhdGggZD0iTTkgMTZoNCIgLz4gPHBhdGggZD0iTTEzLjgwMyA0LjU2bDIuMTg0IC0uNTNjLjU2MiAtLjEzNSAxLjEzMyAuMTkgMS4yODIgLjczMmwzLjY5NSAxMy40MThhMS4wMiAxLjAyIDAgMCAxIC0uNjM0IDEuMjE5bC0uMTMzIC4wNDFsLTIuMTg0IC41M2MtLjU2MiAuMTM1IC0xLjEzMyAtLjE5IC0xLjI4MiAtLjczMmwtMy42OTUgLTEzLjQxOGExLjAyIDEuMDIgMCAwIDEgLjYzNCAtMS4yMTlsLjEzMyAtLjA0MSIgLz4gPHBhdGggZD0iTTE0IDlsNCAtMSIgLz4gPHBhdGggZD0iTTE2IDE2bDMuOTIzIC0uOTgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBM0U2MzUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTBoM3YtM2wtMy41IC0zLjVhNiA2IDAgMCAxIDggOGw2IDZhMiAyIDAgMCAxIC0zIDNsLTYgLTZhNiA2IDAgMCAxIC04IC04bDMuNSAzLjUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQUNDMTUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEzIDNsMCA3bDYgMGwtOCAxMWwwIC03bC02IDBsOCAtMTEiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzOEJERjgiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTNhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjZhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTYiIC8%2BIDxwYXRoIGQ9Ik0xNSA5YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXYxMGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtMTAiIC8%2BIDxwYXRoIGQ9Ik05IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjE0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC0xNCIgLz4gPHBhdGggZD0iTTQgMjBoMTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgN2E0IDQgMCAxIDAgOCAwYTQgNCAwIDEgMCAtOCAwIiAvPiA8cGF0aCBkPSJNMyAyMXYtMmE0IDQgMCAwIDEgNCAtNGg0YTQgNCAwIDAgMSA0IDR2MiIgLz4gPHBhdGggZD0iTTE2IDMuMTNhNCA0IDAgMCAxIDAgNy43NSIgLz4gPHBhdGggZD0iTTIxIDIxdi0yYTQgNCAwIDAgMCAtMyAtMy44NSIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/ccbr-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjcxODUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDhhMyAzIDAgMCAxIDAgNiIgLz4gPHBhdGggZD0iTTEwIDh2MTFhMSAxIDAgMCAxIC0xIDFoLTFhMSAxIDAgMCAxIC0xIC0xdi01IiAvPiA8cGF0aCBkPSJNMTIgOGw0LjUyNCAtMy43N2EuOSAuOSAwIDAgMSAxLjQ3NiAuNjkydjEyLjE1NmEuOSAuOSAwIDAgMSAtMS40NzYgLjY5MmwtNC41MjQgLTMuNzdoLThhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/ccbr-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMDg0RkMiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTYgNmEyIDIgMCAwIDEgMiAtMmg4YTIgMiAwIDAgMSAyIDJ2NGEyIDIgMCAwIDEgLTIgMmgtOGEyIDIgMCAwIDEgLTIgLTJsMCAtNCIgLz4gPHBhdGggZD0iTTEyIDJ2MiIgLz4gPHBhdGggZD0iTTkgMTJ2OSIgLz4gPHBhdGggZD0iTTE1IDEydjkiIC8%2BIDxwYXRoIGQ9Ik01IDE2bDQgLTIiIC8%2BIDxwYXRoIGQ9Ik0xNSAxNGw0IDIiIC8%2BIDxwYXRoIGQ9Ik05IDE4aDYiIC8%2BIDxwYXRoIGQ9Ik0xMCA4di4wMSIgLz4gPHBhdGggZD0iTTE0IDh2LjAxIiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/ccbr-por-agents)

## 라이선스

이 목록은 CC0 1.0 라이선스입니다. 허락을 구하지 않고 복사, 수정, 재배포하셔도 됩니다. 생성기 코드는 awesome-kit에 있으며 MIT 라이선스입니다.

<sub>마지막 업데이트 2026-11-10.</sub>
