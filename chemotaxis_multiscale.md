# FRET measurements and multiscale modeling of E.coli chemotaxis
By the late 1990-s E.coli chemotaxis was a well-established field, and the chemotaxis pathway was resonably well described
to a point where mathematical modeling became a powerful tool
(e.g. [Barkai & Leibler, 1997](http://www.nature.com/nature/journal/v387/n6636/full/387913a0.html "Robustness in simple biochemical networks. Nature, 1997"))

The introduction of [FRET](http://www.rowland.harvard.edu/labs/bacteria/projects/fret.php "Förster resonance energy transfer") 
for measurement of protein interactions exploded the chemotaxis field 
([Sourjik & Berg, 2002](http://www.pnas.org/content/99/1/123.full "V.Sourjik & H.Berg. Receptor sensitivity in bacterial chemotaxis. PNAS, 2002.")).
It allowed measuring protein interactions between pathway components in live cells in real time, compared to costly time-averaged *in vitro* biochemical assays. The avalanche of new data revealed that receptors are organized in clusters that amplify the signal, and inspired a new generation of mathematical models describing the system with unprecedented accuracy ([Tu, Shimizu, Berg, 2008](http://www.pnas.org/content/105/39/14855 "Modeling the chemotactic response of Escherichia coli to time-varying stimuli. PNAS, 2008")).

I was happy to contibute my 5 cents to the field of modeling of E.coli chemotaxis: [RapidCell](http://www.rapidcell.net/) simulator which allows fast and accurate multiscale modeling of bacterial populations in attractant gradients. It allowed us to predict an additional aspect of chemotactic navigation - the gradient-dependent tumbling angle ([Vladimirov, Lebiedz, Sourjik, 2010](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000717 "Predicted Auxiliary Navigation Mechanism of Peritrichously Flagellated Chemotactic Bacteria")), which was later confirmed in experiments ([Saragosi et al, 2011](http://www.pnas.org/content/108/39/16235.full "Directional persistence of chemotactic bacteria in a traveling concentration wave")).
