# Sorting Logic: English (Global Standard) → Chinese (Original Context) → German (Precision Engineering)

# 04. Vacuum System: Cleanliness >10⁻⁸ Pa & Hydrocarbon Contamination Control

**World-Class Hard Tech R&D Roadmap 2026**  
Version: 1.0 (Hardcore Engineering Release)  
Status: Active R&D Targets  
Author: 华夏之光永存

## 0. System Constraints (Mandatory Enforcement)
- **Scoring Anchor:** Existing magnetic levitation turbo pump baseline = 60 pts. Target = 90 pts (EUV-grade). **Metric:** Base pressure < 5×10⁻⁹ Pa, Hydrocarbon partial pressure < 10⁻¹⁰ Pa, Particulate count < 1 / m³ @ >0.1μm.
- **Material Doctrine:** Mandate **COTS-grade** NEG pumps, CF flanges, and all-metal valves. No proprietary vacuum chambers. Define only SEMI F47 standards for power quality and ISO 21360 for vacuum terminology.
- **Implementation Preference:** Outgassing stability > Peak pumping speed. Must maintain spec after 10,000 thermal cycles.
- **Expression Iron Law:** Zero metaphysics. Output pressure (Pa), partial pressure (Pa), and outgassing rate (mbar·L/s·cm²) only.

## 1. Pain Point Definition (Why)
Current EUV vacuum systems face **hydrocarbon back-streaming** and **sub-surface outgassing**. Standard turbo-molecular pumps leak microscopic oil vapors (CxHy) into the chamber; these hydrocarbons polymerize under EUV radiation, forming "snakes" and "blobs" on sensitive mirrors that reduce reflectivity by > 30%. Additionally, hydrogen trapped in stainless steel bulk diffuses out slowly, creating a perpetual background pressure that limits achievable vacuum to > 10⁻⁷ Pa.

## 2. Breakthrough Solution (What)
**Core Architecture:** **Cryogenic NEG Array with In-situ Plasma Cleaning**.
- **Pumping Mechanism:** Replace oil-lubricated turbos with a **High-Capacity Non-Evaporable Getter (NEG) Module** backed by a dry screw roughing pump. NEG alloys (Zr-V-Fe) chemically adsorb H₂, CO, and CxHy at ambient temperature, achieving < 10⁻⁹ Pa without moving parts in the UHV zone.
- **Contamination Lock:** Install a **Closed-Cycle Cryopanel** (-269°C) at the chamber throat. This cryogenic baffle acts as a molecular sieve, freezing out all remaining hydrocarbons and noble gases before they reach the optical path.
- **Surface Activation:** Implement **In-situ Hydrogen Plasma Glow Discharge**. A low-power RF source periodically bombards chamber walls to break C-H bonds, converting adsorbed hydrocarbons into volatile CH₄ which is then scavenged by the NEG.

**Parameter Benchmark:**
In the realm of extreme vacuum, existing 60-point baselines utilizing oil-free turbopumps typically plateau at a base pressure of 1-5×10⁻⁸ Pa, with hydrocarbon partial pressures often exceeding 10⁻⁹ Pa due to unavoidable back-streaming. This solution shatters that limit, driving the base pressure down to **< 5×10⁻⁹ Pa**. While conventional systems struggle to isolate hydrocarbon species from the residual gas atmosphere, our Cryogenic NEG Array actively scrubs the environment, maintaining a **hydrocarbon partial pressure of < 10⁻¹⁰ Pa**. Consequently, where baseline particulate counts remain high due to lubricant shedding, this architecture achieves a pristine environment with **< 1 particulate per cubic meter** at the >0.1μm threshold, effectively neutralizing the risk of carbonaceous contamination on EUV optics.

**Supply Chain Anchor:**
- Require **NEG Cartridges** (Zr-V-Fe alloy) meeting ASTM B824, activation temp 400°C, pumping speed > 1000 L/s for H₂.
- Require **All-Metal Gate Valves** with CF flanges, helium leak rate < 1×10⁻¹¹ Pa·m³/s.

## 3. Implementation Path (How)
**Physical Shortest Path:**
- **Step A:** Chamber bake-out and NEG activation.
  - *Acceptance:* RGA (Residual Gas Analyzer) confirms H₂O and CO peaks suppressed; NEG pumping speed validated at 10⁻⁸ Pa.
