# 个人简历网站

中文简历与轻作品集网站，原生 HTML / CSS / JavaScript，无构建步骤、外部字体、CDN 或第三方脚本。

## 本地查看与修改

双击 `index.html` 即可预览。所有网页样式、SVG 和交互均在这一个文件中。

1. 在文件末尾的 `PROFILE` 对象中填写姓名、城市、邮箱与手机，页面内对应位置会同步更新。
2. 姓名、联系方式、三段工作经历及教育信息已按本人提供资料填写；后续修改时同步更新配套 PDF。
3. 项目区现为“AI试用员番茄”“Video Knowledge”“番茄视觉”三个项目。Video Knowledge 介绍以现有项目功能说明为依据，侧重用途；番茄视觉使用用户提供的抖音账号分享链接。
4. 项目一的封面是用 HTML/CSS/SVG 制作的视觉示意，已在页面标注。后续可替换成真实公众号封面或文章截图。
5. `resume.pdf` 为配套 A4 单页简历，包含相同的个人资料、项目、三段工作经历与教育信息；纸面版对职责作简洁归纳。

署名为“丛瀚林｜番茄”。经历按时间从早到晚展示：扬州玛洛卡遮阳技术有限公司（客服经理，2023—2024），绍兴唯亿网络科技有限公司（渠道销售，2024—2025），绍兴无与伦比电子商务有限公司（内容运营 / 视频剪辑，2025—2025.08），个人项目与 AI 内容实践（2026—至今）。客服职责包含新人带教。教育信息为浙江长征职业技术学院、电子商务，毕业年份为 2023。

网页包含锚点导航、滚动淡入、项目详情展开、轻微悬停反馈和阅读进度。尊重系统的“减少动态效果”设置；JavaScript 关闭时仍可阅读完整页面。

## 2026-11-02 轻量优化

保留暖白底、陶土红强调色、个人卡片、项目展示及时间线。首页突出运营执行、办公整理与 AI 提效，求职方向覆盖运营助理、电商及跨境电商运营、内容运营与 AI 应用。

Skills 采用“能力用途 + 工具”的四组结构：AI 与效率工具、办公与数据处理、内容与运营、工具与网页实践。办公案例以“日常办公任务的应用示例”展示数据整理、AI 辅助表格、日报信息整理与重复任务提效，未作为某公司的历史业绩或库存工作实绩。新系统学习能力不表示已有公司 ERP 使用经验。

## 项目链接与工具区

- 公众号项目已加入真实的[代表文章入口](https://mp.weixin.qq.com/s/QMhXEJcZhftZ8LjePgukAg)，点击后在新标签页打开。
- “查看公众号”弹窗展示名称及复制按钮，方便在微信中搜索。没有使用未经确认的主页 URL，也没有制作虚假的公众号二维码。
- 工具区将 ChatGPT、Claude、Codex、Gemini 放入“AI 与效率工具”，办公数据、内容运营、HTML/CSS 与 GitHub Pages 实践各自说明用途。
- “公众号”作为项目平台保留在项目区。
- “番茄视觉”项目已接入[抖音账号分享链接](https://v.douyin.com/-ppbn5elBxI/)，在新标签页打开；是否需要登录或打开客户端取决于抖音页面的实际提示。
- Video Knowledge 以“视频链接 → 内容与结构 → 笔记总结”展示作用，支持的视频来源以项目当前实际能力为准，不宣称覆盖所有视频平台。

公众号存在 `mp.weixin.qq.com/mp/profile_ext?...` 一类主页入口，但部分公开使用说明明确标注仅限微信查看，不应假设它在所有外部浏览器中都能正常使用。当前采用文章链接与微信搜索入口；如果后续补充后台下载的真实公众号二维码，可再加入弹窗。相关文章能否直接阅读，仍需在实际设备与网络上验证。

研究参考：[四川省地震局公布的服务产品说明，内含仅限微信查看的公众号主页入口](https://www.scdzj.gov.cn/zwgk/tzgg/202404/P020240409397958905240.pdf)。

## GitHub Pages 发布：无需购买域名

推荐建立一个专门存放本网站的公开仓库。GitHub Free 支持公开仓库的 GitHub Pages。

1. 登录 GitHub，新建公开仓库 `resume`。也可建立 `你的用户名.github.io`，获取更短的首页地址；如果已有这个仓库，请使用独立的 `resume` 仓库，避免覆盖原网站。
2. 在仓库中选择 **Add file → Upload files**，将本文件夹里的 `index.html` 和 `resume.pdf` 上传到仓库根目录并提交。`.nojekyll` 可一同上传；无法在文件选择器中看到时，可通过 **Add file → Create new file** 新建同名空文件。
3. 前往 **Settings → Pages**。
4. 在 **Build and deployment → Source** 选择 **Deploy from a branch**。
5. 分支选择 `main`，文件夹选择 `/(root)`，点击 **Save**。
6. 等待部署，Pages 页面会显示正式网站地址。官方说明变更可能需要最多约 10 分钟生效。
7. 打开正式地址，并在手机及目标收件人使用的网络上测试，再把这个地址发给 HR。对方访问公开 Pages 网站无需登录 GitHub。

地址示例（只是格式说明，不是已发布的链接）：

- 仓库 `resume`：`https://你的用户名.github.io/resume/`
- 仓库 `你的用户名.github.io`：`https://你的用户名.github.io/`

GitHub Pages 是公开网页，上传前确认联系方式与作品均适合公开。国内不同网络的访问体验需用正式地址实际验证。

之后修改同名文件并提交，Pages 会自动重新发布。无需服务器、数据库或安装 Node.js。

**只上传本文件夹中的网站文件，不要上传整个工作区。** 本工作区包含其他与简历无关的文件。

## 官方文档

- [GitHub Pages 简介与地址规则](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)
- [创建 GitHub Pages 网站](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [配置发布来源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 设计参考

以下作为排版与交互方向参考，没有复制其源代码、文案或图片。

| 参考 | 借鉴方向 |
| --- | --- |
| [Paco Coursey](https://paco.me/) | 克制留白、文字层级与清晰的分区 |
| [Brian Lovin](https://brianlovin.com/) | 个人介绍与内容组织 |
| [Emil Kowalski](https://emilkowal.ski/) | 简洁的项目展示与细节意识 |

本版使用暖白底、深灰正文与单一陶土红强调色。主视觉权重放在个人定位和项目上，工作经历与教育信息保持简洁。
