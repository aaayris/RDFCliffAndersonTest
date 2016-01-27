# RDFCliffAndersonTest
This repository is for testing RDF using information about Cliff Anderson.
<rdf:RDF>
  @prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
  @prefix foaf: <http://xmlns.com/foaf/0.1/> .
  @prefix dc11: <http://purl.org/dc/elements/1.1/> .
  @prefix skos: <http://www.w3.org/2004/02/skos/core#> .
  @prefix schema: <http://schema.org/Person> .
  @prefix geo: <http://www.w3.org/2003/01/geo/wgs84_pos#> .

  <http://orcid.org/0000-0003-0328-0792>
    a rdf:Person ;
    foaf:name "Cliff Anderson" ;
    dc11:alternative "Clifford Blake Anderson" ;
    schema:PersonadditionalName "Clifford Blake Anderson" ;
    foaf:title "Dr." ;

    schema:PersonalumniOf <https://www.pratt.edu/the-institute/> , <http://www.ptsem.edu/>, <http://hds.harvard.edu/>, <http://www.kenyon.edu/> ;
    dc11:PersoneducationalLevel: <https://en.wikipedia.org/wiki/Master_of_Library_and_Information_Science> ;
    dc11:date "2011-2012" , "1996-2005", "1992-1995", "1988-1992" ;
    dc11:educationalLevel <https://en.wikipedia.org/wiki/Doctor_of_Philosophy> , <https://en.wikipedia.org/wiki/Master_of_Theology> , <https://en.wikipedia.org/wiki/Master_of_Divinity>, <https://en.wikipedia.org/wiki/Bachelor_of_Arts> ;
    schema:Personemployee <http://vanderbilt.edu/> ;
    geo:location [ 
      geo:lat 36.144724 ;
      geo:long -86.802715
    ] ;
    schema:PersonjobTitle "Director of Scholarly Communications" ;
    schema:Personcolleague <http://orcid.org/0000-0002-2174-0484> ;
    foaf:Personknows <http://orcid.org/0000-0003-4365-3135> ;

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
