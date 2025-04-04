작성기한: 2025-03-20

# 2주차 - MSA 개념 이해하기
지난 주부터 지금까지 아래 참고 자료를 통해 MSA 개념을 학습하고 있습니다.

참고 자료:
* [[우아콘2020] 배달의민족 마이크로서비스 여행기](https://youtu.be/BnS6343GTkY?si=1wm-BPV7eZ_sI4_B)
* [YouTube 재생목록 - MSA](https://youtube.com/playlist?list=PLdFZqKf8yzixbYQqVQGF__7UHbyL6H-XG&si=vKyLevdplSEFH13R)

스터디 시작 주라 작업 일지에 적을만한 깊은 내용은 없지만, 느낀점을 적어보자면 다음과 같습니다.
1. **반성**
    * 스스로를 프론트엔드 개발자로 정체화하며 지내왔기에 아키텍쳐 자체에 대한 이해도가 많이 낮음에도 이에 대한 필요성을 못 느껴 그동안 학습을 미뤄왔습니다
    * 때문에 시스템 설계 이론은 그저 어른들의 이야기로만 생각하고 별 관심을 기울이지 않았는데요
    * 이제는 안락 지대를 벗어나 열심히 공부해야겠다는 생각이 들었습니다.
2. **서비스 구분 기준**
    * 하나의 큰 애플리케이션을 여러 개의 작은 서비스로 구분할 때, 그 **적절한 경계를 정의**하는 기준이 궁금해졌습니다.
    * '서로 다른 서비스지만, 데이터를 공유해야 하면 DB를 어떻게 구성해야 할까?'
    * '통신이 너무 잦으면 차라리 합치는 게 나을지도?' 등 서비스를 나눌 때 여러 고민을 하게 만드는 것이 MSA라는 인상을 받았습니다.
    * 비즈니스 로직 파트에서도 여러 서비스를 나누는데, 그 기준을 이해하고 분리하는 방법을 배워야겠다는 생각이 들었습니다.
