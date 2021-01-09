### Git Cherry-pick
\
다음과 같은 형태로 사용한다.
- `git cherry-pick <Commit1> <Commit2> <...>`\
: 현재 위치(HEAD) 아래에 있는 일련의 커밋들에대한 복사본을 만들겠다는 것
\
1. side branch 를 만든다.
2. side branch 에서 커밋을 2회 정도 수행
3. master branch 로 돌아가서 1회 커밋한다.
<<<<<<< HEAD
4. side branch 에서 진행한 1개의 커밋을 `git cherry-pick`한다.
=======
>>>>>>> 3d62768 (second by side branch)
