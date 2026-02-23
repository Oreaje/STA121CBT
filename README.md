
# STA 121: Statistical Inference I – Structured Quiz Data 📊

This repository contains a curated collection of Multiple Choice Questions (MCQs) focusing on the principles of Statistical Inference. The data is structured in a JSON-ready format, making it ideal for developers building Great Ife study tools, CBT practice apps, or data science educational resources.

## 🎓 About the Author

I am a **Computer Science with Economics student at Obafemi Awolowo University (OAU)**. This project is part of an initiative to digitize OAU's academic curriculum, providing fellow students with modern, structured data to master the intersection of Economics theory and Computational Statistics.



## 🛠 Data Schema

The dataset is optimized for JavaScript applications:

```javascript
{ 
  q: "When conducting a two-tailed test of a population mean with a large sample, which distribution is used?", 
  o: ["T-distribution", "Chi-square distribution", "Normal distribution", "F-distribution"], 
  a: "Normal distribution" 
}

```

## 📖 Topics Covered (OAU STA 121 Syllabus)

This repository covers the core pillars of Statistical Inference I:

* **Sampling Distributions:** Understanding the distribution of sample means and the Central Limit Theorem.
* **Point Estimation:** Properties of good estimators (Unbiasedness, Consistency, Efficiency, and Sufficiency).
* **Interval Estimation:** Calculating Confidence Intervals for means and proportions.
* **Hypothesis Testing:** Defining Null () and Alternative () hypotheses, Type I and Type II errors, and -values.
* **Tests of Significance:** -tests, -tests, and introduction to Chi-square tests for goodness of fit.

## 🚀 Usage in Projects

To use this in your web application:

```javascript
// Example: Rendering the options for a question
const renderOptions = (questionIndex) => {
  const options = sta121Data[questionIndex].o;
  options.forEach(option => {
    console.log(`Option: ${option}`);
  });
};

```

## 🤝 Contributing

I encourage fellow **Great Ife** students to contribute! If you have recent, verified STA 121 questions:

1. Fork the repo.
2. Add the questions in the `{ q, o, a }` format.
3. Submit a Pull Request.

---

**Curated with 🎯 at OAU (Obafemi Awolowo University).**

---
