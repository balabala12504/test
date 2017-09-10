基础路径：http://iserp.gzis.ac.cn/

### 1、解决自动登录问题


#### 1. 登录接口：iserp/tenant_login

| 接口名称 | 登录iserp |
| :---: | :---: |
| 接口地址 | iserp/tenant_login |
| 请求方式 | POST |

**请求参数字段：**

| 参数名称 | 类型 | 是否必填 | 字段说明 |
| :---: | :---: | :---: | :---: |
| tenantName | String | 是 | 固定值为：iserp |
| username | String | 是 | 用户名 |
| password | String | 是 | 用户密码 |

完整接口地址：http://iserp.gzis.ac.cn/iserp/tenant_login

**返回结果：**
在 head 字段返回 Location 自动通过地址重定向进行结果执行 

*******
