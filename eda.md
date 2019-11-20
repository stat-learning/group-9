Exploratory Data Analysis
================

## Paul Nguyen & David Herrero-Quevedo

## Data Description

### Provenance

We obtained our datasets from basketball-reference.com and
stats.nba.com. We used the R package `nbastatR` to obtain the data from
those websites.

### Unit of observation

Our unit of observation is a `player`. We have data for n number of
players (\#TODO: need to decide how many players are we going to use)

### Variables

Each player has a series of variables c We have p number of variables
(\#TODO: need to clean this up)

## Data Exploration

### Missingness

(\#TODO: need to complete)

### Univariate analysis of the response

Numerical, graphical (\#TODO: need to complete)

### Bi-, trivariate analysis of the response

graphical (\#TODO: need to complete)

### Variables used:

#### Shooting:

  - pctFTRate
  - pct3PRate
  - pctFG
  - pctFG3
  - pctFG2
  - pctEFG
  - pctFT
  - fgmPerGame
  - fgaPerGame
  - fg3mPerGame
  - fg3aPerGame
  - fg2mPerGame
  - fg2aPerGame
  - ftmPerGame
  - ftaPerGame
  - ptsPerGame

#### Rebounds

  - pctORB
  - pctTRB
  - pctDRB
  - orbPerGame
  - drbPerGame
  - trbPerGame

#### Passing

  - pctAST
  - pctTOV
  - astPerGame
  - tovPerGame

#### Defense

  - pctSTL
  - pctBLK
  - stlPerGame
  - blkPerGame
  - pfPerGame

#### Efficiency stats

  - ratioOWS
  - ratioDWS
  - ratioWS
  - ratioWSPer48
  - ratioOBPM
  - ratioDBPM
  - ratioBPM
  - ratioVORP

#### Other

  - pctUSG
  - countTeamsPlayerSeason
  - countGamesStarted
  - minutesPerGame