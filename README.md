B站滑动块验证码（selenium,Image）
1. 项目描述  
B站滑动块验证码反爬，计算滑块需要滑动的距离  

2. 实现方式
    1. 比较原图片和阴影图片不同之处的位置  
    2. 设置阀值，直接计算阴影图片中的灰色位置  
ps：补充相关图片知识：图片像素决定（r,g,h,px)  

3. 技术方案  
    1. selenium请求url，使用base64,image下载图片  
    2. 解析图片image_load(), 分析图片像素信息即可（r,g,h,px)
