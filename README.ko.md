<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 052 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 052

### 손으로 만든 미니어처 세계를 하나의 풍경선 위에 띄우기

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> 종이 미니어처 · 가로 부유섬 · 진짜 손맛 · 공기감 있는 차가운 파랑 · 넓은 여백

원본에서 가장 알아보기 쉬운 주체와 근거 있는 소수의 환경 요소를 종이, 카드지, 부드러운 점토, 얇은 나무 조각 미니어처로 바꾸어 하나의 길고 가벼운 가로 부유 풍경띠 위에 놓습니다. 손작업 디테일, 매크로 빛, 넓고 옅은 여백이 고급 설치미술의 인상을 만듭니다.

## 이 Skill이 필요한 이유

이 스타일은 원본에 의존하며 내용을 바꿔 끼우는 장식 프리셋이 아닙니다. 다음 변환 인과를 따릅니다:

```text
lock identity, silhouette, pose, direction, and relation → preserve three cues → select one primary subject and limited supported elements → rebuild paper, cardstock, soft-clay, and thin-wood miniatures → place them on one long horizontal floating strip → establish scale depth, overlap, and calm balance → reveal authentic craft through macro light → retain airy cool blue and generous space → add one signature-like short title
```

무관한 사진으로 바꿔도 식별, 모델 구조, 보조 요소, 부유섬 윤곽, 재료, 균형, 색, 여백과 문구가 실질적으로 달라지지 않는다면 이 Panel의 결과가 아닙니다.

## 시각적 원칙

- 실루엣, 비례, 자세, 방향, 동작, 구조, 색, 재료, 관계에서 원본 고유 단서를 세 가지 이상 보존합니다.
- 하나의 주인공과 근거 있는 소수의 보조 모델을 하나의 길고 좁고 가벼운 가로 부유 풍경띠에 놓습니다.
- 크기 차이, 겹침, 조용한 전후경으로 깊이를 만들고 대체로 중앙에 두되 기계적 대칭이나 두 번째 초점을 피합니다.
- 종이 섬유, 접힌 가장자리, 절단 자국, 층 두께, 거친 테두리, 작은 손작업 불완전함을 보여 주고 매끈한 플라스틱 CGI를 거부합니다.
- 공기감 있는 차가운 파랑, 아이보리, 옅은 베이지, 탁한 녹색, 극소량의 탁한 분홍을 부드러운 매크로 빛과 넓고 옅은 여백으로 정리합니다.

전체 미적 제약과 금지 항목은 Skill과 생성 프롬프트에 있습니다. 원문 미학을 보존하지만 역사적인 3:4 화면을 숨은 기본값으로 만들지 않습니다. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-052-prompt.en.md)

## 예시 · X에서

> [샤오샤오둥（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091500926721020375) · 2026년 8월 23일<br>
> GPT2 × 종이 오리기 × 담백한 우아함 × 미학 프롬프트 × VOL.052

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 052 예시 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 052 예시 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 052 예시 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 052 예시 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091500926721020375">원문 게시물과 전체 프롬프트 보기 →</a></p>

이 예시는 052의 미학적 의도를 보여 줄 뿐이며, 예시의 주제, 구성, 색상, 문구, 이전 캔버스 비율은 생성 참고나 현재 기본값이 되지 않습니다.

## 조합 가능한 네 가지 출력

`1`, `1+3`, `1,2,4`, `전체`로 하나 또는 여러 모드를 선택할 수 있으며 `전체`는 원본당 독립 PNG 7개를 만듭니다. 모드 선택 뒤, 생성 전에 완성 이미지 전체의 화면비를 반드시 확인합니다: 원래 프롬프트의 `3:4`, 명시적인 원본 비율, 일반 비율, 사용자 지정 비율／정확한 픽셀입니다. 원본 크기를 묵시적으로 적용하지 않습니다.

| 모드 | 화면비 규칙 | 결과물 |
| --- | --- | --- |
| `top-bottom` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 위에 고충실도 원본, 아래에 052 디자인, 약 50/50 |
| `left-right` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 왼쪽에 고충실도 원본, 오른쪽에 052 디자인, 약 50/50 |
| `design-only` | 사용자가 확인한 전체 캔버스 | 052 디자인이 전체를 채우며 원본 사진은 보이지 않음 |
| `wallpaper-pack` | 기기별 확인 | 휴대전화, iPad, 데스크톱, 어린이용 스마트워치 PNG 개별 출력 |

