# 2D 픽셀 멀티게임 (2D Pixel Multi Game)
- 각자의 직업을 선택하여 플레이어는 다른 플레이어들과 파티를 맺어 던전을 클리어하며 레벨, 스킬, 무기 등으로 성장하는 게임.

<br><br>

## 팀 이름: 창성
|구성원|김창현|한만성|민경환|김형민|안수한|
|------|-----|------|------|------|------|
|역할|기획 및 발표|개발|개발|사용에셋 정리 및 도움|개발 및 데이터처리|

<br><br>

## 개발 도구 🛠️
### - ![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white) 
### - ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34)
### - Photon Engine

<br><br>

## 개발 내용 🖥️
### 1. 채팅
<img src="https://github.com/akstjd31/2D_PixelRPG/assets/18045821/e76efd71-d2c4-4c6a-9fb7-9c96f9d50b04.png" width="600px" height="300px"><br>

### 2. 파티
<img src="https://github.com/akstjd31/2D_PixelRPG/assets/18045821/0eb9d052-40dc-4f81-babd-b9c22a6101ee.png" width="600px" height="300px"><br>

### 3. 상점
<img src="https://github.com/akstjd31/2D_PixelRPG/assets/18045821/310bedda-0d47-481a-aeeb-15b2a4b0e8ba.png" width="600px" height="300px"><br>

### 4. 인벤토리
<img src="https://github.com/akstjd31/2D_PixelRPG/assets/18045821/1b09f15f-01f7-498f-ae52-466287d4736f.png" width="600px" height="300px"><br>

### 5. 미니맵
<img src="https://github.com/akstjd31/2D_PixelRPG/assets/18045821/8b028ecd-ebc3-4234-8139-56ba79abfafc.png" width="600px" height="300px"><br>

### 6. 전투
<img src="https://github.com/akstjd31/2D_PixelRPG/assets/18045821/baf53c9e-537b-46dc-9fee-7b8a3744c362.png" width="600px" height="300px"><br>

### 7. 보스
<img src="https://github.com/akstjd31/2D_PixelRPG/assets/18045821/545da7c6-9a12-4c91-9317-ce5fbfeab7d6.png" width="600px" height="300px"><br>

<br><br>

## 개발에 쓰인 주요 기능 및 기술 📖✅
<pre><code>1. 절차적 맵 생성(Procedural Map Generation)
2. 파이어베이스 인증(FirebaseAuth)
3. 원격 프로시저 호출(Remote Procedure Calls)
4. 드래그 앤 드롭(IDragHandler, IDropHandler)
5. 충돌 체크(Physics.overlap)
6. FSM(Finite-State Machine)
</code></pre>
  
    




<br><br>

## 개발하면서 알게된 점이나 어려웠던 점 😥
1. PhotonNetwork로 생성(Instantiate)된 오브젝트가 `PhotonNetwork.Destroy` 호출로인한 제거가 될때 기존에 존재했던 Parent가 같이 제거가 되는 것을 늦게 알았음.
2. 인스펙터 창에 추가된 PhotonView가 달린 오브젝트의 `소유권(ownership)` 에 따라 처리를 다르게 해줘야 함.
3. 전체적으로 내가 짠 코드가 비효율적이고 혼란스럽다는 것을 많이 느낌. 왜 사람들이 Solid 원칙이나 디자인 패턴 등에 중시하며 코드를 작성하는지 알 것 같음..




