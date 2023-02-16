# gis-common-login
测试自己封装登录函数到npm并使用

# 安装
npm i mynpmutils-login -S

# 使用示例
import commonLogin from 'gmynpmutils-login'
let res =await CommonLogin(requestUrl,'wx01','123456','',APP_ID,SIGN_SECRET);
//参数说明 请求地址，用户名，密码，验证码，下发的APP_ID，下发的SIGN_SECRET
console.log('最终请求结果', res)