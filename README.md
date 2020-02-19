# BlockChain based Treasure Hunt Game ;Founders-Samsung Hackathon
:Prepare Hackathon:

## Summary

![image-20200214144756532](image/image-20200214144756532.png)

##  How to use

just **git clone** or **download zip file** and import project at Android Studio

```latex
  *Requremnts*
  - andrioid developer mode
  - ASTC usable android device
  - device must be connected when Install_bomul-Android-Shipping-armv7-es2.bat is excuting
```



## Tech Stack

- JAVA
- Android Studio

## Tech Demo Video
[youtube link](https://youtu.be/tjttqUkZST8)


## Role 

- 김연욱[PL] : DApp developer : [깃허브](https://github.com/yeonuk44)
- 송민재 : Demo game engineer :  [깃허브](https://github.com/hsu-201458085)
- 유지원 : General designer : [깃허브](https://github.com/AshleyRyu)
- 조은희 : Architecture planner 
- 오동규 : Business planner 



## 기획팀 to do list

- [x] 사업계획서
- [x] PPT
- [x] BM 설계
- [x] 재무재표
- [x] Logo design
- [x] 영상 편집
- [x] Team logo design

## 사업계획서

### 1. Problem & Solution

‘블록체인’이라는 기술이 이슈로 급부상한지 약 4년의 시간이 흘렀다. 그러나 여전히 대중은 블록체인의 개념 정도만 알고 있지, 어디에 사용되는 기술인지, 이를 활용하여 무엇을 할 수 있는지는 모르고 있는 경우가 많다. 블록체인 관련 스타트업뿐 아니라 대기업 역시 산업에 적극적으로 뛰어들고 있다. 이러한 다각적인 노력에도, 여전히 블록체인은 생소하다. 
본 팀은 이러한 현상에 집중하였고, 유저 친화적인 채널과 가벼운 콘텐츠의 부재를 원인으로 꼽았다. 게임은 접근성 제고를 위해 가장 좋은 콘텐츠라 판단하였다. 블록체인 기술은 보상시스템의 투명성을 높이고, 초기 신뢰형성기간을 단축할 것을 기대한다. SDK의 활용은 월렛 및 키관리 등 유저사용의 제약요소를 해소할 수 있을 것이라 판단하였다.
현황을 살펴보면, 삼성은 블록체인 산업을 육성하고자 ‘삼성 블록체인 월렛’을 만들었으며, 여기에 다양한 DApp들을 출시하였다. 살펴본 결과, 블록체인 기술 상용화를 위해 다수의 게임Dapp이 서비스 중에 있었다. 그러나 대부분의 게임Dapp은 실적이 좋지 못한 편이다. 특히, 게임물관리 위원회의 통과를 받은 게임은 전무하며, 관련 법규 역시 애매한 실정이다. 외부적 요인 이외에도, 콘텐츠 자체가 사용자들에게 매력적으로 다가가지 못하고 있다. 본 팀은 이와 관련된 이유들을 분석하여, 다양한 개선점들을 보완하여 본 서비스를 기획하였다.

### 2. Idea 소개
1) 게임 방법
겟챠 크레용은 어린시절 소풍 가서 하던 ‘보물찾기’ 게임에서 아이디어를 착안하였다. 그러나 실제의 공간이 아닌 가상 공간을 활용하고자 하며, 보물을 기프티콘 형태로 제공하고자 한다. 사용자는 본 서비스에 접속한 후, 본인이 원하는 방(치킨방, 커피방, 등)을 만들거나 이미 만들어진 방에 들어갈 수 있다. 게임이 시작하기 전에 사용자들은 동일한 양의 코인을 참가비로 지불하고 게임을 진행한다. 보물의 위치는 지도에서 랜덤 형성되며, 이를 가장 먼저 발견한 사용자가 게임을 시작하기 전에 방안에 예치해둔 모든 코인을 기프티콘 형태로 지급 받는다.
2) 강점 및 차별점
기존의 블록체인 게임들은 코인을 입금 및 분배하는데 있어서 다양한 프로세스를 거쳐야 하는 문제점이 있다. 그러나 본 게임은 SDK를 활용하여 이러한 복잡한 프로세스를 하나의 과정으로 압축하였기 때문에 이와 관련된 플랫폼을 따로 만들 필요가 없다. 즉, 유저 친화적인 프로세스 간소화가 장점이라 할 수 있다. 또한, 갤럭시 S10 이후 출시된 삼성 스마트폰을 이용하는 사람들 모두가 본 서비스를 쉽게 이용할 수 있기 때문에 디바이스를 소지하고 있기만 하면 접근성이 용이하다. 현재 대부분의 블록체인 게임들은 높은 그래픽을 구현하지 못한다. 그러나 겟챠 크레용은 3D로 구현하여 더욱 더 생동감 있는 게임을 제작하였다. 동시에, 블록체인 기술을 이용하였기 때문에 보상 체계가 투명하며, 이를 통해 사용자들로부터 신뢰 관계를 형성할 수 있고, 추가적인 마케팅 비용을 절감할 수 있다. 

### 3. 고객 및 시장 분석
1) Target Market: (초기: 8,000명 / 중기(3년): 18,500명)
TAM - 기프티콘 사용자 (약 1,700만 명)_출처 platum
SAM - DApp 사용자: 약 150만 명 (전세계)_출처: KOTRA,
국내 사용자는 이 중 약 10%일 것으로 추정_출처 : 과학기술정보통신부. (2018). 국가연구개발사업 정보 길잡이
SOM - 게임 DApp 사용자:  약 75만 명 (전세계), 국내 사용자는 이 중 약 10%일 것으로 추정.
2) 블록체인 게임DAPP 시장매력도: 별 2.5개
a) 진입장벽: 블록체인 기술을 활용한다는 측면에서는 높다고 할 수 있으나, 온라인 게임업체의 진입시 그들의 장점도 있을 것이라 판단 (Threat: Middle / 중요도: 25%)
b) 경쟁: DAPP 시장의 상위 랭크의 대부분이 게임으로 높다고 볼 수 있으나, 리워드(기프티콘)를 제공하는 형태나 게임의 퀄리티(3D)면에서 차별성이 있음. (Threat: Middle / 중요도: 25%)
c) 구매자 교섭력: 게임의 유저는 블록체인 프로그램 상에 정해진 스마트 컨트렉트에 의해 플레이하므로 교섭력은 미비 (Threat: Low / 중요도: 10%)
d) 대체재의 위협: 기존 모바일, 온라인 게임이나 유튜브, 실시간 TV앱 등 Time killing 형태의 미디어 및 SNS는 모두 해당 (Threat: Middle / 중요도: 25%)
e) 공급자 교섭력: 게임 제작자도 블록체인 하에서 조작은 불가능 하나, 고사양의 게임을 제공하고 처리해주는DB의 사용은 고려해야 함. (Threat: Low / 중요도: 15%)

