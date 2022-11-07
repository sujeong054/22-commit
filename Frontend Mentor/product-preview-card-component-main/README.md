# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

## Trouble Shooting / Solution

- 웹의 가운데에 놓기
  
  body {
  display: grid;
  place-items: center;
  min-height: 100vh;
}


## Advice

  min-height : 100vh 는 중요하다. body를 브라우저 viewport 만큼 크게 만들어주기 때문. 
  지정하지 않으면 자식요소의 공간만을 차지한다. 항상 지정할 것!

- Semantic tag를 더 많이 사용할 것. main element 를 사용해서 주요한 landmark를 지정해야 함.

- title 을 지정해라.

  <span> 와 무분별한 <div> 보다는 <p> 와 <h1> 을 이용해 한 눈에 알 수 있도록 할 것.
  ![image](https://user-images.githubusercontent.com/111235507/200340693-da769f82-7f75-4367-992b-4e2a6d235b52.png)
