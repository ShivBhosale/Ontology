# Ontology Based Search Engine

This search engine uses a science (physics) ontology to expand the search query which is forwarded to a python script that uses text-mining to extract relevant information about the query from wikipedia and displays the summarized content. This approach is taken to ensure domain specific search results. For instance, searching for the query "Energy" should give me results in physics domain and not show results about "Energy drinks", which in fact is a more popular search result.

## Getting Started

Install git (http://git-scm.com/) onto your system. Then run a clone:

```
https://github.com/ShivBhosale/Ontology.git
```

This will download the Ontology Search Engine Source Code.

### Prerequisites

What things you need to use the search engine and how to install them

1) Xampp

```
https://www.apachefriends.org/download.html
```
2) Python 3

```
https://www.python.org/downloads/

```
### Installing

-Move the Ontology source code /htdocs/ in Xampp folder and start the xampp control panel and start MySQL server and we are ready to run some tests


## Running the tests

Go to:

```
localhost/Ontology
```
and you shall see the home page.

Enter a query related to Physics (Eg: einstein, buoyancy etc) to see the results.


## Built With

* PHP - The web framework used
* SPARQL

## Authors

* **Shivjeet Bhosale** - (https://github.com/ShivBhosale)

## Acknowledgments

* My team members who were as "jugaadu" as me
* Wikipedia
* PurpleBooth for this Readme.md template
