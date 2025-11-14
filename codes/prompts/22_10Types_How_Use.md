```
🌐 Project Review Board (PRB) 보고서: 시니어 교육 사업 요구사항 상세 분석IT 서비스 및 기업 프로젝트 관리 관점에서, 제시된 '시니어 대상 스마트 기기 및 AI 프롬프트 활용 교육 사업' 구상안을 기반으로, 주니어 PM의 가상 문제 (추상적 아이디어를 기술 요구사항으로 변환)에 대한 해결책을 도출합니다.이전 분석에서 채택된 9. 시스템 분해와 재조립법을 적용하여, 교육 사업 구상안의 요구사항을 기술 구현 및 자동화 그룹이 즉시 실행할 수 있는 상세 명세로 변환했습니다.프롬프트 유형과 선택 이유분류내용선택된 사고법9. 시스템 분해와 재조립법 (System Decomposition and Reassembly)선택 이유🧑‍🏫 교육 기획이라는 추상적인 사업 목표를 💻 **기술 구현 (HTML/N8N)**이라는 구체적인 시스템 구성 요소로 구조적으로 분해하고, 각 구성 요소(홈페이지, 자동화 워크플로우)의 상세 기술 요구사항으로 재조립하여 개발팀의 작업을 즉시 가능하게 만들기 위함입니다. 이는 주니어 PM이 겪는 모호성 문제를 해결하는 핵심 단계입니다.작성 위해 추가 필요 요건교육 사업 구상안을 기술 구현 단계로 옮기기 위해 프롬프트에 포함해야 할 기술 구현 및 자동화 그룹 중심의 추가 요건입니다.기술 페르소나 적용: AI를 N8N 및 웹 접근성 전문가로 설정하여, 제시된 HTML/N8N 전략에 대한 구체적인 기술 스택 및 구현 로직을 강제합니다.홈페이지 기술 규격 상세화: 접근성(Accessibility) 및 시니어 특화 디자인을 충족시키기 위한 구체적인 HTML/CSS/JS 요구사항(예: W3C WAI-ARIA 준수)을 명시.N8N 워크플로우 상세 노드 정의: 제시된 3가지 자동화 시나리오에 대해 트리거-노드-액션의 구체적인 N8N 노드 구성 요소를 명시하여, RPA 전문가가 바로 구현할 수 있도록 요구.데이터 통합 요구사항: 자동화 시나리오에서 언급된 Google Sheet/DB, Gmail/SendGrid, Slack 등의 통합 모듈(Integration Node) 사용을 필수로 명시.4. 문제 해결 프롬프트 md 파일.Markdown### 9. 시스템 분해와 재조립법 (교육 사업 시스템 분해 및 재조립) 적용 프롬프트

**[역할 부여 및 사고법 지시]**
당신은 '시니어 대상 스마트 교육 사업'의 **기술 구현 및 자동화 그룹 리더**이자, **N8N 및 웹 접근성 전문가**입니다. 아래 교육 사업 구상안의 **HTML 홈페이지** 및 **N8N 자동화 전략**을 분석하여, **기술팀이 즉시 작업할 수 있는 상세 기술 구현 요구사항**으로 분해 및 재조립하십시오.

**[입력 데이터 (사업 구상 및 전략)]**
1.  **사업 목표:** 시니어 대상 스마트 기기 및 AI 프롬프트 활용 교육.
2.  **핵심 사용자:** 시니어 교육생 및 보호자.
3.  **구축 전략:** HTML/CSS 기반 단순 홈페이지 + N8N 기반 백오피스 자동화.
4.  **핵심 요구:** 접근성 극대화, 큰 글씨/명료한 디자인, 단순 메뉴 구조.

**[요구사항 및 출력 형식]**
위 입력 데이터를 바탕으로, 다음 3가지 핵심 기술 요구사항을 각각 별도의 Markdown 표 형식으로 작성하십시오.

#### 1. HTML 홈페이지 (Front-end) 기술 요구사항
* **분해 원칙:** 시니어 접근성(A11y)과 유용성(Usability)을 최우선으로, 디자인/퍼포먼스/코드 구조 요구사항을 명시.
* **표 형식:** `구분 (Design/Performance/Accessibility)`, `상세 요구사항`, `기술적 근거/표준`

#### 2. N8N 자동화 워크플로우 상세 노드 명세
* **분해 원칙:** 제시된 3가지 자동화 기능에 대해 N8N의 **트리거(Trigger), 핵심 노드(Node), 최종 액션(Action)**을 명확히 명시.
* **표 형식:** `자동화 기능`, `N8N 트리거`, `핵심 노드 구성 (Workflow Logic)`, `사용 통합 모듈`

#### 3. 핵심 데이터베이스 (Back-end) 요구사항
* **분해 원칙:** 교육 사업 운영에 필수적인 핵심 데이터(교육생, 신청, 문의)의 저장소를 정의.
* **표 형식:** `엔티티 명`, `주요 필드`, `N8N 연동 방안`
5. 프롬프트 실행 결과 md 파일.💻 기술 구현 및 자동화 그룹 실행 명세서1. HTML 홈페이지 (Front-end) 기술 요구사항구분 (Design/Performance/Accessibility)상세 요구사항기술적 근거/표준Design (시니어 특화)주 색상은 높은 명암 대비 (최소 4.5:1)를 사용하고, 폰트 크기는 최소 16px 이상의 산세리프체(가독성 우수)로 고정.WCAG 2.1 Level AA (Contrast), 시니어 사용자 행동 패턴 분석.Performance전체 페이지 로딩 시간은 3초 이내로 최적화하고, 이미지 파일은 WebP 포맷을 우선 적용.사용자 이탈률 방지 (특히 모바일 환경), LCP(Largest Contentful Paint) 지표 관리.Accessibility (접근성)모든 이미지 및 아이콘에는 **대체 텍스트(alt 속성)**를 필수 적용. 모든 상호작용 요소(버튼, 링크)는 키보드 접근이 가능하도록 tabindex 및 WAI-ARIA 속성을 준수.과학기술정보통신부 웹 접근성 지침 2.1 준수.Structure페이지 구조는 HTML5 시맨틱 태그( <header>, <main>, <footer> )를 사용하여 스크린 리더기 및 SEO 효율성 확보.개발팀의 모듈화 및 유지보수 효율 증대.2. N8N 자동화 워크플로우 상세 노드 명세자동화 기능N8N 트리거핵심 노드 구성 (Workflow Logic)사용 통합 모듈교육 문의 자동 응답Webhook Trigger (홈페이지 문의 폼 제출) 또는 Email Trigger (특정 문의 메일함 수신)1. Spreadsheet Node (Google Sheets/Airtable)에 문의 내용 기록 $\rightarrow$ 2. IF Node (필수 항목 누락 검사) $\rightarrow$ 3. Email Node (접수 확인 및 FAQ 링크 발송) $\rightarrow$ 4. Slack/Teams Node (담당 운영자에게 알림)Google Sheets, Gmail/SendGrid, Slack/Teams교육 신청/등록 처리Webhook Trigger (홈페이지 신청 폼 제출 시)1. Spreadsheet Node (신청자 정보 기록) $\rightarrow$ 2. IF Node (정원 마감 임박 여부 검사) $\rightarrow$ 3. Email Node (결제/준비물 안내 발송) $\rightarrow$ 4. Set Node (DB Status: '신청 완료' 업데이트)Google Sheets/DB, Gmail/SendGrid교육 만족도 조사Schedule Trigger (매일 09:00 실행)1. DB/Spreadsheet Node (교육 종료일+1일 수료생 목록 추출) $\rightarrow$ 2. Email Node (개인화된 만족도 조사 링크 발송) $\rightarrow$ 3. Spreadsheet Node (발송 기록 업데이트)DB (PostgreSQL 등), Gmail/SendGrid3. 핵심 데이터베이스 (Back-end) 요구사항엔티티 명주요 필드N8N 연동 방안User (교육생)user_id (PK), name, phone, email, age_group, registered_date교육 신청/등록 처리 시 Insert/Update Node 사용.Coursecourse_id (PK), course_name, start_date, end_date, max_capacity, current_count교육 신청 시 Read/Update Node를 통한 정원 검사 및 카운트 업데이트.InquiryLoglog_id (PK), user_phone, inquiry_text, status (처리 중/완료), log_date교육 문의 자동 응답 워크플로우에서 Insert Node를 통해 문의 내용 기록.
```