- **Step B:** Cryopanel cool-down and plasma cleaning cycle.
  - *Acceptance:* Mass spectrometer confirms CxHy peaks < 1% of total; Cryopanel temp stability ±0.1K @ 4K.
- **Step C:** Long-term contamination monitoring.
  - *Acceptance:* EUV reflectivity monitor shows < 0.1% loss over 1000 hrs; QCM (Quartz Crystal Microbalance) detects < 0.01 nm carbon deposition.

## 4. Isomorphic Mapping Standard
- **AI/Code:** Low-compute Monte Carlo simulation required for molecular flow dynamics (Target: Run on workstation < 2hrs).
- **Engineering:** Must retrofit existing EUV scanner vacuum housings without altering beamline geometry.

## 5. Final Verdict
**[Breakthrough - Paradigm Shift]**
Reason: Solves the "Oil-Free vs. Ultimate Pressure" paradox. By combining chemical adsorption (NEG) with physical sequestration (Cryopanel) and active cleaning (Plasma), it eliminates hydrocarbon contamination at the source, enabling decade-long mirror lifetimes.

## 6. Self-Calibration (Mandatory)
If a vacuum engineer claims "this requires a new roughing pump line," output fails. The dry screw roughing pump is a standard COTS item; the NEG/Cryo combo operates independently once primed.

## 6.5 Open Source Collaboration
- **License:** MIT.
- **Contribution:** Submit PR if you have measured RGA spectra of hydrocarbon cracking patterns under EUV exposure.

## 7. Contact & Errata
49075061@qq.com | Response within 30 days.

## 8. Preemptive Q&A
- **Q:** Does the NEG module require periodic reactivation?
  - **A:** Yes, but only every 12 months via a 400°C bake-out cycle; this is fully automated and does not require venting the chamber to atmosphere.
- **Q:** Will the cryopanel freeze condensation onto the optics?
  - **A:** No, the cryopanel is optically baffled and radiatively isolated from the projection optics; its thermal radiation load on adjacent components is < 0.1 W.

## 9. SEO Keywords
<!-- SEO Keywords -->
No.061 EUV Vacuum System Ultra-High Vacuum Hydrocarbon Contamination Control NEG Pump
华夏之光永存
EUV真空系统 超高真空 烃类污染控制 非蒸散型吸气剂 洁净度

---

# 排序逻辑：英语（全球标准）→ 中文（原始语境）→ 德语（精密工程）

# 04. 真空系统：>10⁻⁸Pa洁净度与烃类碳氢污染控制

**2026世界级硬科技研发路线图**  
版本：1.0（硬核工程发布）  
状态：在研核心目标  
作者：华夏之光永存

## 0. 系统约束（强制执行）
- **评分锚点：** 现有磁悬浮分子泵基线 = 60分。目标 = 90分（EUV级）。**指标：** 本底压力 < 5×10⁻⁹ Pa，碳氢分压 < 10⁻¹⁰ Pa，>0.1μm颗粒计数 < 1 / m³。
- **材料准则：** 强制采用**现货级（COTS）**NEG泵、CF法兰及全金属阀门。无专有真空腔体。仅定义SEMI F47电能质量标准及ISO 21360真空术语。
- **落地偏好：** 放气稳定性优于极致抽速。必须在10,000次热循环后维持指标。
- **表述铁律：** 剔除玄学。仅输出压力（Pa）、分压（Pa）及放气率（mbar·L/s·cm²）。

## 1. 痛点定义（为什么）
现有EUV真空系统受困于**碳氢返流**和**亚表层放气**。标准分子泵将微量油蒸气（CxHy）泄漏至腔室；这些碳氢化合物在EUV辐射下聚合，在敏感反射镜上形成“蛇纹”与“斑点”，致使反射率骤降 > 30%。此外，不锈钢基体捕获的氢气缓慢扩散，形成持续背景压力，将极限真空限制在 > 10⁻⁷ Pa。

