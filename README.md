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

除 `banners/` 下的图片外，本仓库内容以 MIT 许可协议发布，全文见 [LICENSE](LICENSE)，版权行为 `Copyright (c) 2026 CrimsonSeraph`。

允许使用、复制、修改、合并、发布、分发、再许可与销售本仓库内容，包括商业用途，条件是在副本或重要部分中保留上述版权声明与许可声明。内容按「原样」提供，不带任何形式的明示或默示担保。

本仓库目前只有 README 与 `banners/` 下的图片，没有可以加注释的源码文件；后续加入的源文件会在文件头加两行 SPDX 声明，标识符为 `MIT`。

### 封面图版权

`banners/gsi.jpg` 与 `banners/warthunder.jpg` 是对应游戏（Game State Integration、War Thunder）的第三方游戏美术素材，版权归各自权利人所有，本仓库不主张任何权利。这两张图仅用于标识对应的插件、供插件市场展示识别，**不受本仓库 MIT 许可覆盖**，不属于 MIT 许可授权的一部分；在其他场合使用需自行向原权利人取得授权。

## 相关仓库

- [DG-LAB-Client](https://github.com/CrimsonSeraph/DG-LAB-Client) — 主程序
- [DG-LAB-Client-Web](https://github.com/CrimsonSeraph/DG-LAB-Client-Web) — 官网与静态资源分发
