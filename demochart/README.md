# demochart

`templates/tests`主要测试Go template语法使用<br>
`templates/yamls`的yaml文件内，字符串值以""来表示，也可不加引号

* 创建生成chart模板：`helm create demochart`
* 测试模板渲染结果： `helm template demochart -x templates/tests/test-xxxx.yaml`