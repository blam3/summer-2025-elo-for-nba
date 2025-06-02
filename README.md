# Erdos Institute Summer 2025 Project - NBA Elo Analysis

Kwame Osei-Tutu, Brendan Lam, Daryl Reed

Creating an Elo rating system using National Basketball Association (NBA) data as a part of the Erdos Institute's data science bootcamp.

What we’re building
We aim to analyze(and possibly improve upon) Elo ratings for NBA teams. Using 75 years of game logs plus nightly updates, we’ll replicate the classic Elo model, test modern tweaks (margin-of-victory scaling, time-decay, Glicko volatility, Bayesian uncertainty), and surface everything in a slick, shareable dashboard if possible.

Why it’s cool
Data fire-hose: 130 K+ historical games, rich box-score detail, and a public API for fresh results every night.
Instant benchmarks: FiveThirtyEight’s published Elo lets us see—quantitatively—when we’re better.
Universal appeal: Even casual fans “get” basketball, so our insights land quickly with any audience.

What we're doing
Build a reproducible data pipeline with nba_api, Parquet storage, and GitHub Actions updates.
Implement and compare rating variants, track predictive accuracy, and quantify uncertainty.

