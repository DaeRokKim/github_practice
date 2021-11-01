전역 사용자 설정
git config --global user.name "NAME"
git config --global user.email "email address"

저장소 사용자 설정
git config user.name "NAME"
git config user.email "email address"

전역 설정 보기
git config --global --list
저장소별 설정 보기
git config --list

기존 리포지토리 remote 제거
git remote remove origin

새 리포지토리 remote 추가
git remote add origin https://github.com/계정/리포지토리

다른 리포지토리 remote 변경
git remote set-url origin https://github.com/계정/리포지토리

현재 리포지토리 확인
git config --list
git remote -v