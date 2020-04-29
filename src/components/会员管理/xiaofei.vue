<template>
    <div class="main">
        <div class="top1">
            <ul>
                <li>注册账号</li>
                <li><input type="text"></li>
            </ul>
            <ul>
                <li>注册时间</li>
                <li>
                    <select disabled>
                    <option value ="volvo">2014-11-25至2014-12-25</option>
                    </select>
                </li>
            </ul>
            <ul>
                <li><button>搜索</button></li>
            </ul>
        </div>
        <div class="top2">
            <ul>
                <li>注册账号</li>
                <li>注册时间</li>
                <li>上次登录时间</li>
                <li>状态</li>
                <li>操作</li>
            </ul>
        </div>
        <div class="top3">
            <ul class="top3_ul1">
                <li>13800138000</li>
                <li>13800138000</li>
                <li>13800138000</li>
                <li>13800138000</li>
            </ul>
            <ul class="top3_ul2">
                <li>2014-15-2-25  17:25</li>
                <li>2014-15-2-25  17:25</li>
                <li>2014-15-2-25  17:25</li>
                <li>2014-15-2-25  17:25</li>
            </ul>
            <ul class="top3_ul3">
                <li>2014-15-2-25  17:25</li>
                <li>2014-15-2-25  17:25</li>
                <li>2014-15-2-25  17:25</li>
                <li>2014-15-2-25  17:25</li>
            </ul>
            <ul class="top3_ul4">
                <li>禁用</li>
                <li>正常</li>
                <li>正常</li>
                <li>正常</li>
            </ul>
            <ul class="top3_ul5">
                <li><a href="#">查看</a></li>
                <li><a href="#">查看</a></li>
                <li><a href="#">查看</a></li>
                <li>查看</li>
            </ul>
        </div>
    </div>
</template>
<script>
export default {
    data(){
        return{
            
        }
    }
}
</script>
<style >
*{
    margin: 0;
    padding: 0;
}
 .main{
     float: left;
     width: 894px;
     height: 856px;
     background-color: #ffffff;
 }
 .top1{
     float: left;
     width: 894px;
     height: 102px;
 }   
 .top1 ul{
     float: left;
     margin-top: 10px;
     padding-left: 14px;
     margin-right: 40px;
 }
 .top1 li{
     list-style-type:none;
     margin-top: 17px;
     font-size: 15px;
     color:#4f4f4f;
 }
 .top1 li input{
     width: 200px;
     height: 19px;
 }
 .top1 li select{
     width: 200px;
     height: 25px;
 }
 .top1 button{
     width: 100px;
     height: 25px;
     margin-top: 36px;
 }
 .top2{
     float: left;
     margin-left: 14px;
     width: 880px;
     height: 35px;
     border: 1px solid #e3e3e3;
 }
 .top2 li{
     list-style-type:none;
     float: left;
     margin-top: 8px;
     margin-right: 80px;
     padding-left: 31px;
     color:#4f4f4f;
     font-size: 15px;
 }
 .top3{
     float: left;
 }
 .top3 ul{
     float: left;
 }
 .top3 li{
     list-style-type:none;
     font-size: 15px;
     color:#4f4f4f;
     margin-top: 27px;
 }
 .top3_ul1{
     padding-left: 45px;
 }
 .top3_ul2{
     padding-left: 75px;
 }
 .top3_ul3{
     padding-left: 30px;
 }
 .top3_ul4{
     padding-left: 59px;
 }
 .top3_ul5{
     padding-left: 110px;
 }
 .top3_ul5 a{
     text-decoration:none;
     font-size: 15px;
 }
</style>