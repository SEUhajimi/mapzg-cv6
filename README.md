# 战国七雄 V3 · 交付文件索引

| 文件夹 | 内容 | 怎么用 |
|---|---|---|
| `01_安装包/` | `Zhanguo_V3_Mod.zip` | 解压后把 `Zhanguo_V3` 整个文件夹放进 `文档\My Games\Sid Meier's Civilization VI\Mods\`，游戏里启用，开局选"战国七雄 V3"、尺寸"巨大" |
| `02_地图集/` | 14 张 PNG | `00_全图` 是总览（右侧有出生点和运河位说明）；`01~07` 分区图；`08~10` 荆州、合肥南京、吴越详图；`11~13` 大运河与水路 |
| `03_文档/` | `地图设定说明.md`、`更新记录.md` | 设定总览、数据、已知局限、未验证清单；每次改动的记录 |
| `04_源码仓库/` | `mapzg-cv6.bundle`、`mapzg-cv6-repo.zip` | bundle 含完整提交记录（`git clone mapzg-cv6.bundle` 即可）；zip 只有文件 |

推送到 GitHub：

```
git clone mapzg-cv6.bundle mapzg-cv6
cd mapzg-cv6
git remote set-url origin https://github.com/SEUhajimi/mapzg-cv6.git
git push -u origin main
```
