<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table border="2" width="600" height="300" cellspacing="0">
        <caption>学生信息</caption>
        <thead>
            <tr> 
                <th colspan="2">姓名性别</th>
                <!-- <th>性别</th> -->
                <th>年龄</th>
                <th colspan="2">民族 政治面貌</th>
                <!-- <th>政治面貌</th> -->
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>张三</td>
                <td>男</td>
                <td>18</td>
                <td>汉族</td>
                <td rowspan="5">团员</td>
            </tr>
            <tr>
                <td rowspan="3">李四</td>
                <td>女</td>
                <td>20</td>
                <td>满族</td>
                <!-- <td>群众</td> -->
            </tr>
            <tr>
                <!-- <td>王二</td> -->
                <td>男</td>
                <td>30</td>
                <td>汉族</td>
                <!-- <td>党员</td> -->
            </tr>
            <tr>
                <!-- <td>麻子</td> -->
                <td>男</td>
                <td>25</td>
                <td>汉族</td>
                <!-- <td>团员</td> -->
            </tr>
            <tr>
                <td>王五</td>
                <td>男</td>
                <td>40</td>
                <td>汉族</td>
                <!-- <td>群众</td> -->
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td>共计：4人</td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
