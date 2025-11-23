# 🥛 Milk Quality Intelligence System
FastAPI · Machine Learning · React · Recharts · MongoDB
Live Demo: https://smart-milk-qa.preview.emergentagent.com/

Data Analytics & Predictive Quality Monitoring

A complete dairy quality analysis solution focused on delivering accurate predictions, actionable insights, and clear operational recommendations for QA and FMCG environments.

📌 Introduction

The Milk Quality Intelligence System analyzes key dairy parameters, predicts milk quality using machine learning, and provides interactive dashboards that help quality analysts monitor trends, detect anomalies, and improve decision-making.

❗ Problem Statement
| Challenge                                        | Impact on Operations                            |
| ------------------------------------------------ | ----------------------------------------------- |
| Manual quality checks vary by operator           | Inconsistent grading & errors                   |
| pH, temperature & turbidity deviations unnoticed | Spoilage & quality degradation                  |
| No unified analytics dashboard                   | Slow decision-making                            |
| Early detection of low-quality batches difficult | High rejection rates & losses                   |
| Parameter-level insights missing                 | Cannot improve supplier or handling performance |
⚙️ Approach
1. Data Processing

Cleaned and standardized 1,059 milk samples

Converted categorical values

Validated parameter ranges

Removed noise/outliers

2. Exploratory Data Analysis (EDA)
   | Parameter       | Insights                          |
| --------------- | --------------------------------- |
| **pH**          | Stable around 6.5–6.8 (optimal)   |
| **Temperature** | Frequently exceeds 40°C (risk)    |
| **Colour**      | Consistent with dairy standards   |
| **Turbidity**   | High variation → quality concerns |

3. 📊 Key Features

✔ Quality Prediction (High / Medium / Low) with 99% accuracy

 ✔ Parameter Analytics for pH, Temp, Turbidity, Fat, Odor, Taste

 ✔ Anomaly Alerts for high-risk samples

 ✔ Trend Insights & Correlations

 ✔ Interactive Dashboard for QA decision-making

📈 Insights Gained

• Temperature is the strongest early indicator of quality drop

 • pH stays stable, but turbidity quietly influences grade shifts

 • 41% of samples fall into low quality — a critical improvement area

 • Dashboards help uncover patterns not visible in manual checks
4. Predictive Modeling

Algorithm: Random Forest Classifier

Accuracy: 99.53%

Input features: pH, Temp, Taste, Odor, Fat, Turbidity, Colour

Output: High / Medium / Low Quality

4. Analytics & Dashboarding

Multi-tab React dashboard (Overview, Analytics, Prediction, Samples)

Parameter trend charts

Parameter vs. optimal comparison

Correlation visualizations

5. Smart Alert System

Flags high-risk samples

Highlights temperature/pH deviations

Generates recommendations automatically

📊 Outputs
System Outputs Overview
| Output                 | Description                                    |
| ---------------------- | ---------------------------------------------- |
| **Quality Prediction** | High/Medium/Low with confidence score          |
| **Risk Level**         | Low / Medium / High risk classification        |
| **Parameter Trends**   | Time series for pH & Temperature               |
| **Parameter Ranges**   | Compares current averages vs optimal standards |
| **Grade Distribution** | Pie chart across High, Medium, Low             |
| **ML Accuracy**        | 99.53% on training dataset                     |
| **Data Storage**       | All samples stored in MongoDB                  |

🔍 Insights
Top Insights from the Analysis
| Insight                                      | Analyst Interpretation                    |
| -------------------------------------------- | ----------------------------------------- |
| **41% Low-quality samples**                  | Requires process/supplier improvements    |
| **Temperature is the strongest risk factor** | Indicates handling/cooling inefficiencies |
| **pH remains stable**                        | Low contamination risk                    |
| **Colour is consistent**                     | Processing is well-controlled             |
| **High turbidity variation**                 | Impacts texture, quality & classification |

🧭 Findings & Conclusions
Key Findings

Temperature deviations correlate directly with quality degradation.

The model’s performance confirms strong feature-parameter relationships.

Certain parameters (Odor, Taste) strongly differentiate Medium vs Low grade.

Correlation analysis shows parameter interactions affecting quality.

Conclusions

The system successfully automates and enhances milk quality monitoring.

Enables proactive intervention rather than reactive correction.

Provides actionable insights for QA teams, procurement, and operations.

Highly effective for improving supplier evaluation and process optimization.
