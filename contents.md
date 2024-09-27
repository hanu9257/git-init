# Contents

## Keywords

- `init` & `clone`
- `add`
- staged ↔ unstaged
- `commit`
- checksum
- `--amend`
- `status`
- `diff`
- `.gitignore`
- `rm`
- `log`
- `--patch` & `--stat`
- `--graph`
- `-S`
- `reset`
- `remote`
- `fetch` & `pull`
- `tag`
- `alias`
- Object
- HEAD
- `checkout`
- `merge`
- 3way-merge
- fast-foward merge
- `rebase`

## Schedule

### 월(18:00~19:00)

> 10/7, 10/14, 10/28, 11/4

- 송은서
- 송현우
- 장채영
- 김지환
- 조은영

### 화(19:00~20:00)

> 10/8, 10/15, 11/5, 11/19

- 권준혁
- 우이산
- 강조은
- 윤주혜(10/8 해외로 참여 불가)

## References

- [So You Think You Know Git](https://youtu.be/aolI_Rz0ZqY?si=ouf--MTml2u39Wgx)
- [So You Think You Know Git 2](https://youtu.be/Md44rcw13k4?si=5iUdFB8Czyjmuhai)
- [Git Book](https://git-scm.com/book/en/v2)

## Agenda

### Session 1

- 깃은 왜 사용하나요?
- commit, add, rm의 파일 상태 변화
- .gitignore 파일은 왜 사용되나요?
- tags 사용법
- HEAD와 branch는 어떤 역할을 하나요?
- commit 사이를 이동하는 방법
- revert, restore, reset의 차이점은 무엇인가요?
- rebase & merge 비교하기
- local branch와 remote branch
- .gitconfig 파일을 사용한 유용한 기능들
  - alias
    - running script
  - conditional config
  - autoCorrect

### Session 2

- revision selection
- ammend commit
- rebase 사용 심화
  - commit 합치기
  - commit 분리하기
  - `--onto`
- revert를 사용해야 하는 경우
- reset & checkout deepdive
- bisect 사용법
- stash 사용법
  - push
  - apply & pop
  - drop

### Session 3

- PR을 생성하는 방법
- conflict 해결법(PR cont.)
- reflog & fsck을 이용해 사라진 데이터 복구하기
- rebase 후 push --force
- rerere
- cherry-pick

### Session 4

- Object
  - commit
  - tree
  - blob
- References
  - HEAD
  - Tags
  - Remotes
- gc
- scalar
  - sparse checkout
- git의 file system
- hooks 사용법
