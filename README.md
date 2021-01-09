### Git Cherry-pick
\
다음과 같은 형태로 사용한다.
<<<<<<< HEAD
- `git cherry-pick <Commit1> <Commit2> <...>`\
: 현재 위치(HEAD) 아래에 있는 일련의 커밋들에대한 복사본을 만들겠다는 것
\
1. side branch 를 만든다.
2. side branch 에서 커밋을 2회 정도 수행
3. master branch 로 돌아가서 1회 커밋한다.
4. side branch 에서 진행한 1개의 커밋을 `git cherry-pick`한다.

예전에 작성한 코드를 날리지 않고 커밋을 선택적으로 가져오고 싶을 때
- 새로운 브랜치를 우선 만든다.
- 원하는 커밋을 `git cherry-pick`한다.
=======
- git cherry-pick <Commit1> <Commit2> <...>\
: 현재 위치(HEAD) 아래에 있는 일련의 커밋들에대한 복사본을 만들겠다는 것
\

>>>>>>> d1da0df (first by side branch)
