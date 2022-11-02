# modu-sStore
모두의 가게를 스프링 기반으로 구현합니다.

## 모두의 가게란?

2017-2018년 경 배달의 민족이 시작-개발 단계에 있을 쯤 저도 소프트마에스트로 과정을 신청하며 냈던 아이디어인데, 
배달의 민족과 유사하나 오프라인 가게들을 방문 하기 전 모든 정보를 공유할 수 있고 사장님들이 가게에 대한 정보를 업데이트할 수 있고,
알림을 보내거나 사용자들은 가게를 방문하기 전에 대기열이나 가게에 대한 모든 정보(그날의 재료입고, 오늘의 메뉴 등)를 파악할 수 있고
방문 전에도 거리뷰와 같은 3d 카메라 뷰를 통해 방문 한 것과 유사한 가게 안을 탐색할 수 있는 시스템을 제공하는 게 목표였습니다.

해당 아이디어를 떠올리게 된 이유는 거리뷰를 오프라인 가게들에 접목하고 미리 가보는 것과 (직접 가보지 않고도 ) 동일한 가게 분위기나 인테리어 등을 파악하고 싶다!
그런데 거리뷰와 같은 사진을 보면 직접 방문을 안해도 되잖아! 신박한데? 에서 시작한 아이디어입니다. (현재는 직방등에도 이런 카메라 방식을 사용하고 있다고 알고 있습니다.)

기술 스택은 자바 스프링을 사용할 예정이며 업데이트 해나갈 예정입니다.



## 브랜치 전략

브랜치 전략은 main을 최종 배포 (서비스 중인 브랜치)로 사용할 예정입니다.
또한 개발 브랜치는 develop로, hotfix는 서비스 브랜치에서 오류가 있을 때 생성하여 사용하고, 
feature 및 fix 등을 develop 하위 브랜치로 두어 develop에 병합 시킨후(merge) stage 브랜치에서 예비 배포 (테스트 서버) 를 진행하려 합니다.

:추후 수정될 수 있습니다.

![image](https://user-images.githubusercontent.com/77390758/199382160-2a53a757-a077-4022-95be-09d56d456e07.png)
