<!--
 * @Descripttion:
 * @Version:
 * @Date: 2021-03-03 15:19:14
-->

#在线预览 pdf

###引入资源包
`将pdf包放入js文件夹中`

###查看 pdf 的

```
//查看pdf的事件
var pdf = 'https://www.baidu.com/1.pdf';// pdf地址必须是线上地址
window.open('./js/pdf/web/viewer.html?file=' + pdf, 'PDF');//viewer.html的路径根据实际情况配置
```

在线上地址就可以正常访问了
