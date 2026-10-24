# 诺贝尔物理学奖视译术语库（2016–2026）

一个单文件网页：2016–2026 十一届诺贝尔物理学奖的授奖词、术语、人物与背景知识，供视译译前准备使用。**无需构建、无外部依赖、无 CDN 请求**，双击即可离线打开。

## 目录内容

| 文件 | 说明 |
| --- | --- |
| `index.html` | 全部内容（约 3.2 MB），数据与图片均以 base64 内嵌 |
| `.nojekyll` | 告诉 GitHub Pages 跳过 Jekyll 处理 |
| `README.md` | 本说明 |

---

## 一、用网页界面发布（最快，不需要命令行）

1. 登录 GitHub，右上角 **＋ → New repository**。仓库名建议 `nobel-glossary`，可见性选 **Public**，然后 **Create repository**。
2. 进入仓库，点 **Add file → Upload files**。
3. 把 `index.html`、`README.md`、`.nojekyll` 三个文件**一起**拖进虚框。

   > macOS 上 `.nojekyll` 是隐藏文件，在 Finder 里按 `Cmd + Shift + .` 才会显示。
   > 如果嫌麻烦，也可以先只传 `index.html` 和 `README.md`，然后再点 **Add file → Create new file**，文件名输入 `.nojekyll`，内容留空，直接提交。

4. 页面底部点 **Commit changes**。
5. 回到仓库首页，点 **Settings → Pages**。
   - Source 选 **Deploy from a branch**
   - Branch 选 **main**，目录选 **/ (root)**
   - 点 **Save**
6. 等 1–2 分钟刷新本页，顶部会出现网址：

   ```
   https://<你的用户名>.github.io/nobel-glossary/
   ```

> 如果仓库名直接写成 `<你的用户名>.github.io`，网址就变成 `https://<你的用户名>.github.io/`（根路径），适合当个人主页。

---

## 二、用命令行发布（可选）

```bash
cd nobel-glossary
git init -b main
git add .
git commit -m "add Nobel physics glossary"
git remote add origin https://github.com/<你的用户名>/nobel-glossary.git
git push -u origin main
```

推送完成后，仍需按上面第 5 步在 Settings → Pages 里开启一次，页面才会生效。

---

## 三、几点说明

- **文件名必须是 `index.html`**，否则访问到的是目录列表或 404。
- 首次打开要下载约 3.2 MB，之后浏览器会缓存；手机建议先在 Wi-Fi 下打开一次。
- 全站没有任何外部请求，断网可用，适合教室、考场这类无网环境。
- 文件远低于 GitHub 网页上传的单文件 25 MB 上限，无需 Git LFS。
- **更新内容**：改好 `index.html` 后重新 Upload 覆盖同名文件即可，Pages 会在一分钟内自动重新构建。
- 仓库为 Public 时页面公开可访问；Private 仓库发布 Pages 需要 GitHub Pro，免费账号不支持。

---

## 四、数据口径

- 授奖词 **15 条**，覆盖 **11 届**（2018–2021 有几年一届分给两个方向，所以是一届两条）
- 专业术语 **226 条** ＋ 获奖人 **30 位** ＝ **256 张卡**
- 基本知识 **38 条**：奖项与评选 24、物理学史脉络 7、背景人物 7
- 标 ★ 的官方译名：术语 35 条、获奖人 30 位、基本知识 14 条，均以当年新华社 / 央视报道**正文**出现过的译法为准，未检出一律不标

---

## 五、内容来源

诺贝尔奖官网（NobelPrize.org）的授奖词、新闻公报、科学背景文件与获奖人档案；中文译名参考新华社、央视新闻当年的报道。详见网页内「资料来源」板块。
