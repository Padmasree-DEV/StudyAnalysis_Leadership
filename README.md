# Leadership Dimensions Analysis

This repository provides an interactive data analysis and visualization framework for exploring leadership development across nine key dimensions. The project uses anonymized survey data and is built using R- RStudio and R Markdown.

📥 **Download the Full Analysis Report**  
[Click here to view or download AnalysisReport.html](https://github.com/Padmasree-DEV/StudyAnalysis_Leadership/releases/download/Results/AnalysisReport.html)

## 📊 Overview

The analysis aims to assess leadership capabilities using both self-assessments and peer/supervisor feedback. It generates a variety of plots to support visual interpretation of leadership dimensions across development levels (D1–D4).

## 🔧 Tools & Libraries

- **Language**: R, R Studio, R Markdown
- **Key Libraries**:
  - [`tidyverse`](https://www.tidyverse.org/)
  - [`fmsb`](https://cran.r-project.org/web/packages/fmsb/)
  - [`echarts4r`](https://github.com/JohnCoene/echarts4r)
  - [`ggchicklet`](https://github.com/hrbrmstr/ggchicklet)
  - [`scales`](https://cran.r-project.org/web/packages/scales/)
  - [`reshape2`](https://cran.r-project.org/web/packages/reshape2/)
  - [`data.tree`](https://cran.r-project.org/web/packages/data.tree/)

## 📁 Repository Structure
├── Data_plot.csv # Anonymized survey dataset  
├── leadership_analysis.qmd # Main R Markdown script with visualizations  
├── output/ # Optional: Exported HTML or PNG files  
└── README.md # Project description (this file)  


## 📈 Visualizations Included

- 🌞 Sunburst chart: Participant background by academic, informal, and professional groups
- 📦 Boxplots & jitter: Style ratings by development level
- 📊 Bar charts: Average scores per dimension
- 🧭 Radar chart: Peer vs. self-assessment comparison
- 📉 Validation plot: Comparison with supervisor ratings
- 🔥 Dot plot & stacked bar chart: Alignment of estimated vs. expected styles

## 🧠 Leadership Dimensions Assessed

1. **Leadership Style Identification**
2. **Style Flexibility (Adaptability)**
3. **Follower Readiness Awareness**
4. **Communication Style**
5. **Perception and Feedback**
6. **Diagnostic Accuracy**
7. **Style Appropriateness**
8. **Developmental Focus**
9. **Emotional Intelligence**

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/leadership-dimensions-analysis.git
cd leadership-dimensions-analysis
```

## 2. Open the Project in RStudio
Open leadership_analysis.qmd inside RStudio or your preferred R environment.

## 3. Install Required Packages
```bash
install.packages(c("tidyverse", "fmsb", "echarts4r", "ggchicklet", "scales", "reshape2", "data.tree"))
```
## 4. Knit the Report
Click the Render button in R-studio or execute the command:
```bash
rmarkdown::render("leadership_analysis.qmd")
```

## 👩‍💻 Author
Padmasree Jayaraman
Designed and developed the analysis framework.
