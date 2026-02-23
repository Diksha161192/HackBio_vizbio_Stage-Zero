**Topic: Dashboards for biology: Stop treating your plots like PowerPoint.**

Biological data is complex, dynamic and multi-dimensional. Yet, the visualization of the data has not evolved at the same pace with which it is generated. We often summarize it with static figures. In many biology workflows, plots are treated as final products rather than as tools for exploration and decision making. When biological plots are treated like PowerPoint slides, it limits its exploration and the questions that can be asked from such data. Interactive visualizations, however, support flexible, iterative data exploration by allowing dynamic manipulate views, test assumptions and uncovering of patterns that static graphics usually do not reveal (Heer & Shneiderman, 2012). Thus, a shift from static presentations to interactive dashboards that support real biological insights is critical and necessary.

**The Problem with Static Plots in Biology**

In biological research, commonly used static plots such as bar and line graphs often obscure data variability and individual observations, limiting transparency and potentially leading to misinterpretation of data (Weissgerber et al., 2016). Bar charts, heatmaps, line graphs and scatter plots are generated, polished and frozen in time. They are optimized for presentation but not for exploration. This approach hides the underlying complexity and creates several limitations as static figures which rarely answer predefined questions. In a field like biology, where results vary across conditions, time points and several samples, this approach can obscure important patterns and uncertainty.

**What Dashboards can Change**

Dashboards represent a shift from static figures to interactive analytical environments. Tools such as **Shiny** and **Quarto** in R allow researchers to build interfaces where data can be explored. Interactive tools and dashboards, including those built with R-based frameworks, are increasingly used in biological research to improve data exploration, reproducibility and communication beyond what static figures allow (Perkel, 2018).

With dashboards, researchers can:

1.  Filter data by condition, time point or sample group.
2.  Adjust thresholds and immediately see how results change.
3.  Compare multiple views of the same dataset side by side

Instead of asking the question of whether the plot looks good, the question immediately becomes, “what happens if the current assumptions are varied or changed entirely?” The purpose of the values on the dashboards is not for aesthetic appeal but for decision-making revealing putative outcomes. They can help biologists evaluate robustness, compare conditions and identify meaningful variables’ relationships which are worth further investigation. By encouraging interaction, dashboards make assumptions visible and support more transparent analysis.

**A Simple Example**

Consider a gene expression study across multiple conditions. A static heatmap might highlight clusters and trends, but it fixes the scale, the ordering and the included genes.\
An interactive dashboard could allow a researcher to:

1.  Select specific genes of interest.
2.  Toggle between normalized and raw expression.
3.  Inspect individual gene profiles over time.

The same dataset becomes more informative, not because it looks better, but because it can be questioned more deeply.

**Conclusion**

The future of biological data visualization should, while maintaining static figures with higher resolution or better color palettes, transition to dashboards that supports interactive visualizations. This form of interactive visualization should reflect how research actually happens; iteratively, uncertainly and driven by decision-making. Dashboards do not replace papers or figures. They complement them by supporting exploration before conclusions are finalized. By moving beyond PowerPoint-style plots, biologists can engage more honestly with their data and make better-informed research choices. In biology, insight comes not from prettier plots, but from better questions. Interactive dashboards help us ask them.

**References**

Heer, J., & Shneiderman, B. (2012). Interactive dynamics for visual analysis. Communications of the ACM, 55(4), 45–54. <https://doi.org/10.1145/2133806.2133821>

Weissgerber, T. L., Milic, N. M., Winham, S. J., & Garovic, V. D. (2016). Beyond bar and line graphs: Time for a new data presentation paradigm. PLoS Biology, 14(4), e1002484.\
<https://doi.org/10.1371/journal.pbio.1002484>

Perkel, J. M. (2018). Data visualization tools drive interactivity and reproducibility in science. Nature, 554(7690), 133–134. <https://doi.org/10.1038/d41586-018-01322-9>
