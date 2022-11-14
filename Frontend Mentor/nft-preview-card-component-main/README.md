# Frontend Mentor - NFT preview card component

![Design preview for the NFT preview card component coding challenge](./design/desktop-preview.jpg)

## Troblue Shooting 

(1) 22.11.13.
- align-items와 align-content 비교

- span안에 들어있는 img와 text를 정리하려면 그것을 감싸고 있는 부모요소가 아니라 해당 span 요소에 align-items: center를 해줘야 함

- img의 hover 적용방법

- 커서 모양 바꾸기 / solution 받은거 보고 업데이트 

##

(2) 22.11.14.
- hover 커서 update > a tag 이용해서 색 변경해도 괜찮을 듯

- active에서 img 변경 기능 update : img의 hover가 아니라 아이콘의 opacity 변경
 1. img-wrapper 만들어서 부모요소 지정
 2. 이미지의 width와 height 고정
 3. 이미지를 원하는 배경색으로 바꾸고 아이콘을 위에 놓는 것이 아니라, 아이콘의 background의 색상을 변경하고, 이를 opacity를 주는 것.
