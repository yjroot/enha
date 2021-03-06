## Contents

    

1. 디스플레이 
    

1.1. 개요

1.2. [LCD](LCD.md)에 비한 장점

    

1.2.1. 잔상이 사실상 없다.

1.2.2. 보는 각도에 의한 색상 왜곡이 발생하지 않는다.

1.2.3. 빛샘과 같은 현상이 일어날 여지가 없다.

1.2.4. 완전한 검은색의 표현력이 좋다.

1.2.5. 대형화에도 유리하다.

1.3. [LCD](LCD.md)와 비교한 단점

    

1.3.1. 검은색에 가까운 색의 표현이 나쁘다.

1.3.2. 전체적으로 전력 소비량이 크다. 특히 밝은 영상을 표시하면 전력 소비량이 더 커진다.

1.3.3. 발열이 심하다.

1.3.4. 번인 현상이 있다.

1.3.5. 수명이 상대적으로 짧다.

1.3.6. 고밀도/고해상도 제작이 어렵다

1.4. 특징

1.5. 황혼의 시대

2. 프로그램 데이터 프로세서 
3. 게임 유튜버 [PewDiePie](PewDiePie.md)의 약자 

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=1)]

## 1. 디스플레이 ¶

상위 : [디스플레이](%EB%94%94%EC%8A%A4%ED%94%8C%EB%A0%88%EC%9D%B4.md)

  

Plasma Display Panel의 약자.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=2)]

### 1.1. 개요 ¶

조그마한 가스 튜브가 촘촘히 박혀 있고 이 가스 튜브에 전기를 통하면 마치 전구처럼
[플라즈마](%ED%94%8C%EB%9D%BC%EC%A6%88%EB%A7%88.md)화된 가스가 빛을 내는 원리로 영상을 표시한다.
각각의 픽셀의 발광 원리는 [형광등](%ED%98%95%EA%B4%91%EB%93%B1.md)과 거의 같다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=3)]

### 1.2. [LCD](LCD.md)에 비한 장점 ¶

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=4)]

#### 1.2.1. 잔상이 사실상 없다. ¶

반응속도가 ms 단위 이하라 사람이 잔상을 느낄 수 없으며, LCD처럼 밝기 변화 차이에 따른 반응속도 차이(LCD는 Gray-to-Gray
반응속도가 Black-to-White에 비해 훨씬 느리다)도 없다.

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=5)]

#### 1.2.2. 보는 각도에 의한 색상 왜곡이 발생하지 않는다. ¶

일반적으로 LCD는 편광을 이용해서 빛을 차단하는 방식으로 명도를 조절하는데, 이것이 편광 정도(즉 원하는 명도)와 보는 각도에 따라
차단되는 수준이 제각각이 되는 경우가 많아서 옆에서 보면 단순히 어둡게 보이는 것이 아니라 원래 색과는 관계 없는 색이 나오곤 한다. 그나마
IPS와 같이 현상을 개선한 제품도 있지만 TN과 같은 경우는 각도 문제가 극악하다. 하지만 PDP는 명도와 각도에 따른 변화가 정비례하므로
색상 왜곡도 없다.`[1]`

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=6)]

#### 1.2.3. 빛샘과 같은 현상이 일어날 여지가 없다. ¶

별도로 백라이트를 이용하지 않으므로 빛샘이 없다.

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=7)]

#### 1.2.4. 완전한 검은색의 표현력이 좋다. ¶

LCD의 편광은 빛 차단이 완벽하지 않아서 아무리 검은색을 만들려 해도 아주 어두운 회색으로 보이지만 PDP의 경우 완전한 검은색을
표시하려면 그냥 가스 튜브를 끄면 된다. 리뷰의 명암비 계측에서 수만~수백만 수준의 명암비가 나오는 이유가 이것 때문.

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=8)]

#### 1.2.5. 대형화에도 유리하다. ¶

LCD는 화면 하나가 통째로 된 대형 필름을 이용하기 때문에 화면 일부에 문제가 생기면 불량품이 되지만 PDP는 PCB 기판에 가스 튜브를
박는 형식이기 때문에 상대적으로 안정적이어서 만들기 쉽다. <del>어째 이것만 빼면 장점들이 [AMOLED](AMOLED.md)랑
매우 비슷하다.</del>

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=9)]

