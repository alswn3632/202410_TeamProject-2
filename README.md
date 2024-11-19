# 😊 Java 단기 팀 프로젝트로 부루마블 게임을 구현했습니다! 
## 🔧 Stack
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)

## 🖥️ Main Image
![b_main](https://github.com/user-attachments/assets/6d5620c5-ecea-42e6-8f0d-bafe1843f598)

## 👨‍👩‍👧‍👦 Develop
- 개발기간<br>
2024.10.17 - 2024.10.18

- 팀원<br>
차민주, 정슬빛, 지윤희, 최수경

## 📖 Description  
- 이번 프로젝트는 부루마블 게임을 구현해보았습니다.
- 저는 조장으로, Controller 제작을 맡아 게임 로직을 구현했습니다. 
- 플레이어를 생성하고 주사위 굴리기, 이벤트 발생 등을 콘솔창에서 시각적으로 표현했습니다.
- 객체는 플레이어, 호텔, 땅, 황금열쇠 등으로 나뉘어져 있으며 게임 준비와 진행에 맞춰 사용됩니다.

## ⭐ Main Feature
### 게임 진행 화면 구현
- 콘솔창에 게임 진행 과정을 출력하였습니다. 플레이어가 이동하거나 호텔을 구입하면 표시됩니다.
- 앞으로 나열될 이벤트 설명에서 확인할 수 있습니다. 

### 부루마블 이벤트 구현
- 전체적으로 각각의 사용자의 차례가 되면 주사위를 굴려 이동합니다. <br>이동한 위치를 계산하고 그 땅의 타입을 받아 어떤 이벤트를 발생시킬지 나뉩니다. 
- 호텔 구입, 사용료 지불, 황금열쇠 이벤트, 세계여행 이벤트 등 여러 이벤트가 존재합니다.

![b_buy](https://github.com/user-attachments/assets/11719582-ab47-4e3e-97c8-7e05009eae88)
![b_event](https://github.com/user-attachments/assets/80a00a5f-2efa-4ab5-a100-f89ca08d80b7)
![b_travel](https://github.com/user-attachments/assets/cf854deb-7b7b-40f9-bfcf-873784a906f9)

### 돈 지불 처리
![b_pay2](https://github.com/user-attachments/assets/12fc8c6a-f80d-4045-bc37-8540ea5e6330)
- 부루마블 특성상 돈을 지불하고 받는 과정이 매번 존재합니다. 은행 시스템 처럼 플레이어가 가진 현금을 확인하고, 지불할 금액을 가지고 있을 경우에는 금액을 차감시킵니다. 그 다음 상대방에게 지불합니다.
- 만약 가진 돈이 부족하다면 가지고 있는 호텔을 매각하거나 파산 절차를 진행합니다. 파산하게 된다면 플레이어의 호텔을 전부 팔아 만든 최대의 금액을 상대에게 지불합니다. 
- 이 과정이 매끄럽게 진행되도록 지불하는 모든 과정에 1. 돈을 낼 수 있는지 검사 2. 매각/파산처리의 두 메서드를 통과하도록 만들었습니다. 파라미터로 플레이어 객체와 지불할 돈의 양만 입력하면 자동으로 진행되도록 구현했습니다. 

## ❤️ Thank you!
읽어주셔서 감사합니다. 이번 프로젝트를 진행하면서 앞으로 어떻게 해야할지에 대해 느낀점이 많습니다. 팀으로 같이 작업하는 만큼 객체와 그의 변수, 메서드에 대해 세세하게 회의하고 정의내려야하는 중요함을 느꼈습니다. 충분한 회의를 통해 설계했음에도 중간 중간 변경사항이 생겨 진행을 멈추고 회의해야할 때가 있었습니다. 어떻게 사용될 것인지에 대한 구체적인 설계가 필요하다고 느꼈습니다. 

