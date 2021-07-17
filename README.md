# Deep Learning in Asset Pricing

Table of Contents
------------------------------

This repository contains empirical results in [paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3350138) to estimate a general non-linear asset pricing model with a deep neural network applied to all U.S. equity data combined with all relevant macroeconomic and firm-specific information. 

- [Empirical Results](#empirical-results)
- [Related Resources](#related-resources)
- [Author](#author)

------

### Empirical Results

We compare our GAN model, with a simple forecasting feedforward network model labeled as FFN, the linear special case of GAN labeled as LS and a regularized linear model labeled as EN. 

- Sharpe Ratio

| Model | SR (Train)  | SR (Valid)  | SR (Test)   |
|:-----:|:-----------:|:-----------:|:-----------:|
| LS    | 1.80        | 0.58        | 0.42        |
| EN    | 1.37        | 1.15        | 0.50        |
| FFN   | 0.45        | 0.42        | 0.44        |
| GAN   | 2.68        | 1.43        | 0.75        |

- Explained Variation

| Model | EV (Train)  | EV (Valid)  | EV (Test)   |
|:-----:|:-----------:|:-----------:|:-----------:|
| LS    | 0.09        | 0.03        | 0.03        |
| EN    | 0.12        | 0.05        | 0.04        |
| FFN   | 0.11        | 0.04        | 0.04        |
| GAN   | 0.20        | 0.09        | 0.08        |

- Cross-Sectional R2

| Model | XS-R2 (Train)  | XS-R2 (Valid)  | XS-R2 (Test)   |
|:-----:|:--------------:|:--------------:|:--------------:|
| LS    | 0.15           | 0.00           | 0.14           |
| EN    | 0.17           | 0.02           | 0.19           |
| FFN   | 0.14           | -0.00          | 0.15           |
| GAN   | 0.12           | 0.01           | 0.23           |

### Related Resources
- [Deep Learning in Asset Pricing (Chen, Pelger and Zhu 2019)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3350138)
- [Pre-trained Models](http://web.stanford.edu/~lych/demo-dlap.html)
- [Data](https://www.dropbox.com/s/mr3ymp9frb425al/Data.xlsx?dl=0)
- [GitHub Repository](https://github.com/LouisChen1992/Deep_Learning_Asset_Pricing)

### Author
- [Luyang Chen](https://github.com/louisChen1992)
