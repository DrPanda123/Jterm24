# Analyzing Billboard Top 100: A Deep Dive into Song Longevity

## Abstract

This paper delves into the analysis of the Billboard Top 100 chart, focusing on the individual performance of Ed Sheeran's song "Bad Habits" and exploring broader trends in song longevity across the chart. The analysis employs Pandas for data manipulation, Plotly and Matplotlib for visualization, and is presented in MyST format. Additionally, this study connects with existing research that suggests an increase in narcissism and individualism in contemporary Western society, examining how these societal changes may manifest in popular music.

## Introduction

The Billboard Top 100 is a renowned music chart that reflects the popularity and success of songs based on various factors. One of the key components of the Billboard Hot 100 is the ranking algorithm, which can be represented as a polynomial equation.

\[
\begin{equation}
\text{Billboard Rank} = a_n \cdot \text{Weeks}^n + a_{n-1} \cdot \text{Weeks}^{n-1} + \ldots + a_1 \cdot \text{Weeks} + a_0
\end{equation}
\]

Here, the coefficients \(a_n, a_{n-1}, \ldots, a_1, a_0\) are determined by the song's performance over time, and the variable \(\text{Weeks}\) represents the number of weeks the song has been on the chart.

This analysis aims to provide insights into the performance of Ed Sheeran's song "Bad Habits" and to understand the distribution of song longevity across the entire chart. Additionally, it connects with recent research suggesting changes in self-promotion tendencies in popular music, reflecting larger societal changes in individualism.

## Individual Analysis: Ed Sheeran's "Bad Habits"

The analysis begins with loading the dataset from a CSV file and displaying the first few rows to get an overview. Subsequently, Ed Sheeran's "Bad Habits" is singled out for a detailed examination. The data is filtered to include only entries related to this particular song, and a time series plot is generated to visualize its Billboard rank over time.

![Ranking of "Bad Habits" by Ed Sheeran Over Time](img/EdSheeran.png)


The plot illustrates the dynamic nature of the song's performance on the chart, providing a visual representation of its fluctuating rank over several weeks.

## Identifying Top Artist and Song

Moving beyond the individual analysis, the paper identifies the top artist and song on the Billboard Top 100. Mariah Carey emerges as the top artist, and "All I Want For Christmas Is You" as the top song. The paper presents relevant information, including peak rank and weeks on the chart, for these entries.

**Top Artist: Mariah Carey**

\[
\begin{equation}
\begin{aligned}
& \text{Song} & \text{Peak Rank} & \text{Weeks on Chart} \\
& \text{All I Want For Christmas Is You} & 1 & 44 \\
& \text{All I Want For Christmas Is You} & 1 & 43 \\
& \text{All I Want For Christmas Is You} & 1 & 42 \\
& \text{All I Want For Christmas Is You} & 1 & 41 \\
& \text{All I Want For Christmas Is You} & 1 & 40 \\
\end{aligned}
\end{equation}
\]

**Top Song: Old Town Road**

\[
\begin{equation}
\begin{aligned}
& \text{Artist} & \text{Peak Rank} & \text{Weeks on Chart} \\
& \text{Lil Nas X Featuring Billy Ray Cyrus} & 1 & 45 \\
& \text{Lil Nas X Featuring Billy Ray Cyrus} & 1 & 44 \\
& \text{Lil Nas X Featuring Billy Ray Cyrus} & 1 & 43 \\
& \text{Lil Nas X Featuring Billy Ray Cyrus} & 1 & 42 \\
& \text{Lil Nas X Featuring Billy Ray Cyrus} & 1 & 41 \\
\end{aligned}
\end{equation}
\]

## Distribution of Song Longevity

To provide a holistic view of song longevity on the Billboard chart, the paper introduces the concept of "Distribution of Song Longevity." The associated histogram visualizes the categorization of songs based on the number of weeks they occupy on the chart.

The chart allows for the identification of peak durations, representing the most common longevity for songs. For instance, if a peak is observed around 8 weeks, it suggests that many songs typically endure for approximately 8 weeks on the chart. The height of each bar indicates the number of songs within a specific duration.

\[
\begin{equation}
\text{![Distribution of Song Longevity](img/newplot.png)}
\end{equation}
\]

The histogram enhances our understanding of the typical duration songs spend on the chart, offering valuable insights into the dynamics of the Billboard Top 100.

## Connecting with Research

This analysis aligns with recent research that suggests an increase in narcissism and individualism in contemporary Western society corresponds with greater self-focus depicted in cultural products (Morling & Lamoreaux, 2008). However, little attention has been given to popular music within this context (DeWall, Pond, Campbell, & Twenge, 2011). The current study examines changes in self-promotion (e.g., references to self, bragging, demands for respect), and the sociodemographic characteristics of both artists and audiences as they relate to self-promoting tendencies in popular music. Data were obtained using Billboard Hot 100 songs for the years 1990, 2000, and 2010. The most popular music in 2010 contained significantly more types of self-promotion than music from previous decades. This change reflects characteristics of genres (e.g., rap/hip-hop, pop, dance) that have gained popularity among younger audiences, but also corresponds to larger societal changes in individualism. Songs by male artists and African American artists were more likely to contain self-promotion than those by female or Caucasian artists. These differences are considered within the context of past theory and research related to socialization across groups more generally. Implications for parents, educators, and consumers are discussed. (PsycInfo Database Record (c) 2020 APA, all rights reserved)

For a more in-depth exploration of this topic, readers are encouraged to refer to the article by McAuslan and Waung (2018), titled "Billboard Hot 100 songs: Self-promoting over the past 20 years" published in *Psychology of Popular Media Culture, 7*(2), 171–184. [https://doi.org/10.1037/ppm0000118](https://doi.org/10.1037/ppm0000118).

## Conclusion

In conclusion, this analysis provides a comprehensive exploration of the Billboard Top 100, from the individual performance of Ed Sheeran's "Bad Habits" to broader trends in song longevity. The combination of Pandas, Plotly, and Matplotlib proves effective in
