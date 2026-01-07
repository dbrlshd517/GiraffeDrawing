# 아티스트 작업 가이드

## 작업 규칙
- **Assets/Textures/ 폴더만** 작업하세요
- 다른 폴더(Scripts, Scenes 등)는 절대 수정하지 마세요

## 작업 방법
1. GitHub Desktop에서 `artist-assets` 브랜치 선택
2. Unity 에디터 열기
3. Project 창에서 Assets/Textures/ 폴더에 파일 드래그앤드롭
4. 저장 후 GitHub Desktop으로 돌아가기
5. 변경사항 확인 후 Commit 메시지 작성
6. "Commit to artist-assets" 클릭
7. "Push origin" 클릭

## 주의사항
- 항상 작업 전 "Fetch origin" 먼저 클릭!
- .meta 파일도 함께 커밋됩니다 (정상입니다)
- Unity 에디터에서만 파일 추가/삭제하세요
- 탐색기에서 직접 파일 복사하지 마세요

## 파일 이름 규칙 (중요!)
- **파일명은 반드시 영문으로 작성**하세요
- 한글 파일명 사용 시 빌드 에러 및 Git 충돌 발생 가능
- 공백 대신 언더스코어(_) 사용
- 예시:
  - ✅ character_main.png
  - ✅ background_forest_01.png
  - ✅ ui_button_start.png
  - ❌ 캐릭터_메인.png
  - ❌ 배경 숲.png

## Pull Request 만들기
1. GitHub Desktop에서 Push 완료 후
2. 상단에 "Create Pull Request" 버튼 클릭
3. 제목과 설명 작성
4. "Create pull request" 클릭
5. 프로그래머가 리뷰 후 Merge 합니다

## 문제 발생 시
- 프로그래머에게 연락하세요
- 모르는 에러 메시지는 스크린샷 찍어서 공유