### 1.3. [LCD](LCD.md)와 비교한 단점 ¶

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=10)]

#### 1.3.1. 검은색에 가까운 색의 표현이 나쁘다. ¶

PDP는 subfield라는 단위 단계의 조합을 통해 색의 명도를 조절한다. 따라서 각 단계 사이마다 초기화를 한번씩 해줘야 하는데, 이
초기화라는게 **강제로 방전을 일으키는 방법이기 때문에 그 방전에 따른 색이 미량으로나마 방출**된다. 따라서 subfield를 거친 결과
발생한 검은색에 가까운 색은 방전 결과에 의해 방출된 약간의 색이 첨가된 상태가 된다. 완전한 검은색(#000000)의 경우 1.2.4에서
다룬 것처럼 그냥 가스 튜브를 끄면 되므로 완벽한 검은색을 표현할 수 있지만, 검은색에 가까운 진한 회색의 경우 LCD와 마찬가지로 발광체가
켜져 있어야 하는 상황이 되기 때문이다. 즉, LCD와 비교하여 이야기하면 **장점이 사라진다**라고 표현하는 쪽이 맞고, 굳이 말하면
PDP의 단점이라 보기에는 다소 애매하다.

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=11)]

#### 1.3.2. 전체적으로 전력 소비량이 크다. 특히 밝은 영상을 표시하면 전력 소비량이 더 커진다. ¶

현재 많이 사용되는 AC PDP의 경우, 전극위에 절연체를 덮어 아크 방전을 막아 안정적인 색 발현을 돕는다. 그런데 절연체는 당연하지만
capacitance가 크기 때문에 방전을 일으키는데 필요한 전력량이 많을 수 밖에 없다. 특히, 밝은 색을 나타낸다는 것은 위에서 언급한
subfield 단계마다 cell 내의 기체들이 빵빵 터진다는 것(방전)을 말한다. 그런데 그 방전을 위해서는 전압을 걸어줘야 한다. 즉,
밝은 색의 발현을 위해서는 전압이 더 많이 들 수 밖에 없다.  
다만 이 말은 화면을 어둡게 하면 전력 소모를 줄일 수 있다는 말도 된다. 그렇다고 전기 아낀다고 어두침침하고 화질이 떨어지는 화면을 계속
보기는 좀...

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=12)]

#### 1.3.3. 발열이 심하다. ¶

전력량이라는게 곧 열 발생량과 상관관계가 있기 때문이다. 부가적으로 열을 식히기 위해 제품에 팬을 달아 소음이 유발되기도 한다.

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=13)]

#### 1.3.4. 번인 현상이 있다. ¶

가스 튜브를 오래 쓰면 노화하여 밝기가 떨어지고 반응도 잘 안 된다. 문제는 패널 부분 및 픽셀마다 노화가 다르게 발생하기 때문에 전체적으로
보기 안 좋아지는 것. 좀 오래 쓴 PDP TV를 가진 사람 중 눈썰미가 좋은 사람은 화면에서 다른 채널의 로고를 볼 수도 있을 것이다.  
물론 LCD도 번인이 없지는 않지만, PDP보다는 훨씬 덜하다. 어지간한 싸구려 또는 불량품을 쓰거나, 24시간 특정한 내용을 틀지 않는
이상 크게 걱정할 수준은 아니다.

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=14)]

#### 1.3.5. 수명이 상대적으로 짧다. ¶

번인 현상뿐만 아니라 인광체로 사용하는 물질들의 수명이 상대적으로 짧은 편이다. <del>어째 첫 번째만 빼면 단점들이
[AMOLED](AMOLED.md)랑 **매우** 비슷하다.</del> 그나마 현재는 초기에 비해 많이 개선된 편.

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=15)]

#### 1.3.6. 고밀도/고해상도 제작이 어렵다 ¶

