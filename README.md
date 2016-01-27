# RDFCliffAndersonTest
This repository is for testing RDF using information about Cliff Anderson.
<rdf:RDF>
  @prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
  @prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
  @prefix foaf: <http://xmlns.com/foaf/0.1/> .
  @prefix dc11: <http://purl.org/dc/elements/1.1/> .
  @prefix skos: <http://www.w3.org/2004/02/skos/core#> .
  @prefix schmea: <http://schema.org/Person> .
  @prefix geo: <http://www.w3.org/2003/01/geo/wgs84_pos#> .

  <http://orcid.org/0000-0003-0328-0792> a rdf:Person ;
    foaf:name "Cliff Anderson" ;
    dc:alternative "Clifford Blake Anderson" ;
    schema:additionalName "Clifford Blake Anderson" ;
    foaf:title "Dr." ;

# is using both dc:alternative and schema:additionalName a good idea?

    schema:alumniOf <https://www.pratt.edu/the-institute/> ;
      dc:educationalLevel: <https://en.wikipedia.org/wiki/Master_of_Library_and_Information_Science> ;
      dc:date "2011-2012" ;
    schema:alumniOf <http://www.ptsem.edu/> ;
      dc:educationalLevel <https://en.wikipedia.org/wiki/Doctor_of_Philosophy> ;
      dc:educationalLevel <https://en.wikipedia.org/wiki/Master_of_Theology> ;
      dc:date "1996-2005" ;
    schema:alumniOf <http://hds.harvard.edu/> ;
      dc:educationalLevel <https://en.wikipedia.org/wiki/Master_of_Divinity> ;
      dc:date "1992-1995" ;
    schema:alumniOf <http://www.kenyon.edu/> ;
      dc:educationalLevel <https://en.wikipedia.org/wiki/Bachelor_of_Arts> ;
      dc:date "1988-1992"

    schema:employee <http://vanderbilt.edu/> ;
      geo:location [ geo:lat 36.144724 ; geo:long -86.802715 ] ;

## is this a statement about the predicate i.e. the semicolon doesn't work?

    schema:jobTitle "Director of Scholarly Communications" ;
    schema:colleague <http://orcid.org/0000-0002-2174-0484> ;
    foaf:knows <http://orcid.org/0000-0003-4365-3135> ;

    foaf:page <http://www.library.vanderbilt.edu/scholarly/> ;
    foaf:page <https://www.hastac.org/u/clifford-anderson> ;
    foaf:account <https://www.linkedin.com/in/cliffordbanderson> ;
      foaf:accountName "cliffordbanderson" ;
    foaf:account <https://twitter.com/andersoncliffb> ;
      foaf:accountName: "@andersoncliffb" ;

    foaf:publications <http://dx.doi.org/10.11630/1550-4891.10.02.118>, <http://dx.doi.org/10.4242/balisagevol13.anderson01>, <http://dx.doi.org/10.11630/1550-4891.09.02.130>, <http://dx.doi.org/10.1163/ej.9789004203365.i-284.36>, <http://dx.doi.org/10.1017/s003693060700364x>, <http://dx.doi.org/10.1163/156973208x316234>, <http://dx.doi.org/10.1177/004057369905500421> ;

    foaf:topic_Interest "Digital Libraries", "XQuery", "Semantic Web", "Library Science", "Theology" ;

    foaf:thumbNail <http://www.library.vanderbilt.edu/scholarly/images/cba-small.jpg> ;
    foaf:thumbNail <http://news.vanderbilt.edu/files/Catherine-Lee-Michael-Stuart-Clifford-Anderson-585x390.jpg> ;



</RDF>
