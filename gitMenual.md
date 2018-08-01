이 문서의 출저는 재혁이가 압니다(수정좀)
by Mgju

[Git 초기설정]

 - Clone or Download => URL Copy (url 복사)
 - Git에 업로드/불러오기 등 사용할 폴더 생성
 - git init (.git) 무조건 해야됨
 - git remote add origin 복사한 URL -> origin 이름지정 
 - git remote -v 리모트 저장소 등록한거 확인하는 명령


[Git 기초사용법]
 1. Status
    - 변경사항 확인
    - (git status)

 2. Add
    - 소스코드/리소스 등 커밋할 파일 추가
    - 작업공간(우리 컴퓨터)에서 스테이징 영역으로 변경사항 이동
    - (git add *)
    - (git add test.txt) <<:D 예제
				
 3. Commit -> 깃허브 저장
    - 스테이징 영역에 있는 파일을 깃에 커밋
    - (git commit -m "커밋 설명")

 4. Push
    - 커밋한 내용을 원격저장소(깃허브 저장소)에 업로드
    - (git push origin master)
    - (git push 등록한저장소이름 브랜치)

 5. Pull
    - 원격저장소에 있는 소스코드를 작업공간으로 다운로드(불러오기)
    - (git pull origin master)
    - (git pull 등록한저장소이름 브랜치)

 6. Error
    - 만약에 오류 발생시 오류 메시지 구글에 검색




 new File -> git add -> git commit -m "Add file" -> git push -> Done
 파일생성 -> 변경/신규파일 이동 ->등록 -> 커밋 설명  -> 깃허브에 업로드 -> 끝
