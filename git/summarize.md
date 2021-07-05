# [실습] 이번 과정에서 작성한 코드 TIL에 정리해보기

## Git

#### Basic CLI

- `git touch a.txt` : `a.txt` 파일을 만들 수 있다.
- `git mkdir b` : `b` 폴더를 만들 수 있다.
- `ls` : 현재 폴더의 목록을 볼 수 있다.
  - `ls-al`을 통해 현재 폴더의 자세한 정보를 볼 수 있다.
- `cd` : 특정 폴더로 이동한다.
  - `cd b/` : 현재 폴더에 있는 하위 폴더 `b`로 이동
  - `cd .` : 현재 폴더를 의미
  - `cd ..` : 상위 폴더로 이동

#### Git

- `git status` : git으로 관리되고 있는 repository(저장소)의 상태를 보여줌
- `git init` : 현재 폴더를 git으로 관리할 것을 선언(초기화)
- `git add` : 작업의 변경 내용을 work space에서 git index에 추가.
  - `git add a.txt` : `a.txt`파일을 index에 등록
  - `git add .` : 현재 폴더 전체를 index에 등록
- `git commit` : index에 있는 파일들을 가지고 commit(기록)을 남김
  - `git commit -m '메시지'` : 기록을 남기면서 `메시지`를 남김.
- `git log` : git에서 작업한 기록을 보여줌.
  - 