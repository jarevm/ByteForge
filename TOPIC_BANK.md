# Topic Bank: Team ByteForge

> **Sample for class demonstration.** This file composes of the compilation of Team ByteForge's ideas.

We add one entry after every lab (Labs 01 to 10) using the template from the Laboratory Module. Scores are team averages from 1 to 5. **Interest** is how much we want to spend a thesis term on the idea. **Feasibility** covers data access, compute, skills, and time (5 = easy).

## Proposed Topics

| Idea | Paradigm | Lab | Interest | Feasibility | Status |
| --- | --- | --- | --- | --- | --- |
| Philippine Political Fake News Detector | Natural Language Processing (NLP), Machine Learning | --- | 3 | 4 | Proposed |
| ML-Based Automated Building Structure Classification (Industrial/Commercial/Residential) | Classical Machine Learning, K-Nearest Neighbors (KNN) | --- | 3 | 1 | Proposed |
| Geospatial Small Business Profit Predictor | Random Forest Regressor, Data Preprocessing, Train-Test Split, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R² Score | --- | 3 | 1 | Proposed |
| --- | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- |

---
## Review of Related Literature List
| Topic | RRL1 | RRL2 | RRL3 | RRL4 | RRL5 |
| --- | --- |  --- | --- | --- | --- |
| Philippine Political Fake News Detector | --- |  --- | --- | --- | --- |
| ML-Based Automated Building Structure Classification (Industrial/Commercial/Residential) | --- | --- | --- | --- | --- |
| Geospatial Small Business Profit Predictor | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- |
---

## Lab 01: Paradigm scan (Week 1)

### 1. Philippine Political Fake News Detector

- **Idea:**  A text classifier (and web or browser tool) that flags likely political disinformation or fabricated claims in Tagalog, Taglish, and Philippine English.
- **Problem it addresses:**  High volume of misleading political posts and recycled narratives on social media outpaces manual fact-checking, especially around elections and major policy debates.
- **Closest existing work:**  Cruz, Tan, and Cheng (2020) introduced the Fake News Filipino dataset and benchmarked transfer learning (such as ULMFiT and BERT) on Filipino news texts, building on earlier English fake-news benchmarks like LIAR (Wang, 2017) and Fake News Challenge datasets. 
- **Data needed:**  Labeled Philippine political articles and social posts (real vs. fabricated/misleading), drawing on public datasets like Fake News Filipino and verified fact-check archives (e.g., VERA Files, Rappler) with clear annotation guidelines. 
- **Compute needed:**  Colab GPU for fine-tuning a compact pretrained transformer or multilingual/Tagalog encoder; CPU or lightweight API hosting for inference. 
- **Biggest risk:**  Sarcasm, satire, code-switching (Taglish), and evolving political narratives/slang causing false positives or concept drift. 
- **Team interest:** 3/5 · **Feasibility:** 4/5

### 2. ML-Based Automated Building Structure Classification (Industrial/Commercial/Residential)
- **Idea:**  A vision model that classifies buildings into industrial, commercial, or residential categories from aerial/satellite imagery, street-level photos, or combined spatial inputs. 
- **Problem it addresses:**  Manual zoning verification, urban land-use mapping, and disaster/infrastructure exposure assessments are slow and costly to keep updated across growing municipalities. 
- **Closest existing work:**  Street-view and multimodal building-use classification work such as Hoffmann et al. (2018) using street-level façade imagery alongside footprint/remote-sensing data, as well as deep-learning building-usage classifiers on street and aerial imagery. 
- **Data needed:**  Georeferenced building images (overhead/satellite tiles and/or street-view photos) paired with verified land-use labels from municipal zoning maps, OpenStreetMap, QGIS, or field surveys. 
- **Compute needed:**  Colab GPU for training CNN or vision-backbone classifiers; standard workstation or cloud batch processing for tiling and inference. Mixed-use buildings (e.g., shophouses or ground-floor retail above residences) and occluded roofs/facades in dense neighborhoods causing class ambiguity. 
- **Biggest risk:**  Mixed-use buildings (e.g., shophouses or ground-floor retail above residences) and occluded roofs/facades in dense neighborhoods causing class ambiguity. 
- **Team interest:** 3/5 · **Feasibility:** 1/5

### 3. Geospatial Small Business Profit Predictor
- **Idea:** A machine learning and geospatial analytics tool that uses customer order locations, sales data, demographic factors, and geographic patterns to identify high-potential regions for business expansion and estimate the profitability of opening a new branch in a target area.    
- **Problem it addresses:** Small businesses often choose new locations based on intuition rather than data. This system helps owners identify underserved but high-demand areas, reducing the risk of opening a store in an unprofitable location and supporting evidence-based expansion decisions.   
- **Closest existing work:** ESRI Business Analyst (location intelligence and market analysis), Google Maps Platform location analytics tools, Retail site-selection systems used by franchises such as Starbucks and McDonald's, Real estate market analysis platforms (e.g., Placer.ai, SiteZeus)
- **Data needed:**  Historical sales and revenue data by location, Customer order and geographic location data, Business branch/store locations, Population density and demographic data, Competitor locations and density, Geographic coordinates (latitude/longitude), Traffic, accessibility, or footfall data (optional for better accuracy)
- **Biggest risk:**  Acquiring accurate real-world sales and location data is difficult. The model's predictions can become unreliable if customer or demographic data is incomplete, outdated, or biased. Additionally, profitability depends on many factors beyond location, such as pricing, marketing, and local economic conditions.  
- **Team interest:** 3/5 · **Feasibility:** 1/5
---

## Lab 02: Classical machine learning (Week 2)

- **Idea:** 
- **Problem it addresses:** 
- **Closest existing work:**
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **What the lab showed:** 


## Lab 03: Transfer learning (Week 3)

- **Idea:** 
- **Problem it addresses:** 
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **What the lab showed:** 
- **Decision:** 

## Lab 04: Retrieval-augmented generation (Week 4)

- **Idea:** 
- **Problem it addresses:** 
- **Closest existing work:** 
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **What the lab showed:** 
- **Decision:** 
## Lab 05: Agents and a responsible AI audit (Week 5)

- **Idea:** 
- **Problem it addresses:**
- **Closest existing work:** 
- **Data needed:** 
- **Compute needed:**
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **Decision:** 

## Lab 06: Qubits and quantum circuits (Week 6)

- **Idea:** 
- **Problem it addresses:** 
- **Closest existing work:** 
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **Decision:** 

## Lab 07: Quantum algorithms and post-quantum cryptography (Week 7)

- **Idea:** 
- **Problem it addresses:** 
- **Closest existing work:** 
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **Decision:** 

## Lab 08: Edge AI (Week 8)

- **Idea:** 
- **Problem it addresses:** 
- **Closest existing work:** 
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **What the lab showed:** 
- **Decision:** 

## Lab 09: Attack, defend, or federate (Week 9)

- **Idea:** 
- **Problem it addresses:** 
- **Closest existing work:** 
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **What the lab showed:** 
- **Decision:** 

## Lab 10: XR, digital twins, and blockchain (Week 10)

- **Idea:** 
- **Problem it addresses:** 
- **Closest existing work:** 
- **Data needed:** 
- **Compute needed:** 
- **Biggest risk:** 
- **Team interest:** -/5 · **Feasibility:** -/5
- **Decision:** 
---

## Outcome: Proof-of-concept showcase (Week 11)

- **Riskiest assumption tested:** ---
- **Result:** ---
- **What changed in the proposal:** ---
- **Demo tag:** ---