# android-lab-projects

Android 原生开发练习与实验室项目集合，使用 **Java + Android SDK** 从零手写实现。

每个模块独立成目录，配自己的 README 说明目标、实现要点与踩坑记录。

---

## 📦 目录规划

| 目录 | 内容 | 关键知识点 |
|---|---|---|
| `01-basics` | Activity / 生命周期 / 布局练习 | Activity、Intent、布局体系 |
| `02-list` | 列表与适配器 | RecyclerView、Adapter、ViewHolder |
| `03-network` | 网络请求与数据解析 | OkHttp / HttpURLConnection、JSON |
| `04-storage` | 本地存储 | SharedPreferences、SQLite、文件 |
| `05-service` | 后台能力 | Service、广播、前台服务 |
| `06-floating-window` | 悬浮窗 | SYSTEM_ALERT_WINDOW、WindowManager |
| `07-accessibility` | 无障碍服务 | AccessibilityService、节点操作 |
| `08-webview` | WebView 壳与混合开发 | WebView、JSBridge、权限回调 |

---

## 🛠 环境

| 项目 | 版本 |
|---|---|
| 语言 | Java |
| 最小 SDK | API 24 |
| 目标 SDK | API 34 |
| 构建 | Gradle |
| IDE | Android Studio |

---

## ▶️ 运行方式

1. 克隆仓库：`git clone https://github.com/hyj-new/android-lab-projects.git`
2. 用 Android Studio 打开对应模块目录
3. 同步 Gradle 后运行到模拟器或真机
4. 悬浮窗 / 无障碍模块需在系统设置中手动授予权限

---

## ⚠️ 安全约定

- 不提交 `local.properties`、`*.jks`、`*.keystore`、`key.properties`
- 不提交 `build/`、`.gradle/`、`.idea/`
- 接口密钥一律走本地配置文件，不进仓库

---

## 📄 License

MIT
