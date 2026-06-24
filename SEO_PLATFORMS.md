# 🌐 全平台搜索引擎站点提交指南

> 网站：**moma-token.com**
> 最后更新：2026-06-22

---

## 一、中国主要搜索引擎

### 1. 🔴 百度（Baidu）
- **站长平台**：https://ziyuan.baidu.com/
- **提交入口**：资源提交 → 普通收录 / 快速收录
- **验证方式**：文件验证 / Meta 标签验证 / CNAME 验证
- **Sitemap 提交**：https://ziyuan.baidu.com/linksubmit/index
- **主动推送 API**：`curl -H 'Content-Type:text/plain' --data-binary @urls.txt "http://data.zz.baidu.com/urls?site=moma-token.com&token=YOUR_TOKEN"`
- **当前状态**：✅ 已验证（验证文件：`baidu_verify_codeva-PpqHeq17Qw.html`）

---

### 2. 🟠 360 搜索（Qihoo 360）
- **站长平台**：https://zhanzhang.so.com/
- **提交入口**：网站管理 → 添加网站
- **验证方式**：Meta 标签验证 / 文件验证
- **Sitemap 提交**：站长平台 → 数据提交 → Sitemap
- **Meta 验证示例**：
  ```html
  <meta name="360-site-verification" content="YOUR_CODE_HERE" />
  ```
- **当前状态**：⬜ 未提交

---

### 3. 🔵 搜狗（Sogou）
- **站长平台**：https://zhanzhang.sogou.com/
- **提交入口**：收录提交 → 网站收录
- **验证方式**：文件验证 / Meta 标签验证
- **Sitemap 提交**：站长工具 → Sitemap 提交
- **Meta 验证示例**：
  ```html
  <meta name="sogou_site_verification" content="YOUR_CODE_HERE" />
  ```
- **当前状态**：⬜ 未提交

---

### 4. 🟡 神马搜索（Shenma / UC）
- **站长平台**：https://zhanzhang.sm.cn/
- **提交入口**：网站管理 → 添加站点
- **验证方式**：文件验证 / Meta 验证
- **特点**：阿里旗下，手机端搜索量大，适合移动端 SEO
- **当前状态**：⬜ 未提交

---

### 5. 🟤 必应中国（Bing CN）
- **站长平台**：https://www.bing.com/webmasters/
- **提交入口**：添加站点 → 验证所有权
- **验证方式**：XML 文件验证 / Meta 标签验证 / CNAME 验证
- **Meta 验证示例**：
  ```html
  <meta name="msvalidate.01" content="YOUR_CODE_HERE" />
  ```
- **当前状态**：⬜ 未提交

---

## 二、国际主要搜索引擎

### 6. 🟢 Google Search Console
- **站长平台**：https://search.google.com/search-console/
- **提交入口**：添加资源 → 网址前缀
- **验证方式**：HTML 文件 / Meta 标签 / Google Analytics / DNS TXT
- **Sitemap 提交**：站点地图 → 添加新的站点地图
- **Meta 验证示例**：
  ```html
  <meta name="google-site-verification" content="YOUR_CODE_HERE" />
  ```
- **当前状态**：⬜ 未提交

---

### 7. 🔵 Bing Webmaster Tools（国际版）
- **站长平台**：https://www.bing.com/webmasters/
- **提交入口**：Add a Site → 验证 → Sitemap 提交
- **特点**：连接后可自动同步 Yahoo、DuckDuckGo 等搜索引擎部分流量
- **当前状态**：⬜ 未提交

---

### 8. 🟠 Yahoo（雅虎）
- **说明**：Yahoo 搜索结果由 Bing 提供，提交 Bing 即覆盖 Yahoo
- **无需单独提交**：✅ 提交 Bing 后自动覆盖

---

### 9. 🦆 DuckDuckGo
- **说明**：部分结果来自 Bing，部分自有爬虫
- **提交方式**：https://duckduckgo.com/duckduckgo-help-pages/results/sources/
- **建议**：提交 Bing 后自然覆盖，也可直接提交 Sitemap 到 DuckDuckGo
- **当前状态**：⬜ 未提交

---

### 10. 🌍 Yandex（俄罗斯最大搜索引擎）
- **站长平台**：https://webmaster.yandex.com/
- **提交入口**：添加站点 → 验证
- **验证方式**：HTML 文件 / Meta 标签 / DNS TXT
- **Meta 验证示例**：
  ```html
  <meta name="yandex-verification" content="YOUR_CODE_HERE" />
  ```
- **当前状态**：⬜ 未提交

---

### 11. 🌐 Naver（韩国最大搜索引擎）
- **站长平台**：https://searchadvisor.naver.com/
- **提交入口**：웹마스터 도구 → 사이트 등록
- **适用场景**：面向韩国市场时使用
- **当前状态**：⬜ 未提交（非主要目标市场）

---

### 12. 🗾 Yahoo Japan（日本）
- **站长平台**：https://webmaster.yahoo.co.jp/
- **提交入口**：サイト登録
- **适用场景**：面向日本市场时使用
- **当前状态**：⬜ 未提交（非主要目标市场）

---

## 三、AI 聚合搜索 / 新兴平台

### 13. 🤖 Perplexity AI
- **收录方式**：自然爬取（基于 Bing 和自有爬虫）
- **优化建议**：结构化数据（Schema.org）+ 高质量内容
- **无主动提交入口**

### 14. 🔍 You.com
- **收录方式**：自然爬取
- **无主动提交入口**

---

## 四、快速操作清单

| 平台 | 优先级 | 状态 | 目标市场 |
|------|--------|------|----------|
| 百度 | ⭐⭐⭐⭐⭐ | ✅ 已验证 | 中国 |
| Google | ⭐⭐⭐⭐⭐ | ⬜ 待提交 | 全球 |
| Bing（国际） | ⭐⭐⭐⭐ | ⬜ 待提交 | 全球 |
| 360搜索 | ⭐⭐⭐⭐ | ⬜ 待提交 | 中国 |
| 搜狗 | ⭐⭐⭐ | ⬜ 待提交 | 中国 |
| 神马搜索 | ⭐⭐⭐ | ⬜ 待提交 | 中国移动端 |
| Yandex | ⭐⭐ | ⬜ 待提交 | 俄罗斯/东欧 |
| Naver | ⭐ | ⬜ 可选 | 韩国 |
| Yahoo Japan | ⭐ | ⬜ 可选 | 日本 |

---

## 五、sitemap.xml 当前内容

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://moma-token.com/</loc>
    <lastmod>2026-05-13</lastmod>
    <changefreq>weekly</changefreq>
    <priority>1.0</priority>
  </url>
</urlset>
```

---

## 六、robots.txt 当前内容

```
User-agent: *
Allow: /

Sitemap: https://moma-token.com/sitemap.xml
```

---

## 七、建议下一步

1. **提交 Google Search Console**（优先级最高，全球流量）
2. **提交 Bing Webmaster Tools**（同时覆盖 Yahoo + DuckDuckGo）
3. **提交 360搜索 + 搜狗**（补全国内流量来源）
4. **更新 sitemap.xml lastmod** 为最新日期
5. 在 `index.html` `<head>` 中添加各平台 Meta 验证标签

---

*文档生成时间：2026-06-22 | 网站：moma-token.com*