가스튜브의 소형화가 어렵기 때문에, 고밀도/고해상도 구현이 근본적으로 어렵다. LCD 와 PDP 가 경쟁하던 시절에 일찌감치 40인치
Full HD LCD TV가 나왔고, PC용 모니터는 24인치 크기로도 Full HD 를 지원하는 모니터가 나왔다.`[2]` 하지만, PDP
로 Full HD를 구현하기 위해서는 50인치급은 되어야 했고, 그 이하급은 해상도가 낮았다. 나중에 40인치급 Full HD PDP 도
나오긴 했지만, 이미 LCD 와의 경쟁에서 뒤쳐진 이후였다. 결국 국내에는 40인치급 Full HD PDP가 아예 나오지 않았다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=16)]

### 1.4. 특징 ¶

위의 장점으로 인해 스포츠 중계 등 움직임이 많은 영상물을 보는데 적합하다는 평가이다. LCD가 오버드라이브니 120Hz, 240Hz
스캔이니 하는 식으로 반응속도를 늘리려 애를 쓰고 있지만 아직도 **그나마** 좀 나아진 정도이지 PDP와 직접 비교하면
[넘사벽](%EB%84%98%EC%82%AC%EB%B2%BD.md)의 차이가 있다.

  

일반인들에게는 PDP TV를 통해 잘 알려져 있지만 기술 자체는 나온지 상당히 오래되었다. 물론 현재와 비할만한 수준은 아니었다. 90년대
초반 나온 노트북에도 PDP를 이용한 모델이 소수 있다. 당시 쓰인 LCD보다 화질은 좋았지만 단색이고 전기를 많이 먹는 단점이 있어서 많이
쓰이지는 않았다.

  

LCD와 [AMOLED](AMOLED.md)에 대한 관심 때문에 인기는 없는 편이다. 따지고 보면 LCD보다 화질면에서 앞서지만
대기업들의 LCD위주 마케팅이 PDP를 사양길에 접어들게 했다고 할 수 있다. 보통 사람들 대부분이 LCD가 PDP보다 화질도 좋고 전력도
덜 먹는 개념있는 패널이라고 생각하고 있다.`[3]`

  

PDP의 특징은 빠른 반응속도인 반면 위의 단점에도 언급되다시피 검은색 표현이 나쁘며, LCD의 최대 밝기가 꽤 밝아서 상대적으로 LCD가
PDP보다 더 선명해 보인다.`[4]` 반면 빠른 반응속도는 대부분의 소비자가 LCD의 잔상이나 PDP의 번인 현상 자체를 경험하지 못한다고
느낄만큼 둔감한지라 별 강점이 되지 못하는면도 있다.<del>게다가 크기도 장점이 못되는게 어짜피 50인치 이상의 크기는 살사람도 별로
없다.</del>

  

하지만 [3D 디스플레이](3D%20%EB%94%94%EC%8A%A4%ED%94%8C%EB%A0%88%EC%9D%B4.md)에서는
[AMOLED](AMOLED.md)는 해당 항목에서도 볼 수 있듯이 대형화에 어려움이 있고 LCD는 전술되어 있듯이 반응속도에서
넘사벽인지라 인기가 꽤 있다.`[5]` 또한 저화질 저가 대형 제품 라인업은 꽤 갖춰져 있어서 공공장소에서 이용하는 경우도 자주 볼 수
있다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=17)]

### 1.5. 황혼의 시대 ¶

