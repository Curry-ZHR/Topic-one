# Topic-one
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>前端招新答题卷</title>
    <style>
        .q4-header {border:pink;
                    width: 100%;
                    height: 60px;
                    margin:0 auto;
                    }
        .q4-footer {
            box-sizing: border-box;
            padding: 15px;
            border:pink 5px solid;
            width: 100px;
            height: 60px;
            margin: 0 auto;
        }

        .q4-body {
            overflow: hidden;
            clear: both;
            width: 500px;
            height:225px;
            margin: 0 auto;
        }
       
        .left{
            border:lightblue 5px solid;
            width: 200px;
            height:200px;
        }
        .right{
            border:lightblue 5px solid;
            width: 200px;
            height:200px;
        } 
    
        .outter,.footer{
            border: 5px solid pink;
            height: 60px;
            margin:0 auto;
            line-height:100px;
        } 
    </style>
</head>
<body>
    <div>
        <p>
            要求: 查询相关知识将下面模板美化成同名文件夹下面picture.png的样式
            1. 中间部分水平居中, 文字水平居中, 边框为 5px lightblue
            2. 头部和尾部要文字水平居中, 高度60px, 边框为 5px 粉色
        </p>
    </div>   
    <div class="outter">
        这里是头部
    </div>
    <div class="q4-body">
        <body style="text-align: center;">
        <div class="left" style="float:left;">经常遇到的布局</div>
        <div class="right" style="float: right;">右边部分</div>
        </body>>
    </div>

    <div class="footer">
        <div >这里是尾部</div>
    </div>
    
    
</body>

</html>







<!DOCTYPE html>
<html>
<body>

<ol>
  <li>使用以下内容完成题目</li>
  <html>
    <body>
      <ul>
        <li>table</li>
        <li>选择框</li>
        <li>表格元素</li>
      </ul>
  <li>用户名可见，密码（最长16位）不可见</li>
  <li>性别单选，默认选中男</li>
  <li>兴趣多选，默认计算机</li>
  <li>点击文字与其相对应的输入框选中</li>
  <li>意愿的内容为</li>
 <html>
   <body>
     <h4>
       <ul>
         <li>前端</li>
         <li>后端</li>
         <li>产品</li>
         <li>设计</li>
         <li>安卓</li>
       </ul>
     </h4>
   </body>
 </html>
  <li>提交按钮不用button</li>
</ol>
 
 
 
 
 <!DOCTYPE html>
<html>
<body>

<form action="/demo/demo_form.asp">
用户名:<br>
<input type="text" name="user" >
</br>
密码:<br>
<input type="text" name="password" >
</br>
</form>
 
</body>
</html>
<html>

<body>

<form name="input" action="/html/html_form_action.asp" method="get">
性别
男:
<input type="checkbox" name="男" value="man" checked="checked" />
<br />
   女：
<input type="checkbox" name="女" value="women" />
<br />
兴趣
计算机：
<input type="checkbox" name="computer" value="computer" checked="checked"/>
<br />
数学：
<input type="checkbox" name="math" value="matj" checked="checked"/>
<br />
化学：
<input type="checkbox" name="chemistry" value="chemistry"checked="checked"/>
物理：
<input type="checkbox" name="physicis" value="physicis"checked="checked"/>

<html>
  <body>
    意愿
    <form>
      <select name="cars">
        <option value="volvo">前端</option>
        <option value="saab">后端</option>
        <option value="设计" selected="selected">设计</option>
        <option value="audi">安卓</option>
        </select>
    </form>
  </body>
</html>

<html>
  <p>自我介绍</p>
  <style>
    div{
    border:solid black
    height:100px
    weight:100px
    margin:0auto
    }
 </style>

</html>
<form>
<input type="Submit"value="提交">
</form>






