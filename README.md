# Interruptibility Analysis
This repository contains additional information to accompany the poster paper submitted to CSCW 2024: 'Interruptibility during Scientific Research Collaborations: The Effect of Pressure, Proximity and Quiet Time'. In this study, we explore the interruptibility of scientific researchers and its correlation with contextual factors such as deadlines, outside-work hours, and location. We report in-progress findings from an autoethnographic study building on an analysis of interaction logs, as well as location and calendar data.

The researcher who is the object of this autoethnography is involved in several collaborative research projects. We will refer to her as Sandra. For this study, we chose four collaborative scientific research projects that occupied most of Sandra's time available for research during that period. She spent a significant amount of time on each project as can be seen in the figure below: 

![calplot](https://github.com/project-pivot/interruptibility-analysis/assets/4890367/898dee9a-1090-4779-9ad4-3d2f476ca3dd)

Sandra recorded her active applications and application titles from December 2022 to October 2023 using an open-source tool called Tockler. The tool continuously records the start and end time of each active window on the computer; it does not require a user to start or stop recording. For the mentioned period, this Active Window Tracking (AWT) data amounts to 195,558 data entries across 280 days for which computer behavior was recorded, averaging a little over 4 hours and 38 minutes per day. Naturally, this excludes work behavior taking place without the use of a computer. To prepare the data for analysis, Sandra manually annotated the data by adding a column to the CSV file and specifying which entries, i.e., window titles, corresponded to which research project. In addition, the titles directly following the work on one of the projects were annotated as `interruption'.

Afterwards, we computed a set of metrics for this data, described in the paper. Moreover, we performed a correlation analysis to examine the relation between the metrics. For example, the following figure depicts the correlation between the time to deadline and the slot duration:

![deadline_versus_meanslotduration](https://github.com/project-pivot/interruptibility-analysis/assets/4890367/c225ebcc-d596-4b37-ab63-8946b353e47d)
