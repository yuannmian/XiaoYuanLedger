# 小圆账单 v4（无图标居中版）

本版本以 v3 为基础，不加入任何软件图标，保留以下功能：

- 首页、记录、功能三个页面
- 记录收入与支出并自动更新总存款
- 本月收入与本月支出统计
- 马卡龙色系皮肤
- JSON 数据导出与恢复
- 调整初始存款、删除记录、清空数据

## 本次界面调整

- 首页标题“小圆账单”水平居中
- 首页日期与副标题居中
- 总存款卡片标题和金额居中
- 本月支出、本月收入方块中的符号、标题、金额全部居中
- 收入和支出金额字体由 22sp 增大至 26sp

## Android Studio 打包

1. 使用 Android Studio 打开本项目文件夹。
2. 等待 Gradle 同步完成。
3. 点击 `Build > Build Bundle(s) / APK(s) > Build APK(s)`。
4. APK 通常位于：
   `app/build/outputs/apk/debug/app-debug.apk`

## GitHub Actions 在线生成 APK

仓库已包含 `.github/workflows/build-apk.yml`。

1. 打开仓库的 **Actions** 页面。
2. 选择 **Build Android APK**。
3. 点击 **Run workflow**。
4. 构建完成后打开本次运行，在 **Artifacts** 下载 `XiaoYuanLedger-debug-apk`。
5. 解压下载文件，即可得到 `app-debug.apk`。
