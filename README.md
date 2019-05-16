

### 安装

```shell
git clone https://github.com/cucygh/JDFinance.git
cd JDFinance
npm install
```

### 切换分支

项目里使用git分支来管理不同章节的代码，根据自己的情况选择不同的分支进行开发。

1. 如何查看所有的分支？

```shell
git branch
```
<table>
  <thead>
    <tr>
      <th>分支名</th>
      <th>章节</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>master</td>
      <td>默认和setup一致</td>
    </tr>
    <tr>
      <td>setup</td>
      <td>最基础的构建部分</td>
    </tr>
    <tr>
      <td>setup-edit</td>
      <td>完整的构建部分，可以在这个基础上进行开发</td>
    </tr>
    <tr>
      <td>router</td>
      <td>增加了vue-router部分，只想看单页面的同学选择这个分支</td>
    </tr>
    <tr>
      <td>chapter-home</td>
      <td>首页</td>
    </tr>
    <tr>
      <td>chapter-money</td>
      <td>理财</td>
    </tr>
    <tr>
      <td>chapter-ious</td>
      <td>白条</td>
    </tr>
    <tr>
      <td>chapter-raise</td>
      <td>众筹</td>
    </tr>
    <tr>
      <td>chapter-download</td>
      <td>活动页</td>
    </tr>
    <tr>
      <td>chapter-online</td>
      <td>上线指导</td>
    </tr>
  </tbody>
</table>

2. 如何切换分支？

```shell
git checkout 分支名
```

