# 开源可复用资源清单（Web / Exe / H5 / App / 小程序）

> 整理时间：2026-11-27；链接已批量探测存活。
> 共 5 类、每类 10 项，以**开源、源码可直接拉取二次开发/部署**的仓库与组件库为主，Vue 系 / React 系分开列。
> 本仓库只收集项目链接与用途说明，不搬运源码；各项目版权与许可归原作者所有，商用前请以仓库内 `LICENSE` 为准。

## 类型说明

- **模板**：可 clone / init 出完整可运行工程
- **组件库**：UI 组件拼装
- **静态模板**：HTML/CSS 主题
- **示例工程**：官方演示工程
- **框架**：跨端基础框架
- **文档规范**：官方文档 / 设计规范，非代码工程

## 协议提醒

- MIT / Apache-2.0：可自由商用修改
- GPL：有 copyleft 传染性，闭源商用前需评估
- CC BY 3.0：需保留署名
- Qt：注意 LGPL / 商业授权
- DCloud 模板：按其服务协议使用

## 目录

- [一、Web（官网 / 落地页 / 后台）](#一web官网--落地页--后台)
- [二、Exe（桌面客户端 GUI）](#二exe桌面客户端-gui)
- [三、H5（移动端营销页 / 活动页）](#三h5移动端营销页--活动页)
- [四、App（移动端原生 / 跨端）](#四app移动端原生--跨端)
- [五、小程序](#五小程序)
- [六、纯灵感参考站（不开源，仅看设计）](#六纯灵感参考站不开源仅看设计)

---

## 一、Web（官网 / 落地页 / 后台）

### Vue 系后台模板

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [SoybeanAdmin](https://github.com/soybeanjs/soybean-admin) | 模板(Vue) | Vue3 + Vite6 + TS + UnoCSS，适配 Element Plus / Naive UI / Ant Design Vue | MIT | clone 后 pnpm install 启动，权限路由/主题/文件路由齐全，可直接做中后台底座 |
| [vue-pure-admin](https://github.com/pure-admin/vue-pure-admin) | 模板(Vue) | Vue3 + Vite + Element Plus + TS | MIT | 功能最全的 Vue3 后台模板之一，富文本/图表/上传/工作流组件预置，clone 即用 |
| [Vue-Vben-Admin](https://github.com/vbenjs/vue-vben-admin) | 模板(Vue) | Vue3 + Vite + TS + Ant Design Vue | MIT | 中后台开箱即用方案，二次封装组件、hooks、动态菜单、权限校验、多主题 |
| [光年后台模板](https://gitee.com/yinqi/Light-Year-Admin-Template) | 静态模板 | Bootstrap + 原生 HTML | 开源免费（已登记软著） | 简洁轻量后台 HTML，无需构建框架，适合简单管理系统，可商用 |

### React 系后台模板

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [Ant Design Pro](https://github.com/ant-design/ant-design-pro) | 模板(React) | React19 + Umi Max + Ant Design 6 | MIT | 蚂蚁官方企业级中后台脚手架，仪表盘/表单/鉴权/i18n/Mock 数据齐全 |
| [Refine](https://github.com/refinedev/refine) | 模板/元框架(React) | React + CRUD 元框架，可接 antd / MUI | MIT | 数据型内部工具/B2B 后台快速搭 CRUD，内置鉴权、权限、状态管理 |

### 静态官网 / 落地页模板

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [Start Bootstrap](https://startbootstrap.com) | 静态模板 | Bootstrap 静态主题/模板 | MIT | 免费官网、落地页、后台静态模板，下载 HTML/CSS/JS 直接改 |
| [SB Admin 2](https://startbootstrap.com/themes/sb-admin-2/) | 静态模板 | Bootstrap 后台静态模板 | MIT | 经典免费后台仪表盘静态模板，开箱即用 |
| [HTML5 UP](https://html5up.net) | 静态模板 | 响应式静态落地页模板 | CC BY 3.0（需署名） | 视觉风格强的落地页/作品集模板，下载后替换内容即可；商用需保留署名 |
| [Element Plus](https://element-plus.org/) | 组件库 | Vue3 + Element Plus | MIT | 桌面后台组件与示例页面，套壳 Web/Exe 后台界面可直接复用 |

## 二、Exe（桌面客户端 GUI）

### Electron（Web 技术套壳）

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [electron-vite-vue](https://github.com/electron-vite/electron-vite-vue) | 模板 | Vue3 + Electron + Vite | MIT | 官方维护模板，集成调试，clone 后 npm install / npm run dev 起桌面应用 |
| [electron-vite-react](https://github.com/electron-vite/electron-vite-react) | 模板 | React + Electron + Vite | MIT | 官方 React 版模板，结构同上 |
| [electron-react-boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate) | 模板 | React + TS + Electron | MIT | 成熟稳定的 Electron+React 脚手架，打包/测试/热更新齐全 |
| [electron-app (daltonmenezes)](https://github.com/daltonmenezes/electron-app) | 模板 | React19 + TS + Tailwind4 + shadcn/ui + Electron Vite | MIT | 现代栈桌面模板，含 Biome、GitHub Action 自动发版 |
| [croissant-electron](https://www.npmjs.com/package/croissant-electron) | 模板(npm) | React19 + Vite8 + Electron44 | 开源（见仓库 LICENSE） | 新版 Vite/Electron 栈脚手架，Tailwind4 + shadcn + 深色模式；npm 网页有反爬，包真实存在 |

### Tauri（轻量 Rust 套壳）

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [create-tauri-app](https://v2.tauri.app/zh-cn/start/create-project/) | 模板(CLI) | Tauri 官方脚手架，支持 Vue/React/Svelte/vanilla 等 | MIT / Apache-2.0 | 官方命令行生成项目，选框架模板后直接开发，安装包体积小 |
| [Tauri 中文文档](https://tauri.org.cn/start/create-project/) | 文档规范 | Tauri 框架中文指引 | — | 窗口自定义、标题栏、打包发布等中文指引与示例 |

### 原生框架 / 界面组件

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [Qt 官方示例](https://doc.qt.io/) | 文档规范 | Qt / QML | Qt 协议（LGPL/商业，注意授权） | 原生桌面控件与官方示例，C++/QML 项目参考；闭源商用需确认授权 |
| [Electron 官方文档](https://www.electronjs.org/) | 文档规范 | Electron | MIT | 窗口、菜单、通知、自动更新、安装包打包等官方能力与示例 |
| [Arco Design](https://arco.design/) | 组件库 | 字节桌面端组件库 | MIT | 套壳 exe 的后台/表单界面组件示例，Vue/React 双栈 |

## 三、H5（移动端营销页 / 活动页）

### 开源搭建器 / 移动端框架

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [H5-Dooring](https://github.com/MrXujiang/h5-Dooring) | 搭建器/模板 | React + Node.js 开源 H5 可视化搭建器 | GPL（闭源商用需评估） | 拖拽搭建 H5 落地页，含组件库/交互/数据源/出码；GPL 有传染性，闭源商用前务必评估 |
| [Vant 4](https://github.com/youzan/vant) | 组件库（跨端） | Vue3 + 移动端 H5 | MIT | 80+ 移动端组件，H5 页面 UI 直接拼装，支持主题定制/暗色模式；小程序版见 Vant Weapp |
| [hello-uniapp](https://gitee.com/dcloud/hello-uniapp) | 示例工程（跨端） | uni-app 官方示例 | MIT | 一套代码发 H5/小程序/App，官方演示工程，扫码可体验 |
| [uni-app 框架](https://gitee.com/dcloud/uni-app) | 框架（跨端） | Vue.js 跨端框架 | Apache-2.0 | 编写一套代码发布 H5 与各小程序/App，国内生态丰富 |

### 开源动画 / 图表 / 静态模板

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [animate.css](https://github.com/daneden/animate.css) | 组件库(动画) | CSS 动画库 | MIT | 页面元素入场/强调动画，class 直接调用 |
| [AOS](https://github.com/michalsnik/aos) | 组件库(动画) | 滚动入场动画库 | MIT | 长 H5 滚动到可视区触发动画，配置简单 |
| [Apache ECharts](https://github.com/apache/echarts) | 组件库(图表) | 移动端图表 | Apache-2.0 | H5 数据图表/大屏可视化，移动端适配 |
| [HTML5 UP 移动适配模板](https://html5up.net) | 静态模板 | 响应式静态模板 | CC BY 3.0（需署名） | 移动端适配的落地页/活动页静态模板；商用需保留署名 |
| [Start Bootstrap 移动模板](https://startbootstrap.com) | 静态模板 | Bootstrap 静态模板 | MIT | 移动端/Landing 页静态模板，可直接改内容 |
| [Vant 官方示例合集](https://github.com/youzan/vant-demo) | 示例工程（跨端） | Vant 组件 demo | MIT | 各组件在线示例与代码，做 H5/小程序页面时对照复用 |

## 四、App（移动端原生 / 跨端）

### React Native / Expo

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [Obytes RN Template](https://github.com/obytes/react-native-template-obytes) | 模板 | Expo + Expo Router + TS + NativeWind + React Query + Zustand | MIT | 生产级 Expo 起步模板，多环境构建、表单校验、安全存储、国际化预置 |
| [Ignite (Infinite Red)](https://github.com/InfiniteRed/ignite) | 模板 | React Native 成熟脚手架 | MIT | 页面/组件生成器、完整测试配置，适合长期维护的团队项目 |
| [create-expo-stack](https://github.com/andrew-levy/create-expo-stack) | 模板(CLI) | CLI 自选 Expo Router/导航/样式方案/认证栈 | MIT | 命令行按偏好拼装 Expo 工程骨架 |
| [Expo 官方模板](https://docs.expo.dev) | 文档规范/示例 | Expo / React Native | MIT | 官方 starter 与示例文档，最基础的 RN 起步参考 |

### 跨端 / Flutter / 组件库

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [uni-app](https://gitee.com/dcloud/uni-app) | 框架（跨端） | Vue 跨端框架 | Apache-2.0 | 一套代码发 iOS/Android/H5/小程序，国内插件生态全 |
| [hello-uniapp](https://gitee.com/dcloud/hello-uniapp) | 示例工程（跨端） | uni-app 官方示例 | MIT | 跨端完整演示工程，含常用页面与能力示例 |
| [TDesign Flutter](https://github.com/Tencent/tdesign-flutter) | 组件库 | 腾讯 Flutter 组件库 | MIT | Flutter App 界面组件，风格统一 |
| [NativeWind](https://github.com/nativewind/nativewind) | 组件库(样式) | RN 的 Tailwind 样式方案 | MIT | Expo 生态常用，用 Tailwind 类名写 RN 样式 |
| [React Native Paper](https://github.com/callstack/react-native-paper) | 组件库 | Material Design RN 组件库 | MIT | RN 基础组件现成可用，符合 Material 规范 |
| [uni-starter](https://doc.dcloud.net.cn/uniCloud/uni-starter) | 模板（跨端） | uniCloud 云端一体商用模板 | DCloud 服务协议（可商用） | 预置登录注册、个人中心、权限、拦截器等通用功能；H5/小程序/App 通用 |

## 五、小程序

### 开源组件库

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [Vant Weapp](https://github.com/youzan/vant-weapp) | 组件库 | 微信小程序组件库 | MIT | 轻量可靠，80+ 组件，零外部依赖，TS 类型完整 |
| [TDesign miniprogram](https://github.com/Tencent/tdesign-miniprogram) | 组件库 | 腾讯小程序组件库 | MIT | 企业级设计体系，组件完整、文档规范，npm 安装 |
| [WeUI (weui-wxss)](https://github.com/weui/weui-wxss) | 组件库/样式库 | 微信官方样式库 | MIT | 与微信原生视觉一致的基础样式与组件 |
| [ColorUI](https://github.com/weilanwl/ColorUI) | 组件库/样式框架 | 小程序 CSS 框架 | MIT | class 调用组件与模板样式；Gitee 备用仓库 https://gitee.com/color-ui/MP-CU |
| [TDesign uniapp](https://tdesign.tencent.com/) | 组件库（跨端） | 腾讯 uni-app 组件 | MIT | 跨端组件，一套用于小程序与 App/H5 |

### 模板 / 示例 / 规范

| 项目 | 类型 | 技术栈 | 协议 | 用途 |
| --- | --- | --- | --- | --- |
| [hello-uniapp](https://gitee.com/dcloud/hello-uniapp) | 示例工程（跨端） | 多端官方示例 | MIT | 小程序 + H5 + App 同工程示例，页面结构可直接参考 |
| [Vant demo 示例](https://github.com/youzan/vant-demo) | 示例工程（跨端） | Vant 小程序示例合集 | MIT | 官方组件示例工程，微信开发者工具导入预览 |
| [uni-starter](https://doc.dcloud.net.cn/uniCloud/uni-starter) | 模板（跨端） | 商用功能模板 | DCloud 服务协议（可商用） | 登录、个人中心、权限等通用模块预置；H5/小程序/App 通用 |
| [WeDesign 官方设计规范](https://wechat.design/tool/) | 文档规范 | 微信原生视觉规范文档 | — | 配色、字体、组件规范参考（文档资源，非代码仓库） |
| [uni-app 框架](https://gitee.com/dcloud/uni-app) | 框架（跨端） | 跨端基础框架 | Apache-2.0 | 小程序工程基础框架与能力支撑 |

## 六、纯灵感参考站（不开源，仅看设计）

> 以下站点不提供可下载源码，只用于看版式、配色、交互风格；需要可运行代码时，以上面开源仓库为准。

- [站酷 ZCOOL](https://www.zcool.com.cn)
- [UI中国](https://www.ui.cn)（域名有效，部分网络环境直连可能不稳定，备选子域 https://hubo.ui.cn/）
- [美叶（已上线 App/小程序截图）](https://www.meiye.art)
- [花瓣网（灵感画板）](https://huaban.com)
- [Mobbin（全球已上线 App 流程截图，国际站）](https://mobbin.com)

---

> 免责声明：本清单仅汇总第三方开源项目的链接与简要用途，不代表对各项目的背书；使用前请自行核对其开源协议、版本与维护状态。
