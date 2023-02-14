<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>注册页面</title>
  <style>
        body{
            background: url("./img/black.jpg");
        }
        .center {
            /*背景颜色*/
            background: #ff0ff;
            /*宽度设置*/
            width: 400px;
            /*文本对齐方式*/
            text-align: center;
            /*外边距设置*/
            margin: auto;
        }
    </style>
</head>
<body>
<div>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
</div>
<!--中间注册信息-->
<div class="center">
  <div>注册详情</div>
  <hr>
  <!--表单标签-->
  <form action="#" method="get" autocomplete="off">
    <div>
      <label for="username">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 姓名： &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</label>
      <input type="text" id="username" name="username" value="" placeholder="在此输入姓名" required/>
    </div>

    <div>
      <label for="password">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 密码： &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</label>
      <input type="password" id="password" name="password" value="" placeholder="在此输入密码" required/>
    </div>
    <div>
      <label for="password">重复输入密码：</label>
      <input type="password" id="password2" name="password2" value="" placeholder="在此输入密码" required/>
    </div>

    <div>
      <label for="email">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 邮箱： &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</label>
      <input type="email" id="email" name="email" value="" placeholder="在此输入邮箱" required/>
    </div>

    <div>
      <label for="sel">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 手机： &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</label>
      <input type="sel" id="sel" name="sel" value="" placeholder="在此输入手机" required/>
    </div>

    <hr>

    <div>
      <label for="gender">性别：</label>
      <input type="radio" id="gender" name="gender" value="men" />男 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      <input type="radio" name="gender" value="women" />女&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    </div>


    <div>
      <label for="birthday">出生日期：&nbsp;</label>
      <input type="date" id="birthday" name="birthday" value=""/>
    </div>
    <div>
      <label for="sel">&nbsp;&nbsp;&nbsp;&nbsp;身份证号码：&nbsp;</label>
      <input type="sel" id="sfz" name="sfz" value="" placeholder="在此输入身份证号码" required/>
    </div>
    <div>
      <label for="city"> 所在城市：</label>
      <select name="city"id="city">
        <option>---请选择所在城市---</option>
        <optgroup label="直辖市">
          <option>北京</option>
          <option>上海</option>
          <option>广州</option>
          <option>深圳</option>
        </optgroup>
        <optgroup label="省会市">
          <option>西安</option>
          <option>杭州</option>
          <option>郑州</option>
          <option>武汉</option>
        </optgroup>
      </select>
    </div>
    <hr>


    <button type="submit">注册</button>
    <button type="reset">重置</button>
  </form>
</div>
</body>
</html>
