# app-bridge-rule

> 所有参数返回值为int，0代表隐藏，1代表显示。(默认app内部全部隐藏，只需传入需要显示的字段为1即可)

|app|NAME|
|-|-|
|营销易|yx|
|应用宝|yyb|

#### 示例(营销易)
```javascript
//不显示的可以不传
wjkjNative={
    elementConfig:{
        yxHeader:1,//显示
        yxBottomBar:1,//显示
    }
}
```
## common
|字段|类型|描述|
|-|-|-|
|(NAME)Header|int|顶部header|
|(NAME)BottomBar|int|底部bar|
|(NAME)Phone|int|打电话按钮|
|(NAME)Im|int|客服按钮|
|(NAME)GoTop|int|返回顶部|
|(NAME)Download|int|APP下载|
## 
