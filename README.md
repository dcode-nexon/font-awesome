# 리액트에 폰트어썸 웹폰트 아이콘 적용

[폰트어썸 사이트 이동](https://fontawesome.com/)</br>

- 폰트어썸 웹폰트 아이콘 사용을 위한 설치 패키지

```js
npm i --save @fortawesome/fontawesome-svg-core  @fortawesome/free-solid-svg-icons @fortawesome/free-regular-svg-icons @fortawesome/free-brands-svg-icons @fortawesome/react-fontawesome@latest
```

- 컴포넌트에 원하는 웹폰트 아이콘 import

```js
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome';
import { faHouse } from '@fortawesome/free-solid-svg-icons';
```

- JSX리턴문 안쪽에 컴포넌트 호출

```js
<FontAwesomeIcon icon={faHouse} />
```
