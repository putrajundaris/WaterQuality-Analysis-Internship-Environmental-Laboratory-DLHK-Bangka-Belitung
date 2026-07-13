# Method Notes — Selected Water Quality Tests

Short technical write-ups for three representative tests performed during the internship, going beyond "followed the SOP" to explain the underlying chemistry/biology and why each parameter matters.

---

## 1. COD (Chemical Oxygen Demand) — SNI 6989.02:2019

**What it measures:** The amount of oxygen equivalent required to chemically oxidize all organic matter in a water sample — a proxy for total organic pollution load.

**How it works:** The sample is sealed with a strong oxidizer, potassium dichromate (Cr₂O₇²⁻), and refluxed at high temperature. Organic compounds are oxidized, converting orange Cr₂O₇²⁻ into green Cr³⁺. The remaining/produced chromium ion concentration is read spectrophotometrically:

- 600 nm for higher-range samples (COD 100–900 mg/L)
- 420 nm for low-range samples (COD ≤ 90 mg/L)

**Why the wavelength changes:** At low COD, the color shift is too subtle to read reliably at 600 nm, so the assay switches to detecting the depletion of the orange dichromate ion itself at 420 nm — a more sensitive read at low organic loads.

**Why it matters:** High COD indicates heavy organic contamination (e.g., domestic sewage, industrial effluent) and predicts oxygen depletion risk in the receiving water body.

---

## 2. BOD₅ (Biochemical Oxygen Demand) — SNI 6989.72:2009, Winkler Method

**What it measures:** How much dissolved oxygen microorganisms consume while biologically degrading organic matter in a sample, over 5 days at a controlled temperature.

**How it works:**
1. Dissolved oxygen (DO) is fixed immediately using manganese sulfate and an iodide-azide reagent, forming a manganese hydroxide precipitate proportional to the DO present (azide neutralizes nitrite interference).
2. Sulfuric acid dissolves the precipitate, releasing free iodine (I₂) in an amount equivalent to the original DO.
3. The iodine is titrated with sodium thiosulfate; starch indicator turns from dark blue to colorless at the endpoint.
4. The same procedure is run on a duplicate sample after 5 days of dark incubation.

**BOD₅ = DO(day 0) − DO(day 5)**

**Why it matters:** Unlike COD (which oxidizes everything chemically), BOD reflects what's *biologically available* — closer to what actually happens in a river or lake as bacteria consume organic waste and deplete oxygen for fish and other aquatic life.

---

## 3. Total Coliform & Fecal Coliform — MPN (Most Probable Number) Method

**What it measures:** A statistical estimate of coliform bacteria density, used as an indicator of fecal/microbial contamination risk in water.

**How it works (two-stage):**

**Stage 1 — Presumptive test:** Serial dilutions of the sample are inoculated into Lauryl Sulfate Broth (LSB) tubes, each containing an inverted Durham tube to trap gas. Incubated 24–48h at 37°C. Gas production + turbidity = presumptive positive (lactose fermentation by coliforms).

**Stage 2 — Confirmatory test:** Positive tubes are sub-cultured into:
- **EC Broth / BGLB** (Brilliant Green Lactose Bile Broth) at 37–44°C, confirming coliform/fecal coliform via gas production
- **Tryptone Water**, tested with Kovac's Reagent for indole production (confirms *E. coli*-type fecal indicators)

The pattern of positive tubes across dilutions is matched to a standard MPN statistical table to estimate bacteria count per 100 mL.

**Why it matters:** Coliforms themselves are mostly harmless, but their presence signals a pathway for fecal contamination — meaning pathogenic organisms (e.g., *Salmonella*, hepatitis A) could also be present. This is the primary microbiological safety indicator for both drinking water and recreational/coastal waters.

---

*Methods summarized from internship training at UPTD Laboratorium Lingkungan, DLHK Provinsi Kepulauan Bangka Belitung, based on SNI/JIS reference standards.*
