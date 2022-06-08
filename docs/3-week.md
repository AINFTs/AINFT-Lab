# 3주차

## 1. The Crypto Anarchist Manifesto - 박범석님, 전선영님

- [The Crypto Anarchist Manifesto](https://groups.csail.mit.edu/mac/classes/6.805/articles/crypto/cypherpunks/may-crypto-manifesto.html)
- [crypto-will-change-value-nfts-will](https://andrewsteinwold.substack.com/p/crypto-will-change-value-nfts-will)

## 2. 이터니티 소개 - 박지은님

- [펄스나인 홈페이지](https://www.pulse9.net)
- [펄스나인 유튜브](https://www.youtube.com/c/PULSE9_Inc)
- [이터니티](https://planet-aiia.com/)
- [Discord](https://discord.com/invite/9hrrUMfzpN)

## 3. AINFT Chatbot for yeoreum - 장래영 랩짱

지난 시간에는 AINFT Chatbot Builder를 통해, No code 형식으로 만들어지는 chatbot을 봤다면 이번에는 이터니티 멤버인 yeoreum을 위한 AINFT Chatbot을 만드는 법을 소개 시켜 드립니다.


### Q. 그런데 왜 Discord Bot이 중요한가요?

AINFT를 구매한 사용자들이 NFT를 사용 할 수 있는 공간이나 방법이 제공되어야, 해당 NFT의 가치가 높아집니다. NFT 프로젝트의 경우 대부분 Discord 커뮤니티를 가지고 있고, NFT 구매희망자 또는 구매자들은 해당 커뮤니티에 가입 되어 있는 경우가 대다수 일 겁니다. Discord가 AINFT의 첫번째 사용 공간으로 되는게 자연스럽고, 또한 Discord 특성상 만들기도 상대적으로 편합니다.

실제로 [Bug City](https://discord.gg/mcEczay4VQ) 프로젝트의 경우, Discord Bot을 이용해 discord 상에 text 기반의 메타버스를 만들었고, [Discord에서 하는 활동을 통해 내부 Token을 받고 이걸로 Bug City NFT를 살 수 있는](https://absorbed-boat-ff3.notion.site/2c7cbc1e7dbf46cabe388ec6cc341594) 토큰이코노미를 만들어 놨습니다. 잘 설계된 구조와 이를 만들어주는 Discord Bot을 통해 불과 1,700명만 가지고 [많은 사용자 컨텐츠를 만들어 내고](https://twitter.com/hashtag/bugcity?src=hashtag_click&f=live) 있습니다.

### 설명

[AINFTs/discord-bot](https://github.com/AINFTs/discord-bot) 프로젝트를 fork해서 Discord Bot을 만들었습니다.

Discord Bot API 중 가장 많이 사용하는 /command 기능과 /trigger 기능을 제공합니다.

- **Slash Command:** Discord 상에서 '/'를 누르면 나오는 command 명령어를 만들 수 있습니다. 해당 버전에서는 `/set-channel name: 'General'` 과 같은 형식의 명령어가 구현되어 있습니다.
- **Trigger Handler:** 사용자가 Discord에 Message를 남길 때, 실행이 됩니다. Trigger는 유저가 `특정 채널`에 보낸 보낸 메세지에 `특정 문구`가 있을 때, 동작을 합니다.

기본 설정은 아래와 같이 설정 되어 있습니다.
- keywords: `ainft`
- prefixes: `yeoreum`
- suffixes: `?`
예를 들어, `?`로 끝나는 문장에 Trigger가 됩니다.

### Discord App

만든 앱을 Discord에 등록하고, 초대링크를 통해 서버에 추가해야 Bot을 사용 할 수 있습니다. 자세한 설명은 여기에서, [개발자 앱 등록하기](https://blog.naver.com/wpdus2694/221192640522)

자세한 설명이나 코드는 아래 프로젝트에 가서 보시면 됩니다.
- [Laeyoung/discord-bot-for-yeoreum](https://github.com/Laeyoung/discord-bot-for-yeoreum)

## 4. 테이블 별 자기소개 및 친해지기

중간 휴식 후, 테이블 별로 자기소개 및 친해지기 시간을 15분간 가지겠습니다.

## 5. Team Building 및 프로젝트 선정 방식 공지
다음 주부터 프로젝트 선정과 팀빌딩을 시작합니다. 프로젝트 선정과 팀빌딩은 해커톤 방식으로 진행됩니다.

1. 프로젝트에 대한 아이디어가 있으신 분이 프로젝트에 대한 설명이 담긴 기획 Proposal을 Discord에 업로드
2. 올라온 프로젝트들을 보고 참여하고 싶은 분이 해당 프로젝트에 지원
3. 프로젝트 별 최대 인원은 4명이고, 인원이 너무 많은 경우 Proposal을 올린 분인 함께 할 팀원을 선정
4. 프로젝트에 참여 할 사람이 없거나 부족한 경우, 해당 프로젝트는 진행이 안되고 다른 프로젝트에 팀원으로 참여
5. 만약 프로젝트에 속하지 못한 랩원이 생기면, 간단한 버전으로 1~4을 퀵하게 진행

