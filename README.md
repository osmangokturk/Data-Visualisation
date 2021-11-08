# Data-Visualisation
Notes and practical guides on the data visualisation

Visualistion choice depends on your choice of message or information you want to transfer. 

you can think s the choice of graph (bar, pairplot) or the specificity of the data you have (categorical, numerical) and the level of interaction (labels, legends, changing the content )

Visualistion can be done through several libraries in the Python. The same thing can be done in each library, however there are some differences.

First of all lets summarize different libraries at a glance

A) pandas or DAtaFrame's own library. -plot(kind="bar", rot=45):based on the mathplotlib. kind define the graph like bar, .. and rot defines the rotation degre of ticks on X axes. -hist() -describe() crosstab()

B) MatplotLib (usually plt): based on the MATLAB. scatter() -make use of fig, axes.

C) Seaaborn: a higher API based on Matplotlib. can provide more features with less coding. -pairplot() -distplot(),violinplot(), boxplot) -jointplot() -lmplot(hue=)

D) Plotly: open librry, more interactive. Figure is the work horse. -trace refer to data -lineplot(); -barchart() -boxplot()

T
