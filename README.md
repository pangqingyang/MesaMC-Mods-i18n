# MesaMC Mods i18n

MesaMC 的社区模组汉化对照库。

## 文件

- `mods-name.json`：Modrinth slug/项目 ID → 中文名称
- `mods-desc.json`：Modrinth slug/项目 ID → 中文简介

两个文件都是普通 JSON 对象。键优先使用稳定的 Modrinth slug，也可以使用项目 ID。

## 贡献格式

```json
{
  "sodium": "钠"
}
```

请保持：

- UTF-8 编码；
- 有效 JSON；
- 不修改模组文件本身；
- 中文简介准确、简洁，不加入宣传内容；
- 一个 PR 尽量只处理一组相关模组。

## CDN

```text
https://cdn.jsdelivr.net/gh/pangqingyang/MesaMC-Mods-i18n@main/mods-name.json
https://cdn.jsdelivr.net/gh/pangqingyang/MesaMC-Mods-i18n@main/mods-desc.json
```

本仓库必须保持公开，jsDelivr 才能访问。MesaMC 会缓存最后一次成功下载的内容；CDN 暂时不可用时不会影响启动。


## 数据范围与参考

首批数据优先覆盖 Modrinth 按下载量排序的热门模组，以及 MesaMC 用户实际安装的项目。

整理时参考了以下公开社区项目的分类、常用模组清单和术语习惯：

- [Wulian233/mcmod-translation-dict](https://github.com/Wulian233/mcmod-translation-dict)
- [CFPAOrg/Minecraft-Mod-Language-Package](https://github.com/CFPAOrg/Minecraft-Mod-Language-Package)
- [zawh4159/MinecraftMods](https://github.com/zawh4159/MinecraftMods)
- [Modrinth API](https://docs.modrinth.com/api/)

本仓库的名称与简介由 MesaMC 项目重新整理，不批量复制其他项目的翻译文件。若译名存在争议，请通过 Pull Request 修订。
