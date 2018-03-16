# OWL API

Go to Tutorial.java and run that working example.

To get ours to work:

comment out the line "OWLOntology ontology = manager.loadOntologyFromOntologyDocument(IRI.create(BASE_URL));"

Replace it with something like "OWLOntology ontology = manager.loadOntologyFromOntologyDocument(new File(OUR_WORKING_OWL_FILENAME"));"

From there we can manipulate the ontology how we want it
