# 2027 CNY 项目时间线

微信广告 2027 CNY 项目启动会用 — 项目关键节点时间线页面，遵循微信营销官方 VI 风格（`wxad-style`）。

## 页面结构

1. **Hero + 6 个里程碑 Ribbon**：8 月底对 🐲 的汇报 / 9 月需求评审 / 10 月中下旬招商 / 12/1 首发 / 1/7 陆续上线 / 2/6 表情雨
2. **01 总览时间线**：7 行泳道 × 9 个月（2026.7 → 2027.3），含纵向引导线、上线里程碑徽章和对 🐲 汇报里程碑
3. **02 日历视图**：8 个月每月一行，左侧月份重点 + 右侧产品 / 设计 / 运营 / 研发 4 列分角色 ToDo
4. **03 下一关键节点**：7/7 全员脑暴 + W1–W4 每周一个关键成果

## 本地预览

```bash
cd 2027-cny-timeline
python3 -m http.server 8077
# 打开 http://localhost:8077/index.html
```

## 目录

```
2027-cny-timeline/
├── index.html              # 主页面（单文件，含全部样式）
├── assets/
│   ├── brand-logos/        # 微信营销 / 腾讯营销 lockup
│   ├── fonts/gilroy/       # Gilroy 6 字重
│   └── *.svg               # 产品线 icon
└── README.md
```

## 设计规范

- 主色：微信营销绿 `#07C160`
- 字体：Gilroy（数字 / 英文）+ 汉仪旗黑（中文标题）
- 圆角：14px 卡片 / 6px 按钮 / 4px 标签
- 阴影：`shadow-as-border`（不用 border）
- 完整规范见 `wxad-style` skill
