<style>
  /* CSS Toggle Logic for EN/CN */
  input[name="lang"] { display: none; }
  .content-en, .content-cn { display: none; }
  #toggle-en:checked ~ .content-en { display: block; }
  #toggle-cn:checked ~ .content-cn { display: block; }

  /* Language Buttons */
  .lang-btn-container { text-align: center; margin-bottom: 20px; }
  label[for="toggle-en"], label[for="toggle-cn"] {
    display: inline-block; padding: 8px 16px; margin: 0 8px; border-radius: 6px; cursor: pointer; font-weight: bold; border: 2px solid #d0d7de; background: #f6f8fa; color: #24292f; transition: all 0.2s;
  }
  label[for="toggle-en"]:hover, label[for="toggle-cn"]:hover { background: #e1e4e8; }
  #toggle-en:checked ~ .lang-btn-container label[for="toggle-en"],
  #toggle-cn:checked ~ .lang-btn-container label[for="toggle-cn"] {
    background: #2da44e; color: white; border-color: #2da44e;
  }

  /* Card styling */
  .card-container { display: flex; flex-wrap: wrap; gap: 16px; margin: 20px 0; justify-content: center; }
  .card { background: #f6f8fa; border: 1px solid #d0d7de; border-radius: 8px; padding: 16px; width: 300px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
  .card h3 { margin-top: 0; font-size: 1.1em; }
  .btn-subscribe { display: inline-block; padding: 10px 20px; background-color: #2da44e; color: white; border-radius: 6px; text-decoration: none; font-weight: bold; margin-top: 10px; border: none; }
  .btn-subscribe:hover { opacity: 0.9; text-decoration: none; }
</style>

<!-- Hidden Radio Buttons for Toggle -->
<input type="radio" name="lang" id="toggle-en" checked>
<input type="radio" name="lang" id="toggle-cn">

<!-- Visible Language Switcher Buttons -->
<div class="lang-btn-container">
  <label for="toggle-en">🇺🇸 English</label> 
  <label for="toggle-cn">🇨🇳 中文</label>
</div>

<!-- ================= ENGLISH CONTENT ================= -->
<div class="content-en" align="center">

### 👋 Hi, I'm **Rong Fan**

🛡️ Lightning Protection Researcher | 💹 Quant Developer | 🏥 US Healthcare IT Professional

---

## 🔬 Three Domains of Expertise

#### ⚡ Lightning Science & Protection Technology
**Research focus:** Lightning location system data analysis, flash density computation, GIS visualization.
- Published multiple papers on lightning data processing algorithms.
- Developed [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) — an open-source cross-platform library for lightning spatiotemporal analysis (published on NuGet).

#### 💹 Quantitative Trading & Financial Technology
**Research focus:** Multi-source market data ingestion, broker execution systems, real-time analytics.
- Built [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) — a one-stop .NET infrastructure for quantitative trading (Binance/IB/Schwab unified API, real-time alerting, portfolio analytics).

#### 🏥 US Healthcare IT
**Research focus:** FHIR R4/R5 interoperability, clinical data ETL pipelines, semantic validation with AI.
- Developed [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) — a production-ready Healthcare Interoperability Engine built on .NET 10, implementing HL7 FHIR R4/R5 compliance for the 21st Century Cures Act mandate.

---

## 🚀 Key Projects
| Project | Description | License |
|---------|-------------|---------|
| [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) ⭐7 | Open-source lightning location data analysis library (.NET, cross-platform) | GPLv3 |
| [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) | Quantitative trading infrastructure in .NET | MIT |
| [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) | AI-driven FHIR R4/R5 interoperability engine (.NET 10, Healthcare IT) | MIT |

---

## 🎓 Academic Profiles
- 🔗 **[Rong Fan - Google Scholar](https://scholar.google.com/citations?user=Zxn84ckAAAAJ&hl=en)**
- 🔗 **[Baidu Xueshu - 樊荣](https://xueshu.baidu.com/scholarID/CN-BM75JUJJ)**

---

## 📦 NuGet Packages
| Package | Downloads | Version |
|---------|-----------|---------|
| [LLSDA](https://www.nuget.org/packages/LightningLocationSystemDataAnalyzer-LLDSA/) | ![Downloads](https://img.shields.io/nuget/dt/LightningLocationSystemDataAnalyzer-LLDSA) | ![Version](https://img.shields.io/nuget/v/LightningLocationSystemDataAnalyzer-LLDSA.svg) |

---

## 💼 Professional Links
- 📧 **Email**: [fanrong1985@126.com](mailto:fanrong1985@126.com)
- 🔗 **LinkedIn**: [linkedin.com/in/rongfan1031](https://www.linkedin.com/in/rongfan1031/)
- 📝 **Medium**: [medium.com/@rex.fan18](https://medium.com/@rex.fan18)

---

## ☕ Collaboration
If you are working on lightning research, quant development, or healthcare IT projects and believe a collaboration could be mutually beneficial — feel free to reach out via email or submit an issue/PR in the relevant repository.

</div>

<!-- ================= CHINESE CONTENT ================= -->
<div class="content-cn" align="center">

### 👋 你好，我是 **樊荣 (Rong Fan)**

🛡️ 防雷专家 | 💹 量化开发者 | 🏥 美国医疗 IT 从业者

---

## 🔬 三大研究领域

#### ⚡ 雷电科学与技术
**研究方向：** 闪电定位系统数据分析、雷击密度计算、GIS 可视化。
- 发表多篇关于雷电数据处理算法的学术论文。
- 开发了 [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) —— 一个开源跨平台的闪电时空分析类库（已在 NuGet 发布）。

#### 💹 量化交易与金融科技
**研究方向：** 多源市场数据接入、券商执行系统、实时数据分析。
- 构建了 [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) —— 一站式 .NET 量化交易基础设施（Binance/IB/嘉信统一 API、实时预警、投资组合分析）。

#### 🏥 美国医疗信息技术 (Healthcare IT)
**研究方向：** FHIR R4/R5 互操作性、临床数据 ETL 流水线、基于 AI 的语义验证。
- 开发了 [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) —— 基于 .NET 10 构建的生产级医疗互操作性引擎，实现了符合《21世纪治愈法案》标准的 HL7 FHIR R4/R5 合规性。

---

## 🚀 核心项目
| 项目 | 简介 | 许可证 |
|---------|-------------|---------|
| [LLSDA](https://github.com/memoryfraction/LLSDA-Lightning-Location-System-Data-Analyzer) ⭐7 | 开源闪电定位数据分析库 (.NET, 跨平台) | GPLv3 |
| [Quant.Infra.Net](https://github.com/memoryfraction/Quant.Infra.Net) | .NET 量化交易基础设施 | MIT |
| [HealthData-Interoperability-Csharp](https://github.com/memoryfraction/HealthData-Interoperability-Csharp) | AI驱动的 FHIR R4/R5 互操作性引擎 (.NET 10, 医疗IT) | MIT |

---

## 🎓 学术主页
- 🔗 **[Rong Fan - Google Scholar](https://scholar.google.com/citations?user=Zxn84ckAAAAJ&hl=en)**
- 🔗 **[樊荣 - 百度学术](https://xueshu.baidu.com/scholarID/CN-BM75JUJJ)**

---

## 📦 NuGet 发布包
| 软件包 | 下载量 | 版本 |
|---------|-----------|---------|
| [LLSDA](https://www.nuget.org/packages/LightningLocationSystemDataAnalyzer-LLDSA/) | ![Downloads](https://img.shields.io/nuget/dt/LightningLocationSystemDataAnalyzer-LLDSA) | ![Version](https://img.shields.io/nuget/v/LightningLocationSystemDataAnalyzer-LLDSA.svg) |

---

## 💼 职业主页
- 📧 **邮箱**: [fanrong1985@126.com](mailto:fanrong1985@126.com)
- 🔗 **LinkedIn**: [linkedin.com/in/rongfan1031](https://www.linkedin.com/in/rongfan1031/)
- 📝 **Medium 博客**: [medium.com/@rex.fan18](https://medium.com/@rex.fan18)

---

## ☕ 合作邀请
如果您从事雷电研究、量化开发或医疗 IT 项目，并认为我们可以进行互利的合作 —— 请随时通过电子邮件联系我，或在相关仓库提交 Issue / PR。

</div>

<!-- ================= SUBSCRIPTION SECTION (BILINGUAL) ================= -->
<div align="center" style="margin-top:40px; border-top:1px solid #d0d7de; padding-top:20px;">
<h3>📩 Stay in the Loop / 订阅更新</h3>
<p><strong>Want early access to my open-source tools, research papers, and tech insights?<br>希望第一时间获取我的开源工具、论文和资讯？</strong></p>

<!-- Mailchimp Button -->
<a href="https://fanrong-us4.list-manage.com/subscribe?u=YOUR_GROUP_ID&id=YOUR_FORM_ID" class="btn-subscribe" target="_blank">📧 Join My Mailing List</a>

<div style="margin-top:20px;">
    <!-- Paste your Mailchimp <iframe> embed code below this line -->
</div>
</div>