### 4. Business Model - (본 팀은 B2C Business Model를 지향하며, 아래는 우선 순위 순서로 나열한 것이다. )
1) 기프티콘 업체와 파트너십을 채결하게 되면 정가보다 할인된 가격을 적용 받을 수 있으면 이 부분을 운영자금으로 활용.
2) 게임 내 캐릭터 아이템 판매: 스킨, 액세서리, 캐릭터 등 게임 자체에 영향을 주지 않는 선에서 판매 (초기보다는 사용자 수가 늘어나게 되면 자신의 캐릭터를 차별화 하고자 하는 욕구가 발현될 것을 기대)
3) 리워드 상품 본사 혹은 배너 운영을 통한 광고 수입
4) 게임 입장 시 일정 %의 수수료 수취 → 풀투게더와 같이 예치를 활용한 이자더미 분배 형태로는 바람직함

### 5. 재무 계획
1) 수익구조 
* DApp 이용자 수: 13,500 명 (초기 8,500명 / 중기 18,500명의 중간값 사용)
S10 이용자: 1,700,000명 / S20 이후 이용자 추정(3년 이내): 2,000,000명
KEYSTORE 이용 확률: 5% / 겟챠 크레용 이용 확률: 10 %
* 일 평균 거래액: 2,700만원 - 2(일 평균 유저의 플레이 횟수) * 2,000(플레이 당 평균 지불액) * 13,500(DAPP 이용자 추정치) * 0.5 (유저 중 실제 플레이율)
* BEP: 이용자 15,000명 (서비스 시작 이후 2.5년 예상) - 수익 함수: y = 2347.5x / 비용 함수: y = 27000 + 468x [y: 금액(만원) / x: 이용자 수(1,000명)]
* 연간 수익 추정: 23,475만원
a) IP비즈니스(게임 내 캐릭터 아이템 & 굿즈 판매): 3,645만원
- 270,000 (연간 사용자당 IP 매출액) * 0.01(업계 1위 대비 시장 점유율 예측) * 13,500(DAPP 이용자 추정치)
b) 기업용 기프티콘 할인: 19,440만원
0.03 (sendbee - 최대 15%까지 할인) * 27,000,000(일 평균 거래액) * 20(월 환산) * 12(연 환산)
c) 리워드 상품 본사 혹은 배너 운영를 통한 광고수입: 390만원
400(배너 노출 단가 - CPM) * 0.001(CPM을 1회 단위로 환산) * 3(운영 배너 수) * 2(유저 1인당 노출 횟수) * 6,750(일 평균 사용유저 수)*20(월 환산) * 12(연 환산)
2) 소요 자금 계획
✔ 개발비: 단기적(1~3달) 게임 개발자, UI&UX 디자이너 자문 비용
✔ 비품 기타: IMAC 1대 기준(2,500,000)*5, 책상 및 집기(7,500,000)
✔ 인건비: 3,000,000(벤처기업 평균 연봉) * 5(직원 수)
✔ 서버 운영비: 13,500(Dapp사용자 예상)*20(인당 월별 서버운영비)*12(1년 단위 환산)
✔ 광고비: 초기 홍보를 위해, 타겟층이 주로 활용할 것으로 기대되는 온라인 채널 공략(웹툰, SNS, 유튜브, 등)
3) 초기 자금 조달 계획
✔ 창업존: 기본 입주 2년 + 연장심의 통과 시 최대 1년 연장
✔ 청년추가고용장려금: 성장 유망업종, 벤처기업 등은 임직원 수 제한 없이 인건비를 지원해주는 프로그램

