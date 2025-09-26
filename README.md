# Google SEO 教学材料

> 本教程适合 **零基础新手** 学习 Google SEO，从概念到实操逐步掌握。
> 学习目标：能理解 SEO 核心原理，掌握关键词研究、页面优化、外链建设和数据分析的基本方法。

---

## 1. SEO 基础概念

### 什么是 SEO
SEO（Search Engine Optimization）即 **搜索引擎优化**，是通过优化网站结构、内容和外部链接，提高网站在 Google 等搜索引擎自然排名的过程。

### 为什么要做 SEO
- 获得 **长期免费的流量**（和广告不同）
- 增加网站曝光度与品牌影响力
- 带来高转化的精准访客

### SEO 与 SEM 的区别
- **SEO**：自然排名，长期有效，但见效较慢。
- **SEM**：付费广告，立刻见效，但需要持续花钱。

---

## 2. 关键词研究

### 关键词类型
- **核心词**：搜索量大，竞争高（如 "shoes"）
- **长尾词**：搜索量中等或低，竞争小，转化率高（如 "best running shoes for women 2025"）
- **品牌词**：包含品牌名（如 "Nike shoes"）

### 关键词研究工具
1. **Google Keyword Planner**（需要 Google Ads 账号）
2. **Ubersuggest**（免费入门）
3. **Ahrefs / SEMrush**（专业付费工具）
4. **Google Trends**（搜索趋势分析）

### 实操练习
1. 打开 [Google Trends](https://trends.google.com)
2. 搜索 "t-shirt" 和 "hoodie"
3. 比较搜索趋势，判断哪个在你的市场更受欢迎

---

## 3. 页面优化（On-Page SEO）

### Title 标签优化
- 建议长度：50-60 个字符
- 必须包含主要关键词
- 建议写法：`关键词 + 卖点 + 品牌`

✅ 示例：  
`Men's Running Shoes - Lightweight, Comfortable Sneakers | XYZ Brand`

---

### Meta Description
- 建议长度：150-160 字符
- 用一句话概括页面内容，吸引点击
- 包含关键词但不要堆砌

✅ 示例：  
`Discover our best running shoes for men. Lightweight, durable, and designed for comfort. Free shipping on all orders.`

---

### H 标签结构
- 每个页面只能有一个 H1，且包含主关键词
- H2、H3 用于分层次展示小标题

示例：
```html
<h1>Best Running Shoes for Men in 2025</h1>
<h2>Why Running Shoes Matter</h2>
<h2>Top Brands</h2>
  <h3>Nike</h3>
  <h3>Adidas</h3>
```

---

### 图片优化
- 文件名用英文+关键词：`red-running-shoes.jpg`
- 添加 ALT 属性：
```html
<img src="red-running-shoes.jpg" alt="Red lightweight running shoes for men">
```

---

### URL 优化
- URL 简短、可读、包含关键词
✅ `https://example.com/mens-running-shoes`  
❌ `https://example.com/p=123?id=567`

---

### 内部链接策略
- 相关文章之间互相链接
- 锚文本自然（避免堆砌关键词）

---

## 4. 外部优化（Off-Page SEO）

### 为什么需要外链
Google 把外链看作“投票”，高质量网站的推荐能提升你的权重。

### 获取外链的常见方法
1. **高质量内容**（别人愿意引用）
2. **客座博客**（在相关网站发表文章，带上你的链接）
3. **社交媒体推广**
4. **目录网站提交**（如 Crunchbase, ProductHunt）

### 黑帽 SEO 风险
- 买链接
- 链接农场
- 关键词堆砌  
⚠️ 可能被 Google 惩罚，排名消失。

---

## 5. 技术 SEO

### 网站速度优化
- 使用 **Google PageSpeed Insights** 检测
- 压缩图片（WebP 格式）
- 开启 CDN（Cloudflare 等）

### 移动端适配
- 响应式设计（移动端友好）
- 检测工具：[Mobile-Friendly Test](https://search.google.com/test/mobile-friendly)

### Robots.txt
- 控制哪些页面允许搜索引擎爬取
示例：
```txt
User-agent: *
Disallow: /cart/
Disallow: /checkout/
```

### Sitemap.xml
- 提供网站所有页面的目录
- 上传到 Google Search Console

### HTTPS
- 必须使用 SSL 证书（https://）
- 提升用户信任与排名

### 结构化数据（Schema Markup）
- 让搜索引擎更好理解内容
- 可展示富文本结果（评分星级、FAQ 展开）

示例（FAQ Schema）：
```json
{
 "@context": "https://schema.org",
 "@type": "FAQPage",
 "mainEntity": [{
   "@type": "Question",
   "name": "Are running shoes machine washable?",
   "acceptedAnswer": {
     "@type": "Answer",
     "text": "Most running shoes are not machine washable. Hand wash with mild soap."
   }
 }]
}
```

---

## 6. 数据分析与持续优化

### Google Analytics
- 查看流量来源（自然搜索、社交、付费广告）
- 追踪转化率

### Google Search Console
- 监控关键词点击量和展示量
- 检查页面收录和错误

### 核心指标（KPI）
- 自然流量（Organic Traffic）
- 关键词排名（Keyword Ranking）
- 点击率（CTR）
- 转化率（Conversion Rate）

---

## 7. 实战案例

### 案例 1：电商网站
- 优化产品页标题、描述
- 增加产品评论（用户生成内容）
- 架构：分类页 → 产品页 → 博客内容互链

### 案例 2：博客网站
- 选择细分领域（例如“素食食谱”）
- 长尾关键词文章（如“10 easy vegan dinner recipes”）
- 建立内部链接网络

### 案例 3：本地 SEO
- 注册 [Google Business Profile](https://www.google.com/business/)
- 优化 NAP 信息（Name, Address, Phone）
- 获得本地评论

---

## 8. 学习路径与工具推荐

### 工具清单
- 关键词：Google Keyword Planner / Ubersuggest
- 外链：Ahrefs / SEMrush
- 技术检测：Screaming Frog
- 趋势：Google Trends

### 学习网站
- [Moz Blog](https://moz.com/blog)
- [Backlinko](https://backlinko.com/)
- [Search Engine Journal](https://www.searchenginejournal.com/)

### 社区
- Reddit /r/SEO
- 专业 Facebook SEO 群组

---

## 9. 常见问题（FAQ）

**Q: SEO 多久见效？**  
A: 通常 3-6 个月才能看到明显效果。  

**Q: 新网站如何快速排名？**  
A: 从长尾关键词入手，发布高质量内容，逐步积累外链。  

**Q: Google 算法更新怎么办？**  
A: 关注官方公告，保持内容高质量，避免过度依赖单一策略。  

---

## 10. 总结

- SEO 三大支柱：内容、技术、外链  
- SEO 是一个 **长期优化过程**，不能急功近利  
- 数据驱动，持续调整，才能在 Google 排名中长期获胜
