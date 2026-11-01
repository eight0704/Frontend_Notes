# meta 元信息

`meta` 是单标签，通常写在 `<head>` 标签中，用于配置网页的元信息。

## 配置字符编码

```html
<meta charset="utf-8">
```

## 针对 IE 浏览器的兼容性配置

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

## 针对移动端的配置

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## 配置网页关键字

```html
<meta name="keywords" content="8-12个以英文逗号隔开的单词/词语">
```

## 配置网页描述信息

```html
<meta name="description" content="80字以内的一段话，与网站内容相关">
```

## 针对搜索引擎爬虫配置

```html
<meta name="robots" content="此处可选值见下表">
```

| 值 | 描述 |
| --- | --- |
| `index` | 允许搜索爬虫索引此页面。 |
| `noindex` | 要求搜索爬虫不索引此页面。 |
| `follow` | 允许搜索爬虫跟随此页面上的链接。 |
| `nofollow` | 要求搜索爬虫不跟随此页面上的链接。 |
| `all` | 与 `index`、`follow` 等价。 |
| `none` | 与 `noindex`、`nofollow` 等价。 |
| `noarchive` | 要求搜索引擎不缓存页面内容。 |
| `nocache` | `noarchive` 的替代名称。 |

---

← 返回 [HTML4 章节目录](README.md)
