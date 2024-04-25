<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: skyblue;
        }
        .header {
            overflow: hidden;
            background-color: #f1f1f1;
            padding: 20px 10px;
        }
        .header a {
            float: left;
            color: black;
            text-align: center;
            padding: 12px;
            text-decoration: none;
            font-size: 18px;
            line-height: 25px;
            border-radius: 4px;
        }
        .header a.logo {
            font-size: 25px;
            font-weight: bold;
        }
        .header a:hover {
            background-color: #ddd;
            color: black;
        }
        .header a.active {
            background-color: dodgerblue;
            color: white;
        }
        .header-right {
            float: right;
        }
        .text-block {
            position: absolute;
            top: 70%;
            left: 50%;
            color: white;
            padding-left: 20px;
            transform: translate(-50%, -50%);
        }
    </style>
</head>
<body>
    <div class="header">
        <a href="#home" class="logo">蔡洪波</a>
        <div class="header-right">
            <a class="active" href="#home">主页</a>
            <a href="#about">关于我</a>
            <a href="#doc">文档</a>
        </div>
    </div>
    <div class="text-block">
        <h1>欢迎来到我的网站</h1>
        <p>你好</p>
        <p>很高兴认识你</p>
    </div>
</body>
</html>
