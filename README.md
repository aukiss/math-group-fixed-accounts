
# 六年级学习小组（清爽绿 · 固定账号版）
- 已关闭注册；使用预置账号登录（学生默认密码 = 手机号）
- 老师：17826182908 / mayi223462123
- 含错题本、错题辅导、7天计划、广播、排行榜、移动端优化
- Netlify Functions + Netlify Blobs（首次调用会自动写入用户种子到 blobs）

## 账号清单
- 老师：17826182908 / mayi223462123
- 学生：见 _lib/users_fixed.json（密码=手机号）

## 部署
1) Netlify → Add new site → Deploy manually，上传整个文件夹
2) 环境变量：OPENAI_BASE_URL、OPENAI_API_KEY、（可选）OPENAI_MODEL、（建议）SITE_SECRET

## 无需依赖安装的上传方式
- 直接把整个文件夹打包成zip拖到 Netlify（Deploys → Deploy manually）。
- 不需要 npm 安装步骤；函数使用 Netlify 运行时内建模块。
