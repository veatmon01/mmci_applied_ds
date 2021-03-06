# Applied Data Science, Block 1

---

### Reading Questions

*from Obermeyer and Emanuel*
<https://www.nejm.org/doi/full/10.1056/NEJMp1606181>

1. The authors are optimistic about the impact machine learning will have on clinical medicine.
  - True
  - False
2. Which of the following two statements fits best?
  - Machine learning algorithms are "expert systems" that apply rules based on domain knowledge to a dataset of interest.
  - Machine learning algorithms "learn rules from data" by matching the parameters of a statistical model to a dataset of interest.
3. The authors discuss potential disruption in all of the following areas, except:
  - pathology
  - surgery
  - radiology
  - anesthesiology
4. Machine learning is designed to uncover causal relationships between variables.
  - True
  - False
5. The following strategies can be used to protect against model overfitting, except:
  - Evaluating performance on data not used during training
  - Evaluating performance on data from different populations or time periods
  - Penalizing model parameters to prevent them from becoming too large
  - Creating models with as many features (i.e. covariates) and parameters as possible
  - All of the above are valid

*from Chen and Asch*
<https://www.nejm.org/doi/full/10.1056/NEJMp1702071>

6. Predictive models are new in medicine, brought on by recent advances in machine learning.
  - True
  - False

7. Learning from real-world data sources (e.g. billing systems) can be hazardous for all of the following reasons, except:
  - Patients may not be representative of the broader population (i.e. participation bias).
  - Patterns of treatment and care may reflect socioeconomic or racial/ethnic disparities.
  - Non-random patterns of missing data may be present.
  - Data collection practices may differ between systems and/or change over time.
  - All of the above are valid.

8. When training a model with historical data, including more years of data always leads to better performance.
  - True
  - False

9. Which of the following best describes the authors' attitude toward forecasting (i.e. predicting future values) via machine learning:
  - Forecasting is imprecise but can be useful, for example to establish a prognosis or stratify patients by risk.
  - Forecasting has little to no practical value due to the short "half-life" of clinical data.

10. A strength of machine learning lies in its ability to capture complex, nonlinear relationships in a dataset.
  - True
  - False

### Discussion Questions

1. Chen and Asch say that algorithm performance should be compared to "real-world standards of care" rather than "an idealized and unrealizable standard of perfection". Yet in practice, we're often less willing to tolerate errors made by technology than those made by humans. What benchmark should a machine learning model exceed before it's used in clinical decision-making, e.g. performance of the average expert, the best expert, or something else?
2. When developing a predictive model, machine learning practitioners often use whatever data is available rather than a curated set of predictors. The article by Rajkomer et al. provides an excellent example of this. What are the dangers of using *all* the data, and do they outweigh its advantages?
3. In their editorial, Obermeyer and Emanuel suggest that some specialties (e.g. radiology) will see major disruption in "years, not decades". Is this prediction overly optimistic? If so, what barriers are they missing? If not, what unintended consequences will these disruptions bring?

