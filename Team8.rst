=======================
Open S/W Exploring Camp
=======================

Project
=======

Team8 Member
------------

* MinKuk Jo
* Donghoon Song
* YEONJE CHOI
* Sanggoo Kim

8. 풀리퀘스트 해보기
----------------
* Pull request
- git remote add upstream git@github.com:openstack-kr/contributhon-2018-knu.git 입력
- 이 때 명령어는 72자 단위로 개행해야 한다.
- git pull upstream master 입력하여, 온라인에 있는 변경 사항을 로컬로 다운로드해야 하는데, 로컬 저장소에 원격 저장소를 추가해야한다
- 그 다음으로 ls 입력하여 README.rst 있는지 확인함. 존재한다면 제대로 다운로드 된 것
- 만약 존재하지 않는 다면, 입력 되었던 명령어들을 제거(git remote rm)한다음 처음부터 다시 실행할 것.
- 제대로 다운로드 되었다면, nano README.rst 입력한 뒤, 내 이름을 README.rst에 추가 후 저장 (ctrl + o -> enter -> ctrl + x )
- git commit -a 후 이번 커밋(변경) 의 변경사항을 입력
        : 변경한 내용에 대해 commit을 추가하여서 어떤 내용이 바뀌
        었는지에 대해 알려줍니다.
- git push origin master 입력하여 내 온라인 저장소에 변경 사항을
      업로드
        : local의 브렌치에서 서버의 master 로 정보를 이동합니다.
- 파이어폭스로 github 홈페이지 들어가 내 저장소 (https://github.com/내 ID/contributhon-2018-knu) 들어가 New Pull request 클릭

- 변경사항을 설명으로 입력한 후, pull request

16. 다른 팀원 평가해보기
-------------------
* My -> Changes -> 자기 문서 -> URL 확인 -> 다른 사람들이 접근해서 리뷰가능

* Reply -> 리뷰가능

* Code-review :
- -2 : 못 쓰는 코드 (Do not merge)
- -1 : 수정이 필요함 (This patch needs further work before it can be merged)
- +1 : 잘한 코드 (Looks good to me, but someone else must approve)
- +2 : 코어 코드 (Looks good to me (core reviewer))

* Commit message : Commit message들을 볼 수 있음, 필요하면 Edit도 가능
