# Test-Statistic-Guitar-Hero
# Statistical Analysis of Guitar Hero Misses

This project explores the randomness of missed notes in the Guitar Hero video game, analyzing whether the distribution of missed notes is random or follows a pattern. Using various statistical methodologies, this project examines miss streaks, distances between misses, and randomness tests to gain insight into the gameplay data.

## Project Overview

In collaboration with Shannon Coyle and Samantha Colucci, this project investigates the distribution of missed notes in Guitar Hero songs. The study employs statistical tests such as the Runs Test, parametric and nonparametric bootstrapping, and permutation resampling to assess whether missed notes are randomly distributed or grouped in patterns.

You can find the full project guidelines and explanation in the original publication [here](https://www.tandfonline.com/doi/abs/10.1080/10691898.2011.11889623).

## Key Objectives:
- Evaluate the randomness of missed notes in Guitar Hero songs.
- Apply resampling techniques and hypothesis testing.
- Utilize statistical programming tools, including R and the snpar package, for computation.

## Research Question:
Are missed notes in a Guitar Hero song distributed randomly or grouped together in specific regions? This project explores the use of statistical tools and methods to answer this question.

## Methodologies:
1. Miss Streaks Analysis: Calculate the proportion of consecutive missed notes (miss streaks) relative to total missed notes.
2. Distance Between Misses: Measure the distances between missed notes to assess potential non-random patterns.
3. Runs Test: Use the Runs Test to determine if distances between missed notes suggest randomness.

## Resampling Methods:
- Parametric Bootstrap: Resamples data using a Bernoulli distribution.
- Nonparametric Bootstrap: Resamples the data with replacement to simulate sampling distributions.
- Permutation Resampling: Randomly permutes the data without replacement to test for randomness.

## Key Findings:
- Results varied across songs, with some tests indicating non-randomness, while others did not.
- The project found that the Runs Test results were inconsistent when used across different songs and resampling methods.

## Songs Analyzed:
- Judith
- Hurts
- American Girl
- Funky
- Ring of Fire
- Watchtower
- Wolf

## Tools & Techniques:
- R Programming: Utilized for data analysis and simulation, using packages like snpar for the Runs Test.
- Statistical Methods: Bootstrapping, Permutation Testing, Runs Test.

## Conclusion:
This project provides a framework for undergraduate students to explore statistical concepts in a practical, engaging context. Although the results are inconclusive in fully determining the randomness of missed notes, the process demonstrates the importance of resampling methods and hypothesis testing in real-world data analysis.
