# Git 명령어

보관소 초기화</br>
git init</hr></br>

</br></br>

Git 사용자 설정</br>
git config user.name <사용자 이름></br>
git config user.email <사용자 ></hr></br>

</br></br>

Git 저장소 관련 설정</br>
git remote -v  -> 저장소 URL 확인</br>
git remote add <저장소 이름> <URL>.git -> 저장소 URL 추가 </br>
git remote delete <저장소 이름> -> 저장소 URL 삭제 </br>
git remote set -url <저장소 이름> <URL>.git -> 저장소 URL 수정 </hr></br>

</br></br>

변경 파일 여부 상태 확인 </br>
git status </hr></br>

</br></br>

파일 업로드할시</br>
git add filename -> 파일 단위로 올리는 방법 </br>
git add . -> 변경된 전체 파일을 올리는 방법 </br>
git commit -> git 에디터를 통해 커밋 메세지 입력 </br>
git commit -m "commit message" -> 인라인으로 커밋 메세지 입력하는 법 </br>
git commit -a -m "commit message"</br>
git reset HEAD filename -> 스테이지에 올린 파일을 되돌리고 싶을 때 </br>
git log -> 히스토리 보기 </br>
git config --global --list -> git 설정 목록 확인 </br>
$echo <filename> >> .gitignore -> git 관리목록에서 제외 </br>
$echo "# project-test" >> README.md -> 텍스트를 README 파일에 기록 </br>

</br></br>

## Markdown 문법
