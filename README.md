# jQuery 表单验证功能

这是一个使用 jQuery 实现的表单验证功能，通过自定义规则对表单输入内容进行验证。适用于需要进行前端表单验证的各种项目。

## 特性

- **实时验证**：在用户输入完成时显示校验结果。
- **表单提交验证**：在表单提交时确保所有字段都符合规则。
- **自定义验证规则**：可以为每个输入字段设置不同的验证规则。

## 使用方法

### 1. 引入依赖

在使用之前，请确保在 HTML 文件中引入了 jQuery 以及所需的 CSS 和 JS 文件：

```html
<!-- 引入样式和脚本 -->
<link rel="stylesheet" href="https://cdn.bootcss.com/normalize/7.0.0/normalize.css">
<script src="https://cdn.bootcss.com/jquery/3.2.1/jquery.js"></script>
<link rel="stylesheet" href="css/main.css">
<script src="js/validator.js"></script>
<script src="js/input.js"></script>
<script src="js/main.js"></script>

<!-- 使用示例 -->
<input data-rule='pattern:"^[a-z0-9]*$"|maxlength:18|minlength:4'
  type="text"
  name="username"
  class="input-control"
>
<div id="username-input-error" class="input-error">用户名格式有误</div>
```



