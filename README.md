# re01
<!DOCTYPE html>
<html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>C的个人网站</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            background-color: #eee;
        }
      
        .flex {
            display: flex;
        }
        .baise {
            background-color: white;
        }
        .flex {
            flex: 1;
        }
        .column {
            flex-direction: column;
        }
        .mgh{
            margin: 8px;
        }
        .mgr{
            margin-right: 8px;
        }
        .mgt{
            margin-top: 8px;
        }
    </style>
</head>
<body class="flex">
    <!--侧边栏-->
    <div style="width: 200px;" class="baise">zs</div>
    <!--主区域-->
    <div class=" flex  column ">
        <!--头部栏-->
        <div style="height: 60px;" class="baise "></div>
        <!--内容区-->
        <div class=" flex">
            <!--左区-->
            <div style="flex: 3" class="flex column mgh">
            <!--数据区-->
            <div class="flex">
                <!--数据块-->
                <div style="height: 100px;" class="flex baise mgr"></div>
                <div style="height: 100px;" class="flex baise mgr"></div>
                <div style="height: 100px;" class="flex baise mgr"></div>
                <div style="height: 100px;" class="flex baise "></div>
            </div>
            <!--列表区-->
            <div>
                <!--列表项-->
                <div style="height: 160px;" class="baise mgt">这是我的</div>
                <div style="height: 160px;" class="baise mgt"></div>
                <div style="height: 160px;" class="baise mgt"></div>
            </div>
            </div>
            <!--右区-->
            <div style="flex: 1" class="flex column">
            <!--提示区-->
            <div style="height: 150px" class=" baise mgh"></div>
            <!--消息区-->
            <div style="height: 300px" class=" baise mgh"></div>
            </div>

        </div>
    </div>
</body>
</html>
