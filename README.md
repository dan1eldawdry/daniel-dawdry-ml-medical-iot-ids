# Machine Learning Intrusion Detection for Medical IoT

**Daniel Dawdry** | COMP3000 Computing Project | University of Plymouth
**Supervisor:** Shaymaa Al-Juboori

## About the project
Hospitals use more and more connected devices, like heart monitors, drip pumps and wearable sensors. A lot of them aren't very secure. Some go years without an update, and most are too small to run normal security software. If one gets attacked, it could stop working or show the wrong reading, which could put a patient at risk.

My project is about protecting these devices from the outside by watching the traffic they send over the network. I'm training a few machine learning models to tell normal traffic apart from attacks, then building a small working version that shows an alert on a dashboard when it spots something.

## Project vision
I want to build a tool that uses machine learning to spot cyber attacks on medical devices, and test it properly so I can be honest about what it can and can't do.

## Datasets
I'm using two public datasets:

- **CICIoMT2024**: my main dataset, covering 40 medical devices and 18 types of attack.
- **WUSTL-EHMS-2020**: a smaller dataset I'll use to check if my models still work on data they haven't seen.

The datasets aren't stored here because they're too big. Download links and setup steps will be added soon.

## Folder layout
```
data/          datasets (kept off GitHub)
notebooks/     trying things out and exploring the data
src/           the main project code
tests/         tests for my code
docs/          notes and screenshots
results/       charts, scores and saved models
```

## Tools
Python, pandas, scikit-learn, XGBoost, PyTorch, Scapy and Streamlit.

## Current status
I'm in the planning and setup stage. I've chosen my datasets and set up this repo, and I'm cleaning the data now. Most of the coding will happen over the Christmas break.

## Disclaimer
This is a student research project, not a medical device. It should not be used in a real hospital. All testing is done on my own machine using recorded traffic only.
