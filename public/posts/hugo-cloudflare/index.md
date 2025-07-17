# Hugo 部署 Cloudflare 流水账


*Hugo 部署 Cloudflare 流水账*

# 1.Cloudflare控制台 “计算 (Workers)” -> “Workers 和 Pages” 点击“创建”

![alt text](/assets/image.png)

# 2.点击“Pages”，可导入现有Git存储库 或者 直接上传文件

![alt text](/assets/image-1.png)

# 3.Git存储卡目前支持Github和Gitlab，添加Git账户后选择对应存储库

![alt text](/assets/image-2.png)

# 4.确定项目名称，生成分支。总店为框架预设选择 Hugo，构建命令默认为 hugo，构建输出目录填写为 “public”

![alt text](/assets/image-3.png)

# 5.部署提示Success即代表成功

正在初始化构建环境 3s
正在克隆 Git 存储库 2s
正在构建应用程序 8s
正在部署到 Cloudflare 全球网络 8s
![alt text](/assets/image-4.png)

# 6.默认可访问域名为添加的项目名称+.pages.dev域名后缀，可添加自定义域，如果域名已托管至Cloudflare则自动添加CNAME解析，如果是其他域名托管商则需自行添加CNAME解析

![alt text](/assets/image-5.png)
![alt text](/assets/image-8.png)
![alt text](/assets/image-7.png)
![alt text](/assets/image-6.png)

---

> 作者: <no value>  
> URL: http://localhost:1313/posts/hugo-cloudflare/  

