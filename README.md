# AI Football Manager

Final project for the Building AI course

## Summary

AI Football Manager is an AI-powered system that helps football clubs with limited budgets find undervalued players. Using machine learning models, it predicts player market values and categorizes them based on performance data, optimizing recruitment strategies.

## Background

Football clubs often struggle with scouting due to financial constraints and subjective decision-making. This project aims to provide an AI-driven alternative for objective player valuation and selection.

This project solves:
* Identifying undervalued players based on performance metrics.
* Optimizing team recruitment within a given budget.
* Reducing reliance on subjective scouting methods.

## How is it used?

The system collects player statistics, predicts their market values using regression models, and classifies them into categories (Prospect, Value Player, Star) via a neural network. Club managers can use these insights to make informed transfer decisions.

## Data sources and AI methods

The system relies on data from sources such as:
- [Transfermarkt](https://www.transfermarkt.com/) for market values.
  [Erling Braut Håland](https://www.transfermarkt.com/erling-haaland/profil/spieler/418560) for market values.
  [Bruno Miguel Borges Fernandes](https://www.transfermarkt.com/bruno-fernandes/profil/spieler/240306) for market values.
  [Amad Diallo](https://www.transfermarkt.com/amad-diallo/profil/spieler/536835) for market values.
  [Kobbie Mainoo](https://www.transfermarkt.com/kobbie-mainoo/profil/spieler/820374) for market values.
  [Alejandro Garnacho Ferreyra](https://www.transfermarkt.com/alejandro-garnacho/profil/spieler/811779) for market values.
  
- [Open-Meteo API](https://open-meteo.com/) for weather conditions.
- Match statistics and player performance data from various sports APIs.

AI methods used:
| AI Technique      | Usage |
| ----------------- | ------------------------- |
| Linear Regression | Predicts player market value |
| Neural Network    | Classifies players into categories |
| Optimization Algorithm | Selects best players within budget |

## Challenges

This project does not account for:
* Sudden player injuries affecting long-term value.
* Psychological factors and team chemistry.
* Real-time fluctuations in market value.

Ethical considerations:
* Ensuring data privacy and fair evaluations.
* Avoiding biases in player assessment.

## What next?

Future improvements include:
* Integrating more detailed player performance data.
* Enhancing predictions using deep learning.
* Connecting real-time transfer data through APIs.

## Acknowledgments

* Inspired by Moneyball tactics in sports.

