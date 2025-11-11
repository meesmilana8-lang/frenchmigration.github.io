<div align="center">

  **🇫🇷 French Migration Project 🇫🇷**

</div>

<hr style="border: 1px solid #C0C0C0;">

## **Quantitative Analysis of Immigration in France (2010–2025)**

<hr style="border: 0.8px solid #E0E0E0;">

## **1. Research Objective**

This quantitative study aims to understand the evolution and socio-economic dynamics of immigration in France between 2010 and 2025. The analysis examines the relationship between migration flows, control policies, territorial distribution, demographic composition, and labor market participation.  
The objective is to determine whether available empirical evidence aligns with or contradicts prevailing political narratives on immigration, including claims that immigration imposes a burden on state systems or, conversely, represents an economic and social asset.

---

## **2. Research Question**

Political discourse on immigration in France is characterized by polarization.  
Right-wing actors frequently describe immigration as excessive, insufficiently regulated, and economically costly.  
Left-wing perspectives tend to emphasize the contributions of migrants to social cohesion, diversity, and economic dynamism.

This study seeks to move beyond ideological interpretation by grounding the analysis in quantitative indicators.

**Research question:**  
To what extent do quantitative indicators of migration and socio-economic integration in France confirm or contradict political narratives about immigration?

---

## **3. Hypotheses**

| Hypothesis | Statement |
|-----------|-----------|
| **H1** | Right-wing narratives exaggerate the growth of immigration and underestimate its cyclical nature. |
| **H2** | Left-wing narratives highlight migrant contributions but often overlook persistent economic and territorial disparities. |
| **H3** | The empirical situation is more complex: migratory flows are irregular, regulatory control varies with context, and immigrants are geographically concentrated yet economically active. |

---

## **Data Sources**

All data used in this analysis originate from official French institutions.

**Ministry of the Interior**  
• Asylum applications  
• Residence permits  
• Forced removals  
• Demographic statistics  

**INSEE (National Institute of Statistics and Economic Studies)**  
• Socio-economic indicators of immigrant populations  
• Employment, education, household and territorial data  

Datasets were selected on the basis of reliability, relevance, and preliminary data cleaning conducted by the institutions, enabling a more efficient analytical process.

---

## **Methodology**

The analysis was conducted using **Python** in **Google Colab**.  
The libraries **pandas** and **matplotlib** were employed for dataset processing, cleaning, and visualization.

Each dataset underwent a uniform preparation sequence:

1. **Importation**  
2. **Cleaning**: removal of empty rows, redundant headers, irrelevant footnotes  
3. **Variable selection**: retention of key indicators such as *Year, Population, Immigrants, Applications,* and *Employment rate*  
4. **Numeric conversion** and dataframe restructuring  
5. **Visualization**: construction of line graphs and bar charts to highlight yearly and cross-category trends  

This standardized workflow ensured analytical transparency and reproducibility.  
Each figure in the study corresponds to one cleaned dataset and one thematic dimension of immigration.

---

## **Use of AI in the Analytical Process**

The large language model **ChatGPT** served as a technical assistant during the data preparation phase.  
Its role included:

• providing explanations of Python functions and methods  
• assisting in the structuring of cleaning routines  
• identifying coding errors and proposing corrections  
• validating intermediate outputs  

The use of AI improved workflow efficiency while maintaining methodological rigour and human oversight.

---
