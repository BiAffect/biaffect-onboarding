# 👋 Welcome to BiAffect!

We're excited to have you on board. This document will guide you through the key resources to help you get familiar with what we're researching & building.

---

## 📱 Download the App

Start by exploring the BiAffect iOS app:  
🔗 [Download from the App Store](https://apps.apple.com/us/app/biaffect3/id6451423106)

---

## 🎥 Overview Video

Get a high-level introduction to BiAffect:  
▶️ [TEDx Talk by Dr. Alex Leow](https://www.youtube.com/watch?v=FGggieYbN2g&themeRefresh=1)

---

## 🌐 Visit Our Website

Learn more about the project, our goals, and background:  
🔗 [www.biaffect.com](https://www.biaffect.com/)

---

## 📚 Deep Dive: Research Background

Below are key publications that form the scientific foundation of BiAffect. Start with the **Core Papers** for the most recent and directly relevant work, then refer to **Earlier Papers** for deeper context and evolution of the research.

---

### Most Recent Papers
**Knol et al. (2024)**  
*Smartphone keyboard dynamics predict affect in suicidal ideation*  
https://pubmed.ncbi.nlm.nih.gov/38076837/

**Liu et al. (2024)**  
*Digital phenotypes of mobile keyboard backspace rates and their associations with symptoms of mood disorder*  
https://pmc.ncbi.nlm.nih.gov/articles/PMC11558221/

**Ross et al. (2023)**  
*A novel approach to clustering accelerometer data for application in passive predictions of changes in depression severity*
https://www.mdpi.com/1424-8220/23/3/1585

---

### Earlier Papers
**Bennett et al. (2022)**  
*Smartphone accelerometer data as a proxy for clinical data in modeling bipolar disorder symptom trajectory*
https://www.nature.com/articles/s41746-022-00741-3

**Chen et al. (2022)**  
*Associations between smartphone keystroke dynamics and cognition in MS*
https://pubmed.ncbi.nlm.nih.gov/36506490/

**Vesel et al. (2020)**  
*Effects of mood and aging on keystroke dynamics metadata in a large open-science sample*
https://pubmed.ncbi.nlm.nih.gov/32467973/

**Rashidisabet et al. (2020)**  
*Characterizing keyboard dynamics in mood disorders by age and time-of-day*
https://www.academia.edu/94787156/Characterizing_Passively_Collected_Real_World_Keyboard_Dynamics_in_Mood_Disorders_as_a_Function_of_Age_and_Time_of_Day

**Zulueta, Ajilore & Leow (2020)**  
*The Effects of Bipolar Disorder Risk on a Mobile Phone Keystroke Dynamics Based Biomarker of Brain Age*
https://pmc.ncbi.nlm.nih.gov/articles/PMC8727438/

**Zulueta et al. (2018)**  
*Predicting mood disturbance severity with keystroke metadata: A BiAffect study*
https://pubmed.ncbi.nlm.nih.gov/30030209/

**Stange et al. (2018)**  
*Passive typing instability predicts future mood outcomes*
https://pubmed.ncbi.nlm.nih.gov/29516666/

**Cao et al. (2017)**  
*DeepMood: Modeling typing dynamics for mood detection*
https://arxiv.org/abs/1803.08986

---

## 📈 Data Analysis Prep

If you're going to work on data analysis of the keyboard dynamics collected by the BiAffect app, please review the following to prepare.

We use Synapse as our data repository, and the `synapseclient` Python package to access and download data. Below are essential resources to get you started:

- [Synapse Python Client Setup](https://python-docs.synapse.org/tutorials/python_client/)  
  Installation and authentication guide for `synapseclient`.

- [Using `synapseutils.syncFromSynapse()`](https://python-docs.synapse.org/reference/synapse_utils/)  
  Reference for downloading files and working with manifests.

- [Entity Types, Annotations, and File Metadata](https://help.synapse.org/docs/Downloading-Data-Programmatically.2003796248.html)  
  Overview of Synapse IDs, files, folders, and how to access metadata and annotations.

---
