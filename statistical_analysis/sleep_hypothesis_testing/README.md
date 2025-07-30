# 💤 Sleep Health Statistical Study

This project explores the relationship between various factors (gender, stress, BMI) and sleep health indicators (hours of sleep, sleep quality, presence of disorders) using descriptive and inferential statistical techniques in R.

## 📊 Objectives

- Assess whether the population sleeps less than the recommended 7.5 hours.
- Compare sleep quality between genders.
- Analyze the effect of stress levels on the prevalence of sleep disorders.
- Investigate the association between BMI and sleep disorder types.

## 🛠️ Tools & Technologies

- **Language:** R
- **Libraries:** ggplot2, readxl, stats
- **Techniques:** t-test (one-sample, independent), proportions test, chi-square test

## 📈 Summary

The analysis is based on a dataset of 374 individuals. The study addresses four main research questions:

1. Is the mean number of sleep hours significantly lower than 7.5?
2. Are there gender-based differences in sleep quality?
3. Is the rate of sleep disorders higher in individuals with high stress?
4. Is there an association between BMI categories and types of sleep disorder?

## 📁 Project Structure

```text
📂 sleep_hypothesis_testing
├── sleep_hypothesis_testing.Rmd     # R Markdown with full analysis  
├── sleep_hypothesis_testing.html    # Rendered HTML report  
├── sleephealth_processed.xlsx       # Dataset  
└── README.md                        # Project overview and instructions
```

## 🧪 Key Results

| Research Question | Test Applied | Result |
|-------------------|---------------|--------|
| PR1 | One-sample t-test | Mean sleep hours < 7.5 (p < 0.001) |
| PR2 | Independent t-test | Women sleep better than men (p < 0.001) |
| PR3 | Two-proportion test | Higher disorder rate in stressed individuals (p < 0.001) |
| PR4 | Chi-square test | Significant association between BMI and sleep disorders (p < 0.001) |

## 👩‍💻 Author

**Rebeca Suárez**  
Data Scientist | AI Engineer  
📫 rebecaasuarezojeda@gmail.com
