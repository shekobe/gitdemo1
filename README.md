# 前端监控

---
## frontEndError前端监控
---
*监控脚本异常、监控资源下载错误、监控网络请求错误，上报参数如下：*    
        info error:错误等级  
        message：错误描述(包括：错误行、错误文件)  
        target: 错误文件  
        require_url：错误请求url
        file: 加载错误文件的文件名  
        type：请求类型  
        status Code：状态码（status<200 && status >=400）  

 注：参数使用需要与接口对接后确认
## 安装和使用
---  
**直接在项目中引入js文件。**

```javascript
<script src="frontEndError.js"></script>
<script>
    fontEndError('---URL---')//URL为对应的上报接口
</script>
```

