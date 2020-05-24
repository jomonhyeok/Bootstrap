# Bootstrap
Bootstrap start

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> <!--edge버전으로만 본다-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Bootstrap</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">
    <!-- 합쳐지고 최소화된 최신 CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css">
    <!-- 부가적인 테마 -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
    <!-- 합쳐지고 최소화된 최신 자바스크립트 -->
    <style>
        div{border: 1px solid black;}
    </style>
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-xs-6">div.col-xs-6</div>
            <div class="col-xs-4">
                col-xs-4
            </div>
            <div class="col-xs-2">col-xs-2</div>
        </div>
    </div>
    <div class="container-fluid">
        <div class="row">
            <div class="col-xs-6">div.col-xs-6</div>
            <div class="col-xs-4">
                col-xs-4
            </div>
            <div class="col-xs-2">col-xs-2</div>
        </div>
    </div>
    <hr/><hr/>
    <div class="container">
        <div class="row">
            <div class="col-sm-6">div.col-sm-6</div>
            <div class="col-sm-4">
                col-sm-4
            </div>
            <div class="col-sm-2">col-xs-2</div>
        </div>
    </div>
    <div class="container-fluid">
        <div class="row">
            <div class="col-sm-6">div.col-sm-6</div>
            <div class="col-sm-4">
                col-sm-4
            </div>
            <div class="col-sm-2">col-sm-2</div>
        </div>
    </div>
    <!-- 
        container : 해상도 마다 width값을 가진다
        container-fluid : width값이 없다.0

        .row : .container  or   .container-fluid안에 .row로 행을 만든다

        .col-*-*
        .row안에 .col-*-*로 열을 만듭니다. 
        첫번째 *에는 xs, sm, md, lg중의 하나
        두번쩨 *에는 1~12 숫자중 하나
        
        - xs: default
        - sm: 가로 해상도 768px 이상에서 적용
        - md: 가로 해상도 992px 이상에서 적용
        - lg: 가로 해상도 1200px 이상에서 적용
        1 ~ 12 : 행을 12등분하여 그 중 몇개를 사용할지 정한다
     -->
     <hr/><hr/>

     

</body>
</html>
