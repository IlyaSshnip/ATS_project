## Price Discovery and Information Revelation

This repository contains a presentation on **Single- and Multi-Period Kyle Models**, exploring how private information becomes incorporated into asset prices through strategic trading and market response.

## Overview

The presentation builds on the classic single-period Kyle (1985) model and extends it to:

- **Multi-period** setting, where informed traders can spread trades over multiple auctions.
- **Multiple informed traders**, as introduced by Holden and Subrahmanyam (1992).

---

## **Project Structure**
```plaintext
├── .gitignore                     
├── kyle_model.ipynb               # Project Implementation
├── requirements.txt               # Python dependencies
├── .python-version                # Python version
├── presentation
│   ├── presentation.tex           # LaTeX source of the Beamer presentation
│   └── presentation.pdf           # Compiled slides
```
---

## Models

- **Single-period Kyle model**: Linear equilibrium under asymmetric information. Price adjusts based on total order flow, partially revealing the asset’s true value.
- **Multi-period Kyle model**: Sequential auctions allow gradual information revelation and recursive Bayesian price updates.
- **Holden & Subrahmanyam extension**: Introduces competition among informed traders, accelerating the rate at which information is impounded into prices.

## Authors

Andrei Shelest, Filipe Correia, Ilya Shnip, Zofia Bracha  
Presented: May 27, 2025

## Main References

- **Kyle, A. S. (1985).** *Continuous Auctions and Insider Trading*. *Econometrica*, 53(6), 1315–1335.  
  Introduces the canonical single-period and multi-period model of insider trading with strategic interaction between informed traders, noise traders, and a market maker.

- **Holden, C. W., & Subrahmanyam, A. (1992).** *Long-Lived Private Information and Imperfect Competition*. *Journal of Finance*, 47(1), 247–270.  
  Extends Kyle’s model to include multiple informed traders competing over multiple periods. Derives closed-form solutions for equilibrium with linear strategies.

- **Back, K. (1992).** *Insider Trading in Continuous Time*. *Review of Financial Studies*, 5(3), 387–409.  
  Offers a continuous-time limit of Kyle’s model.
