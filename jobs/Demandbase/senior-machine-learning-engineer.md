
Performance improvements, Infrastructure, Monitoring, Security/Vulnerabilities, Standardization, Other accomplishments

## Performance improvements

* Implemented new cosine similarity algorithm which allowed to process 10 times more data in same amount of time
* Conducted research on data distribution which allowed to process 10 times more data with minor time increase
* Implemented fuzzy search algorithm to process hundreds of keywords per second
* Converted python project to Scala/Spark:
    * Increased speed of endpoint 20x
    * Increased training sample size from 250k to 20 millions rows
* Imagined clever way to optimize model experimentation by decoupling pipeline into several cached components:
    * Saved 20min per code change
    * Increased testing loop and overall speed of delivery of project
* Took over project after coworker left company: improved time, memory performances, deployment processes and finished productization

## Infrastructure 

* Contributed to move Spark project from Qubole to AWS EMR. Involved creation of library and framework to automate creation of cluster using EMR and Spotinst endpoint with automated pipeline
* Built framework combining Spark and Akka to turn Spark pipeline into rest API
* Implemented Docker image to enable engineers to interact with local Scala/Spark cluster using Jupyter Notebooks for fast prototyping

## Monitoring

* Implemented async library to automatically collect Spark metrics (number of executors, number of running tasks, memory usage, etc...) using InfluxDB
* Improved library to track any data though InfluxDB in functional way
* Improved library to automatically track each run arguments through integration with Scallop (command line argument library in Scala)
* Created Grafana dashboards using standardize metrics collected by library. With standard metrics, became trivial to create dashboards
* Leveraged metric tracking capabilities of library to build framework to perform "hyper-parameter grid search" for best Spark/Hadoop/Yarn configurations (number of executors, number of core, parallelism, quantity of memory, size of ebs volume, etc...)

## Security/Vulnerabilities

* Handled fixing security vulnerabilities for several projects (rewrite sbt build files)
* Wrote SBT plugin to automate those modifications and enforce safety measure designed by security team
* Open-sourced SBT Plugin: https://github.com/leobenkel/Soteria
* Helped established safety standards at company and provided feedback on security training

## Standardization

* Started Scala/Spark/Akka committee to propagate good practices and share knowledge
* Established standards for code styling and built tools to enforce them
* Wrote ScalaStyle, ScalaFMT, ScalaFix guidelines
* Wrote Dockerfile to handle common dependencies and speed up CI/CD time: build and test time improved 3x
* Wrote framework to automatically pushed PRs to all repos when standard configuration files are being changed to ensure company-wise compliance

## Other accomplishments

* Conducted several projects from Research phase to delivery including design, api endpoint, data pipeline, production delivery
* Used numerous cloud technologies including but not limited to AWS, Athena, EMR, Cloudwatch, GCP, Composer, BigQuery, BQML, etc...
* Completed several quick POCs to decide how to implement systems which saved countless engineering time by avoiding bad technical decisions
* Completed several python prototypes and converted them into Scala/Spark pipelines to improve performances
