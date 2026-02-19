# Normal Distribution and Empirical Rule
## Domain choosen: Healthcare – Adult Resting Heart Rate

### 1.Introduction

In the Healthcare domain, many physiological measurements follow a Normal Distribution, also known as the Gaussian Distribution. 
Examples include:

- Blood pressure

- Cholesterol levels

- Body temperature

- Resting heart rate
We analyze Adult Resting Heart Rate and demonstrate how it follows the Normal Distribution and how the Empirical Rule (68–95–99.7 Rule) applies.

### 2.What is Resting Heart Rate:

Resting Heart Rate (RHR) is the number of times a person's heart beats per minute while they are at complete rest.

For healthy adults:

- Typical range: 60–100 bpm

- Athletes may have lower values (40–60 bpm)

When measured across a large population, resting heart rate forms a bell-shaped pattern.

### 3.Why Resting Heart Rate Follows Normal Distribution

When data is:

1.Collected from a large population

2.Influenced by many small biological factors

3.Naturally centered around an average

It tends to form a Normal Distribution.

Heart rate is affected by:

 - Age

 - Fitness level

 - Genetics

 - Stress levels

- Lifestyle

Because these factors vary randomly, the overall distribution becomes symmetric around the mean.

### 4.Mathematical Formula of Normal Distribution

The probability density function is:

<img width="292" height="124" alt="Screenshot 2026-02-19 192902" src="https://github.com/user-attachments/assets/936b5d7a-7cb1-4942-ac23-d084e0f05cb1" />

Where:

 - μ = Mean

 - σ = Standard deviation

 - x = Observed value

This formula creates the bell-shaped curve.

### 5.Assumed Dataset for Analysis

For this example, we consider realistic population values:

 - Mean (μ) = 72 bpm

 - Standard Deviation (σ) = 8 bpm

This means:

 - The average resting heart rate is 72 bpm.

 - Most people's heart rates vary about 8 bpm from the mean.

### 6.Understanding the Normal Distribution Curve

The graph plotted represents:

 - X-axis → Heart Rate (bpm)

 - Y-axis → Probability Density

The highest point of the curve is at the mean (72 bpm).
The curve is symmetric on both sides.

<img width="580" height="435" alt="Screenshot 2026-02-19 194438" src="https://github.com/user-attachments/assets/89672a9e-26c9-40c6-9dce-d898d17ec7fa" />


Key points marked on the graph:

| Standard Deviation | Value  |
| :----------------: | :-----:|
| μ − 1σ             | 64 bpm |
| μ + 1σ             | 80 bpm |
| μ − 2σ             | 56 bpm |
| μ + 2σ             | 88 bpm |
| μ − 3σ             | 48 bpm |
| μ + 3σ             | 96 bpm |

### 7.Empirical Rule (68–95–99.7 Rule)

The Empirical Rule applies only to Normal Distributions.

It states:

1) 68% Rule (Within 1 Standard Deviation)

Range: 72 ± 8
-  64 bpm to 80 bpm

Interpretation: About 68% of healthy adults have a resting heart rate between 64 and 80 bpm.

This is the most common range.

2) 95% Rule (Within 2 Standard Deviations)

Range: 72 ± 16
 - 56 bpm to 88 bpm

Interpretation: About 95% of healthy adults fall within this range.

Values outside this range are uncommon.

3) 99.7% Rule (Within 3 Standard Deviations)

Range: 72 ± 24
 - 48 bpm to 96 bpm

Interpretation: Almost 99.7% of healthy adults fall within this range.

Values below 48 or above 96 bpm are extremely rare and may require medical attention.

### 8.Real-Life Interpretation
**Case 1**: Person with 75 bpm

Falls within 1σ -> Completely normal

**Case 2**: Person with 85 bpm

Falls within 2σ -> Slightly above average but still normal

**Case 3**: Person with 100 bpm

Outside 3σ -> Needs medical evaluation

### 9.Importance in Healthcare

Normal distribution helps in:

- Identifying abnormal patients
- Setting medical thresholds
- Designing health research studies
- Detecting early warning signs
- Population health monitoring

Doctors use statistical distribution to decide:
 - What is normal
 - What is borderline
 - What is abnormal

### 10.Conclusion

In the Healthcare domain, adult resting heart rate follows a Normal Distribution because it is influenced by many small biological variations.

Using the Empirical Rule (68–95–99.7 Rule):

 * 68% of adults fall within 64–80 bpm

 * 95% fall within 56–88 bpm

 * 99.7% fall within 48–96 bpm

This statistical model helps medical professionals detect abnormalities and improve healthcare decision-making.
