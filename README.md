# Predicting-H1N1-and-Seasonal-Flu-Vaccination-Uptake-Using-Machine-Learning
This project builds a machine learning model to predict whether an individual received a H1N1 and Seasonal Flu Vaccine using demographic, behavioral, and opinion-based survey data. The project is part of my fulfillment of course expectations for my Moringa School Phase 3 Data Science Course. 

### Introduction
**Influenza** is a contagious respiratory illness that can cause serious complications, sometimes leading to hospitalization or even death. Remember the **Spanish Flu** that spread across the world courtesy of returning soldiers after World War 1? That was influenza. Those most at risk include older adults (65+ years), young children, and individuals with underlying health conditions (WHO, 2024).

![Makeshift Spanish Flu ward, 1918](Makeshift_spanish_flu_ward.JPG)

The best way to protect yourself is through an annual flu vaccine, which reduces the severity of illness and related complications. The vaccine works by stimulating your immune system to produce protective antibodies within about two weeks (CDC, 2024). Health authorities recommend that everyone aged 6 months and older get vaccinated every year.

The **H1N1 pandemic** began in 2009 when a new influenza A virus strain emerged in the United States. It caused widespread illness and an estimated 151,700–575,400 deaths globally. Unlike typical seasonal flu, this outbreak mainly affected children and younger adults, while older adults were less impacted—likely because they had pre-existing immunity from exposure to a similar virus decades earlier. A targeted vaccine was rolled out in October 2009, and by August 2010, the World Health Organization declared the pandemic over. However, H1N1 did not disappear; it continues to circulate as part of the seasonal flu viruses we see today (CDC, 2024).

![Electron microscope image of H1N1 virus](Electron_microscopy_h1n1_virus.JPG)

**Coronavirus Disease 2019 (COVID‑19)** was first identified in late 2019 in Wuhan, China, after clusters of patients presented with a severe respiratory illness resembling viral pneumonia. Rapid global spread, high hospitalization burdens in some settings, and early mortality uncertainty drove an urgent push to develop vaccines at unprecedented speed. That speed—along with changing public guidance, misinformation, and broader social distrust—contributed to widespread worry and reluctance around COVID‑19 vaccination in many communities (WHO; CDC; global public health reports).

This hesitation was not new. During the 2009 pandemic, public health officials reported similar concerns about a “fast‑tracked” vaccine, and uptake varied widely across populations. Studies from that period showed that risk perception, trust in authorities, and beliefs about vaccine safety strongly influenced whether people agreed to be immunized (global influenza behavior studies; pandemic preparedness literature).

Vaccine hesitancy refers to delay in acceptance or refusal of vaccines despite availability of vaccination services. It is shaped by factors such as confidence (trust in the vaccine and the system that delivers it), complacency (perceived need for the vaccine), and convenience (access). Hesitancy can shift over time and across social or cultural settings and has been identified by global health agencies as a significant threat to disease control efforts (WHO Strategic Advisory Group of Experts on Immunization; global vaccine confidence monitoring initiatives).

![To vaccinate, or not to vaccinate? That's the question.](Herd_immunity.JPG)

Pandemics amplify the stakes. When large numbers postpone or refuse vaccination during a fast‑moving outbreak, the result can be preventable illness, strain on health systems, and sustained community transmission. Evidence from recent survey research suggests that past vaccine behavior may predict future decisions: people who declined a prior influenza (including H1N1) vaccine have often reported lower willingness to accept newer vaccines such as those for COVID‑19 (comparative vaccine acceptance studies; vaccine confidence surveys).

#### What should public health teams do?
A practical first step is to use available data to identify groups at higher risk for hesitancy. From there, programs can:

* Tune messages to address local concerns (from safety, to side effects, to speed of development).
* Involve local health networks to disemminate information (community health workers, level 1 and level 2 facilities).
* Improve convenience through the use of mobile clinics, mass vaccination drives.
* Share data on safety monitoring and real‑world effectiveness.
* Track sentiment over time and use it to alter approaches before another epidemic or pandemic occurs.

By combining behavioral insight with targeted communication and easier access, public health practitioners can reduce vaccine gaps, and be better prepared when the next emerging infection appears.

### Objective
The goal of this project is to create a model that can predict seasonal flu vaccine uptake based on a person's background and behavioral patterns. The project will be deemed a success when a model with the highest accuracy is developed.

### Project Pipeline
This outlines the processes to be undertaken in this project. They are:
1. Loading the data
2. Exploratory data analysis
3. Data processing
4. Modelling
5. Evaluation
6. Recommendations

### Repository contents
This repository contains:
* A Jupyter notebook (vaccination_notebook.ipynb).
* A folder containing the testing and training data.
* A folder containing images linked to the notebook.
* A presentation pdf containing a brief on the project.

The testing and training data was obtained from:
(DrivenData. (2020). Flu Shot Learning: Predict H1N1 and Seasonal Flu Vaccines. Retrieved [Month Day Year] from https://www.drivendata.org/competitions/66/flu-shot-learning.)
