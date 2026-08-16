[![Portfolio](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=header&text=✨%20Click%20And%20Check%20My%20Portfolio%20✨&fontSize=30&fontAlignY=38)](https://indaegu.github.io/portfolio/)

# 성창민 (Changmin Seong) | Fullstack Developer

> **금융 앱 WebView 환경에서 화면과 서버를 함께 만듭니다.**
> 폐쇄망, 레거시, 규제라는 제약 안에서 기존 동작을 깨지 않고 개선하는 방법을 찾는 일을 합니다.

하나금융티아이 비대면채널파트에서 **하나저축은행 스마트뱅킹(하나원큐 저축은행) 채널**을 담당하고 있습니다.
Vue 2 WebView 화면, Spring Boot 서버, 관리자 페이지, 빌드와 배포 파이프라인까지 하나의 기능을 처음부터 끝까지 맡습니다.

<br>

## 📌 Impact at a glance

| 무엇을 | 어떻게 | 결과 |
|---|---|---|
| **프론트 빌드 속도** | "화면이 많아서"로 끝내지 않고, 번들러가 정적 분석을 포기하는 조건을 찾아 코드에서 제거 | **풀빌드 5분대 → 1분대, 약 80% 단축** (팀 기준 월 약 13시간 대기 시간 절감) |
| **공공마이데이터 연계** | 검증된 인증 모달을 수정하지 않고 감싸는 방식으로 의존을 역전, 상품별 복붙 제거 | 조회 전문 **4종 전환 완료**, 명세 변경 시 **한 파일 수정으로 전 상품 반영** |
| **웹 접근성(KWCAG)** | 스크린리더가 상태를 인식하지 못하는 원인을 프레임워크 동작 레벨에서 규명 | 심사 지적 웹 영역 **전건 대응, 1차 심사 통과** (CSS와 기존 동작 무변경) |
| **레거시 공시 화면** | 계산 편의가 아니라 **공시 표기 보존**을 데이터 모델의 제1원칙으로 설정 | **41개 분기 556행** 무손실 이관, 이관 과정에서 원본 데이터 오류 다수 검출 및 교정 |
| **운영 자동화** | 망 경계를 넘는 방식을 두 번 시도하고 두 번 폐기, 경계 이동 자체가 없는 구조로 재설계 | 현업 직접 등록으로 **개발자 수동 반입 절차 제거**, 4개 채널 표준 구현체 제공 |

🏅 위 빌드 최적화 성과로 **ICT&디지털혁신본부 2025년 상반기 우수직원** 선정

<br>

## 👋 About me

- **원인을 도구 탓으로 넘기지 않습니다.** "빌드가 느린 건 화면이 많아서"로 결론내면 답은 인프라 증설밖에 없습니다. 번들러가 어떤 조건에서 정적 분석을 포기하는지 알아야 원인을 코드 레벨에서 제거할 수 있습니다. 성능 문제의 해답이 도구 교체가 아니라 도구의 동작 원리 이해에 있는 경우가 많다고 생각합니다.
- **건드리면 안 되는 코드는 감싸서 확장합니다.** 검증된 컴포넌트를 수정하는 대신 래퍼로 의존을 역전시키면, 원본 회귀 리스크 없이 재사용성을 확보할 수 있습니다. 금융권에서 특히 유효한 접근이라고 봅니다.
- **경계에서 끊기지 않는 것을 중요하게 봅니다.** 화면 버그를 서버 로그와 DB로 따라가고, 필요하면 네이티브 개발자와 브릿지 스펙을 함께 맞춥니다. 담당 경계에서 공을 넘기는 순간 문제 해결 속도가 결정됩니다.
- **검증할 수 없는 것은 검증할 수 없다고 씁니다.** 개발 환경에서 확인 불가한 잔여 리스크는 문서에 명시하고 관련 부서에 공식 공유합니다. 넘어간 리스크는 반드시 오픈일에 드러납니다.

<br>

## 💼 Experience

**하나금융티아이** | 비대면채널파트 | Fullstack Developer *(재직 중)*
하나저축은행 하나원큐 저축은행 디지털뱅킹 채널의 WebView 프론트엔드와 Spring Boot 서버 개발
담당 범위: 스마트뱅킹(주담당), 제휴 채널, 관리자 페이지 (2026년 담당 채널 확대)

<br>

## 🚀 Selected Work

| 프로젝트 | 기간 | 역할 |
|---|---|---|
| [Webpack 라우터 코드 스플리팅 개선](#1-webpack-라우터-코드-스플리팅-개선) | 2025.04 ~ 2025.05 | Fullstack |
| [공공마이데이터 전자서명 기반 인증 전환](#2-공공마이데이터-전자서명-기반-인증-전환) | 2026.05 ~ 2026.06 | Fullstack |
| [안심차단 비대면 신청 서비스 신규 구축](#3-안심차단-비대면-신청-서비스-신규-구축) | 2025.10 ~ 2026.03 | Fullstack |
| [관리자 페이지 이미지 등록 자동화 및 전 채널 일원화](#4-관리자-페이지-이미지-등록-자동화-및-전-채널-일원화) | 2026.02 ~ 2026.07 | Fullstack |
| [민원공시 화면 DB 전환](#5-민원공시-화면-db-전환) | 2026.07 | Fullstack |
| [웹 접근성(KWCAG) 인증 갱신심사 대응](#6-웹-접근성kwcag-인증-갱신심사-대응) | 2025.07 ~ 08 (1차), 2026.07 (2차) | Frontend |
| [제휴 채널 진입점 단일화와 타사 연동 규격 사전 정정](#7-제휴-채널-진입점-단일화와-타사-연동-규격-사전-정정) | 2026.07 | Fullstack |

<br>

### 1. Webpack 라우터 코드 스플리팅 개선

`Vue 2` `Webpack` `JavaScript`

<details>
<summary><b>풀빌드 시간 약 80% 단축, 원인은 인프라가 아니라 정적 분석 실패에 있었습니다</b></summary>

<br>

**문제**
- 프론트 풀빌드에 약 5분 소요. 화면이 늘수록 느려지고, 청크 경계와 해시가 자주 바뀌어 재빌드 캐시가 거의 듣지 않음
- 폐쇄망이라 빌드 서버 증설이나 Vite 같은 신규 번들러 도입으로 우회 불가. **기존 Webpack 설정 안에서 풀어야 하는 조건**

**원인 규명**
- 라우터 lazy-load에서 import 경로와 청크명을 **변수로 조합**하고 있었음
- Webpack은 경로를 정적으로 결정하지 못하면 **context 모듈**을 만들고, 해당 폴더에서 정규식에 걸리는 모든 후보 파일을 스캔하고 파싱해 번들 그래프에 올림
- 실제 라우팅되지 않는 화면까지 매 빌드마다 전부 빌드 대상이 되는 구조였음

**조치**
- 변수 조합 import를 **라우트별 정적 경로**로 전환해 context 모듈 생성 자체를 제거
- 변수가 섞인 청크명을 **고정 webpackChunkName**으로 통일해 청크 경계와 해시를 안정화. 변경되지 않은 청크는 캐시가 유지됨
- 동적 로딩이 실제로 필요한 지점은 **화이트리스트 매핑 객체**로 한정. 임의 문자열로 경로를 만들지 않게 해 정적 분석 가능성과 동적 요구를 함께 충족

**왜 번들러를 바꾸지 않았나**
라우팅 정의는 URL 계약이 아니라 내부 구성이므로, 정적화해도 외부 계약과 화면 동작이 바뀌지 않습니다. 금융 채널에서 동작 보존이 최우선인데 이 변경은 그 조건을 만족했습니다. 번들러 교체는 폐쇄망 반입 절차와 회귀 리스크가 큰 반면, 같은 효과를 설정 변경으로 얻을 수 있다면 그쪽이 옳다고 판단했습니다.

**결과**
- 풀빌드 **5분대 → 1분대 (약 80% 단축)**, 해시 안정화로 재빌드 시간도 함께 감소
- Vue 담당 2명이 하루 5회 이상 빌드하는 환경 기준, 월 20영업일로 **약 13시간**의 대기 시간 절감
- **ICT&디지털혁신본부 2025년 상반기 우수직원 선정**

</details>

### 2. 공공마이데이터 전자서명 기반 인증 전환

`Vue 2` `Spring Boot` `전자서명` `외부기관 연동`

<details>
<summary><b>수정하면 안 되는 컴포넌트를 감싸서 의존을 역전시키기</b></summary>

<br>

**배경**
- 공공마이데이터 수신 방식이 "매 요청마다 인증정보 동봉"에서 "전자서명 후 토큰 발급, 토큰 기반 묶음정보 수신"으로 변경
- 기존 조회 전문 4종에 토큰 적용 필요. 인증서 선택부터 서명, 발급까지의 흐름을 여러 상품 화면에 붙여야 하는 상황

**핵심 설계: 오케스트레이터 래퍼**

기존 인증 모달은 부모 컴포넌트의 특정 메서드를 직접 호출하는 구조라, 상품 화면마다 같은 코드를 복사해야 했고 **성공과 취소가 같은 콜백으로 들어와 구분이 불가능**했습니다. 그런데 이 모달은 이체 등 다른 흐름에서 이미 검증된 코드라 수정하고 싶지 않았습니다.

모달을 **자식으로 직접 렌더하는 래퍼 컴포넌트**를 만들어, 부모 계약을 래퍼가 단 한 번만 구현하게 했습니다.

- 상품 페이지는 래퍼를 배치하고 `open()` 호출과 `@success` / `@fail` 처리만 하면 됨. **모달의 존재 자체를 몰라도 되는 의존성 역전**
- 성공, 취소, 실패를 각각의 이벤트로 분리해 호출부의 분기 실수 제거
- 인증 SDK 중복 콜백 방어 로직을 래퍼 한 곳에 집약해 모든 상품에 자동 적용
- 결과적으로 **새 상품 추가가 메타 한 줄과 핸들러 추가로 축소**

**설계 결정 두 가지 더**

*환경별 키 관리를 VO 밖으로*
요청 VO 안에서 프로파일 값을 직접 주입받는 구조는, `new`로 생성하면 null이 들어오고 직렬화에도 인프라 필드가 섞입니다. 환경별 키를 enum과 프로퍼티 컴포넌트로 분리하고 VO는 **순수 데이터 컨테이너로 유지**해, Spring 컨텍스트 없이도 단위 테스트가 가능하게 했습니다.

*토큰 수명 주기*
성공 시 클라이언트 저장소에서 삭제, 실패 시 재사용 가능하도록 보존하는 하이브리드 모델을 택했습니다. 별도 사용 여부 플래그를 두지 않고 **토큰의 존재 자체를 유효 신호로** 삼아 상태를 하나로 줄였습니다. 저장 키에는 사용자 식별 요소를 포함해 공용 기기에서의 교차 사용을 차단했습니다.

**결과**
- 조회 전문 4종 전환 완료. 기관 명세나 서명 포맷이 바뀌어도 **한 파일 수정으로 전 상품 반영**
- 기존 모달과 다른 인증 흐름은 무수정이라 회귀 리스크 최소화
- 특정 인증 경로에서 전자서명 원문이 반환되지 않던 원인을 서비스 계층 역추적으로 규명하고, 플래그 방식으로 **기존 이체 및 본인확인 흐름에 영향 없이** 해소
- 인증 SDK가 동일 서명 데이터로 콜백을 두 번 발화해 재전송이 거부되던 건을 중복 처리 가드로 차단

**기록해 둔 것**
개발 환경에서 토큰 미전송 시에도 정상 응답이 수신되어 신규 경로 적용 여부를 자체 검증할 수 없는 잔여 리스크를 확인하고, 기획 부서에 공식 공유했습니다.

</details>

### 3. 안심차단 비대면 신청 서비스 신규 구축

`Vue 2` `Spring Boot` `계정계 연동`

<details>
<summary><b>금융사고 예방 제도 대응, 신청부터 해제까지 전 구간 신규 개발</b></summary>

<br>

- 여신거래 안심차단과 오픈뱅킹 안심차단 2개 유형의 **신청, 조회, 해제 전 구간**을 비대면 채널에 신규 구축
- 상품 가입 흐름의 약관 및 동의 절차에 안심차단 항목을 **기존 동작 영향 없이** 통합
- 작업 중 안심차단 약관 노출 분기가 특정 상품 코드에만 걸려 있어 신상품 추가 시 고지가 누락될 수 있는 구조를 발견. **상품별 분기 자체를 제거**해 향후 신상품 추가 시 누락 리스크를 구조적으로 없앰
- 계좌 목록 조회에 오버 스크롤 기반 추가 로딩을 적용해 목록 규모 증가에 대응

**왜 분기를 제거했나**
버그를 고치는 방법은 두 가지입니다. 누락된 상품 코드를 분기에 추가하거나, 분기가 필요 없는 구조로 바꾸거나. 전자는 다음 신상품에서 같은 문제가 반복됩니다. 제도 대응 과제는 고지 누락이 곧 규제 리스크라 후자를 택했습니다.

</details>

### 4. 관리자 페이지 이미지 등록 자동화 및 전 채널 일원화

`Spring Boot` `Vue` `NFS` `보안 설계`

<details>
<summary><b>망 경계를 넘지 않는 구조를 찾기까지, 두 번의 아키텍처 폐기</b></summary>

<br>

**문제**
팝업과 공지 이미지를 등록할 때마다 개발자가 수동으로 파일을 반입해야 했고, 채널마다 이미지 서빙 방식이 달랐습니다.

**시행착오와 최종 구조**
1. 관리자 WAS에서 프론트 파일 서버 경로에 직접 쓰기 → 두 컨테이너가 서로 다른 망에 있어 파일시스템 접근 불가
2. SFTP 자동화 → 로컬은 성공했으나 개발 서버 아웃바운드 차단으로 실패. 더 근본적으로는 **내부망 WAS가 DMZ로 SSH를 여는 구조 자체가 망 분리 원칙 위반**이라 방화벽을 열어달라고 요청하는 것이 답이 아니라고 판단
3. **최종**: 공유 스토리지에 저장하고 각 채널이 같은 마운트를 읽어 서빙. **망 경계 이동을 원천 제거**

**왜 방화벽 개통을 요청하지 않았나**
2번은 기술적으로는 동작시킬 수 있었습니다. 하지만 그 경로가 열리면 이후 다른 기능도 같은 경로를 쓰게 되고, 망 분리 설계가 예외의 누적으로 무너집니다. 한 번 뚫은 구멍은 회수하기 어렵다고 봤습니다.

**결과**
- 현업이 관리자 페이지에서 직접 등록 가능해져 **개발자 수동 반입 절차 제거**
- 업로드와 서빙 API 표준 구현체를 스마트뱅킹에 선구현해 **타 3개 채널이 참조 개발 가능**하도록 제공
- 파일명 화이트리스트와 경로 정규화 검증으로 경로 조작 차단
- 채널 간 계약(파일명 규칙, 설정 키, 마운트 정책)을 문서화해 파트 내 공유

**과정에서 정리한 것**
`MultipartFile.transferTo`가 상대 경로를 컨테이너 임시 디렉터리 기준으로 해석하는 동작, 물리 저장 경로와 서빙 URL을 분리 설정해야 하는 이유, `catch (Exception e)`가 실제 IOException을 삼켜 원인 규명을 늦추는 패턴을 팀 컨벤션 문서에 반영했습니다.

</details>

### 5. 민원공시 화면 DB 전환

`PostgreSQL` `MyBatis` `Spring Boot` `Vue 2`

<details>
<summary><b>하드코딩에서 JSON, 다시 DB로. 41개 분기 556행 무손실 이관</b></summary>

<br>

**설계 결정 두 가지**

*항목을 컬럼이 아니라 행으로*
분기 1행에 50개 이상 컬럼을 두는 wide 테이블 대신 분기 마스터와 항목 상세 2테이블로 분리했습니다. 공시 항목 증감 시 ALTER가 불필요하고, 특정 분기에 상품별 표 자체가 없는 케이스를 **행을 넣지 않는 것만으로 표현**할 수 있습니다. 컬럼 방식으로는 "이 분기에는 그 표가 존재하지 않았다"는 상태를 나타낼 방법이 없습니다.

*수치 컬럼 전량 VARCHAR*
원본 표기에 `-`, `N/A`, `39.4%`, `21,800%`가 혼재합니다. 숫자 타입으로 변환하면 공시 표기가 훼손되므로 **표기값 보존을 우선**하고, 화면과 서버에서 합계나 증감률을 재계산하지 않는 원칙을 확립했습니다. 산술은 등록 시점에 수행하고 결과 문자열을 저장하는 방식으로 책임을 옮겼습니다. 금융 공시 데이터는 원천과 미세하게 어긋나는 순간 신뢰를 잃기 때문에, 계산 편의보다 표기 보존이 상위 원칙이라고 봤습니다.

**이관 검증**
- 41개 분기 556행을 수기 작성하지 않고 스크립트로 생성한 뒤 컬럼 수, 따옴표 짝, 분기별 항목 수를 자동 검증
- 이 과정에서 존재하지 않는 날짜, 열 밀림, 종료일 오타, 분기 간 데이터 복사 후 미수정 등 **원본 데이터 오류를 다수 검출**하고 교정 내역을 별도 문서로 정리
- 기간 표기 문자열만 예외적으로 분기 코드 기준 서버 생성으로 전환해 날짜 오타 재발을 구조적으로 차단

**후속 개선**
매퍼를 수동 목록에 등록하는 방식은 등록을 빠뜨려도 빌드가 성공해 배포 시점까지 드러나지 않습니다. **디렉터리 패턴 기반 자동 스캔으로 전환**해 누락 자체가 불가능하도록 구조를 바꿨습니다.

</details>

### 6. 웹 접근성(KWCAG) 인증 갱신심사 대응

`Vue 2` `WAI-ARIA` `VoiceOver` `TalkBack`

<details>
<summary><b>CSS와 동작을 전혀 건드리지 않고 심사 지적 해소하기</b></summary>

<br>

**제약**
운영 중인 금융 앱이라 CSS, 화면 동작, API 계약을 바꿀 수 없는 상태에서 스크린리더 대응만 추가해야 했습니다. 접근성 개선이 시각적 회귀를 만들면 그 자체가 더 큰 문제가 됩니다.

**대표 사례 두 건**

*선택 상태가 스크린리더에 전달되지 않던 문제*
Vue 2는 `aria-pressed`를 불리언 `false`로 바인딩하면 속성을 DOM에서 **제거**합니다. 미선택 버튼에 속성이 아예 없으니 스크린리더가 토글 버튼으로 인식하지 못했고, 클릭 시 변화도 "속성 없음 → 속성 생김"이라 상태 변경으로 읽히지 않았습니다. 문자열 바인딩으로 전환해 속성이 항상 렌더링되도록 정정하고 14개 카테고리 전체에 적용했습니다. 버튼 역할이 아닌 요소에 잘못 부여된 속성도 함께 제거했습니다. 적용 전 CSS 셀렉터를 전수 확인해 `aria-pressed`를 참조하는 스타일이 없음을 검증했습니다.

*CSS 가상요소로 그려진 아이콘의 대체텍스트*
`::after`로 그려진 아이콘은 대체텍스트를 부여할 방법이 없습니다. 컨테이너 맨 앞에 화면에서만 숨겨지는 텍스트를 삽입해 읽기 순서를 자연스럽게 만들었고, **CSS는 한 줄도 수정하지 않았습니다.** FAQ 화면 72개 항목에 일괄 적용.

**결과**
심사 지적 웹 영역 전건 대응, 1차 심사 통과. 공통 유틸 수정 범위는 타 팀 담당과 분리해 회귀 위험을 관리했습니다. 2027년 인증 갱신을 목표로 잔여 항목을 계속 대응 중입니다.

</details>

### 7. 제휴 채널 진입점 단일화와 타사 연동 규격 사전 정정

`제휴 연동` `JSP` `기술 커뮤니케이션`

<details>
<summary><b>타사 연동에서 URL은 코드가 아니라 계약입니다</b></summary>

<br>

**발견**
그룹 행사 연계 이벤트로 타 금융사 앱 배너에서 저축은행 제휴 페이지로 진입시키는 연동을 준비하던 중, 상대사가 **폐기된 구 경로를 진입 URL로 인지**하고 있다는 사실을 확인했습니다. 금년부터 해당 제휴 진입은 단일 엔드포인트로 통일된 상태였습니다. 그대로 오픈했다면 배너 클릭이 오픈일에 바로 오류로 드러났을 상황입니다.

**판단**
우리 쪽에서 구 경로를 다시 열어 맞춰줄 수도 있었습니다. 그러면 폐기 대상 경로가 이벤트 트래픽 때문에 되살아나면서 레거시가 고착됩니다. 진입점을 하나로 유지해야 이후 인증, 채널 식별, 로깅 지점을 한 곳에서 관리할 수 있다고 보고, **상대 쪽 호출 URL 정정을 요청하는 방향**을 택했습니다.

**커뮤니케이션 방식**
"틀렸다"로 시작하면 협의가 길어집니다. 상대사 앱에서 저축은행으로 진입하는 **기존 경로 3건을 전수 확인**해 모두 신규 경로로 동작 중임을 먼저 확보한 뒤, 그 현황을 근거로 정정 요청을 보냈습니다. 우리 주장이 아니라 확인된 사실이 되면 왕복이 줄어듭니다. 여기에 우리에게만 당연했던 **환경별 도메인 규칙까지 문서화해 함께 전달**해, 개발 테스트 단계에서 다시 물어볼 일을 미리 없앴습니다.

**배운 점**
우리 쪽에서 규격을 정리했더라도 그 사실이 상대에게 전달되지 않으면, 계약이 어긋난 채로 오픈일에 드러납니다. 상대가 인지하고 있는 규격이 최신인지 확인하는 절차 자체가 개발만큼 중요합니다.

</details>

<br>

## 🧪 Side Projects

### 수신호 (Mulsigye) | AI 물관리 코치

**[GitHub](https://github.com/indaegu/3rd-krc-ai-digital)** | **[Live Demo](https://3rd-krc-ai-digital-web.vercel.app/)**
`Kotlin` `Jetpack Compose` `Next.js` `TypeScript` `Supabase` `Vercel` `Claude API`
**제3회 KRC AI 디지털 혁신 공모전 출품작 (서비스개발 분야) | 기획, 웹, Android 앱 단독 개발**

농업용수 부족 시점을 예측하고 농업인에게 지금 해야 할 행동을 알려주는 서비스입니다. **Android 네이티브 앱과 반응형 웹을 직접 만들었습니다.**

**무엇이 다른가**
기존 포털은 현재 저수율과 공식 가뭄 단계를 보여줍니다. 수신호는 한국농어촌공사 공공데이터 5종의 지역 평년 대비 저수율 추세로 **다음 단계에 이를 가능성이 있는 시점**을 계산하고, 그 전에 할 일을 쉬운 말로 알려줍니다.

**설계에서 신경 쓴 것**

<details>
<summary><b>LLM에 경계를 두고, LLM 없이도 동작하게 만들기</b></summary>

<br>

- **LLM 통제형 코치**: 모델이 자유롭게 조언하게 두지 않고, 서버가 허용한 행동 집합만 설명하도록 경계를 뒀습니다. 생성형 모델을 그대로 신뢰하면 농업 의사결정에 근거 없는 조언이 섞일 수 있습니다
- **폴백 우선 설계**: LLM 장애나 예산 초과 시에도 **정적 코치가 동작**합니다. 외부 의존이 있는 기능은 그것이 없을 때의 동작을 먼저 정의해야 한다고 봤습니다
- **책임 경계 명시**: 자체 예측은 참고 정보이고 **공식 가뭄 예경보가 항상 우선**한다는 원칙을 UI와 문서에 고정했습니다. 공공 데이터를 재해석하는 서비스는 이 경계를 흐리면 안 됩니다
- **개인정보 최소 수집**: 회원가입과 로그인이 없고, 주소 원문과 지역 설정을 서버에 저장하지 않습니다. 수집하지 않으면 지킬 것도 없습니다
- **모노레포와 공용 계약**: 웹과 Android가 **OpenAPI 계약 패키지를 공유**해 클라이언트 2종의 스펙 불일치를 구조적으로 차단했습니다. 실무에서 채널마다 계약이 어긋나는 비용을 겪어 본 경험이 반영된 선택입니다

**구성**
`apps/web` (Next.js, Vercel Route Handler API), `apps/android` (Kotlin, Jetpack Compose), `packages/contracts` (웹과 Android 공용 OpenAPI 계약), `packages/llm` (LLM 서버 경계와 정적 폴백), `infra/supabase` (PostgreSQL 마이그레이션과 테스트)

</details>

<br>

### SBOM 기반 사내 오픈소스 취약점 관리 플랫폼

`TypeScript` `Next.js` `TanStack Query` `AWS` `Docker`
**2026.04 ~ 진행 중 | 사내 CoP 6인 팀 팀장, 프론트엔드 단독**

- SBOM(SPDX, CycloneDX) 기반으로 사내 오픈소스 구성요소를 수집하고 자산 현황을 대시보드로 가시화
- OSV, GitHub Advisory 등 취약점 DB와 매칭하고 AI로 영향도를 분석해 조기 탐지, Slack과 이메일로 자동 알림
- 팀장으로서 브랜치 전략, 커밋 및 PR 규칙, 마일스톤을 정하고 코드 리뷰를 운영
- 프론트엔드 아키텍처는 단독으로 설계하고 구현

<br>

## 🧭 How I work
- **기록을 팀 자산으로.** 파트 정기회의 회의록과 플랫폼 아키텍처 문서를 맡아 작성하고 관리합니다. 흩어진 맥락을 문서로 남겨야 누가 봐도 같은 그림을 그릴 수 있습니다.
- **반복 문서 작업은 파이프라인으로.** 회의록 정리처럼 반복되는 작업을 AI 도구로 자동화해 팀의 문서 작업 시간을 줄였습니다.
- **큰 변경은 되돌릴 수 있는 크기로.** 약 2,000줄 규모 컨트롤러를 Strangler 방식으로 분리 중이며, 골든 전문 diff를 안전망으로 두고 순수 유틸부터 단계적으로 추출하고 있습니다. 되돌릴 수 있는 크기로 나누는 것이 속도를 포기하는 일은 아니라고 생각합니다.

<br>

## 🛠️ Tech Stack

**실무 (Production)**

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black"/> <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white"> <img src="https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=Webpack&logoColor=black"> <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/MyBatis-000000?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=Postgresql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=Nginx&logoColor=white"> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=Jenkins&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=GitLab&logoColor=white"> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=black">

> Spring Cloud (Eureka, Zuul) 기반 게이트웨이 환경, WAI-ARIA, iOS 및 Android 네이티브 브릿지 연동 포함

**사이드 및 개인 프로젝트**

<img src="https://shields.io/badge/TypeScript-3178C6?logo=TypeScript&logoColor=FFF&style=flat-square"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white"> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=Kotlin&logoColor=white"> <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white"> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=Supabase&logoColor=white"> <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=Vercel&logoColor=white"> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/ORACLE-F80000?style=flat-square&logo=oracle&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">

**협업 도구**

<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=Slack&logoColor=white"> <img src="https://img.shields.io/badge/Teams-6264A7?style=flat-square&logo=microsoftteams&logoColor=white"> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"> <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=Claude&logoColor=white">

<br>

## 🏆 Achievements

| 구분 | 내용 | 일자 |
|---|---|---|
| ICT&디지털혁신본부 2025 상반기 우수직원 | 우수직원 선정 | 2025.07 |
| 마이크로소프트 클라우드 AI 모델 경진대회 | 최우수상 | 2024.10 |
| 한국소프트웨어기술진흥협회 | 프로젝트 최우수상 | 2023.12 |
| ICT 한이음 공모전 | 한국정보산업연합회장상 | 2023.12 |

<br>

## 🌱 그 외 개인 및 학습 프로젝트

카드 혜택 극대화 서비스 **HANARO** (Oracle PL/SQL 최적화로 응답 속도 80% 개선) | 통합 여행 플랫폼 **Journey Mate** | CNN 기반 폰트 추천 웹 | 물물교환 서비스 **가치잇솝** | OCR 간편 계좌이체

<br>

## 📬 Contact

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=GitHub&logoColor=white)](https://indaegu.github.io/portfolio/)
[![Gmail](https://img.shields.io/badge/hys1693359@gmail.com-D14836?style=flat-square&logo=Gmail&logoColor=white)](mailto:hys1693359@gmail.com)

<br>

![](./profile-3d-contrib/profile-night-rainbow.svg)
