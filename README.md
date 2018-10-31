# GitHub

git init
보관소 초기화

git config user.name <사용자 이름>
git config user.email <사용자 이메일>
Git 사용자 설정

git remote -v                              // 저장소 URL 확인
git remote add <저장소 이름> <URL>.git      // 저장소 URL 추가
git remote delete <저장소 이름>             // 저장소 URL 삭제
git remote set-url <저장소 이름> <URL>.git  // 저장소 URL 수정
Git 저장소 관련 설정

git status 
변경파일 여부 상태 확인

git add filename                  // 파일 단위로 올리는 방법
git add .                         // 변경된 전체 파일을 올리는 방법         
git commit                        // 깃 에디어를 통해 커밋 메세지 입력
git commit -m "commit message"    // 인라인으로 커밋 메세지 입력하는 법
git commit -a -m "commit message"
git reset HEAD filename           // 스테이지에 올린파일을 되돌리고 싶을때
git log                           // history 보기
git config --global --list        //git 설정 목록 확인
$ echo <filename> >> .gitignore   // git 관리목록에서 제외한다
echo "# project-test" >> README.md  // text 를 README 파일에 기록한다
git init                            // setp 01 저장소 초기화
git add README.md                   // setp 02 git 에 파일을 추가한다
git add .                           // setp 02 파일추가명령어지만 git 에 업로드는 아직 아님 중간단계임
git commit -m "first commit"        // setp 03 파일을 커밋한다 설명으로 "first commit" 추가함
git remote add origin https://github.com/xsiasu/project-test.git
//git 저장소 url 추가
git push -u origin master           // setp 04 git 저장소에 푸쉬한다
파일 업로드 할시
