# 接口：updateTest  [返回](../README.md)
用例： [修改实验](../用例/修改实验.md)

* 权限：
    老师登录

* 功能：
    老师为每个课程修改实验

* API请求地址：
   接口基本地址/com/api/updateTest

* 请求方式 ：
   POST

* 请求参数说明:
    无

* 返回实例：
    
       {
               "code": 200,                         
               "data": {
                   {
                      "TERM_NAME": "2017-2018",
                      "COURSENAME": "软件设计",
                      "TEST_ID": "2015-2-1",
                      "TITLE": "实验1",
                     },
                     
                },              
               "msg": "操作成功"
            }

* 返回参数说明：

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|
  |code|请求响应状态|
  |data|信息数组|
  |TERM_NAME|实验所属的学期|
  |COURSENAME|课程名称|
  |TEST_ID|实验ID|
  |TITLE|实验标题|
  |msg|操作信息|
 