![display.png](//rv.wkcdn.net/http://rigvedawiki.net/r1/pds/display.png)

[PNG image (36.94 KB)]

  

![PDP.jpg](//rv.wkcdn.net/http://rigvedawiki.net/r1/pds/PDP.jpg)

[JPG image (38.94 KB)]

  

2000년대 들어 디스플레이 산업의 세대 교체로 [CRT](CRT.md)를 대체하는 차세대 디스플레이로 [LCD](LCD.md)와
치열한 경쟁을 벌였다. PDP가 [LCD](LCD.md)보다 시장 점유율을 앞선적도 있으나 2007년경 물량 기준으로
[LCD](LCD.md)에게 역전되고 이후 [TV](TV.md)등 디스플레이 산업의 주류가 LCD로 넘어가게 된다. 결국
2007년 [필립스가 PDP TV 산업 철수](http://news.naver.com/main/read.nhn?mode=LSD&mid=sec
&sid1=101&oid=015&aid=0000950695)하고 2008년 [히타치와 파이오니아가 PDP TV 산업 철수](http://ne
ws.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=105&oid=031&aid=0000144279)하면
서 2010년 [파나소닉](%ED%8C%8C%EB%82%98%EC%86%8C%EB%8B%89.md),
[삼성SDI](%EC%82%BC%EC%84%B1SDI.md), [LG전자](LG%EC%A0%84%EC%9E%90.md)가 시장
점유율의 90% 이상을 차지하였다.

  

PDP 미래가 사실상 저물어 가며 시장 규모 자체가 **역성장**하는 상태에서 주요 생산업체들도 매우 불안한 행보를 보이고 있다. 기존 1위
업체인 [파나소닉](%ED%8C%8C%EB%82%98%EC%86%8C%EB%8B%89.md)은 2012년들어 점유율 1위를
[삼성SDI](%EC%82%BC%EC%84%B1SDI.md)에 빼앗기고 대규모 적자로 회사 의 생존을 걱정하는 처지라 [PDP
연구개발을 중단](http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=27
7&aid=0002899902)하는 등 안습한 처지. [삼성SDI](%EC%82%BC%EC%84%B1SDI.md)와
[LG전자](LG%EC%A0%84%EC%9E%90.md)는 시장 점유율을 늘리고 있지만 두회사 모두 [LCD](LCD.md)가
중심인데다가 차세대 디스플레이로 [AMOLED](AMOLED.md)에 주력하려는 모습을 보이며 [사실상 PDP에 대한 투자를 중단](h
ttp://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=018&aid=00026
67241)하고 있다. 결국 2013년 10월 9일
[파나소닉](%ED%8C%8C%EB%82%98%EC%86%8C%EB%8B%89.md)이 [PDP 시장에서 철수](http://news.
naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=277&aid=0003102736) 한다는 
[기사들](http://news.naver.com/main/read.nhn?mode=LSD&mid=sec&sid1=101&oid=015&ai
d=0002961273)이 나왔다. 삼성과 LG도 시장이 어느 정도 유지될 때까지만 생산을 이어간다고 하는 중으로 수년 내에 PDP는 결국
사멸할 가능성이 크다.`[6]` 결국 마지막 주요 업체들인 삼성과 LG가 [2014년내 PDP 관련 생산시설 가동을 중지한다](http://
news.naver.com/main/read.nhn?mode=LSD&mid=shm&sid1=105&oid=366&aid=0000202448)
고 발표함으로써 PDP의 시대의 종말이 공식적으로 선언된 셈이 되었다.`[7]`

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=18)]

## 2. 프로그램 데이터 프로세서 ¶

![http://upload.wikimedia.org/wikipedia/commons/thumb/3/35/PDP-10_1090.jpg
/640px-PDP-
10_1090.jpg](http://upload.wikimedia.org/wikipedia/commons/thumb/3/35/PDP-
10_1090.jpg/640px-PDP-10_1090.jpg)

[[JPG external
image]](http://upload.wikimedia.org/wikipedia/commons/thumb/3/35/PDP-
10_1090.jpg/640px-PDP-10_1090.jpg)

  
DEC의 PDP 10.

  

1960년대 있었던 [미니 컴퓨터](%EB%AF%B8%EB%8B%88%20%EC%BB%B4%ED%93%A8%ED%84%B0.md)의
종류중 하나. 정식 명칭은 프로그램 데이터 프로세서(Programmed Data Processor) 이다.

  

얼핏 "미니컴퓨터"라는 말만 듣고 위의 사진을 보면 저 [크고아름다운](%ED%81%AC%EA%B3%A0%20%EC%95%84%EB%A6%84%EB%8B%A4%EC%9A%B4.md)크기에 당황하는
경우가 있지만, 미니컴퓨터의 "미니"는 작아서 미니...가 아니라 어디까지나 대형 컴퓨터와 **마이크로** 컴퓨터 사이에 있는 컴퓨터이기
때문에 저런 이름이 붙어 있는 것이다. 지금도 산업용, 학술용으로는 여전히 미니 컴퓨터가 나오고 있다. 덧붙히자면, 이 물건이 나왔을 당시엔
미니 컴퓨터란 단어조차 없었다.

  

당시 컴퓨터는 크고 값비싼 존재란 인식 때문에 PDP라는 명칭을 사용하였다.

  

