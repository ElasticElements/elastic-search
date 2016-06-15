# elastic-search

Element which provides a web component interface to the elasticsearch client search API, and coordinates building and issuing queries using the elastic.js library.  Satellite elements for query, filters, aggregation, sorting, and paging communicate with this element to make changes to the index object, and to receive results from queries that are issued to an elastic server instance.


## Credit to <a href="https://github.com/YousefED/ElasticUI" target="_blank">ElasticUI</a>
This suite of web components is inspired by the angular project ElasticUI:  Many of the ng directives used in that project are mimicked with these web components.


## Dependencies

* Elasticsearch server instance
* mockads index (run data/import_test_data.sh after installing and starting elastic search).  This is used for the test suite.
* Web Component Tester
* Polyserve (optional)



