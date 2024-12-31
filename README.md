# **PTCGPB v3.0.0 noob_v2**

**기능 설명(+변경사항) :**
- **크라운 뜨면 정지하는 기능 추가(피카츄/뮤/리자몽 다 멈춤)**
- **나이 미성년자 -> 성인 나이로 수정**
- 그에 따라 화면 배치 달라진 거 적용
- 2.8.0 -> 3.0.0으로 변경(이름 입력안되던거 해결)


**다운 방법**
- 오른쪽 Releases에서 PTCGPB v3.0.0 noob_v2.zip 다운받으면 됨(latest적힌거)


**원작자 코멘트**

*이 봇은 현재 방식이 유효한 한 무료로 제공되며 계속 업데이트됩니다. PTCGPB 제작에 많은 시간을 투자했으며, 여러분의 컬렉션 완성에 도움이 되었다면 커피 한잔의 후원으로 새로운 기능 개발을 지원해주세요!*
https://buymeacoffee.com/aarturoo
*후원해주셔서 감사합니다. 갓팩을 계속 찾아보세요!* 😄

- 원본 링크
- https://github.com/Arturo-1212/PTCGPB
  



**이 봇은 무엇을 하나요?**
- 계정 생성부터 삭제까지 7분 이내에 26장까지 뽑음.
- 갓팩이 나오거나 크라운 카드가 나오면 해당 인스턴스 중지
- 봇 실행 예시: https://i.imgur.com/DfqAp7c.gif

**필요한 것들**
- [MuMu 플레이어](https://www.mumuplayer.com/)
- [AutoHotkey v1.X](https://www.autohotkey.com/download/ahk-install.exe)
- [PTCGP Bot.zip](https://github.com/Arturo-1212/PTCGPB/archive/refs/tags/v3.0.0.zip)

**설치 방법**
1단계: 필수 프로그램 설치
- AutoHotKey
- MuMu 플레이어 (기본 설치 경로 사용)

2단계: MuMu 플레이어 설정
- 설치
- 권장 설정 **(굵은 글씨 = 필수)**
  - CPU: 2
  - RAM: 2
  - 저사양 모드
  - 전용 그래픽 카드 사용
  - **해상도: 540 x 960 220 dpi**
  - **화면 밝기: 50**
  - FPS: 60
  - **FPS 표시 끄기**
  - 시스템 사운드 끄기
  - **백그라운드 실행 체크 해제**
  - 직접 종료
- 인스턴스 이름을 "1", "2", "3", "4" 등으로 설정 (따옴표 제외)
- 첫 번째 인스턴스는 호환되지 않으므로 다른 인스턴스를 1번으로 지정하세요.

3단계: PTCGP 설치
- ~~PTCGP 스피드 모드 [[구버전]](https://modsfire.com/y6p37S9f7n2fD38) [[신버전]](https://modsfire.com/6OIgGK903XQXy6O) ** - *platinmods 포럼의 nowhere_222님께 감사드립니다*~~
- ~~MuMu 인스턴스에 드래그 앤 드롭~~
- ~~**새 버전은 1x-3x 속도 선택 가능한 모드 메뉴가 있습니다. 3x는 여러 인스턴스 실행 시 더 많은 리소스를 사용합니다. 구버전은 2x로 계속 사용 가능합니다.~~
- 실사용하려면 배속사용x (정지위험)

4단계: 
- 봇 압축파일 다운로드
- 우클릭 > 압축 해제

5단계: **Windows 설정에서 배율을 125%로 변경**
- Windows 키 누르기
- "디스플레이 설정" 입력
- 모든 모니터의 배율 설정을 125%로 변경

6단계:
- 인스턴스 시작
- PTCGP 실행
- 초기 600MB 다운로드
- 계정 삭제
- 재시작 후 생년월일과 국가 선택 화면까지 진행

7단계:
- PTCGPB.ahk 실행

8단계: 스크립트 설정 입력 **(굵은 글씨 = 필수)**

- **Name : 한글안됨. 영어로 입력할것**
- Instances : 실행할 인스턴스 수(난 3으로함. 본인사양따라 설정하셈)
- Columns : 기본 5인데 인스턴스 많이 안쓰면 그냥 냅두면됨
- Pack : 열고 싶은 팩
- God Packs : 갓팩 찾으면 일시정지/클라종료 (리소스 절약용)
- **Language : Korean선택 (다른거로하면 이미지없어서 안돌아감)**
- Monitor : 투모니터면 보고 1이나 2 적절히 선택하셈
- Delay : 동작 간 딜레이. (기본250인가? 버그나면 400으로 늘려보셈셈)
- **Time Zone: 게임 날짜 변경 시간 (한국은 1500으로 설정하라고 함)**
- Folder: 기본 설치 경로 사용 시 그대로 두기, 변경했다면 새 경로 입력
- **Speed : 2x로 설정** (어차피 배속안됨)

9단계: 시작 클릭
- **요청 시 adb 실행 및 방화벽 허용**

10단계: 갓팩 찾기
- 봇이 실행됩니다

**최종수정일 2024-12-31**
