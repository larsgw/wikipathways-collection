<img style="float: right; width: 200px" src="../logo.png" />
# WikiPathways WP7

* WikiPathways: [WP7](https://identifiers.org/wikipathways:WP7)
* Scholia: [WP7](https://scholia.toolforge.org/wikipathways/WP7)
* WPRDF file: [wp/Human/WP7.ttl](../wp/Human/WP7.ttl)
* GPMLRDF file: [wp/gpml/Human/WP7.ttl](../wp/gpml/Human/WP7.ttl)
* SBML file: [sbml/WP7.sbml](../sbml/WP7.sbml) ([SVG](../sbml/WP7.svg)) ([conversion notes](../sbml/WP7.txt))

## Tests
* CASMetabolitesTests: all 2 tests OK!
* ChEBIMetabolitesTests: all 4 tests OK!
* ChemSpiderTests: all 2 tests OK!
* DataNodesTests: all 4 tests OK!
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
* ReferencesTests
    * nonNumericPubMedIDs: .. all OK!
    * zeroPubMedIDs: .. all OK!
    * atLeastOneReference: .x we found 1 problem(s):
        * [Found 1 pathways with zero references](#35eb778e)
* UniProtTests: all 5 tests OK!
* WikidataTests: all 14 tests OK!


## Summary

* Number of test classes: 21
* Number of tests: 102
* Number of assertions: 205
* Number of fails: 2

## Fails

<a name="ad154c1e" />

## HMDBMetabolitesTests.correctFormat

I expected more than zero HMDB identifiers.
<a name="35eb778e" />

## ReferencesTests.atLeastOneReference

Found 1 pathways with zero references
```
http://www.wikipathways.org/instance/WP7.gp_r117342 'Sulfur amino acid biosynthesis' in Saccharomyces cerevisiae has zero references; 
```

