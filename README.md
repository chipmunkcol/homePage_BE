1. <img />
   - 웹 용량의 60%를 넘게 차지하는 img를 깊게 이해하자요
   - height: px, width: 100%, object-fit: cover;
2. 반응형 만들 때 고려해야할 unit
   - px (확장성x 브라우저 글 크기 값 조정이 안되기 때문에 사용자 선택지를 제한함)
   - %, em (부모요소 영향을 받기 때문에 구조가 많아질 수록 관리하기 힘들어짐)
   - rem (최상위 root 요소 영향을 받음 설정 안해주면 사용자 브라우저에 따라 설정됨 \_선호되는 방법)
   - rem 쓸거면 전체를 전부 rem으로! (border-radiaus 같은 곳은 px값)