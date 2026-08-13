<style>
/* Toggle Logic */
input[name="lang"] { display: none; }
.content-en, .content-cn { display: none; }
#toggle-en:checked ~ .content-en,
#toggle-cn:checked ~ .content-cn { display: block; }

/* Button Styles */
.btn-toggle {
  display: inline-block; padding: 8px 16px; margin: 0 8px; border-radius: 6px; cursor: pointer; font-weight: bold; text-align: center;
  background-color: #f6f8fa; border: 2px solid #d0d7de; color: #24292f; text-decoration: none !important; transition: all 0.2s ease;
}
.btn-toggle:hover { background-color: #e1e4e8; }

/* Active State */
#toggle-en:checked ~ .lang-container label[for="toggle-en"],
#toggle-cn:checked ~ .lang-container label[for="toggle-cn"] {
  background-color: #2da44e; color: white !important; border-color: #2da44e;
}

/* Layout Helpers */
.container-center { text-align: center; }
.btn-subscribe { display: inline-block; padding: 10px 20px; background-color: #2da44e; color: white; border-radius: 6px; text-decoration: none !important; font-weight: bold; margin-top: 15px; }
</style>

<!-- Hidden Radio Inputs -->
<input type="radio" name="lang" id="toggle-en" checked>
<input type="radio" name="lang" id="toggle-cn">

<!-- Visible Toggle Buttons -->
<div class="lang-container container-center">
  <label for="toggle-en" class="btn-toggle">🇺🇸 English</label>
  <label for="toggle-cn" class="btn-toggle">🇨🇳 中文</label>
</div>

<!-- ================= ENGLISH CONTENT ================= -->
<div class="content-en container-center">

### 👋 Hi, I'm **Rex Fan**

🏥 US Healthcare IT Professional | 💹 Quant Developer | ⚡ Lightning Researcher

---

## 🔬 Three Domains of Expertise

#### 🏥 US Healthcare IT & Interoperability
**Research focus:** FHIR R4/R5 compliance, clinical data pipelines, semantic validation with AI.
- Developed [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) — a production-ready Healthcare Interoperability Engine built on .NET 10 for the 21st Century Cures Act mandate.

#### 💹 Quantitative Trading & FinTech
**Research focus:** Multi-source data ingestion, execution systems, real-time analytics.
- Built [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) — a one-stop .NET infrastructure for quantitative trading (Binance/IB/Schwab unified API, portfolio analytics).

#### ⚡ Lightning Science & Protection Technology
**Research focus:** Lightning location data analysis, flash density computation, GIS visualization.
- Developed [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) — an open-source cross-platform library for lightning spatiotemporal analysis (published on NuGet).

---

## 🚀 Key Projects
| Project | Description | License |
|---------|-------------|---------|
| [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) ⭐ | AI-driven FHIR R4/R5 interoperability engine (.NET 10, Healthcare IT) | MIT |
| [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) | Quantitative trading infrastructure in .NET | MIT |
| [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) ⭐7 | Open-source lightning location data analysis library (.NET, cross-platform) | GPLv3 |

---

## 🎓 Academic Profiles
- 🔗 **[Rex Fan - Google Scholar](https://scholar.google.com/citations?user=Zxn84ckAAAAJ&hl=en)**
- 🔗 **[Rex Fan - Baidu Scholar](https://xueshu.baidu.com/scholarID/CN-BM75JUJJ)**

---

## 💼 Professional Links
- 📧 **Email**: [rex.fan18@gmail.com](mailto:rex.fan18@gmail.com)
- 📅 **Book a Meeting**: [Calendly](https://calendly.com/rex-fan18/30min)
- 🔗 **LinkedIn**: [linkedin.com/in/rongfan1031](https://www.linkedin.com/in/rongfan1031/)
- 📝 **Medium**: [medium.com/@rex.fan18](https://medium.com/@rex.fan18)

---

## ☕ Collaboration
If you are working on healthcare IT, quant development, or lightning research and believe a collaboration could be mutually beneficial — feel free to reach out.

</div>

<!-- ================= CHINESE CONTENT ================= -->
<div class="content-cn container-center">

### 👋 你好，我是 **Rex Fan**

🏥 美国医疗 IT 专家 | 💹 量化开发者 | ⚡ 雷电研究者

---

## 🔬 三大研究领域

#### 🏥 美国医疗信息技术 (Healthcare IT)
**研究方向：** FHIR R4/R5 互操作性、临床数据 ETL 流水线、基于 AI 的语义验证。
- 开发了 [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) —— 基于 .NET 10 构建的生产级医疗互操作性引擎，实现了符合《21世纪治愈法案》标准的 HL7 FHIR R4/R5 合规性。

#### 💹 量化交易与金融科技
**研究方向：** 多源市场数据接入、券商执行系统、实时数据分析。
- 构建了 [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) —— 一站式 .NET 量化交易基础设施（Binance/IB/嘉信统一 API、实时预警、投资组合分析）。

#### ⚡ 雷电科学与技术 (Lightning Science)
**研究方向：** 闪电定位系统数据分析、雷击密度计算、GIS 可视化。
- 开发了 [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) —— 一个开源跨平台的闪电时空分析类库（已在 NuGet 发布）。

---

## 🚀 核心项目
| 项目 | 简介 | 许可证 |
|---------|-------------|---------|
| [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) | AI驱动的 FHIR R4/R5 互操作性引擎 (.NET 10, 医疗IT) | MIT |
| [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) | .NET 量化交易基础设施 | MIT |
| [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) ⭐7 | 开源闪电定位数据分析库 (.NET, 跨平台) | GPLv3 |

---

## 🎓 学术主页
- 🔗 **[Rex Fan - Google Scholar](https://scholar.google.com/citations?user=Zxn84ckAAAAJ&hl=en)**
- 🔗 **[Rex Fan - Baidu Scholar (百度学术)](https://xueshu.baidu.com/scholarID/CN-BM75JUJJ)**

---

## 💼 职业主页
- 📧 **邮箱**: [rex.fan18@gmail.com](mailto:rex.fan18@gmail.com)
- 📅 **预约会议**: [Calendly](https://calendly.com/rex-fan18/30min)
- 🔗 **LinkedIn**: [linkedin.com/in/rongfan1031](https://www.linkedin.com/in/rongfan1031/)
- 📝 **Medium 博客**: [medium.com/@rex.fan18](https://medium.com/@rex.fan18)

---

## ☕ 合作邀请
如果您从事医疗 IT、量化开发或雷电研究，并认为我们可以进行互利的合作 —— 请随时通过邮件联系我或在相关仓库提交 Issue / PR。

</div>

<!-- ================= SUBSCRIPTION SECTION (BILINGUAL) ================= -->
<div align="center" style="margin-top:40px; border-top:1px solid #d0d7de; padding-top:20px;">
<h3>📩 Stay in the Loop / 订阅更新</h3>
<p><strong>Want early access to my open-source tools, research papers, and tech insights?<br>希望第一时间获取我的开源工具、论文和资讯？</strong></p>

<!-- Mailchimp Button -->
<a href="https://github.us5.list-manage.com/subscribe?u=b84c103f99360d3605739e59e&id=a93d0d33ce" class="btn-subscribe" target="_blank">📧 Join My Mailing List</a>

</div>
