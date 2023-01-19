<a href="https://stakingcrypto.info/ko/coins/wemix/logo"><img src="https://stakingcrypto.info/static/assets/coins/wemix-logo.png" width="100" height="100" title="WEMIX logo" alt="WEMIX logo"></a>
# Blockchain-Project-WEMEX
## 프로젝트 소개
'WEMEX'는 WEMIX + DEX를 조합한 약어로 WEMIX 네트워크에서 사용되는 토큰들의 스왑 및 DeFi 서비스를 위한 DEX 프로젝트입니다.

WEMIX에는 다양한 게임들이 있습니다. 그중 저희는 P2E(Play to Earn)게임에 초점을 맞췄습니다. 토큰의 관리 및 매매를 중계하는 거래소인 DEX 프로젝트 또한 필연적인 프로젝트라고 생각하였습니다.

WEMIX 생태계에서 토큰을 사용하는 사용자들에게 더 간편한 거래 서비스를 제공하기 위한 프로젝트입니다.

자세한 사항은 [Notion](https://www.notion.so/codestates/WEMEX-f8f2d9d98e164743b9efc67870884a52) 링크를 참고해주세요

## 목차
  - [설치 방법](#설치-방법)
  - [개발 스택](#개발-스택-통합)
  - [구현 목록](#구현-목록)
  - [결과물](#결과물)


## 설치 방법
```go
  go mod tidy
```
## 개발 스택 (통합)

[Collaboration Tool]

<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">

[Blockchain]

<img src="https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white"> <img src="https://img.shields.io/badge/Truffle-5E464D?style=for-the-badge&logo=truffle&logoColor=white"> <img src="https://img.shields.io/badge/Ganache-E4A663?style=for-the-badge&logo=ganache&logoColor=white"> 

[Daemon]

<img src="https://img.shields.io/badge/Wemix Network-CD4CFC?style=for-the-badge&logo=wemix&logoColor=white"> <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=black"> <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">


## 결과물

### DeFi
1. 교환 (Swap): 바꿀 토큰 (input, output) 
2. 풀에 유동성 추가(add liquidity) 
3. 풀에 유동성 제거(remove liquidity)
4. 리워드 지급
### Daemon
1. 위믹스 네트워크에 블록 정보 요청
2. WEMEX 서비스에서 배포한 컨트랙트들의 주소로 블록 필터링
3. 필터링된 블록정보를 DB에 저장
4. 블록의 적재된 트랙잭션들의 정보도 DB에 저장



