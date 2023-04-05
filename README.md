## 快速开始

> https://dejavu.moe/posts/how-i-built-my-personal-blog/

```bash
# 克隆本仓库
git clone https://github.com/DejavuMoe/hugo-start.git Blog
# 克隆 Git 子模块
cd Blog && git submodule update --init --recursive
# 启动 Hugo 预览服务器
hugo server -D
# 更新主题
git submodule update --remote --merge
```

