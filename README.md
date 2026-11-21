# DG-LAB-Client-Plugin

DG-LAB-Client 的插件发布仓库：插件的源码包、发行包，以及插件市场展示所需的封面资源。

## 目录约定

```
banners/            插件市场封面图（jpg）
  gsi.jpg           Game State Integration 插件封面
  warthunder.jpg    War Thunder 插件封面
```

插件包与清单文件会在后续阶段加入本仓库；封面图按上面的约定放在 `banners/` 下，
以普通二进制文件提交，不使用 Git LFS，便于 CDN 与市场前端直接按 raw 链接引用。

## 封面图引用

```
https://raw.githubusercontent.com/CrimsonSeraph/DG-LAB-Client-Plugin/main/banners/gsi.jpg
https://raw.githubusercontent.com/CrimsonSeraph/DG-LAB-Client-Plugin/main/banners/warthunder.jpg
```

## 许可

除封面图外，本仓库中的代码与文档以 MIT 许可协议发布，全文见 [LICENSE](LICENSE)。

`banners/` 下的图片为对应游戏/厂商的素材，版权归其各自权利人所有，仅用于插件识别与展示。

## 相关仓库

- [DG-LAB-Client](https://github.com/CrimsonSeraph/DG-LAB-Client) — 主程序
- [DG-LAB-Client-Web](https://github.com/CrimsonSeraph/DG-LAB-Client-Web) — 官网与静态资源分发
