# 🎯 study_polymarket

> 블록체인 기초부터 **폴리마켓(Polymarket)의 작동 원리**까지, 비유 중심으로 친절하게 정리한 한국어 학습 저장소입니다.

블록체인을 처음 접하는 사람도 폴리마켓이 어떻게 동작하는지 끝까지 이해할 수 있도록, **기본 개념 → 폴리마켓에서의 실제 쓰임 → 컨트랙트 레벨 → 직접 만들기**까지 한 흐름으로 이어집니다.

---

## 📚 무엇을 다루나요?

- **블록체인 기초** — 트랜잭션·가스·스마트 컨트랙트·토큰 표준·오라클·스테이블코인
- **폴리마켓 메커니즘** — CTF 토큰화·가격=확률·오더북·UMA 오라클·정산
- **컨트랙트 심화** — CTF Exchange / CLOB 구조와 정산 3방식
- **직접 만들기** — Solidity 미니 예측시장 + Foundry 배포 + wagmi/viem 프론트엔드
- **부록·치트시트** — 용어 사전, EIP/ERC 표준, 함수 총정리, USDC 멀티체인, Circle Arc

## 🗂️ 문서 바로가기

전체 학습 자료는 [`docs/polymarket/`](docs/polymarket/README.md)에 있습니다. **위에서부터 순서대로** 읽으면 됩니다.

| 파트 | 문서 | 내용 |
|------|------|------|
| **Part 1** | [블록체인 기반 기술](docs/polymarket/01-blockchain-basics.md) | 폴리마켓 이해에 필요한 최소한의 블록체인 지식 |
| **Part 2** | [폴리마켓 작동 원리](docs/polymarket/02-polymarket-mechanics.md) | 입금 → 토큰화 → 거래 → 판정 → 정산 |
| **Part 3** | [거래 계약 심화](docs/polymarket/03-ctf-exchange.md) | CTF Exchange / CLOB 컨트랙트 구조 |
| **Part 4** | [직접 만들기 로드맵](docs/polymarket/04-build-roadmap.md) | 단계별 학습 지도 + 미니 컨트랙트 코드 |
| **Part 5** | [부록](docs/polymarket/05-appendix.md) | 용어 사전, 요약 다이어그램, EIP 표준 |
| **Part 6** | [기능 총정리 & 표준](docs/polymarket/06-functions-and-standards.md) | 컨트랙트별 함수 전체 목록 + 표준 레퍼런스 |

📊 발표용 슬라이드: [`docs/polymarket/slides/presentation.html`](docs/polymarket/slides/presentation.html)

## 🎓 한 문장 요약

> **폴리마켓 = "Polygon 위에서, USDC로, 미래 사건의 확률에 베팅하는 탈중앙 예측시장"**
> 결과 토큰(Yes/No)을 사고팔며, 가스비는 거의 안 들고, 결과는 UMA 오라클이 판정한다.

## 👀 다이어그램 보기

문서의 흐름도는 **Mermaid**로 작성돼 있습니다. GitHub·VS Code(Mermaid 확장)·Obsidian 등 지원 뷰어에서는 도형으로 보이며, 안 보이면 [mermaid.live](https://mermaid.live)에 코드를 붙여넣어 확인하세요.

---

> ⚠️ 교육·학습 목적의 정리 자료입니다. 투자 권유가 아니며, 실제 배포·거래 전에는 원문 컨트랙트와 공식 문서를 직접 확인하세요.
