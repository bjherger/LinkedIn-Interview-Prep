# Study list

A list of things I should brush up on

## Recruiter recommendation
 - Data structures & algorithms
   - Binary search
## From `Data Specific Questions for Prep.pdf`
 - Preference: Customer facing, middleware, infrastructure?
 - Ranking methods (?): Is this score and then rank?
   - Reding [this paper](http://sci2s.ugr.es/keel/pdf/specific/congreso/brazdil00comparison.pdf)
 - Regularization / overfitting
   - Reading good ol' [ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Sixth%20Printing.pdf)
   - L1 (ridge): absolute sum |b_i| 
   - L2 (lasso):  sum (b_i)^2)
 
## From `SWE- Data Mining_ Machine Learning JD.pdf`
 - Information retrieval: Lucene / SOLR
   - What do these companies do? Why are they preferable?
   - Apache project. Lucene core: indexing and search, solr: search server
 - Preference for folks w/ a CS degree
   - Too late for that. Hopefully a minor will work (?)
 - Emphasis on Test Driven Development
 - Experience with Pig
   - SQL ish syntax for dealing with data (e.g. `A = LOAD 'student' USING PigStorage() AS (name:chararray, age:int, gpa:float);
B = FOREACH A GENERATE name;`)
 - Links to check out
   - [LI engineering blog](https://engineering.linkedin.com/)
   - [Getting that job at LI](https://www.linkedin
   .com/pulse/20140205163949-28614372-getting-that-job-at-linkedin): I kind of high level pointer to learning 
   resources 
   
## From [Getting that job at LinkedIn](https://www.linkedin.com/pulse/20140205163949-28614372-getting-that-job-at-linkedin)
 - Binary trees / B-Trees
 - Graphs
  - Min path algorithms
  
## Other follow up
 - [Kafka](https://kafka.apache.org/)
 - [DataFu](https://datafu.incubator.apache.org/)
   - Extension of Pig analytics syntax, with distributed deployment engine
 - [Samza](https://samza.apache.org/)
   - Stream processing framework, built on Kafka, Yarn
 - [Simoorg](https://github.com/linkedin/simoorg)
   - kafka chaos monkey? 
   

