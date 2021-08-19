# 前端监控

---
## frontEndError监控类型
---
*监控JS语法错误*    
    info error:错误等级  
    message：错误描述(包括：错误行、错误文件)  
  

*监控css，js文件加载错误*  
    info error:错误等级  
    file: 加载错误文件的文件名  
    target: 错误文件  
    message：错误描述  
  

*监控ajax请求错误*  
    info error:错误等级  
    require_url：错误请求url  
    type：请求类型  
    status Code：状态码（status<200 && status >=400）  
    message：错误描述  

---
## 安装和使用(具体使用需要与接口对接后确认)：  
---  
**直接在项目中引入js文件。**

```javascript
<script src="frontEndError.js"></script>
<script>
    fontEndError('---URL---')//URL为对应的上报接口
</script>
```