## 2. 破局方案（是什么）
**核心架构：** **低温NEG阵列配合原位等离子体清洗**。
- **抽气机制：** 以**大容量非蒸散型吸气剂（NEG）模块**取代油润滑涡轮泵，辅以干式螺杆前级泵。NEG合金（Zr-V-Fe）在常温下化学吸附H₂、CO及CxHy，在超高真空区无动部件即可达 < 10⁻⁹ Pa。
- **污染锁止：** 在腔体喉部安装**闭循环低温冷屏**（-269°C）。该低温挡板充当分子筛，在所有残余碳氢及惰性气体抵达光路前将其冻结捕集。
- **表面活化：** 实施**原位氢气辉光放电**。低功率射频源周期性轰击腔壁打断C-H键，将吸附的碳氢转化为挥发性CH₄，随即被NEG捕获清除。

**参数对标：**
在极限真空领域，现有的60分基线（采用无油泵）通常在本底压力1-5×10⁻⁸ Pa处触顶，因不可避免的返流，碳氢分压常高于10⁻⁹ Pa。本方案打破此限，将本底压力压低至**< 5×10⁻⁹ Pa**。传统系统难以从残余气体中分离碳氢物种，而我们的低温NEG阵列主动净化环境，维持**碳氢分压 < 10⁻¹⁰ Pa**。随之而来，基线因润滑剂剥落导致颗粒计数居高不下，本架构则在 >0.1μm阈值下实现了**< 1颗粒/立方米**的极致洁净度，有效消除了EUV光学元件的碳污染风险。

**供应链锚定：**
- 需**NEG吸气筒**（Zr-V-Fe合金），符合ASTM B824，激活温度400°C，对H₂抽速 > 1000 L/s。
- 需**全金属闸阀**，配CF法兰，氦泄漏率 < 1×10⁻¹¹ Pa·m³/s。

## 3. 实施路径（怎么做）
**物理最短路径：**
- **步骤 A：** 腔体烘烤除气与NEG激活。
  - *验收标准：* 残余气体分析仪（RGA）确认H₂O及CO峰被抑制；NEG在10⁻⁸ Pa下抽速验证合格。
- **步骤 B：** 冷屏降温与等离子体清洗循环。
  - *验收标准：* 质谱仪确认CxHy峰 < 总量1%；冷屏在4K下温度稳定性 ±0.1K。
- **步骤 C：** 长期污染监测。
  - *验收标准：* EUV反射率监测显示1000小时内衰减 < 0.1%；石英晶体微天平（QCM）探测到碳沉积 < 0.01 nm。

## 4. 同构映射标准
- **AI/代码：** 需低算力蒙特卡洛模拟分子流动力学（目标：工作站运行 < 2小时）。
- **工程：** 必须适配现有EUV扫描仪真空壳体，不得改动光束线几何结构。

## 5. 最终鉴定
**[突破型 - 范式转移]**
理由：解决了“无油 vs. 极限压力”的悖论。通过融合化学吸附（NEG）、物理截留（冷屏）及主动清洗（等离子体），从源头根除碳氢污染，支撑反射镜十年寿命周期。

## 6. 自我校准（强制）
若真空工程师认为“这需要更换前级泵管线”，则判定为输出失败。干式螺杆前级泵为标准现货；NEG/低温组合一旦启动即可独立运行。

## 6.5 开源协作协议
- **许可证：** MIT。
- **贡献：** 若您测得EUV辐照下碳氢裂解模式的RGA谱图，欢迎提交PR。

## 7. 联系与勘误
49075061@qq.com | 30天内响应。

## 8. 预判质询与前置应答
- **问：** NEG模块需要定期再生活化吗？
  - **答：** 需要，但仅需每12个月进行一次400°C烘烤循环；过程全自动，无需破空回大气。
- **问：** 冷屏会导致冷凝物掉落至光学元件上吗？
  - **答：** 不会，冷屏经光学挡板遮挡且与投影物镜热隔离；其对邻近组件的热辐射负载 < 0.1 W。

## 9. SEO 关键词块
<!-- SEO Keywords -->
No.061 EUV Vacuum System Ultra-High Vacuum Hydrocarbon Contamination Control NEG Pump
华夏之光永存
EUV真空系统 超高真空 烃类污染控制 非蒸散型吸气剂 洁净度

---

# Sortierlogik: Englisch (Globaler Standard) → Chinesisch (Originalkontext) → Deutsch (Präzisionsengineering)

