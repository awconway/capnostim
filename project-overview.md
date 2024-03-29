
---
csl: Extras/anesthesiology.csl
bibliography: [Extras/references.bib]
---

# Peripheral electrical stimulation for sedation-induced respiratory depression during procedural sedation and analgesia

## Overview

Sedation-induced respiratory depression is common during procedures performed with procedural sedation. This project aims to develop a closed-loop system capable of delivering low-level peripheral electrical stimuli (PES) when respiratory depression is detected. A transcutaneous carbon dioxide (TcCO~2~) monitoring system will be used to detect respiratory depression. Specifically, the PES will be triggered when the rise in TcCO~2~ over a specified interval has exceeded a set threshold. 

Prior studies have confirmed the safety of applying peripheral electrical stimulation, including a similar clinical setting.[@smith2019peripheral; @suen2019pulse; @bisogni2017electrical; @pengo2015emerging] A randomized controlled trial of PES was undertaken for 106 post-operative patients with obstructive sleep apnea.[@smith2019peripheral] There were no adverse events related to the use of PES in this study.[@smith2019peripheral] Results also demonstrated initial evidence for the efficacy of this approach. Patients with obstructive sleep apnea who were randomized to receive PES had reduced duration and magnitude of hypoxemia during their stay in the post-anesthetic care unit.[@smith2019peripheral] 

Although there are similarities between this previous study and our plans for applying PES for respiratory depression during procedural sedation, there are some differences to consider. The most important is that it is common for patients receiving procedural sedation to receive supplemental oxygen routinely. Supplemental oxygen delays the detection of respiratory depression by indirect methods such as pulse oximetry. We will use a transcutaneous carbon dioxide monitoring system to assess the adequacy of ventilation directly. An analysis of TcCO~2~ monitoring data from ~200 patients in our previous studies will be used to guide the identification of an optimal threshold for detection of respiratory depression.

## System requirements

- Input from a Sentec digital monitoring system with V-Sign^TM^ Sensor 2 will be used as the trigger for initiating peripheral electrical stimulation. A technical manual can be accessed [here](https://www.sentec.com/fileadmin/documents/Labeling/Technical_Manuals/HB-005752-t-SDM_Technical_Manual.pdf).
- The closed-loop system that used SpO~2~ as the trigger in the Smith et al. [@smith2019peripheral] study required a motion sensor to detect inaccurate SpO~2~ measurements. A motion sensor will not be necessary for the closed-loop system using TcCO~2~ as the trigger to initiate PES.
- A peripheral nerve stimulator, such as the system used by Smith et al.[@smith2019peripheral] (DS7A, Digimeter), will be used to deliver electrical stimulation using a bar electrode.

\newpage

## References