# 卡牌对对碰

这是可直接发布到 GitHub Pages 的单文件网页游戏。卡牌图片已经嵌入 `index.html`，不需要上传素材目录或运行构建命令。

## 首次发布

1. 在 GitHub 建立一个仓库。
2. 将 `index.html` 和 `README.md` 上传到仓库根目录，并提交到 `main` 分支。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 里选择 **Deploy from a branch**，分支选 `main`，文件夹选 `/(root)`，然后保存。
5. 等待 Pages 发布完成。项目仓库的页面地址通常为 `https://用户名.github.io/仓库名/`。

## 更新已发布的网页

1. 下载并解压这个上传包。
2. 打开 GitHub 上原来的游戏仓库，进入 **Code** 页面。
3. 点击 **Add file → Upload files**。
4. 把解压后的 `index.html` 和 `README.md` 拖进上传区域。不要把 ZIP 压缩包本身上传。
5. 确认同名文件替换后，提交到原来的 `main` 分支。
6. 等 GitHub Pages 更新。只要沿用原来的仓库，分享链接就不变；GitHub Pages 更新可能需要几分钟。

游戏余额、局数和盒柜记录保存在各自设备的浏览器中，不会跨设备同步。