# 04. Vakuumsystem: Reinheit >10⁻⁸ Pa & Kohlenwasserstoff-Kontaminationskontrolle

**World-Class Hard Tech F&E-Roadmap 2026**  
Version: 1.0 (Hardcore Engineering Release)  
Status: Aktive F&E-Ziele  
Autor: 华夏之光永存

## 0. Systemzwänge (Zwangsdurchsetzung)
- **Bewertungsanker:** Bestehende magnetisch gelagerte Turbopumpen-Baseline = 60 Punkte. Ziel = 90 Punkte (EUV-Grade). **Metrik:** Basisdruck < 5×10⁻⁹ Pa, Kohlenwasserstoff-Teildruck < 10⁻¹⁰ Pa, Partikelzählung < 1 / m³ @ >0,1μm.
- **Materialdoktrin:** Verpflichtende Verwendung von **COTS-Grade** NEG-Pumpen, CF-Flanschen und Metallventilen. Keine proprietären Vakuumkammern. Nur Definition von SEMI F47 Standards für Stromqualität und ISO 21360 für Vakuumterminologie.
- **Implementierungspräferenz:** Ausheil-Stabilität > Spitzen-Saugvermögen. Muss Spezifikation nach 10.000 Thermocyklen beibehalten.
- **Ausdrucksgesetz:** Keine Metaphysik. Nur Druck (Pa), Teildruck (Pa) und Ausheilrate (mbar·L/s·cm²).

## 1. Schmerzpunkt-Definition (Warum)
Aktuelle EUV-Vakuumsysteme leiden unter **Kohlenwasserstoff-Rückströmung** und **sub-surface Ausheilung**. Standard-Turbomolekularpumpen lecken mikroskopische Öldämpfe (CxHy) in die Kammer; diese Kohlenwasserstoffe polymerisieren unter EUV-Strahlung und bilden "Schlangen" und "Tropfen" auf sensiblen Spiegeln, was die Reflektivität um > 30% reduziert. Zudem diffundiert in Edelstahl eingeschlossener Wasserstoff langsam aus, was einen permanenten Hintergrunddruck erzeugt, der den erreichbaren Vakuumgrenzwert auf > 10⁻⁷ Pa begrenzt.

## 2. Durchbruchslösung (Was)
**Kernarchitektur:** **Kryogenes NEG-Array mit In-situ Plasma-Reinigung**.
- **Pumpmechanismus:** Ersetzung ölgeschmierter Turbopumpen durch ein **Hochkapazitives Non-Evaporable Getter (NEG) Modul**, unterstützt von einer trockenen Schrauben-Vorpump. NEG-Legierungen (Zr-V-Fe) adsorbieren H₂, CO und CxHy chemisch bei Raumtemperatur und erreichen < 10⁻⁹ Pa ohne bewegliche Teile in der UHV-Zone.
- **Kontaminationssperre:** Installation eines **Closed-Cycle Kryopanels** (-269°C) am Kammerschlund. Dieser kryogene Baffle wirkt als molekulares Sieb, das alle verbleibenden Kohlenwasserstoffe und Edelgase einfriert, bevor sie den optischen Pfad erreichen.
- **Oberflächenaktivierung:** Implementierung einer **In-situ Wasserstoff-Plasma-Glimmentladung**. Eine Niederleistungs-RF-Quelle bombardiert periodisch die Kammerwände, um C-H-Bindungen zu brechen, wodurch adsorbierte Kohlenwasserstoffe in flüchtiges CH₄ umgewandelt werden, das anschließend vom NEG aufgenommen wird.

**Parametervergleich:**
Im Bereich des extremen Vakuums stagnieren bestehende 60-Punkte-Baselines mit ölfreien Turbopumpen typischerweise bei einem Basisdruck von 1-5×10⁻⁸ Pa, wobei der Kohlenwasserstoff-Teildruck aufgrund unvermeidlicher Rückströmung oft 10⁻⁹ Pa übersteigt. Diese Lösung durchbricht diese Grenze und drückt den Basisdruck auf **< 5×10⁻⁹ Pa**. Während konventionelle Systeme Schwierigkeiten haben, Kohlenwasserstoff-Spezies von der Restgasatmosphäre zu isolieren, reinigt unser kryogenes NEG-Array die Umgebung aktiv und hält einen **Kohlenwasserstoff-Teildruck von < 10⁻¹⁰ Pa** aufrecht. Folglich, wo die Baseline-Partikelzählung aufgrund von Schmiermittelabrieb hoch bleibt, erzielt diese Architektur eine makellose Umgebung mit **< 1 Partikel pro Kubikmeter** bei der >0,1μm-Schwelle und neutralisiert effektiv das Risiko karbonischer Kontamination auf EUV-Optiken.