### 6. 향후 계획
현재 본 서비스는 하나의 게임만 존재한다. 그러나 사용자들이 증가하고 사용량이 늘어나면 서비스를 발전시킬 계획이다. 우선, IP Business를 활성화시켜, 게임 내 commerce 확대와 굿즈 판매를 통해 수익을 올릴 것이다. 또한, 보물찾기 게임뿐만 아니라 다양한 게임들을 추가하여, 사용자들의 선택성을 증가시킬 것이다. 이를 통해 서비스의 확장이 가능하여 추가 수익 창출이 가능하고, 사용자들의 만족감 또한 증대될 수 있을 것이다. 


## Unreal Project (bomul) -- Update 20/02/12
- bomul 폴더
- Unreal Engine4 기반 게임프로그램입니다.  
- 용량이 너무 커서(약 6GB) .gitignore txt로 줄인 뒤 commit합니다.
-  https://drive.google.com/drive/folders/1fTMB3LtBQH14AewwqbWYEE57RGISkAMI?usp=sharing 
    -> 구글 드라이브 전체 위치, 올리지 못한 파일들이 전부 공유되어 있습니다. 
- pull하는 방법은 제가 추후에 google Drive에 전체 폴더를 압축해서 올리면 
    압축 푸신 뒤에 그 폴더에 pull하게 되면 자동으로 merge가 되면서 
    최신 버전으로 업데이트 될 것입니다. 
- 게임을 APK형식으로 다운로드 하는 방법은 폴더 내 Android_ASTC 폴더에서 
    Install_bomul-Android-Shipping-armv7-es2.bat을 실행하시면 휴대폰에 자동으로 다운로드 됩니다.
    ### ..다운로드 요구사항 ..
          - 스마트폰 개발자모드 + USB 디버깅 허용 
          - 최신의 안드로이드 환경 (ASTC 플랫폼 형식이므로 오래된 폰은 구동 불가능)
          - Install_bomul-Android-Shipping-armv7-es2.bat 실행 시 휴대폰이 연결된 상태여야함 
            만약 연결이 안되어있을 경우 아무것도 실행되지 않음 
