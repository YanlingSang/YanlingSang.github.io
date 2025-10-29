---
permalink: /
title: "Yanling Sang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.news-item {
  margin-bottom: 8px;
}
.news-date {
  font-weight: bold;
  color: #2196F3;
}
.award-highlight {
  background: linear-gradient(120deg, #a2facf 0%, #64b3f4 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: bold;
}
.section-header {
  border-bottom: 2px solid #e9ecef;
  padding-bottom: 5px;
  margin-bottom: 15px;
  margin-top: 25px;
}

/* Responsive design for publications */
@media (max-width: 768px) {
  .publication-container {
    flex-direction: column !important;
    align-items: center !important;
  }
  .publication-image {
    flex: none !important;
    width: 100% !important;
    max-width: 280px !important;
    margin-right: 0 !important;
    margin-bottom: 15px !important;
  }
  .publication-image img {
    width: 100% !important;
    height: auto !important;
    max-height: 180px !important;
  }
  .publication-content {
    text-align: center;
  }
  .publication-content h3 {
    font-size: 16px !important;
  }
  .publication-content p {
    font-size: 13px !important;
  }
}
</style>

👋 I am a **Master's student** in the **Civil Engineering Department** at the University of California, Los Angeles (UCLA), specializing in **Transportation Engineering**. I received my Bachelor's degree in Traffic and Transportation from Beijing Jiaotong University (in collaboration with Delft University of Technology) in 2024.

My research interests span **transportation systems optimization**, **human mobility modeling**, **demand responsive transit**, and applications of **artificial intelligence** in transportation, with particular emphasis on activity chain generation, congestion pricing analysis, and intelligent transportation systems. I am passionate about developing data-driven solutions that can make transportation systems more efficient, sustainable, and equitable.

<h1 class="section-header">🔬 Research Experience</h1>

<div class="publication-container" style="margin-bottom: 30px;">
  <div style="margin-bottom: 15px;">
    <h3 style="margin-bottom: 6px; color: #2c3e50;">RoutineHub: Persona-Conditioned Activity Chain Generation Framework</h3>
    <p style="margin: 6px 0; color: #666; font-size: 14px;"><strong>Advisor:</strong> Prof. Jinhua Zhao, MIT | <em>July 2025 - Present</em></p>
    <p style="margin: 6px 0; line-height: 1.4; font-size: 14px;">
      • Designed end-to-end activity chain generation framework combining symbolic reasoning and deep learning<br>
      • Analyzed Singapore HITS2012 dataset with 21,936 users and 85,882 trips<br>
      • Engineered dual-architecture: Transformer seq2seq model + LLM-augmented retrieval system<br>
      • Implemented rare pattern mining with Bernoulli modeling and boosting mechanisms<br>
      • Achieved fine-grained temporal modeling with 15-minute precision slots
    </p>
  </div>
</div>

<div class="publication-container" style="margin-bottom: 30px;">
  <div style="margin-bottom: 15px;">
    <h3 style="margin-bottom: 6px; color: #2c3e50;">Impact of Congestion Pricing on Ride-hailing and Subway in NYC</h3>
    <p style="margin: 6px 0; color: #666; font-size: 14px;"><strong>Advisor:</strong> Asst. Prof. Manxi Wu, UC Berkeley | <em>May 2025 - Present</em></p>
    <p style="margin: 6px 0; line-height: 1.4; font-size: 14px;">
      • Analyzed NYC's $1.50 congestion surcharge using 11M TLC trip records and 57M MTA ridership estimates<br>
      • Applied two-way fixed effects difference-in-differences design<br>
      • Identified platform-specific responses: Uber trips -6%, Lyft trips +2-5%, subway ridership +1%<br>
      • Revealed heterogeneous impacts on short trips (-9%) and low-fare rides (-35%)<br>
      • Manuscript submitted to <em>Transportation Research Part A</em>
    </p>
  </div>
</div>

<div class="publication-container" style="margin-bottom: 30px;">
  <div style="margin-bottom: 15px;">
    <h3 style="margin-bottom: 6px; color: #2c3e50;">Tourist Mobility Modeling for Tokyo via Survey Data</h3>
    <p style="margin: 6px 0; color: #666; font-size: 14px;"><strong>Advisor:</strong> Prof. Jiaqi Ma, UCLA Mobility Lab | <em>Dec 2024 - May 2025</em></p>
    <p style="margin: 6px 0; line-height: 1.4; font-size: 14px;">
      • Fused GPS pins with Tokyo Visitor Survey to create zonal mobility dataset<br>
      • Developed Random Forest model predicting nights stayed and locations visited<br>
      • Generated trajectories using LLM matching survey chain length and activity distribution<br>
      • Built full pipeline for synthetic tourist activity chain generation at high spatiotemporal resolution
    </p>
  </div>
</div>

<div class="publication-container" style="margin-bottom: 30px;">
  <div style="margin-bottom: 15px;">
    <h3 style="margin-bottom: 6px; color: #2c3e50;">QuantV2X: Communication–Compute Co-Design for Cooperative Perception</h3>
    <p style="margin: 6px 0; color: #666; font-size: 14px;"><strong>Advisor:</strong> Prof. Jiaqi Ma, UCLA | <em>Aug 2025 - Present</em></p>
    <p style="margin: 6px 0; line-height: 1.4; font-size: 14px;">
      • Built C-V2X testbed benchmarking message representations (PointCloud, BEV, Boxes, PointCluster)<br>
      • Designed dual-quantization stack (INT8 models + feature codebooks) with TensorRT deployment<br>
      • Achieved order-of-magnitude feature compression while preserving accuracy<br>
      • Established end-to-end benchmarks for multi-agent cooperation under bandwidth/latency constraints<br>
      • Planned as M.S. thesis and NeurIPS submission component
    </p>
  </div>
</div>

<div class="publication-container" style="margin-bottom: 30px;">
  <div style="margin-bottom: 15px;">
    <h3 style="margin-bottom: 6px; color: #2c3e50;">Trajectory-Based Optimization of Night Customized Bus Route</h3>
    <p style="margin: 6px 0; color: #666; font-size: 14px;"><strong>Advisors:</strong> Prof. Ailing Huang (BJTU) & Asst. Prof. Yimeng Zhang (SWJTU) | <em>Feb - May 2024</em></p>
    <p style="margin: 6px 0; line-height: 1.4; font-size: 14px;">
      • Extracted features from taxi/ride-hailing trajectory data and passenger travel characteristics<br>
      • Constructed mixed-integer programming model for customized bus route and vehicle scheduling<br>
      • Designed genetic algorithm for solving the proposed model<br>
      • <span class="award-highlight">🏆 Won Outstanding Thesis Award at Beijing Jiaotong University</span>
    </p>
  </div>
</div>

<h1 class="section-header">📝 Publications and Patents</h1>

**Y. Sang**, Y. Tang, A. Qu, and J. Zhao. "RoutineHub: A Framework for Persona-Conditioned Activity Chain Generation via Structured Templates and RAG-Augmented LLM Refinement." *Manuscript prepared for submission to Travel Behaviour and Society*.

Y. Zhang*, **Y. Sang***, and M. Wu. "Congestion Pricing in New York City: Effects on Ride-Hailing, Transit, and Welfare." *Manuscript submitted to Transportation Research Part A: Policy and Practice*.

**Y. Sang**. "Research on Demand Responsive Transit Route Optimization, Scheduling Models, and Solution Algorithms." *Highlights in Science, Engineering and Technology*. Presented at the 2nd International Conference on Civil Engineering, Architecture and Transportation (CEAT 2024).

B. Wang, Y. Gao, A. Huang, and **Y. Sang**. "Game Models for Taxi Decision-Making Considering Online Ride-Hailing Competition in Airport." *2023 IEEE 8th International Conference on Intelligent Transportation Engineering (ICITE)*, (2023): 248–254.

B. Han, Y. Yu, Z. Xi, Y. Sun, F. Lu, S. Li, Z. Li, S. Huang, J. Hu, **Y. Sang**, and Y. Zhao. "Overview of Global Urban Rail Transit Operation Statistics and Analysis in 2023." *Urban Rail Transit*, 2024, 37(1): 1–9.

**Patent:** "Integrated Optimization of Train Diagram and Rolling Stock Circulation with Full-length and Short-length Routes of Virtual Coupling Trains in Urban Rail Transit." Application Number: 202311592436.X, 2023.

<h1 class="section-header">🎓 Education</h1>

* **2024 - Present**, M.S., Civil Engineering (Transportation Engineering), University of California, Los Angeles (UCLA)
  * Overall GPA: **3.9/4.0**
  * Key Coursework: Traffic Engineering Systems, GIS and Spatial Data Science, Large-Scale Data Mining, Intelligent Transportation Systems

* **2020 - 2024**, B.E., Traffic and Transportation, Beijing Jiaotong University (with Delft University of Technology)
  * Overall GPA: **3.7/4.0**
  * Key Coursework: Operations Research (100), Physics (96), Transportation Economics (94), Transportation Facilities (91), Public Transport Systems (90), Logistics and Supply Chain Management (90)

<h1 class="section-header">🏆 Honors and Awards</h1>

* **2024** Outstanding Thesis Award, Beijing Jiaotong University
* **2023** Third Prize, Transportation Science and Technology Competition, Beijing Jiaotong University
* **2023** Third Prize, Social Practice Activity at BJTU
* **2023** Second Prize, "Jiaoyun · Cafe" Cultural Space Operation Competition, School of Traffic and Transportation, BJTU
* **2022** Summer Social Practice Excellent Team at BJTU
* **2021** Third-class Scholarship for Excellent Academic Performance at BJTU

<h1 class="section-header">💼 Internship Experience</h1>

**Traffic Engineering Intern**  
*Qingdao Kaiyuan Kerun Electronics Co., LTD | July 2023*
* Redesigned deformed (Y-shaped) intersection in Jiaozhou, Qingdao with three improvement schemes
* Applied Synchro and VISSIM, achieving up to 28% reduction in average stop delay
* Improved left-turn flow and safety through optimized signal timing

<h1 class="section-header">🛠️ Skills</h1>

**Computer Skills:** Python, MATLAB, SPSS, Gurobi, VISSIM, CAD, MATSim, AutoCDA

**Standardized Tests:** 
* IELTS: 7.0 (Overall)
* GRE: Verbal 160, Quantitative 168, Analytical Writing 4.0

---

*Last updated: October 2025*
