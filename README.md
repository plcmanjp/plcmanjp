# plcmanjp

PLC와 산업 자동화 현장에서 필요한 도구를 만들고 공개하는 PLC 엔지니어입니다.

현장 점검과 계산, 반복 업무 자동화, CAD 라벨 제작과 정보 정리에 쓰는 Android, Windows와 Web 도구를 개발합니다. MELSEC 통신 라이브러리와 브라우저 기반 실험 프로젝트도 함께 운영하고 있습니다.

[프로젝트 홈페이지](https://plcmanjp.github.io/) | [PLC 기술 블로그](https://plcman.tistory.com/)

## 한눈에 보기

| 분야 | 프로젝트 | 플랫폼 | 바로가기 |
|---|---|---|---|
| 주력 앱 | PLC 업무수첩 | Android | [앱 소개](https://plcmanjp.github.io/plc-io-check-helper/) / [Google Play](https://play.google.com/store/apps/details?id=com.plciocheck.iocheck) |
| 주력 앱 | JP's Codeless Macro Tool | Windows | [앱 소개](https://plcmanjp.github.io/codeless-macro-tool/) / [Microsoft Store](https://apps.microsoft.com/detail/9NXX9L2ZW52W) |
| 주력 앱 | FeedGrove | Android | [앱 소개](https://plcmanjp.github.io/feedgrove/) / [Google Play](https://play.google.com/store/apps/details?id=com.plcmanjp.feedgrove) |
| 데스크톱 도구 | Excel CAD Label Maker | Windows | [다운로드](https://github.com/plcmanjp/excel-cad-label-maker/releases/latest) / [사용 안내](https://github.com/plcmanjp/excel-cad-label-maker) |
| 데스크톱 도구 | Q-FX Converter | Windows | [다운로드](https://github.com/plcmanjp/fx5-q-converter/releases/latest) / [공개 소스](https://github.com/plcmanjp/fx5-q-converter) |
| 브라우저 도구 | 엔지니어 도구 16종 | Web | [웹에서 실행](https://plcmanjp.github.io/engineer-tool/) / [저장소](https://github.com/plcmanjp/engineer-tool) |
| PLC 학습 | Ladder Quest | Web | [게임 실행](https://plcmanjp.github.io/ladder-quest/) / [저장소](https://github.com/plcmanjp/ladder-quest) |
| 공개 소스 | MELSEC MC Kotlin | Kotlin/JVM | [소스와 빌드 안내](https://github.com/plcmanjp/melsec-mc-kotlin) / [한국어 안내](https://github.com/plcmanjp/melsec-mc-kotlin/blob/main/README.ko.md) |
| Labs | AI 웹소설 연재관 | Web | [연재관 보기](https://plcmanjp.github.io/novel/) / [저장소](https://github.com/plcmanjp/novel) |

## 관심 분야

- PLC, HMI와 산업 자동화
- Mitsubishi MELSEC와 MC Protocol/SLMP
- Modbus RTU와 시리얼 통신
- 현장 점검, 데이터 모니터링과 엔지니어링 계산
- Android, Windows와 Web 기반 실무 도구

## 주요 앱

### PLC 업무수첩

**Android | MELSEC I/O 점검과 모니터링**

Mitsubishi MELSEC PLC에 Ethernet으로 연결해 I/O 상태와 디바이스 값을 읽고, 점검 결과를 기록하는 앱입니다. 프로젝트와 그룹 관리, 심플 로거, 현장 계산 도구를 제공합니다.

읽기 전용 모니터링 도구로, PLC 값을 쓰거나 출력을 강제로 켜지 않습니다.

[Google Play에서 설치](https://play.google.com/store/apps/details?id=com.plciocheck.iocheck) | [앱 소개](https://plcmanjp.github.io/plc-io-check-helper/) | [제품 안내와 가이드](https://github.com/plcmanjp/plc-io-check-helper)

### JP's Codeless Macro Tool

**Windows | 코딩 없는 반복 업무 자동화**

마우스와 키보드 동작을 녹화하거나 스텝으로 구성하는 무료 매크로 도구입니다. 이미지 검색, OCR, 조건과 반복을 조합해 자동화 순서를 만들 수 있습니다.

최신 설치와 업데이트는 Microsoft Store에서 제공합니다.

[Microsoft Store에서 설치](https://apps.microsoft.com/detail/9NXX9L2ZW52W) | [앱 소개](https://plcmanjp.github.io/codeless-macro-tool/) | [사용 안내와 매뉴얼](https://github.com/plcmanjp/codeless-macro-tool)

### FeedGrove

**Android | RSS, Atom과 웹페이지 피드 리더**

RSS와 Atom을 구독하고, 공식 피드가 없는 공개 웹페이지는 파서 스튜디오로 피드를 구성하는 로컬 우선 앱입니다. 규칙 기반 다이제스트와 직접 설정해 활성화하는 선택형 Discord 전달을 지원합니다.

[Google Play에서 설치](https://play.google.com/store/apps/details?id=com.plcmanjp.feedgrove) | [앱 소개](https://plcmanjp.github.io/feedgrove/) | [안내와 의견 보내기](https://github.com/plcmanjp/feedgrove)

앱별 공개 저장소에서는 제품 소개, 도움말과 배포 정보를 확인할 수 있습니다. 공개 저장소가 앱 소스 코드 전체의 공개를 뜻하지는 않습니다.

## 설계와 프로젝트 작업 도구

### Excel CAD Label Maker

**Windows | Excel에서 전기함 덕트 라벨 도면 만들기**

Excel의 글자를 덕트 라벨용 DXF 도면으로 만드는 Windows 앱입니다. `.xlsx`와 `.xls` 행 기준 불러오기, Excel 없이 시작하는 표 직접 편집, 도면 미리보기와 설정 프리셋 재사용을 지원합니다. 원본 Excel 파일은 변경하지 않으며, DWG는 직접 생성하지 않습니다.

[Windows 다운로드](https://github.com/plcmanjp/excel-cad-label-maker/releases/latest) | [소개와 사용 안내](https://github.com/plcmanjp/excel-cad-label-maker)

### Q-FX Converter

**Windows | FX5와 Q 계열 프로젝트 변환 검토**

Mitsubishi FX5 계열과 Q 계열 프로젝트의 래더 텍스트와 코멘트를 검토하고, 반대 계열의 GX 가져오기용 CSV 후보를 만듭니다.

앱 소스는 MIT 라이선스로 공개하며, 포함된 라이브러리와 Qt/PySide6 등에는 각자의 라이선스가 적용됩니다. 생성 결과는 GX와 실제 설비에서 별도로 검증해야 합니다. PLC 접속이나 다운로드 기능은 없습니다.

[Windows 다운로드](https://github.com/plcmanjp/fx5-q-converter/releases/latest) | [지원 범위와 사용 안내](https://github.com/plcmanjp/fx5-q-converter)

## 브라우저 도구와 PLC 학습

### 엔지니어 도구

**Web | 현장 계산과 변환 16종**

수치와 기하, PLC DB, 서보와 모션, 통신과 코드를 다루는 무료 웹 도구 16종입니다. SM/SD 주소 검색, 인버터와 서보 이상코드 검색, 서보 버퍼 주소 계산, 이동시간 계산과 Modbus RTU 프레임 생성 등을 설치와 회원가입 없이 사용할 수 있습니다. 계산과 검색은 기기에서 처리하며 Modbus RTU 도구는 실제 장치에 송신하지 않습니다. 공식 자료를 열 때는 인터넷 연결이 필요합니다.

[웹에서 실행](https://plcmanjp.github.io/engineer-tool/) | [공개 저장소](https://github.com/plcmanjp/engineer-tool)

### Ladder Quest

**Web | 래더 로직 퍼즐 게임**

미션 사양을 읽고 래더 다이어그램을 편성해 가상 설비의 요구 동작을 재현하는 무료 브라우저 게임입니다. 설치와 회원가입 없이 실행하며, 진행 기록은 사용 중인 브라우저에 저장됩니다.

[게임 실행](https://plcmanjp.github.io/ladder-quest/) | [공개 저장소](https://github.com/plcmanjp/ladder-quest)

## 개발자용 공개 소스

### MELSEC MC Kotlin

**Kotlin/JVM | MC Protocol 통신 라이브러리**

Mitsubishi MELSEC PLC의 MC Protocol 3E/4E 통신을 위한 라이브러리입니다. TCP/UDP와 Binary/ASCII 형식, 읽기와 명시적 쓰기를 지원하며 Android SDK 없이 사용할 수 있습니다.

소스에서 빌드해 사용하는 공개 라이브러리로, Maven 저장소에는 아직 배포하지 않았습니다. 공개판 검증은 실PLC 비연결 범위이며, 실제 설비 적용 전 별도 검증이 필요합니다.

[소스와 빌드 안내](https://github.com/plcmanjp/melsec-mc-kotlin) | [한국어 안내](https://github.com/plcmanjp/melsec-mc-kotlin/blob/main/README.ko.md)

## Labs (실험 프로젝트)

### AI 웹소설 연재관

**Web | 설치 없이 읽는 AI 창작 웹소설 리더**

산업용 도구와 분리된 Labs 영역의 웹소설 연재관입니다. 세 작품(허상의 경계, 서툰 계절의 끝에서, 잿불의 검)을 설치와 회원가입 없이 브라우저에서 바로 읽을 수 있으며, 라이트/다크 테마와 글자 크기, 줄 간격 설정을 지원합니다. 모든 회차는 AI가 생성한 창작물입니다.

[연재관 보기](https://plcmanjp.github.io/novel/) | [공개 저장소](https://github.com/plcmanjp/novel)

---

Mitsubishi 관련 도구는 Mitsubishi Electric과 무관한 독립 프로젝트입니다. 제품별 지원 범위와 사용 전 확인 사항은 각 안내를 참고해 주세요.
