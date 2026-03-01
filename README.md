# 💪 Workout Log — PWA

주 2회 운동(유산소 + 헬스) 목표를 체크하는 홈 화면 앱입니다.

-----

## 설치 방법

### 1. GitHub Pages 활성화

1. 이 레포를 GitHub에 올린 뒤
1. **Settings → Pages → Source: `main` branch → Save**
1. 잠시 후 `https://[유저명].github.io/[레포명]` 주소 생성

### 2. 아이폰에 설치

1. Safari로 위 주소 접속
1. 하단 **공유(□↑) 버튼** 탭
1. **“홈 화면에 추가”** 선택
1. 홈 화면에서 앱 아이콘으로 실행 🎉

-----

## 업데이트 방법

Claude에게 기능 수정을 요청한 뒤 받은 `index.html`을 GitHub에 덮어쓰면 자동 반영됩니다.

-----

## 파일 구성

```
index.html      ← 앱 본체 (이것만 수정하면 됨)
manifest.json   ← PWA 설정
icon-192.png    ← 앱 아이콘
icon-512.png    ← 앱 아이콘 (고해상도)
README.md       ← 이 파일
```