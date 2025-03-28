# netlify-gemini-proxy
## 1. 准备文件

目录结构如下所示

```bash
 .
├──  _redirects
└──  empty.html
```

_redirects 内容为：`/*  https://generativelanguage.googleapis.com/:splat  200`

empty.html 内容为空即可

## 2. 上传文件

访问 [netlify](https://netlify.com)，注册登录后，上传文件夹，创建 Site，自定义自己喜欢的 site name

## 3. API 地址

- openai: https://<site_name>.netlify.app/v1beta
- gemini: https://<site_name>.netlify.app
