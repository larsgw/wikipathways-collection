<img style="float: right; width: 200px" src="../logo.png" />
# WikiPathways WP6

* WikiPathways: [WP6](https://identifiers.org/wikipathways:WP6)
* Scholia: [WP6](https://scholia.toolforge.org/wikipathways/WP6)
* WPRDF file: [wp/Human/WP6.ttl](../wp/Human/WP6.ttl)
* GPMLRDF file: [wp/gpml/Human/WP6.ttl](../wp/gpml/Human/WP6.ttl)
* SBML file: [sbml/WP6.sbml](../sbml/WP6.sbml) ([SVG](../sbml/WP6.svg)) ([conversion notes](../sbml/WP6.txt))

## Tests
* CASMetabolitesTests: all 2 tests OK!
* ChEBIMetabolitesTests: all 4 tests OK!
* ChemSpiderTests: all 2 tests OK!
* DataNodesTests
    * dataNodesWithoutIdentifier: .x we found 1 problem(s):
        * [The following DataNodes have no identifier: 3](#d2d32fa2)
    * unknownTypes_knownDatasource: .. all OK!
    * unknownTypes: .. all OK!
    * unknownTypes_Reactome: .. all OK!
* EnsemblTests: all 4 tests OK!
* GeneralTests: all 13 tests OK!
* GeneTests: all 3 tests OK!
* HMDBMetabolitesTests
    * outdatedIdentifiers: .. all OK!
    * correctFormat: .x. we found 1 problem(s):
        * [I expected more than zero HMDB identifiers.](#ad154c1e)
* HMDBSecMetabolitesTests: all 3 tests OK!
* InteractionTests
    * noMetaboliteToNonMetaboliteConversions: .. all OK!
    * noNonMetaboliteToMetaboliteConversions: .. all OK!
    * noGeneProteinConversions: .. all OK!
    * nonNumericIDs: .. all OK!
    * interactionsWithLabels: .x we found 1 problem(s):
        * [Interactions found that involve Labels: 11](#fe97a8b9)
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
* Number of fails: 3

## Fails

<a name="d2d32fa2" />

## DataNodesTests.dataNodesWithoutIdentifier

The following DataNodes have no identifier: 3
```
http://www.wikipathways.org/instance/WP6.gp_r116713 http://rdf.wikipathways.org/Pathway/WP6.gp_r116713/DataNode/ab0 (MYO-P)
http://www.wikipathways.org/instance/WP6.gp_r116713 http://rdf.wikipathways.org/Pathway/WP6.gp_r116713/DataNode/e6a (PI5K)
http://www.wikipathways.org/instance/WP6.gp_r116713 http://rdf.wikipathways.org/Pathway/WP6.gp_r116713/DataNode/f05 (p110)
```

<a name="ad154c1e" />

## HMDBMetabolitesTests.correctFormat

I expected more than zero HMDB identifiers.
<a name="fe97a8b9" />

## InteractionTests.interactionsWithLabels

Interactions found that involve Labels: 11
```
http://www.wikipathways.org/instance/WP6.gp_r116713 "ERK" with graphId eb3
http://www.wikipathways.org/instance/WP6.gp_r116713 "RAF" with graphId cac
http://www.wikipathways.org/instance/WP6.gp_r116713 "cell motility" with graphId d23
http://www.wikipathways.org/instance/WP6.gp_r116713 "MEK" with graphId db9
http://www.wikipathways.org/instance/WP6.gp_r116713 "ITGB" with graphId de2
http://www.wikipathways.org/instance/WP6.gp_r116713 "cell maintenance" with graphId b05
http://www.wikipathways.org/instance/WP6.gp_r116713 "PAK" with graphId b8f
http://www.wikipathways.org/instance/WP6.gp_r116713 "F-actin" with graphId c40
http://www.wikipathways.org/instance/WP6.gp_r116713 "cell maintenance" with graphId e00
http://www.wikipathways.org/instance/WP6.gp_r116713 "CAPN" with graphId dd0
http://www.wikipathways.org/instance/WP6.gp_r116713 "cell proliferation" with graphId dbd
```

