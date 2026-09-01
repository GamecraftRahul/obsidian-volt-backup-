## definition










### Formulas 

**Measures of Central Tendency**

|**Measure**|**Data Type**|**Formula**|**Key Terms**|
|---|---|---|---|
|**Arithmetic Mean**|Ungrouped|$$\bar{x} = \frac{\sum x}{N}$$|$N = \text{total number of observations}$|
|**Mean (Frequency Data)**|Discrete / Grouped|$$\bar{x} = \frac{\sum fx}{\sum f}$$|$f = \text{frequency},\; x = \text{value or midpoint}$|
|**Median**|Ungrouped|$$\text{Position} = \left(\frac{N+1}{2}\right)^{\text{th}}\text{ item}$$|Data arranged in ascending order|
|**Median**|Grouped|$$\text{Median} = L + \left(\frac{\frac{N}{2} - CF}{f}\right)h$$|$L = \text{lower limit of median class}$<br><br>  <br>  <br><br>$CF = \text{cumulative freq. before median class}$<br><br>  <br>  <br><br>$f = \text{frequency of median class}$<br><br>  <br>  <br><br>$h = \text{class width}$|
|**Mode**|Ungrouped|$$\text{Most frequent value}$$|Peak frequency in the set|
|**Mode**|Grouped|$$\text{Mode} = L + \left(\frac{f_1 - f_0}{2f_1 - f_0 - f_2}\right)h$$|$f_1 = \text{frequency of modal class}$<br><br>  <br>  <br><br>$f_0 = \text{frequency of preceding class}$<br><br>  <br>  <br><br>$f_2 = \text{frequency of succeeding class}$|

**Partition Values & Positional Measures**

  

|**Measure**|**Notation**|**Position Formula (Ungrouped)**|
|---|---|---|
|**First Quartile**|$Q_1$|$$\left(\frac{N+1}{4}\right)^{\text{th}}\text{ item}$$|
|**Second Quartile (Median)**|$Q_2$|$$\left(\frac{N+1}{2}\right)^{\text{th}}\text{ item}$$|
|**Third Quartile**|$Q_3$|$$\left(\frac{3(N+1)}{4}\right)^{\text{th}}\text{ item}$$|
|**$k^{\text{th}}$ Decile**|$D_k$|$$\left(\frac{k(N+1)}{10}\right)^{\text{th}}\text{ item} \quad (k = 1, 2, \dots, 9)$$|
|**$k^{\text{th}}$ Percentile**|$P_k$|$$\left(\frac{k(N+1)}{100}\right)^{\text{th}}\text{ item} \quad (k = 1, 2, \dots, 99)$$|

**Measures of Dispersion**

  

|**Measure**|**Formula**|**Notes**|
|---|---|---|
|**Range**|$$\text{Range} = X_{\max} - X_{\min}$$|Absolute difference of extremes|
|**Interquartile Range (IQR)**|$$\text{IQR} = Q_3 - Q_1$$|Middle 50% spread|
|**Quartile Deviation (QD)**|$$\text{QD} = \frac{Q_3 - Q_1}{2}$$|Also called Semi-Interquartile Range|
|**Coefficient of QD**|$$\text{Coeff. of QD} = \frac{Q_3 - Q_1}{Q_3 + Q_1}$$|Relative measure of QD|
|**Population Variance**|$$\sigma^2 = \frac{\sum (X - \bar{x})^2}{N}$$|Average squared deviation from the mean|
|**Standard Deviation (SD)**|$$\sigma = \sqrt{\text{Variance}} = \sqrt{\frac{\sum (X - \bar{x})^2}{N}}$$|Root mean square deviation|
|**Coefficient of Variation (CV)**|$$\text{CV} = \left(\frac{\sigma}{\bar{x}}\right) \times 100$$|Measures relative variability (expressed as %)|

**Measures of Skewness & Kurtosis**

  

| **Measure**                             | **Formula**                                          | **Interpretation**                                                                                                                                                                                                                    |
| --------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Karl Pearson's Skewness ($Sk_p$)**    | $$Sk_p = \frac{\bar{x} - \text{Mode}}{\sigma}$$      | $Sk > 0$: Right-skewed<br><br>  <br>  <br><br>$Sk = 0$: Symmetric<br><br>  <br>  <br><br>$Sk < 0$: Left-skewed                                                                                                                        |
| **Pearson's Skewness (Empirical)**      | $$Sk_p = \frac{3(\bar{x} - \text{Median})}{\sigma}$$ | Used when mode is ill-defined                                                                                                                                                                                                         |
| **Bowley's Quartile Skewness ($Sk_b$)** | $$Sk_b = \frac{Q_3 + Q_1 - 2Q_2}{Q_3 - Q_1}$$        | Ranges between $-1$ and $+1$                                                                                                                                                                                                          |
| **Kurtosis ($\beta_2$)**                | $$\beta_2 = \frac{\mu_4}{\mu_2^2}$$                  | $\mu_k = \frac{\sum(X-\bar{x})^k}{N}$ (Central moments)<br><br>  <br>  <br><br>$\beta_2 = 3$: Mesokurtic (Normal)<br><br>  <br>  <br><br>$\beta_2 > 3$: Leptokurtic (Peaked)<br><br>  <br>  <br><br>$\beta_2 < 3$: Platykurtic (Flat) |
| **Excess Kurtosis ($\gamma_2$)**        | $$\gamma_2 = \beta_2 - 3$$                           | $\gamma_2 = 0$ for a Standard Normal distribution                                                                                                                                                                                     |