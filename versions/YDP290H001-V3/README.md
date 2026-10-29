<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 2.9″ RLCD 显示屏 168×384（YDP290H001-V3）</h1>

<p align="center"><b>RLCD 模组 · SPI · ST7305</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: SPI" src="https://img.shields.io/badge/Interface-SPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7305" src="https://img.shields.io/badge/Driver-ST7305-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 2.9 寸 168×384 RLCD 模组宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 2.9 英寸 |
| 类型 | RLCD |
| 分辨率 | 168×384 |
| 外形尺寸 | 31.1 x 70.95 mm |
| 有效显示区域 | 29.1 x 66.85 mm |
| 接口 | SPI |
| 驱动 IC | ST7305 |
| 触摸驱动 | — |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`ST7305 APPLICATION NOTE (HSD)_122x250.pdf`](./datasheets/ST7305%20APPLICATION%20NOTE%20%28HSD%29_122x250.pdf) |
| 规格文档 | [`ST7305_V1.2.pdf`](./datasheets/ST7305_V1.2.pdf) |
| 规格文档 | [`ST_7305_V0_2_d0b99d9cdb.pdf`](./datasheets/ST_7305_V0_2_d0b99d9cdb.pdf) |
| 规格文档 | [`YDP290H001-V3.pdf`](./datasheets/YDP290H001-V3.pdf) |
| 规格文档 | [`YDP_290_H001_V3_1dcc5ea9e3.pdf`](./datasheets/YDP_290_H001_V3_1dcc5ea9e3.pdf) |
| CAD 图纸 | [`YDP290H001-V3.dwg`](./cad/YDP290H001-V3.dwg) |
| 转接板资料 | [`2.9寸全反转接板-24pin.pdf`](./adapter/2.9%E5%AF%B8%E5%85%A8%E5%8F%8D%E8%BD%AC%E6%8E%A5%E6%9D%BF-24pin.pdf) |
| 转接板资料 | [`SCH_2.9寸全反转接板_DEMO.pdf`](./adapter/SCH_2.9%E5%AF%B8%E5%85%A8%E5%8F%8D%E8%BD%AC%E6%8E%A5%E6%9D%BF_DEMO.pdf) |

## 仓库结构

```text
display-rlcd-2.9inch-168x384/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── YDP290H001-V3/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── cad/              # 外形/盖板 CAD
        └── adapter/          # 转接板资料 + 转接板图片
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
