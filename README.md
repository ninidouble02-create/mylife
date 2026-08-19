# My Life OS PWA v0.2

本版本基于 PRD v1.1 更新，新增 Anniversary / 纪念日。

## v0.2 新增
- Plan 页面新增 Anniversary 入口与列表
- 新建纪念日：名称、日期、公历/农历标记、每年/每月/不重复
- 倒数日 / 累计天数
- 提前提醒设置字段
- 临近纪念日在 Today「轻提醒」出现
- 纪念日详情可“记下今天”，自动写入 Life
- Archive 增加纪念日数量摘要
- My Space 增加 Anniversary 入口
- 保持原底栏 Today / Plan / ＋ / Life / Archive 不变
- Focus 继续保持悬浮逻辑，不占底部导航

### 说明
V0.2 对农历先完成数据字段和界面支持；真实农历换算与农历重复日期计算在后续版本完善。

# My Life OS PWA V0.1

这是一个可安装的 PWA 项目，不是效果图。

## 当前能试用
- Today：首页、My Day、今日计划、轻提醒
- 全局 ＋：记账、Life、体重、计划、饮品、Focus
- Plan：日历 + 列表、完成计划、从计划直接开始 Focus
- Focus：番茄、倒计时、正计时；开始后以悬浮计时器存在，可继续浏览其他页面
- Life：私人生活流
- 饮品：保存后进入 Life；填写价格时同步生成 Money 数据
- Archive：读取 Life / Plan / Focus / Drinks 的基础摘要
- 数据保存在浏览器本地 localStorage
- Service Worker 离线缓存
- iPhone 主屏幕图标 + standalone 模式

## 安装前必须知道
PWA 需要通过 HTTPS 地址访问才能在 iPhone 上完整安装并启用 Service Worker。直接打开本地 HTML 只能预览。

## 0 元部署
可使用任意免费的静态 HTTPS 托管，例如 GitHub Pages、Cloudflare Pages 或 Netlify。

部署后：iPhone Safari 打开网址 → 分享 → 添加到主屏幕。
