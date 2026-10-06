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
