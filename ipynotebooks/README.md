IPython notebooks 
=================

[IPython notebooks](http://ipython.org/notebook.html) illustrating specific MMI ORR functionality and access mechanisms. [Rendered versions can be browsed and viewed easily at this http://nbviewer.ipython.org link.](http://nbviewer.ipython.org/github/emiliom/mmipy/tree/master/ipynotebooks/)

Initially I'm populating this folder with my existing notebooks, from my gist and other sources. [My relevants gists are easily found via the _mmi_ tag](https://www.mygists.info/emiliom/tags/mmi) I've used (hopefully on all relevant gists). 

The `get_term_ontmeta_jsonurl()` function I created in my [mmi_term_testing.ipynb gist](https://gist.github.com/emiliom/6514804) is already fully copied and illustrated in [AOOS_SOS_SensorML_owslib_AlaskaNDBCBuoy_1.ipynb] (https://github.com/emiliom/mmipy/blob/master/ipynotebooks/AOOS_SOS_SensorML_owslib_AlaskaNDBCBuoy_1.ipynb), so I didn't copy that notebook here.

I also have one or two notebooks on [my Wakari account](https://www.wakari.io/emayorga), though they may be duplicates of my gists:
- [ioossos_owslib_SensorML_MMIcheck_demo1](https://www.wakari.io/sharing/bundle/emayorga/ioossos_owslib_SensorML_MMIcheck_demo1): From Feb 12, 2014
- [SPARQLWrapper_MMI_IOOSParameterVocabTerm](https://www.wakari.io/sharing/bundle/emayorga/SPARQLWrapper_MMI_IOOSParameterVocabTerm): From Sep 26, 2013
- [SPARQLWrapper%20against%20MMI%20IOOS%20Parameter%20Term](https://www.wakari.io/sharing/bundle/emayorga/SPARQLWrapper%20against%20MMI%20IOOS%20Parameter%20Term): From Sep 25, 2013

For the [IOOS System Integration Test](https://github.com/ioos/system-test), ASA's [Kyle Wilcox](https://github.com/kwilcox) created a nice and succinct illustration of how to use [rdflib](https://github.com/RDFLib/rdflib) to pull all entries in an MMI vocabulary into a pandas DataFrame: 
- [The IPython notebook.](http://nbviewer.ipython.org/github/ioos/system-test/blob/master/Theme_1_Baseline/Scenario_1B_CoreVariable_Strings/Scenario_1B_CoreVariable_Strings.ipynb) See the first two cells only, in the first section: "Get a list of the IOOS Core Variables from MMI". Note that the set of "attributes" that will be pulled in are hard-coded.
- [The specific IOOS System Integration Test scenario.](https://github.com/ioos/system-test/tree/master/Theme_1_Baseline/Scenario_1B_CoreVariable_Strings) Goes way beyond the rdflib test, to using MMI SPARQL query results ran against OGC CSW endpoints.
