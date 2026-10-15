# firefly 用户满意度研究台

纯静态 GitHub Pages 网站，打开后导入问卷 .xlsx。

## 部署
将本目录文件放在仓库根目录。在仓库 Settings → Pages 中选择 Deploy from a branch，选择 main 分支的 / (root) 后保存。

## 功能
用户画像、多选拆分、车型合并、满意度及有效样本计算、购买原因规则分类与人工复核、历期对比、CSV 导出、打印保存 PDF、JSON 数据备份。

## 数据与限制
不包含真实问卷、报告或访问密钥。导入在浏览器本地解析，数据仅保存于浏览器 localStorage；清除浏览器数据前请下载备份。规则分类不是在线 AI 推理。城市等级映射未配置，实际使用者性别不推断。

依赖：JSZip，保留 jszip.min.js 中许可证声明。
