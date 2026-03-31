# webp
实验一下deepseek写的代码

* 它会调用浏览器内置的 WebP 编码器将画布上的像素数据重新编码成 WebP 格式的二进制数据
* 如果浏览器不支持的话，会提示不支持

引用了[jszip](https://github.com/Stuk/jszip/tree/main)的CDN，让多张图片打包成一个zip下载。

压缩包里图片的时间戳可能会跟你不是一个时区，可能需要自己部署一个[jszip](https://github.com/Stuk/jszip/tree/main)然后添加自己的时区?  
太麻烦了，我没有试

> [deepseek](https://www.deepseek.com/)
>
> [jszip](https://github.com/Stuk/jszip/tree/main)

2026-03-31 23:37更新
* 更改为暗色界面，适配我的使用习惯
* 添加更为流畅的过渡动画与js代码，避免了界面闪烁
