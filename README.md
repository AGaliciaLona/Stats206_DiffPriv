STAT 206 Final Project

Group Members: <br />
Axel Galicia Lona, Linlin Liu, and Nancy Lopez

Questions: <br />
What factors significantly impact a movie's revenue, and how can predictive models be used to analyze these factors? Additionally, how can differential privacy (DP) be incorporated into the model, and how effectively will the implementation protect sensitive data while maintaining the utility of the analysis?

Project Summary: <br />
Movies are a dynamic art form and a significant economic driver in the entertainment industry. This project leverages a MLR model to analyze key factors influencing a movie's revenue. As an experimental feature, we apply differential privacy (DP) on the final model to examine its effect on protecting sensitive data, such as financial details and user-related information. This addition aims to balance confidentiality and utility while exploring DP’s feasibility in movie data analysis.

Required Packages: <br />
library(tidyverse) <br />
library(lubridate) <br />
library(dplyr) <br />
library(ggplot2) <br />
library(gridExtra) <br />
library(GGally) <br />
library(car) <br />
library(mltools) <br />
library(data.table) <br />
library(fastDummies) <br />
library(lmtest) <br />
library(tidyr) <br />
library(grid) <br />
library(scales) <br />
library(forcats) <br />
library(diffpriv) <br />
