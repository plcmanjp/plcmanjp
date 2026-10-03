# plcmanjp

PLC와 산업 자동화 현장에서 필요한 도구를 만들고 공개하는 PLC 엔지니어입니다.

현장 점검과 계산, 반복 업무 자동화, 정보 정리에 쓸 수 있는 Android, Windows와 Web 도구를 개발합니다. 지원 범위의 GX Works 프로젝트 형식을 분석하는 Python 연구 도구도 공개하고 있습니다.

PLC and industrial automation engineer focused on control software, electrical design, field commissioning, and practical engineering tools.

[프로젝트 홈페이지](https://plcmanjp.github.io/) · [PLC 기술 블로그](https://plcman.tistory.com/)

## 관심 분야

- PLC, HMI와 산업 자동화
- Mitsubishi MELSEC와 MC Protocol/SLMP
- Modbus RTU와 시리얼 통신
- 현장 점검, 데이터 모니터링과 엔지니어링 계산
- Android, Windows와 Web 기반 실무 도구
- Python을 활용한 GX Works 프로젝트 형식의 오프라인 분석

## 주요 앱

### PLC 엔지니어의 작은 업무수첩

**Android · MELSEC I/O 점검과 모니터링**

Mitsubishi MELSEC PLC에 Ethernet으로 연결해 I/O 상태와 디바이스 값을 읽고, 점검 결과를 기록하는 앱입니다. 프로젝트와 그룹 관리, 심플 로거, 현장 계산 도구를 제공합니다.

읽기 전용 모니터링 도구로, PLC 값을 쓰거나 출력을 강제로 켜지 않습니다.

[Google Play에서 설치](https://play.google.com/store/apps/details?id=com.plciocheck.iocheck) · [제품 소개와 가이드](https://github.com/plcmanjp/plc-io-check-helper)

### JP's Codeless Macro Tool

**Windows · 코딩 없는 반복 업무 자동화**

마우스와 키보드 동작을 녹화하거나 스텝으로 구성하는 무료 매크로 도구입니다. 이미지 검색, OCR, 조건과 반복을 조합해 자동화 순서를 만들 수 있습니다.

최신 설치와 업데이트는 Microsoft Store에서 제공합니다.

[Microsoft Store에서 설치](https://apps.microsoft.com/detail/9NXX9L2ZW52W) · [사용 안내와 매뉴얼](https://github.com/plcmanjp/codeless-macro-tool)

### FeedGrove

**Android · RSS, Atom과 웹페이지 피드 리더**

RSS와 Atom을 구독하고, 공식 피드가 없는 공개 웹페이지는 파서 스튜디오로 피드를 구성하는 로컬 우선 앱입니다. 규칙 기반 다이제스트와 직접 설정해 활성화하는 선택형 Discord 전달을 지원합니다.

[Google Play에서 설치](https://play.google.com/store/apps/details?id=com.plcmanjp.feedgrove) · [앱 소개](https://plcmanjp.github.io/feedgrove/) · [안내와 의견 보내기](https://github.com/plcmanjp/feedgrove)

앱별 공개 저장소에서는 제품 소개, 도움말과 배포 정보를 확인할 수 있습니다. 공개 저장소가 앱 소스 코드 전체의 공개를 뜻하지는 않습니다.

## 브라우저 도구와 PLC 학습

### 엔지니어 도구

**Web · 현장 계산과 변환**

진법과 비트 연산, 전자기어비, 아날로그 스케일, UVW 스테이지, Modbus RTU 프레임 등 PLC와 자동화 실무에 필요한 무료 도구 모음입니다. 설치와 회원가입 없이 브라우저에서 사용할 수 있습니다.

[웹에서 실행](https://plcmanjp.github.io/engineer-tool/) · [공개 저장소](https://github.com/plcmanjp/engineer-tool)

### Ladder Quest

**Web · 래더 로직 퍼즐 게임**

미션 사양을 읽고 래더 다이어그램을 편성해 가상 설비의 요구 동작을 재현하는 무료 브라우저 게임입니다. 설치와 회원가입 없이 실행하며, 진행 기록은 사용 중인 브라우저에 저장됩니다.

[게임 실행](https://plcmanjp.github.io/ladder-quest/) · [공개 저장소](https://github.com/plcmanjp/ladder-quest)

## 오프라인 연구 도구

### GX RE Toolkit

**Python · 지원 범위의 GX Works 프로젝트 형식 분석**

명시된 GXW와 GX3 프로젝트 형식을 오프라인으로 분석하는 독립 연구 도구입니다. Python 소스를 공개하며, 지원 CPU와 형식별 제한은 문서에서 확인할 수 있습니다. 전체 작성 기능은 Windows와 pywin32를 사용합니다.

소스는 오프라인 연구용이며 현장 적용 승인본이 아닙니다. 분석 성공이 GX 재빌드, 공식 내보내기 결과와의 일치 또는 PLC 적용 안전성을 보장하지 않습니다.

[공개 저장소](https://github.com/plcmanjp/gx-re-toolkit) · [한국어 안내](https://github.com/plcmanjp/gx-re-toolkit/blob/main/README-ko.md) · [지원 범위와 제한](https://github.com/plcmanjp/gx-re-toolkit/blob/main/docs/compatibility-matrix-ko.md)

---

Mitsubishi 관련 도구는 Mitsubishi Electric과 무관한 독립 프로젝트입니다. 제품별 지원 범위와 사용 전 확인 사항은 각 안내를 참고해 주세요.
