
# Senior Data Engineer

Infrastructure, Teaching, Projects, Company culture

## Infrastructure

* Automated pipeline caching to speed up model training
* Created research group to improve code reviews and pull request processes

## Teaching

* Introduced ZIO and functional programming for Spark pipelines to increase reliability and testability
* Taught Scala and Spark internally 2 hours once per week
* Managed Demandbase http://exercism.io/ private team

## Projects

* Converted scala/spark job to BQML 
    * Saved about half million dollars per year 
    * Reduced time to completion from 40min to 6min
    * Reduced failure rate from 5% to less than 1%
* Built BQML management library:
    * Takes folder containing BigQuery queries as input
    * Parses queries to organize them in graph of dependencies
    * Analyzes content of cache
    * Serializes graph to optimize parallelization and smallest amount of queries needed to produce results
    * Allowed to productize several reliable pipeline leveraging BQML. 
    * Featured at Google Cloud Next '20: https://cloud.withgoogle.com/next/sf/speakers?speaker=161CC62959A64018
* Built Dynamic Audience project: 
    * https://www.demandbase.com/b2b-marketing-blog/automated-advertising-a-scalable-way-to-reach-high-intent-buyers/
    * https://www.demandbase.com/press-release/demandbase-optimizes-marketing-spend-with-automated-advertising/
* Improved influxDB library to allow use of Prometheus using same functional interface
* Built python pipeline to convert 55 millions user entries into consolidated and standardized vocabulary
* Built library to read vault secrets:
    * Functional
    * Cross built for several scala versions
    * No dependencies other than AWS
    * Support Akka and Spark projects 
    * Intuitive functional interface
* Open source libraries: 
    * https://github.com/leobenkel/ZparkIO
    * https://github.com/leobenkel/Soteria
    * https://github.com/leobenkel/Laeta 
* Researched, designed and drafted proposal on model standardization focused on :
    * Reducing POC to production timeline
    * Improving data infrastructure
    * MLOps 
    * Data pipeline involving :
        * Data source of truth: Delta Lake, Snowflake
        * Feature store: FEAST, Tecton
        * Model store: MLFlow
        * Model serving: Seldon

## Company culture

* Organized first grand scale internal hackathon: 
    * 10 teams
    * 70 people participants
    * 3 days
    * Entirely virtual during Covid19 pandemic
    * Pluri-disciplinary: entire company was included, not only engineering
    * incredible feedback across entire company
* Organized first virtual happy hour at start of covid19 pandemic
* Launch Folding@Home movement to help research on cure for corona virus: https://folding.extremeoverclocking.com/team_summary.php?s=&t=244897
* Promoted image of company, company culture and engineering excellency at several conferences: Scala in the city, SF-Scala, Scala Love
* Helped improve communication between Data engineering and Data Science teams
* Organized virtual meet and greet to Engagio new employees post-acquisition
* Accompanied 4 new hires through "Demandbase buddy" system, contributed to improve company culture and fostered welcoming environment

