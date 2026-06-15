# 공개 경계

이 레포는 One-Minute Three Kingdom의 공개 현관입니다. 관심 있는 플레이어가
프로젝트를 이해하고 베타 참여 가능성을 살펴볼 수 있게 돕는 것이 목적입니다.

공개 범위는 의도적으로 좁게 둡니다. 투명성은 신뢰를 만들지만, 운영 정보와 플레이어
정보를 너무 많이 공개하면 악용, 사칭, 과도한 압박, 숨은 상태 역추적을 쉽게 만들 수
있습니다.

## 공개해도 되는 것

다음 내용은 공개용으로 정리된 경우 이 레포에 둘 수 있습니다.

- 게임 소개, 핵심 콘셉트, 커뮤니티 목표
- 베타 상태, 알려진 한계, 공개 가능한 milestone
- 공개 참여 안내와 신청에 포함할 수 있는 정보
- README용 SVG, 스크린샷, 공개 이미지
- 공개 가능한 제작 노트, 회고, 디자인 의도
- 플레이어가 알아도 되는 수준의 시스템 설명
- 비공개 접속 정보를 포함하지 않는 placeholder 명령 예시

공개 문서는 독자가 "지금 무엇을 기대하면 되는가"를 이해하도록 돕는 데 집중합니다.

## 공개하면 안 되는 것

다음 내용은 이 레포에 들어오면 안 됩니다.

- private source code, build script, deployment file, infrastructure detail
- 실제 server address, IP, tunnel name, private network name, service topology
- 운영자 계정, admin workflow, credential, token, secret, API key
- invite link, invite-only channel, beta roster, player account identifier
- 내부 운영 로그, moderation 기록, incident note, support history
- 상세 abuse-response playbook, detection rule, threshold, enforcement timing
- 숨은 상태값, economy formula, unreleased system number
- spoiler-heavy story content or unreleased scenario text
- private repository, private task board, private document, 내부 coordination 링크
- 내부 프롬프트, 사내 드라마, 작업자 관계 기록, 비공개 운영 메모

공개 독자에게 필요한 것은 게임의 약속과 현재 단계입니다. 운영자가 어떻게 내부에서
판단하고 조율하는지는 공개 레포의 자료가 아닙니다.

## 공개 전 질문

새 문서, 이미지, 예시, 링크를 추가하기 전에 아래 질문을 통과해야 합니다.

1. 이 내용이 실제 접속면, 계정, 경로, 사람, 비공개 공간을 드러내는가?
2. 누군가 이 정보를 이용해 플레이어를 압박하거나 운영자를 사칭할 수 있는가?
3. 숨은 게임 상태, 보상 계산, moderation 기준을 역추적하기 쉬워지는가?
4. 아직 확정되지 않은 기능을 출시 약속처럼 보이게 만드는가?
5. 공개 독자가 프로젝트를 이해하는 데 실제로 도움이 되는가?

1-4 중 하나라도 "예"라면 원문을 공개하지 말고 더 안전한 요약으로 바꿉니다. 5가
"아니오"라면 공개 레포에 둘 이유가 약합니다.

## 안전한 표현 방식

위험한 원문을 공개해야 할 이유가 있을 때는 다음 방식으로 낮춥니다.

| 위험한 원문 | 공개용 표현 |
| --- | --- |
| 실제 접속 명령 | `ssh <player>@<beta-host>` |
| 운영자 계정명 | "운영자" 또는 "관리자" |
| 특정 플레이어 사건 | 개인을 식별할 수 없는 요약 |
| abuse 탐지 수치 | "악용 방지 기준" 같은 고수준 설명 |
| 내부 배포 경로 | 공개 milestone 또는 상태 변화 |
| 미공개 시나리오 원문 | spoiler 없는 분위기 설명 |

## 이미지와 링크 기준

- SVG와 스크린샷에는 실제 host, 계정, 내부 경로, private URL을 넣지 않습니다.
- 이미지 속 터미널 예시는 placeholder와 공개 명령어만 사용합니다.
- 링크는 공개 GitHub 문서, 공개 신청 안내, 공개 가능한 외부 페이지로 제한합니다.
- 깨진 링크를 발견하면 공개 가능한 대체 링크로 바꾸거나 제거합니다.
- private 레포나 내부 문서를 "나중에 열릴 수도 있음"처럼 예고하지 않습니다.

## 운영 원칙

이 공개 레포는 호기심을 키우는 문이어야지, 운영 흔적을 긁어모으는 archive가 되면
안 됩니다. 공개할수록 좋은 정보와 공개하면 공동체를 약하게 만드는 정보는 다릅니다.

좋은 공개 자료는 다음 세 가지를 동시에 만족합니다.

- 새 독자가 게임의 현재 모습을 이해한다.
- 베타 플레이어와 운영자의 안전을 약하게 만들지 않는다.
- 과장 광고보다 현재 상태와 한계를 더 정확히 말한다.
