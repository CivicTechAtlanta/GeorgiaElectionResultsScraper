# Georgia Election Results Scraper

This java program scrapes the [Georgia Election Results site](http://results.enr.clarityelections.com/GA/63991/184321/en/select-county.html) for files.

The program outputs downloaded files to the local downloads folder (not to be confused with ~/Downloads).

Lots of debugging statements have been commented out. 
Feel free to uncomment them in your clone if you want to troubleshoot something or just know what it's doing.

## Compile
Mac
* `javac -cp bin:bin/jsoup-1.11.1.jar -d bin GeorgiaElectionResultsScraper.java`
Windows [unverified]
* `javac -cp bin;bin\jsoup-1.11.1.jar; -d bin GeorgiaElectionResultsScraper.java`

## Run
Mac
* `java -cp bin:bin/jsoup-1.11.1.jar GeorgiaElectionResultsScraper`
Windows [unverified]
* `java -cp bin;bin\jsoup-1.11.1.jar; GeorgiaElectionResultsScraper`