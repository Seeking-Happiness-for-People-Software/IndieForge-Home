# IndieForge-Home

IndieForge 两个项目的发布主页(GitHub Pages):

- **IndieForge 应用**(Flutter,私有仓库 IndieForge-APP)
- **IndieForge 工牌固件**(ESP32-C3,私有仓库 IndieForge-Passport)

发布方式:Actions 里手动运行「编译并发布(APP + 固件)」workflow,填版本号即可——CI 会编译两个项目,把 APK 与整包固件挂到本仓库 Release,并更新 GitHub Pages 下载页。

站点源文件:`index.html`;工作流:`.github/workflows/release.yml`。
