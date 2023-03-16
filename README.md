# Responsive_Crossbrowsing_Test

**반응형 웹과 크로스 브라우징에 대해 공부 후 간단하게 구현**

## 반응형 웹

```
html의 meta 태그 - 사용자의 보이는 영역인 뷰포트의 크기 지정 (디폴트값 content="width=device-width, initial-scale=1.0")
디폴트값: 뷰포트의 너비는 device의 너비에 따라 지정

grid 레이아웃에서 auto-fit 또는 auto-fill, minmax를 이용하여 창 크기에 따른 grid 레이아웃 형태의 변화
(ex. repeat(auto-fit, minmax(150px,1fr));) 

@media 쿼리를 활용하여 min-width과 max-width를 지정해 디바이스에 따른 css 각각 구현가능
```

## 크로스 브라우징

**브라우저별 지원가능여부 - https://caniuse.com/ 참고**

```
@media 쿼리를 활용하여 IE 브라우저에서 동작할 css 따로 구현
(IE 브라우저는 grid 속성을 지원하지 않기 때문)

브라우저 환경에 따라 속성을 적용하기 위해 vender prefix 요구할 수 있음
```