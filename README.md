# Git 명령어

**보관소 초기화**</br>
git init</hr></br>

</br></br>

**Git 사용자 설정**</br>
git config user.name <사용자 이름></br>
git config user.email <사용자 ></hr></br>

</br></br>

**Git 저장소 관련 설정**</br>
git remote -v  -> 저장소 URL 확인</br>
git remote add <저장소 이름> <URL>.git -> 저장소 URL 추가 </br>
git remote delete <저장소 이름> -> 저장소 URL 삭제 </br>
git remote set -url <저장소 이름> <URL>.git -> 저장소 URL 수정 </hr></br>

</br></br>

**변경 파일 여부 상태 확인** </br>
git status </hr></br>

</br></br>

**파일 업로드할시**</br>
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
**문법의 개용에 대응하는 문법**</br>
//# 제목1 </br>
//## 제목2 </br>

</br></br>

**문자를 굵게**</br>
**문자**</br>
__문자__</br>

</br></br>

**문자를 기울게**</br>
*문자*</br>
_문자_</br>

</br></br>

**취소선** </br>
~~취소선~~</br>

</br></br>

**코드 입력**</br>
'코드 코드 코드'

</br></br>

**인용문** </br>
// 꺽쇠기호(>) 인용글 </br>

</br></br>

**링크** </br>
[페이지 정보 등](해당 페이지 주소)</br>

</br></br>

**그림 삽입** </br>
[그림 정보 등](해당 그림 주소 "툴팁 메세지, 생략 가능")</br>



