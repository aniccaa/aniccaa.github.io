curl -X GET -k -v --basic -u user:pass "https://test.baidu.com/111/222/333" -d '{"name": "aniccaa","id":"123456"}'

-X GET或者POST
-k https请求忽略ssl证书
-v 显示详细
--basic basic认证
-u 认证的用户名和密码
-d post的请求body数据,json格式的数据等
