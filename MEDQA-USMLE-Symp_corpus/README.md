# File Format:
The dataset is in the brat format, see below. For each abstract there is one .txt file containing the text and one .ann file containing the annotations. The annotation.conf contains the configuration for the annotations for brat.

# Annotation Tool:
The brat annotation tool (version 1.3 "Crunchy Frog") was used for annotation.
It can be downloaded from http://brat.nlplab.org

To visualise the annotations in brat, copy the content of the data file(including the annotation.config) to the data folder in the brat directory, start brat and select the data set in the menu.

# Statistics
| **Label**                | **# Entities** |
|--------------------------|----------------|
| Sign or Symptom          | 1579           |
| Finding                  | 1169           |
| Temporal Concept         | 567            |
| Location                 | 498            |
| Population Group         | 364            |
| Age Group                | 304            |
| No Symptom Occurrence    | 264            |

Table: Statistics of the MEDQA-USMLE-Symp dataset