<img style="float: right; width: 200px" src="../logo.png" />
# WikiPathways WP1

* WikiPathways: [WP1](https://identifiers.org/wikipathways:WP1)
* Scholia: [WP1](https://scholia.toolforge.org/wikipathways/WP1)
* WPRDF file: [wp/Human/WP1.ttl](../wp/Human/WP1.ttl)
* GPMLRDF file: [wp/gpml/Human/WP1.ttl](../wp/gpml/Human/WP1.ttl)
* SBML file: [sbml/WP1.sbml](../sbml/WP1.sbml) ([SVG](../sbml/WP1.svg)) ([conversion notes](../sbml/WP1.txt))

## Tests
* CASMetabolitesTests: all 2 tests OK!
* ChEBIMetabolitesTests: all 4 tests OK!
* ChemSpiderTests: all 2 tests OK!
* DataNodesTests: all 4 tests OK!
* EnsemblTests: all 4 tests OK!
* GeneralTests: all 13 tests OK!
* GeneTests: all 3 tests OK!
* HMDBMetabolitesTests: all 2 tests OK!
* HMDBSecMetabolitesTests: all 3 tests OK!
* InteractionTests
    * noMetaboliteToNonMetaboliteConversions: .. all OK!
    * noNonMetaboliteToMetaboliteConversions: .. all OK!
    * noGeneProteinConversions: .. all OK!
    * nonNumericIDs: .. all OK!
    * interactionsWithLabels: .x we found 1 problem(s):
        * [Interactions found that involve Labels: 4](#630d267b)
    * possibleTranslocations: .. all OK!
    * noProteinProteinConversions: .. all OK!
* KEGGMetaboliteTests: all 2 tests OK!
* LIPIDMAPSTests: all 1 tests OK!
* MetabolitesTests: all 14 tests OK!
* MetaboliteStructureTests: all 2 tests OK!
* OudatedDataSourcesTests: all 7 tests OK!
* PathwayTests: all 5 tests OK!
* ProteinsTests: all 2 tests OK!
* PubChemMetabolitesTests: all 3 tests OK!
* ReferencesTests: all 3 tests OK!
* UniProtTests: all 5 tests OK!
* WikidataTests: all 14 tests OK!


## Summary

* Number of test classes: 21
* Number of tests: 102
* Number of assertions: 205
* Number of fails: 1

## Fails

<a name="630d267b" />

## InteractionTests.interactionsWithLabels

Interactions found that involve Labels: 4
```
http://www.wikipathways.org/instance/WP1.gp_r117947 "IDL" with graphId c83
http://www.wikipathways.org/instance/WP1.gp_r117947 "LDL" with graphId d57
http://www.wikipathways.org/instance/WP1.gp_r117947 "HDL" with graphId cdf
http://www.wikipathways.org/instance/WP1.gp_r117947 "VLDL" with graphId fca
```

