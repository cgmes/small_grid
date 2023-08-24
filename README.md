# Small Grid

The Small Grid Test Configuration for the ENTSO-E Common Grid Model Exchange Standard (CGMES) Conformity Assessment.

Small Grid test configurations models are planned to be used for testing of both interoperability of HVDC
and interoperability of equivalent elements. Also they are used to test the support to a load flow analyses.
Short-circuit calculations and dynamics simulations cannot be performed using this test configuration.

## Trig

The "trig" branch of this repository contains the Small Grid Test Configuration in [TriG](https://www.w3.org/TR/trig/) format.
CIM/XML is a domain specific syntax used in the energy sector.
It is based on RDF/XML, but is not compatible.
As a result, it can not be used directly with generic RDF tools and libraries.
TriG is an extension to [TURTLE](https://www.w3.org/TR/turtle/) for representing complete RDF datasets.
TURTLE and TriG are well established syntaxes for RDF and are supported by many tools and libraries.
TriG allows metadata to be associated with named graphs.
This allows separate parts of a CGMES model to be stored in a single text file and avoids the need to use an opaque ZIP archive.

## SPARQL Update

CIM/XML `DifferenceModel` files are also a custom format that lacks widespread support.
[SPARQL 1.1 Update](https://www.w3.org/TR/sparql11-update/) is a standard language for specifying updates to RDF graphs.
The difference models from the Small Grid Test Configuration have been converted to SPARQL Update (.rq) format.

## Note

This is an unofficial source for the Small Grid Test Configuration.
Please refer to [ENTSO-E](https://www.entsoe.eu) for official resources.