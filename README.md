# blog
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>小课堂</title>
</head>
<body>
1111
<br>
<script type="text/javascript">
    document.write('这里是一行JavaScript代码1');
    var i;
    var counter=0;
    var x=Math.random()*100;
    var y=Math.random()*10;
    for (i=0;i<10;i++)
    {
        document.write('这里是一行JavaScript代码1'+'<br>' );//换行
        document.write(counter+'<br>' );
        counter++;
        if(x<y)
        {
            document.write("x less than y");
        }
        else if(x>y)
        {
            document.write("y less than x"+'<br>');
        }
        else
        {
            document.write("x=y"+'<br>');
        }
        document.write('x='+x+'<br>' ,'y='+y+'<br>');

    }
    //数字，字符串为参数
    fn(100,'px')
    function fn(a,b) {
        alert(a+b)
    }
    //函数为参数
    f1(function () {
        alert("函数做参数")
    })
    function f1(a) {
        a()
    }
</script>
</body>
</html>
