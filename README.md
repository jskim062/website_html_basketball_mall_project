# website_html_basketball_mall_project


https://www.free-css.com/free-css-templates/page283/lodge 위 웹사이트에서 html 샘플을 따와 바꾸는 형태로 만들게 되었다.

![image](https://user-images.githubusercontent.com/35617378/199526699-3dc3d8e8-19bd-463a-ba67-c99afc3af290.png)

검색기능을 이용한 이미지의 위치를 유추하여 농구샵에 맞는 이미지로 교체하고 배경화면 또한 css코드를 활용하여 바꾸어 주었다.

또한 기존에 되어있지 않던 href문을 이용한 html 연결부분도 추가하여 다음페이지로 넘어갈 수 있게 하였다.
 
![image](https://user-images.githubusercontent.com/35617378/199538701-b4d04baa-4eaa-44a2-a4d1-b4f82c02c0c7.png)


이후 구글지도 api시스템을 이용해보고 싶어 웹사이트 하단에있는 adress 클릭시 구글지도 api형태로 분당고등학교가 출력되게 바꾸어보았다.

![image](https://user-images.githubusercontent.com/35617378/199529740-83e7a5c0-29dd-42b7-a8fd-6993db08be6b.png)

```c
<div class="map_container">
<div class="map-responsive">
 <<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3170.608011681489!2d127.11414391562235!3d37.375451042805445!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357b5823238e1e3b%3A0x2c544965fe4b031c!2z67aE64u56rOg65Ox7ZWZ6rWQ!5e0!3m2!1sko!2skr!4v1667396181658!5m2!1sko!2skr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```

또한 기존 html 샘플에는 없던 결제부분도 가져와 buy now 클릭시 따로 연결시킨 purchase.html을 통해 구매 창이 뜨게 만들었다.
![image](https://user-images.githubusercontent.com/35617378/199532718-7c880dc3-71e3-4ab9-bd95-993d84d5f78d.png)

php파일을 이용하여 내용이 입력 가능하도록 하였고 continue to chack out 클릭시 자체적으로 만든 원래 메인 홈페이지로 5초후 자동으로 돌아가는 형태에 코드를 짰다.
![image](https://user-images.githubusercontent.com/35617378/199533426-c23aa4c9-8c83-4b74-9381-e5d57e1c8844.png)
```c
	<!DOCTYPE html>
	<html>
	<head>
	<meta charset="EUC-KR">
	<title>구매완료</title>
	<meta http-equiv="refresh" content="5; url=index.html"> 
	<style type="text/css">
	    div { border:1px solid; padding:10px; }
	</style>
	</head>
	<body>
		<div style="text-align:center">
	    <p style="font-size:500%"> 구매 감사합니다 </p>
	    <p style="font-size:250%">앞으로 5초후 홈페이지로 돌아갑니다.</p>

	    </div>
	</body>
	</html>
```
meta문을 이용하여 자체적으로 돌아가는 형태에 웹사이트를 구성해보았다.