PDP는 기존에 짜여진 논리 모듈을 활용하여 새롭게 프로그램이 가능한 데이터 프로세서(Programmable Data
Processor)`[8]`를 만들 수 있는 컴퓨터로,
[메인프레임](%EB%A9%94%EC%9D%B8%ED%94%84%EB%A0%88%EC%9E%84.md)을 도입할 수 없는 시장을 주
목표로 삼아 빠르게 시장에 퍼져나갔다.

  

지금이야 누구든지 약간의 프로그래밍 지식만 있으면 간단한 계산기쯤은 만들 수 있지만, 이 시기는 그렇지가 않았다. 하드웨어와 소프트웨어가
일심동체인 시절이었기 때문에, 컴퓨터 소비자가 컴퓨터를 발주하면 제조자가 소비자의 요구에 맞춰서 하드웨어도 만들고 그에 따라 소프트웨어도
만들어 탑재한 뒤 판매하는 것이 상례였다. 그런데 PDP의 등장으로 기존에 짜여진 몇 개의 요소들을 활용하여 자신 스스로 운영체제도 만들고
그 위에서 프로그램도 만들 수 있으니 엄청난 각광을 받은 것이다. 즉, 컴퓨터의 새로운 지평을 열 수 있는, 컴퓨터를 학술적으로 연구할 수
있는 길이 열린 것이다. PDP 이전에는 [IBM](IBM.md)이나 [델](%EB%8D%B8.md) 연구소,
[HP](HP.md) 같은 기업에서만 상업적 목적으로 컴퓨터가 연구되었던 것이다.

  

PDP는 수많은 대학이나 민간 연구기관으로 퍼져나갔으며, 특히 [MIT](MIT.md) 인공지능연구소에서 엄청난 발전을 하게 된다.
[UNIX](UNIX.md)의 원형도 PDP에서 탄생하였고, 이후 [GNU](GNU.md)의 창시자 [리처드스톨만](%EB%A6%AC%EC%B2%98%EB%93%9C%20%EC%8A%A4%ED%86%A8%EB%A7%8C.md)도 이 컴퓨터의
연구에서 GNU 정신을 기초하였다.

  

PDP가 한 시대를 풍미한 컴퓨터인 것은 사실이나 시장에서 지배적인 위치에 있었던 것은 아니었다. 왜냐하면 IBM과 같은 기업의 컴퓨터보단
절대적으로 성능이 떨어졌기 때문. 또 DEC에서 자체적으로 제공하는 운영체제의 성능도 정말 구린 것이었기 때문에 정부 기관이나 [록히드마틴](%EB%A1%9D%ED%9E%88%EB%93%9C%20%EB%A7%88%ED%8B%B4.md), [아메리칸항공](%EC%95%84%EB%A9%94%EB%A6%AC%EC%B9%B8%20%ED%95%AD%EA%B3%B5.md),
[보잉](%EB%B3%B4%EC%9E%89.md) 등과 같은 신형 컴퓨터를 마구잡이로 사들이는 기업들은 PDP를 외면했다.`[9]`

  

![http://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/PDP-1.jpg/640px-
PDP-1.jpg](http://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/PDP-1.jpg
/640px-PDP-1.jpg)

[[JPG external
image]](http://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/PDP-1.jpg
/640px-PDP-1.jpg)

  
초기 제품인 PDP 1. **<del>무려 [모니터](%EB%AA%A8%EB%8B%88%ED%84%B0.md)가
달려있다!</del>**`[10]`

  