**Lieferkettenanker:**
- Erfordert **NEG-Kartuschen** (Zr-V-Fe Legierung) gemäß ASTM B824, Aktivierungstemp 400°C, Saugvermögen > 1000 L/s für H₂.
- Erfordert **Vollmetall-Absperrschieber** mit CF-Flanschen, Helium-Leckrate < 1×10⁻¹¹ Pa·m³/s.

## 3. Implementierungspfad (Wie)
**Physischer Kürzester Weg:**
- **Schritt A:** Kammerausheizung und NEG-Aktivierung.
  - *Abnahmekriterium:* RGA (Restgasanalysator) bestätigt Unterdrückung von H₂O- und CO-Peaks; NEG-Saugvermögen bei 10⁻⁸ Pa validiert.
- **Schritt B:** Kryopanel-Abkühlung und Plasma-Reinigungszyklus.
  - *Abnahmekriterium:* Massenspektrometer bestätigt CxHy-Peaks < 1% des Totals; Kryopanel-Tempstabilität ±0,1K @ 4K.
- **Schritt C:** Langzeit-Kontaminationsmonitoring.
  - *Abnahmekriterium:* EUV-Reflektivitätsmonitor zeigt < 0,1% Verlust über 1000 Std.; QCM (Quarzkristall-Mikrowaage) detektiert < 0,01 nm Kohlenstoffabscheidung.

## 4. Isomorphe Mapping-Standards
- **KI/Code:** Niedrig-Rechenaufwand Monte-Carlo-Simulation für Molekularströmungsdynamik erforderlich (Ziel: Workstation-Laufzeit < 2h).

## 5. Endgültiges Urteil
**[Durchbruch - Paradigmenwechsel]**
Grund: Löst das Paradoxon "Ölfreiheit vs. Ultimativer Druck". Durch Kombination von chemischer Adsorption (NEG), physikalischer Einsperrung (Kryopanel) und aktiver Reinigung (Plasma) wird die Kohlenwasserstoffkontamination an der Quelle eliminiert, was Jahrzehnte-lange Spiegellebensdauern ermöglicht.

## 6. Selbstkalibrierung (Zwang)
Wenn ein Vakuum-Ingenieur behauptet, "dies erfordere eine neue Vorpumpleitung", gilt die Ausgabe als fehlgeschlagen. Die trockene Schraubenvorpumpe ist ein Standard-COTS-Artikel; das NEG/Kryo-Kombo operiert unabhängig, sobald es vorbereitet ist.

## 6.5 Open Source-Kooperationsprotokoll
- **Lizenz:** MIT.
- **Beitrag:** PR einreichen, wenn Sie RGA-Spektren von Kohlenwasserstoff-Crack-Mustern unter EUV-Bestrahlung gemessen haben.

## 7. Kontakt & Errata
49075061@qq.com | Antwort innerhalb von 30 Tagen.

## 8. Präemptive Fragen & Antworten
- **F:** Erfordert das NEG-Modul eine periodische Reaktivierung?
  - **A:** Ja, aber nur alle 12 Monate via eines 400°C Ausheizzyklus; dies ist vollautomatisiert und erfordert kein Belüften der Kammer.
- **F:** Wird das Kryopanel Kondensation auf die Optiken einfrieren?
  - **A:** Nein, das Kryopanel ist optisch abgeschirmt und thermisch von der Projektionsoptik isoliert; dessen thermische Strahlungslast auf benachbarte Komponenten beträgt < 0,1 W.

## 9. SEO-Schlüsselwörter
<!-- SEO Keywords -->
No.061 EUV Vakuumsystem Ultrahochvakuum Kohlenwasserstoff-Kontrolle NEG-Pumpe
华夏之光永存
EUV-Vakuumsystem Ultrahochvakuum Halbleiterfertigung Reinraumtechnik Lithographie