이중 패널 모드는 원본을 고충실도 편집／참조 입력으로 사용하고 완전한 스타일 프롬프트 한 세트로 최종 화면을 직접 생성합니다. 사진, 디자인, 색, 빛, 타이포그래피와 의미가 하나로 이어지게 하기 위해서입니다. 결정적 합성은 전체 캔버스 재시도 후에도 실패한 경우, 원본의 픽셀 완전 보존을 명시한 경우, 현재 경로가 목표 화면비를 만들 수 없는 경우, 또는 무손실 최종 픽셀 조정이 필요한 경우에만 사용합니다.

배경화면은 연결형 또는 독립형입니다. 연결형은 iPad 기준 작품 하나를 승인한 뒤 다른 기기를 원본＋같은 기준 작품에서 각각 재구성합니다. 독립형은 각 기기가 원본만 참조합니다. 어느 쪽도 다른 기기 결과를 자르거나 파생 결과를 연쇄 참조하지 않습니다.

## 문구와 언어

생성 전에 자동 문구, 정확한 사용자 문구, 무문자 중 하나를 확정합니다. 언어는 명령문이 아니라 대상 독자를 따르며 완성 문구는 그대로 유지합니다.

이 프로젝트의 문구 규칙: 장소, 주체 정체성, 주제 또는 감정에서 짧은 제목 하나만 추출하고 작고 세련되며 약간 손글씨 같은 문자를 풍경띠 아래, 바닥 흐름 또는 모델 공간에 놓아 상업 제목이 아닌 작가 서명처럼 보이게 합니다.

## 완성 캔버스 우선과 래스터 경계

이미지 모델이 완성 화면 전체의 미학적 재구성을 담당하며 이중 패널도 완성 캔버스 한 장의 직접 생성을 기본으로 합니다. `scripts/compose_panel.py`는 조건부 복구, 무손실 픽셀 조정, 읽기 전용 검수에만 사용하고 매번 사전 계획하거나 미학적 성공을 판단하지 않습니다.

모든 결과물은 PNG 래스터이며 호출마다 `~/Desktop/xxd/`에 새 작업을 만듭니다. 설정된 이미지 경로는 비식별 상태만 반환하며 제공자, 엔드포인트, 인증 정보, 헤더, 프롬프트, 응답, 계정 정보를 공개하지 않습니다. SVG, HTML, Canvas, 도표와 프로그램 그림은 최종 작품을 대신할 수 없습니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-052.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-052" ~/.codex/skills/xxd-panel-052
```

Claude Code 사용자는 같은 폴더를 다음 위치에 연결할 수 있습니다: `~/.claude/skills/xxd-panel-052`. 설치 후 에이전트 세션을 다시 시작하세요.

```text
$xxd-panel-052
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

전체 사양: [Skill 워크플로](SKILL.md) · [원본 스타일 자료](references/052-source.md) · [영문 생성 프롬프트](references/xxd-panel-052-prompt.en.md) · [중문 생성 프롬프트](references/xxd-panel-052-prompt.zh-CN.md)

## XXD 소개

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 제작 및 유지관리: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 지원과 멤버십

### 심층 상담 · 시간당 CNY 299

Skills 사용과 워크플로에 관한 일대일 심층 상담입니다. WeChat으로 Xiaoxiaodong에게 문의하세요. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills 사용자 교류 그룹 · CNY 99

한 번의 결제로 Skills 사용자 교류 그룹에 참여합니다. 시간제 일대일 상담은 별도입니다.

### Knowledge Planet＋회원 프롬프트 라이브러리 · 연 CNY 699

Knowledge Planet과 회원 프롬프트 라이브러리는 연 CNY 699 한 번의 결제로 두 혜택을 모두 엽니다. Knowledge Planet 가입 후 WeChat으로 Xiaoxiaodong에게 연락해 프롬프트 라이브러리 교환 코드를 받고, 프롬프트 라이브러리에서 셀프서비스 개통 후에는 WeChat으로 연락해 Knowledge Planet 초대를 받으세요.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>가벼운 풍경띠 하나에 사진 속 기억할 일상을 올립니다.</strong></div>

---

<div align="center">

## ☕ 오픈 소스 프로젝트 후원

중국어판 이외에는 Buy Me a Coffee를 이용할 수 있습니다. 후원은 선택 사항이며 오픈 소스 접근 권한을 바꾸지 않습니다.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
