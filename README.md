# **Movement Ecology and Home Range Use of Black Capuchin Monkeys (_Sapajus nigritus_) in Pine Plantation Landscapes**  

## **Overview**
This repository contains R scripts used to analyze movement and space-use data of black capuchin monkeys (_Sapajus nigritus_) inhabiting pine plantations and Iguazú National Park, northeastern Argentina. Data were collected using a combination of methods, including GPS collars, VHF telemetry, and direct full-day group follows.  

To understand how the conversion of native forests into plantations affects spatial ecology, we conducted three main analyses:

## **Analyses**
### **Daily Trajectories** **[(CODE)](https://valentinzarate.github.io/Biol_Cons_Capuchins/daily_paper.html)**
**How much do capuchins move daily in plantations?**  
- We examined the effects of plantations and other environmental covariates on daily travel distances using **Generalized Linear Mixed Models (GLMMs)**.  
- Daily travel distance is directly linked to **energy expenditure** and the **challenges of meeting ecological needs** in altered landscapes.  

### **Movement Segmentation** **[(CODE)](https://valentinzarate.github.io/Biol_Cons_Capuchins/hmm_paper.html)** 
**How do capuchins move within plantations?**  
- To characterize movement patterns, we used **Hidden Markov Models (HMMs)** to segment trajectories into two behavioral states:  
  - **Resident**: Associated with resting, social interactions, feeding, and stationary foraging.  
  - **Transit**: Associated with traveling between resource patches.  
- This analysis provides insights into **how movement states are distributed spatially** and **how capuchins interact with landscape features**.  

### **Space Use** **[(CODE)](https://valentinzarate.github.io/Biol_Cons_Capuchins/akdes_paper.html)**
**How and where do capuchins distribute their activities in plantations?**  
- We estimated **home ranges and core areas** using **Autocorrelated Kernel Density Estimators (AKDEs)**.  
- Using **GLMMs**, we tested how home range size and core areas were influenced by plantations and other key covariates.  
- These findings provide **critical insights for primate conservation in forestry landscapes**, supporting **sustainable management practices** and **predicting population outcomes**.  






