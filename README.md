# website_html_basketball_mall_project


(https://www.free-css.com/free-css-templates/page283/lodge) 위 웹사이트에서 html 샘플을 따와 바꾸는 형태로 만들게 되었다.

![image](https://user-images.githubusercontent.com/35617378/199526699-3dc3d8e8-19bd-463a-ba67-c99afc3af290.png)

검색기능을 이용한 이미지의 위치를 유추하여 농구샵에 맞는 이미지로 교체하고 배경화면 또한 css코드를 활용하여 바꾸어 주었다.

또한 기존에 되어있지 않던 href문을 이용한 html 연결부분도 추가하여 다음페이지로 넘어갈 수 있게 하였다.
 '''
            </div>
            <div class="carousel-item ">
              <div class="row">
                <div class="col-md-6">
                  <div class="detail_box">
                    <h2>
                      <span> 24시간 한정</span>
                      <hr>
                    </h2>
                    <h1>
                      조던 29% 할인
                    </h1>
                    <p>
                      프라임만에 할인을 누려보세요
                    </p>
                    <div>
                      <a href="Products.html">Shop Now</a>
                    </div> 
'''
이후 구글지도 api시스템을 이용해보고 싶어 웹사이트 하단에있는 adress 클릭시 구글지도 api형태로 분당고등학교가 출력되게 바꾸어보았다.

![image](https://user-images.githubusercontent.com/35617378/199529740-83e7a5c0-29dd-42b7-a8fd-6993db08be6b.png)

또한 기존 html 샘플에는 없던 결제부분도 가져와 buy now 클릭시 따로 연결시킨 purchase.html을 통해 구매 창이 뜨게 만들었다.
![image](https://user-images.githubusercontent.com/35617378/199532718-7c880dc3-71e3-4ab9-bd95-993d84d5f78d.png)

php파일을 이용하여 내용이 입력 가능하도록 하였고 continue to chack out 클릭시 자체적으로 만든 원래 메인 홈페이지로 5초후 자동으로 돌아가는 형태에 코드를 짰다.
![image](https://user-images.githubusercontent.com/35617378/199533426-c23aa4c9-8c83-4b74-9381-e5d57e1c8844.png)
'''
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
'''
meta문을 이용하여 자체적으로 돌아가는 형태에 웹사이트를 구성해보았다.

