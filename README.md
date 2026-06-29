# 🦌 Wildlife Corridor Suitability & Least-Cost Path Analysis
### State College, Pennsylvania

---

## 📌 Project Overview

Habitat fragmentation caused by roads, urban development, and land use changes restricts wildlife movement and increases wildlife-vehicle collisions. This project uses GIS-based suitability modeling and least-cost path analysis to identify potential wildlife corridors and habitat pinch points throughout the State College, Pennsylvania region.

The resulting corridor network highlights areas where conservation efforts, wildlife crossings, and habitat restoration could most effectively improve landscape connectivity.

---

## 🎯 Project Objectives

- Identify habitat fragmentation throughout the study area
- Develop a wildlife movement suitability model
- Generate resistance surfaces using environmental and human factors
- Perform least-cost path analysis
- Identify wildlife corridor pinch points
- Support conservation planning and land management decisions

---

# 🌎 Study Area

<img width="990" height="760" alt="Study Area" src="https://github.com/user-attachments/assets/c0232afb-a6b0-49af-9953-434856da0dee" />


The study area encompasses the State College, Pennsylvania region and surrounding public lands. This landscape contains a mixture of protected forests, private property, transportation corridors, agricultural land, and expanding urban development.

---

# 🛰️ Data Sources

The analysis integrates numerous spatial datasets, including:

- Protected Lands (PAD-US)
- Parks & Public Lands
- Road Network
- Population Density
- Land Cover
- Administrative Boundaries
- Wildlife Habitat Data

These datasets were standardized and combined to create a resistance surface representing barriers to wildlife movement.

---

# ⚙️ GIS Workflow

The overall workflow consisted of:

1. Collect spatial datasets
2. Reclassify land cover
3. Create movement resistance surface
4. Calculate cost distance
5. Generate least-cost paths
6. Identify habitat pinch points
7. Evaluate corridor suitability

---

# 🌿 Land Cover Reclassification

<img width="638" height="336" alt="Land Cover Reclassification Values" src="https://github.com/user-attachments/assets/d406c060-ea4b-476c-93bb-5b6736ff22a2" />

<img width="662" height="117" alt="PAD-US GAP Status Code Reclassification Values" src="https://github.com/user-attachments/assets/2ab5678a-9cf6-45ef-be3e-a76dcbbc63bd" />

Land cover classes were reclassified according to their relative resistance to wildlife movement. Natural vegetation received lower movement costs while developed areas and major roadways received higher resistance values.

---

# 🚧 Resistance Surface

<img width="997" height="770" alt="Resistance Surface Comparison" src="https://github.com/user-attachments/assets/01d8b463-7227-4298-8613-eb39718a5ac4" />


The resistance surface integrates multiple environmental and anthropogenic variables into a single raster representing movement difficulty across the landscape.

---

# 🦌 Cost Distance Analysis

<img width="997" height="756" alt="Cost Distance Rothrock State Forest" src="https://github.com/user-attachments/assets/7e172f2b-f1b4-4283-b010-d5438ef5d380" />

<img width="998" height="770" alt="Cost Distance Bald Eagle State Forest" src="https://github.com/user-attachments/assets/a7734fe4-68b6-4858-a148-2de2f582c90a" />

Cost distance analysis estimates the cumulative effort required for wildlife to travel through the landscape while avoiding high-resistance areas.

---

# 🌲 Wildlife Corridor Analysis

<img width="997" height="765" alt="Wildlife Corridor NoRoads" src="https://github.com/user-attachments/assets/f98e693a-1cfc-4c70-8021-b31b66ddd136" />

<img width="1001" height="773" alt="Wildlife Corridor With Roads" src="https://github.com/user-attachments/assets/f95a1e6d-168a-48ce-9759-5fd7b557e746" />


Least-cost path modeling identifies potential movement corridors connecting protected habitats while minimizing exposure to barriers such as roads and urban development.

---

# 🔍 Corridor Comparison


<img width="992" height="762" alt="Corridor Comparison" src="https://github.com/user-attachments/assets/e37ea624-7f5a-4661-a010-a16ee98bb5b5" />


Multiple corridor scenarios were evaluated to compare connectivity patterns and identify areas where wildlife movement becomes constrained.

---

# 💡 Key Findings

- Multiple habitat pinch points occur where wildlife corridors intersect transportation infrastructure.
- Protected lands serve as critical anchor habitats for maintaining regional connectivity.
- Urban development substantially increases landscape resistance and fragments wildlife movement.
- Several high-priority areas were identified where conservation efforts or wildlife crossings could improve ecological connectivity.
<img width="653" height="503" alt="Corridor suitability Zone Areas Figure 13" src="https://github.com/user-attachments/assets/21044e28-8d20-45d0-b9f6-2aa946f58115" />
---

# 🌱 Why This Matters

Maintaining wildlife connectivity is essential for preserving biodiversity, supporting genetic exchange, and reducing wildlife-vehicle collisions. GIS-based corridor modeling provides conservation organizations and land managers with a powerful decision-support tool for prioritizing habitat protection and restoration.

---

## 🛠️ Software

- ArcGIS Pro
- ArcGIS Spatial Analyst
- ModelBuilder
- ArcPy
- Microsoft Excel

---

## 📄 Report

The complete technical report is included in this repository.