여담으로 [빌 게이츠](%EB%B9%8C%20%EA%B2%8C%EC%9D%B4%EC%B8%A0.md)가 이 컴퓨터(?)와 인연이 많은데
학창 시절 C 큐브드 사의 PDP 10을 문제가 발생할 때마다 결함기록을 써준다는 조건 하에 허락을 받아 자신의 그룹 임원들과 함께
사용하였고 이후 회사 암호장치를 풀다가 **시스템을 고장내버려** 쫓겨나기도 했고`[11]` 고등학교 시절 대학 도서관 컴퓨터실에서 또
PDP 10을 만나버려 직원들이 소방 훈련에 나간 사이 자신의 프로그램을 작성해서 사이버 네트로 연결된 시스템에 보냈다가 돌아온 직원에게
걸렸고 사이버 네트에 연결돼있던 시스템들이 **또 고장나버려** 잠시 동안이었지만 감옥 신세도 져야 했었다. <del>하지만 당시 사람들은
미래에 그와 그의 친구들이 세웠던
[회사](%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%86%8C%ED%94%84%ED%8A%B8.md)가
컴퓨터 역사에 한 획을 그음을 넘어 세계를 정복하게 될 줄은 꿈에도 모르고 있었다.</del> <del>[그런데 그것이 실제로 일어났습니다]
(/wiki/%EA%B7%B8%EB%9F%B0%EB%8D%B0%20%EA%B7%B8%EA%B2%83%EC%9D%B4%20%EC%8B%A4%E
C%A0%9C%EB%A1%9C%20%EC%9D%BC%EC%96%B4%EB%82%AC%EC%8A%B5%EB%8B%88%EB%8B%A4).</d
el>

  

[[edit](http://rigvedawiki.net/r1/wiki.php/PDP?action=edit&section=19)]

## 3. 게임 유튜버 [PewDiePie](PewDiePie.md)의 약자 ¶

**P**ew**D**ie**P**ie.  
[PewDiePie](PewDiePie.md) 항목 참조.

  

`\----`

  * `[1]` 전등을 다른 위치에서 본다고 다른 색이 되지 않는 것과 같은 이치다.
  * `[2]` 심지어 2013년 기준으로는 Full HD LCD 가 탑재된 5인치 스마트폰마저 등장했다. 거기에 더해서 27인치 기준으로 WQHD(2560×1440), 더 큰 모니터는 **QFHD (3840×2160)**까지 지원한다.
  * `[3]` 현재 PDP TV는 전력 소모가 많이 줄어서 이전의 CCFL 백라이트를 쓰는 LCD TV와 비슷한 수준이 되었으나, LCD TV의 백라이트가 이미 [LED](LED.md)로 넘어간 지라 실제 차이가 다시 꽤 벌어진 상태다.
  * `[4]` 특히 밝은 매장에서는 TV 밝기를 마구 올리기 때문에 같이 놓고 비교하면 차이가 꽤 크게 보인다.
  * `[5]` LCD TV는 반응 속도로 인한 문제를 감추기 위해 중간중간 백라이트를 꺼서 변경 도중의 화면을 안 보이게 하는 경우가 많아 밝기가 떨어진다.
  * `[6]` 고가 시장은 [LCD](LCD.md), [AMOLED](AMOLED.md)에 빼앗기고 개발도상국 저가 시장은 [CRT](CRT.md)가 건재하다.
  * `[7]` 단, 타업체에 의한 생산은 2017년 까지 소규모로 이어질 전망이다.
  * `[8]` 쉽게 말해서 과정을 처리하는 순서 즉 프로그램
  * `[9]` 사실 DEC 계열의 컴퓨터는 호환성이 없다는 더 큰 문제가 있었다. 쉽게 말해서 PDP-10에서 작성해 둔 프로그램들은 PDP-11에서는 쓰레기가 되는 상황이 실제로 발생했다. 그리고 나아가 DEC는 신제품이 나오면 구제품을 단종하고 그에 대한 사후 지원 업무를 제공하지 않았다. 리처드 스톨만이 잠시 좌절하는 것도 10에서 11로 넘어가며 자신이 만든 프로그램들이 쓸모 없게 된 때이다. 이 시기 스톨만 뿐만 아니라 수많은 컴퓨터 공학자(순수하게 학술적으로만 컴퓨터를 연구하던 사람들. 쉽게 말해서 덕후들.)이 좌절하고 기업으로 가게 되는 계기가 된다. 컴퓨터를 연구하던 교수들의 엄청난 수가 IBM이나 미 국방성 컴퓨터 연구소로 빠져나가 사회 문제가 될 정도니 말 다한 것.
  * `[10]` 이미 이 시기에는 위와 같은 모니터 사용이 널리 퍼져 있었다. 그 당시에는 '콘솔'이라 불렀다.
  * `[11]` 쫓겨날 때 빌 게이츠 혼자만 쫓겨났고 그 친구들은 결함 보고서 작성에 매달려야 했다.

