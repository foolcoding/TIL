# git bash, markdown
---
### git bash 명령어
- . : 현재 디렉토리
- .. : 상위 디렉토리
- touch : 파일 생성
- mkdir : 새 디렉토리 생성
- ls : 현재 작업 중인 디렉토리 내부 목록을 출력
- cd : 현재 작업중인 디렉토리를 변경(위치 이동)
- cd - : 뒤로가기
- start : 폴더/파일 열기
- rm : 파일 삭제 (디렉토리 삭제는 -r 추가)
- pwd : 현재 작업중인 폴더의 절대 경로 출력
- ctrl l : clear
---
### Markdown
- `#` : 제목1
- `##` : 제목2
- `###` : 제목3
- `1.` : 순서가 있는 리스트
- `- ` : 순서가 없는 리스트
- `[google](http://www.google.com/)`
- `![이미지](http://picsum.photos/200/300)`
- `**굵게**`
- `*기울임*`
- `~취소선~`
- 코드를 보여 줄수 있는 백틱 활용
``` python
print('hello')
```

## git 명령어

---

- git remote add remote_repo_url : 로컬이랑 원격 연결
- git remote -v : 현재 연결된 원격 확인
- git push 별칭 (+)remote_repo_url : 로컬저장소 변경 내용 업로드, +는 강제실행
- git pull 별칭 remote_repo_url :  원격저장소 변경 내용 다운로드
- git clone remote_repo_url : 원격 저장소 전체를 복제 (다운로드) (git init도 따라옴)
- git revert commitid : 특정 커밋 실행취소, ..로 연결해서 여러 커밋가능
- git reset [옵션] commit_id : 특정 커밋으로 되돌리기, 되돌린 이후 커밋 삭제
    - —soft : 삭제한 커밋의 기록 스테이징에 남기기
    - —mixed : 삭제한 커밋의 기록 워킹디렉토리에 남김(기본)
    - —hard : 삭제된 커밋 기록 안남김
- git flog : 이전의 모든 기록 보여줌 (—hard로 지워진 커밋도 조회가능)
- git restore filename : 수정 상태의 파일 되돌리기 (복원 불가능)
- git rm —cached filename : 스테이징에서 워킹으로 되돌리기 (커밋 없을때)
- git restore —staged filename : 스테이징에서 워킹으로 되돌리기 (커밋 있을때)

## 자리 옮길때

---

제어판 → window 자격 증명 → github 계정 제거
