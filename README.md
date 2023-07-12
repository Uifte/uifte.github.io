<!DOCTYPE html>
<html>
<head>
    <title>UifteOS软件代码编写</title>
    <style>
        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #014a82;
        }

        li {
            float: left;
        }

        li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        li a:hover {
            background-color: #014a82;
        }

        .textarea {
            font-family: "Cascadia Code", monospace;
            font-size: 15px;
            width: 1350px;
            height: 500px;
        }

    </style>

</head>
<body>
    <ul>
        <li><a href="index.html">编写代码</a></li>
    </ul>

    <h2>开始编写你的代码吧</h2>
    <textarea class="textarea">
        

#创建窗口
widgets = MainWindow(
    title='MainWindow', #标题
    size=(1000,800),    #窗口大小(width,height)
    widgets=[           #组件
            # ('Lable' , 文本 , (字体 , 字号) , 字体颜色 , (x , y))
            (('Label', 'label1'), '示例文本', ('微软雅黑', 11),'black', (10, 10)),#文本组件

            # ('Button' , 文本 , (字体 , 字号) , 字体颜色 , 背景颜色, (长 , 高), 边框厚度, 点击事件, (x , y), 点击后背景色 , 文字对齐法则)
            (('Button', 'button1'), '示例按钮', ('微软雅黑', 11), 'white', '#0078D4', (10, 1), 0, None, (10, 100),'white', 'center'),#按钮组件

            # ('Entry', (字体 , 字号) , 长度 , (x , y))
              (('Entry', 'entry1'), ('微软雅黑',11), 15, (10, 200),#输入框组件                      
            ]
        
)        
show_window() #窗口显示</textarea>   


    <p1>CopyRight Uifte工作室 2023</p1><br>
    <p1>感谢您对UifteOS的贡献</p1>
</body>
</html>
