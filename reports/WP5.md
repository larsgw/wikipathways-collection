<img style="float: right; width: 200px" src="../logo.png" />
# WikiPathways WP5

* WikiPathways: [WP5](https://identifiers.org/wikipathways:WP5)
* Scholia: [WP5](https://scholia.toolforge.org/wikipathways/WP5)
* WPRDF file: [wp/Human/WP5.ttl](../wp/Human/WP5.ttl)
* GPMLRDF file: [wp/gpml/Human/WP5.ttl](../wp/gpml/Human/WP5.ttl)
* SBML file: [sbml/WP5.sbml](../sbml/WP5.sbml) ([SVG](../sbml/WP5.svg)) ([conversion notes](../sbml/WP5.txt))

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
* InteractionTests: all 7 tests OK!
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
* Number of fails: 2

## Fails

<a name="d2d32fa2" />

## DataNodesTests.dataNodesWithoutIdentifier

The following DataNodes have no identifier: 3
```
http://www.wikipathways.org/instance/WP5.gp_r116955 http://rdf.wikipathways.org/Pathway/WP5.gp_r116955/DataNode/b83 (APPL)
http://www.wikipathways.org/instance/WP5.gp_r116955 http://rdf.wikipathways.org/Pathway/WP5.gp_r116955/DataNode/bbc (APPL)
http://www.wikipathways.org/instance/WP5.gp_r116955 http://rdf.wikipathways.org/Pathway/WP5.gp_r116955/DataNode/e52 (APPL)
```

<a name="ad154c1e" />

## HMDBMetabolitesTests.correctFormat

I expected more than zero HMDB identifiers.
