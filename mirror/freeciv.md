![http://images3.wikia.nocookie.net/__cb20070217112258/freeciv/ja/images/1/1d/
Shot1.png?align=right](http://images3.wikia.nocookie.net/__cb20070217112258/fr
eeciv/ja/images/1/1d/Shot1.png)

[[PNG external image]](http://images3.wikia.nocookie.net/__cb20070217112258/fr
eeciv/ja/images/1/1d/Shot1.png)

발매

1996.01.05

제작

The Freeciv developers

유통

The Freeciv project

플랫폼

리눅스, 윈도우, 맥 OS, 안드로이드`[1]`

장르

경영 전략 시뮬레이션

<http://freeciv.wikia.com/>

  

## Contents

    

1. 개요 
2. 일반 
3. 상세 규칙 

[[edit](http://rigvedawiki.net/r1/wiki.php/freeciv?action=edit&section=1)]

# 1. 개요 ¶

freeciv는 유명한 경영 전략 시뮬레이션 시드마이어의 문명 시리즈의 규칙을 기반으로 만들어진 턴제 전략 시뮬레이션이다. GNU 일반 공중
허가서에 의해 배포되고 있으며, 자유 소프트웨어이다. <del>그렇게 리눅스 사용자들도 무료로 문명하고 있다.</del>

  

[[edit](http://rigvedawiki.net/r1/wiki.php/freeciv?action=edit&section=2)]

# 2. 일반 ¶

기본적으로 freeciv 1.0은 문명1에 기반하여 만들어 졌으며, 이후 꾸준한 업데이트를 통해 freeciv 2.0 이후 버전에서는
문명2의 모든 규칙을 구현하는데 성공했다. freeciv 프로젝트는 아직까지도 현재 진행형으로, 문명2를 넘어서 freeciv만의 독자적인
규칙을 도입하여 사실상 문명 2.5라고 봐도 과언이 아닐 정도로 장족의 발전이 이루어 졌다고... 첫 공식버전 릴리즈가 96년도에 발표가
되었으니, 거의 [듀크 뉴켐 포에버](%EB%93%80%ED%81%AC%20%EB%89%B4%EC%BC%90%20%ED%8F%AC%EC%97%90%EB%B2%84.md)에 버금가는 개발 기간인셈.

  

데비안 계열의 리눅스 배포판의 기본 게임으로 포함되어서 리눅스 운영체제를 사용하는 유저라면 꼭 한번은 실행해보게 되는 게임이다(우분투의 경우
9.10 버전까지 포함되었다).

  

오픈소스이기에 리눅스용은 공식적으로 소스코드만 배포되고 컴파일을 해야 하지만, 우분투와 오픈수세, 페도라의 경우는 꾸준히 비공식 패키지가
나오고 있다. 윈도우와 맥OS용은 공식 패키지로 배포된다.  

그래픽은 문명 1과 2를 오고가는 약간 안습한 gtk+ 기반의 그래픽 인터페이스지만, 그래픽에 구애받지 않는다면 있을 것은 다 있다. 개발자
그룹이 '시드 마이어'가 게임 디자인에 참여하지 않은 유일한 문명 시리즈(콜 투 파워는 흑역사.)인 문명 2의 열혈 팬이라서 2 기반으로
만들고 있다(그래서 문명 3 규칙은 집어넣지 않는다.). 하지만 문명 2도 세계 100대 PC게임 중 3위로 문명 시리즈 중 가장 높은
평가를 받고 있는걸 보면, 게임성은 결코 얕볼 수가
없다.[#](http://psx.ign.com/objects/010/010640.html)

  

freeciv의 무서운 점은 무지막지한 자유도에 있다. 일단 AI 스크립트가 [lua](lua.md)로 돼있어서 lua에 조금이라도
지식이 있으면 컴퓨터의 패턴을 완전히 뜯어 고칠수가 있다. 더군다나 규칙 스크립트와 유닛 스크립트는 일반 텍스트로 돼있어서 몇가지 사항만
외우면 모드가 따로 없다. 거기다 굳이 스크립트를 건드리지 않아도 옵션에서 국경선, 도시 간격, 시작 소지금, 기술, 지형, 외교 등 웬만한
것을 다 바꿀수 있으니...

  

더 경악스러운 것은 [시드 마이어의 문명](%EC%8B%9C%EB%93%9C%20%EB%A7%88%EC%9D%B4%EC%96%B4%EC%9D%98%20%EB%AC%B8%EB%AA%85.md) 시리즈의 플레이어 숫자는 많아봐야 16명이 한계였으나, freeciv는 최대
125명까지 지원한다. 컴퓨터 사양만 받춰준다면 유엔 가입국이 총출동하는 레알 세계 재현 문명을 즐길 수 있다.`[2]``[3]`

  

2011년 8월 현재 2.3 베타2 버전이 공개되었다. 기존 룰에서 벗어나 실험적인 요소를 몇가지 도입할 예정이다.`[4]`

  

2012년 8월 11일 2.4.0 베타1 버전이 공개되었다. 1년만의 메이저 넘버링 업데이트로, 여러가지 요소가 포함되었다. 게임 외적인
면에서는 문명 3에서 처음 선보인 맵핑 리플레이`[5]`와 유닛의 방향 전환 그래픽 도입`[6]`이 가장 큰 변화이다. AI 개선이 특히
눈에 띄는데, 여러가지 AI 패턴이 도입되어서 이제는 AI마다 각각의 선호도에 따라 다른 결정을 내릴 수 있게 되었다. 하지만 외교 AI의
병맛나는 협상 거부는 여전한 듯 보인다. 그밖에 AI에 대한 유저의 커스텀이 더욱 용이하도록 AI 스크립트를 다시 구성하였다. 게임 플레이
면에서는 민족 개념이 도입되었다. 문명 3과 마찬가지로 적국의 도시를 점령한 이후 민족이 다른 시민은 불만도가 상승하게 되었다. 2013년
11월 14일, 2.4.0 안정 버전이 공개되었다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/freeciv?action=edit&section=3)]

# 3. 상세 규칙 ¶

베이스가 문명 2인 만큼 대부분 2의 룰을 따르고 있지만, 꾸준한 업데이트로 사실상 문명 2.5에 가까울 정도로 새로운 규칙들이 도입되었다.
문명 2에는 없는 자원 개념과, 다양한 정부 체제, 문명 3 스타일의 외교가 그것이다.

  

전투 규칙은 기본적으로 문명 2에 기반하는데, 대표적으로 한 타일에 유닛 겹치기가 허용되지만, 문제는 그 타일에 있는 단 한 유닛만 죽어도
그 타일에 있는 모든 유닛이 죽는걸로 처리된다는 것이다.`[7]` AI들도 이를 고려해서 결코 유닛을 겹치지 않고 웨이브를 보내, AI
국가와 전쟁을 하게 되면 수많은 유닛의 떼를 볼 수 있다. 근데 시작전에 설정 파일에서 kill stack을 꺼버리면 문명3 스타일의 뭉치기
전투 방식이 된다. 유닛간 전투 승리-패배는 꽤나 까다로운 계산식을 거쳐서 이루어진다.`[8]` 요새화, 도시 방어도, 지형 방어도, 유닛의
행동력 등이 전투에 영향을 끼친다. 유닛 상성도 존재하여, 창병 유닛은 기병 유닛에게 2배 방어 보너스를 받는다.`[9]`

  

정부 체제는 [무정부체제](%EB%AC%B4%EC%A0%95%EB%B6%80%EC%B2%B4%EC%A0%9C.md) \-
[전제](%EC%A0%84%EC%A0%9C.md) \- [군주제](%EA%B5%B0%EC%A3%BC%EC%A0%9C.md) \-
[공화정](%EA%B3%B5%ED%99%94%EC%A0%95.md) \-
[공산주의](%EA%B3%B5%EC%82%B0%EC%A3%BC%EC%9D%98.md) \-
[민주주의](%EB%AF%BC%EC%A3%BC%EC%A3%BC%EC%9D%98.md) 5가지로 문명2와 동일하다.

  

외교 방식은 특이하게 문명3에 많은 영향을 받았는데, 이젠 팀 동맹과 팀승리가 가능해졌다(물론 시작전 설정해야 하지만). 외교 AI는
플레이어 사이에서 가장 논란이 되는 문제중 하나이다. AI가 보통 보수적인것이 아니여서 어지간히
[호감도](%ED%98%B8%EA%B0%90%EB%8F%84.md)가 높지않은 이상 기술 교환은 꿈도 못꾼다.<del>본격
[문명](%EB%AC%B8%EB%AA%85.md) [미연시](%EB%AF%B8%EC%97%B0%EC%8B%9C.md)</del>
문명4나 문명5 처럼 동맹 맺을 정도가 되도 금 원조는 절대 안해준다. 뿐만 아니라 국경만 맞대고 있어도 몇십턴을 못가 무조건 선전포고를
해대고, 어떤 경우에도 -심지어 AI가 지고 있는 상황에서도- 평화 협정을 맺어주지 않는다.`[10]` 매 번 AI 수정이 이루어지고 있지만
실감나는 외교전을 펼치기에는 제한이 많다.

`\----`

  * `[1]` 아직 버전이 1.0이라 느려서 플레이하기가 쉽지않다.
  * `[2]` 2.0 이전의 freeciv에서의 국가는 국기와 건물 스타일이 바뀌는 정도였지만, 2.3버전에서는 국가간 플래그가 있어서 각 국가마다 역사적으로 서로 친하거나 상극인 문명이 존재하고 선호하는 정부체제, 호전도가 설정돼있다. 예를 들면 남한은 북한과 civil war 상태이고 남한은 민주주의 정부를 선호하고 반대로 북한은 공산주의 체제를 선호, 소비에트는 러시아와 civil war 상태이고, 미국과 갈등으로 설정돼있다.
  * `[3]` 사실 사양이 안좋은 컴퓨터라도 125명 최대 플레이어 상태로 플레이 했을때 초반 BC1000 이전 까지는 꽤 원할하다. 하지만 문명 류의 게임이 그렇듯, 시간이 갈수록 처리해야하는 명령이 기하급수적으로 늘어나서 나중에 가면 한턴 넘기는데 <del>리얼타임</del> 한오백년 걸린다.
  * `[4]` 대표적으로 유닛을 대형 유닛과 그렇지 않은 유닛으로 나누어서 대형 유닛은 산 지형에는 움직일 수 없는 패널티를 부여한다던가.
  * `[5]` 게임 종료 이후에 미니맵에서 게임 시작부터 종료할 때까지 플레이어들의 세력 변화를 보여주는 리플레이.
  * `[6]` 이전까지는 어떤 방향에서든 한가지 그래픽이었다.
  * `[7]` 원작 문명2에서도 사실상 유닛 겹치기를 방지하려는 제작자의 고려였다.
  * `[8]` 다행히도 2.3버전에서는 문명4 스타일로 유닛을 선택하면 상대 유닛에 대한 공격 승리 확률, 방어 승리 확률이 떠오르게 되어있다. 이전 버전에서는 감으로 때려 맞춰야 했던거에 비하면 장족의 발전.
  * `[9]` 또한 .ruleset 파일만 고치면 모든 유닛이 폭격 명령(Bombard)를 쓸 수도 있다. 다만 현재까지 AI가 Bombard를 이해하지 못하기 때문에 기본 룰에서는 모두 빠져있다.
  * `[10]` 때문에 문명 시리즈 같이 도시 한 두개만 먹고 정전하는 전략은 무의미하다.

