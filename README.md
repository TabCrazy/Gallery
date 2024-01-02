# Gallery
个人图库
要想访问仓库中的这个 test.png 图片，需要把链接地址中的 blob 改为 raw。即 

`https://github.com/TabCrazy/myImages/raw/main/test.png` 
或者在地址后拼接一段 ?raw=true，即 
`https://github.com/TabCrazy/myImages/blob/main/test.png?raw=true `

但是，我们发现，通过 github 直接访问图片，速度不是特别理想，毕竟服务器在国外。

因此，我们可以使用 jsDelivr 进行 CDN 加速。这是完全开源免费的。

使用方法，非常简单，即把图片地址链接域名改为 CDN 的域名。格式如下：

`https://cdn.jsdelivr.net/gh/<你的github用户名>/<你的图床仓库名>@<仓库版本号>/图片的路径`

还是以上边的 test.png 图片为例，仓库版本号直接用分支名，由于现在 github 主分支名字都叫 main 了，因此版本号写 main 。图片路径，是在仓库中的相对路径，因为我这里就在根目录，因此就是 test.png 。
https://demo.grapecity.com.cn/spreadjs/SpreadJSTutorial/quickstart/quickstart-vue

最终地址为 
`https://cdn.jsdelivr.net/gh/TabCrazy/myImages@main/test.png`
