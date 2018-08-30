4. Create SSH KEY
=================


기본 Syntax는 다음과 같이 구성됩니다.
 $ ssh-keygen -t rsa -b 4096

위의 문장을 아래와 같이 해석할 수 있습니다.
 * ssh-keygen : ssh-key를 생성한다.
 * -t rsa     : 보안 방식은 RSA를 사용한다.
 * -b 4096    : 비트 수를 설정한다.
                (비트 수는 보통 4096으로 설정합니다.) 



Github와 Desktop에서 해야하는 절차
----------------------------------

1. 홈 -> 우측 상단 메뉴-> 숨긴 파일 보이기를 누릅니다.
2. .ssh -> id_rsa.pub -> Ctrl+A -> Ctrl + C를 통해 전체 암호키를 복사합니다.
3. github의 자신의 repositary의 setting에 들어가서 deploy key에 Paste해주면 됩니다.



Deploy Key가 이미 사용중이라면?
-------------------------------

1. 이전에 사용중이던 repositary에 deploy key를 삭제합니다.
2. 계정의 Settings에 진입합니다.
3. 좌측 메뉴 중간 지점의 SSH and GPG keys에 진입합니다.
4. SSH keys에 key를 Paste해주면 됩니다.

