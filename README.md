# Shapley

Shapley value utilities in Julia.

This repository is going to be confusing for anyone snooping around. Come back later and it might be cleaned up.

## Methods

Shapley(team, game, removal)

## Abstract types

-   Team (for defining players) - supertype of (grouped) data set, ...
-   Removal (for subsetting the team) - supertype of column select, marginalise, ...
-   Game (for characteristic function) - supertype of model, dc, hsic, ...

## Goals

Extensible and modular, e.g.:

-   Ease of implementing similar Shapley value alternatives, e.g., asymmetric Shapley - but this suggests a more general package / structure
-   Ease of implementing approximation techniques
-   Ease of implementing alternative calculation methods, e.g., Harsanyi dividends

## Long term goals

-   Integration with popular model outputs including LightGBM and XGBoost
-   Plot Shapley values over time, with e.g., ADL, ADP and ADR
