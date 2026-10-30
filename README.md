# Arsène Lupin - Once a Thief 한국어 패치

Steam판 **Arsène Lupin - Once a Thief**의 비공식 한국어 패치입니다.

- 배포 버전: `v0.1.0-full`
- 번역 항목: 5,400개
- 지원 환경: Windows 64비트판
- 필수 구성: BepInEx 5 x64
- 테스트 환경: BepInEx `5.4.23.6`

## 설치 방법

1. 게임과 Steam을 완전히 종료합니다.
2. BepInEx 5 x64를 게임 설치 폴더에 설치합니다.
3. 게임을 한 번 실행한 뒤 종료하여 BepInEx 하위 폴더를 생성합니다.
4. 이 저장소의 파일을 ZIP으로 내려받습니다.
5. 압축을 푼 뒤 `BepInEx` 폴더를 게임 설치 폴더에 그대로 덮어씁니다.
6. 게임을 실행합니다. 언어 설정과 관계없이 한국어가 기본 적용됩니다.

게임 폴더 예시:

```text
D:\SteamLibrary\steamapps\common\Arsène Lupîn - Once a Thief
```

정상 설치 시 다음 파일들이 같은 플러그인 폴더 아래에 배치됩니다.

```text
BepInEx\plugins\ArseneLupin.KoreanPatch\
```

## 문제 해결

- 한국어가 나오지 않으면 BepInEx가 정상적으로 로드되는지 확인합니다.
- 패치 파일을 ZIP 내부에서 바로 실행하지 말고 먼저 전부 압축 해제합니다.
- 게임 실행 후 다음 설정 파일이 생성되는지 확인합니다.

```text
BepInEx\config\kr.codex.arsenelupin.koreanpatch.cfg
```

- 설정 파일의 `ForceKorean` 기본값은 `true`입니다.
- 게임 업데이트 후 문제가 발생하면 Steam에서 게임 파일을 확인한 뒤 BepInEx와 패치를 다시 설치합니다.

## 제거 방법

1. 게임을 종료합니다.
2. 다음 폴더를 삭제합니다.

```text
BepInEx\plugins\ArseneLupin.KoreanPatch
```

3. 필요하면 다음 설정 파일도 삭제합니다.

```text
BepInEx\config\kr.codex.arsenelupin.koreanpatch.cfg
```

## 주의 사항

- BepInEx 자체는 이 저장소에 포함되지 않습니다.
- 원본 게임 파일 전체, 개인 로그, 개발 소스, 번역 중간본 및 백업본은 포함되지 않습니다.
- `SHA256SUMS.txt`에서 배포 파일의 무결성 확인값을 확인할 수 있습니다.
- 이 패치는 비공식 사용자 제작 패치입니다.

