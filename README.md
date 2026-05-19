# Python 学习与编程互助社区网站

这是一个可部署到 Gitee Pages 的静态网站初版，风格参考 NCL 文档门户：顶部导航、左侧分类目录、右侧文档内容区。

## 文件说明

- `index.html`：网站首页和主要内容
- `styles.css`：页面样式

## 本地预览

在当前目录执行：

```bash
python3 -m http.server 8000
```

然后打开：

```text
http://localhost:8000
```

## 部署到 Gitee Pages

1. 在 Gitee 新建仓库，例如 `python-learning-site`。
2. 将本目录内容推送到仓库默认分支。
3. 在仓库页面进入 `服务` -> `Gitee Pages`。
4. 选择部署分支和根目录，点击启动或更新。
