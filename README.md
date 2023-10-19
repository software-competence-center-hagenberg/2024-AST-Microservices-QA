# An Overview of Microservice-Based Systems Used for Evaluation in Testing and Monitoring: A Systematic Mapping Study

Online Appendix for AST 2024 Paper

## Abstract

Microservice-based systems have emerged as an effective architecture for countless industry applications. They provide applications
as small, independent, and modular services. With the increasing interest in such systems it is important to tackle challenges related
to their quality assurance. However, to advance research in this area, systems are required to evaluate new approaches and tools.
In this paper, we perform a systematic literature search for systems used in research for testing and monitoring microservice-based 
systems to aid future research. We provide an overview of the found studies and the systems used in their evaluation. We compose a
list of publicly available systems and their characteristics, like size, available tests, and technologies used. Finally, we investigated the context in which these systems were used to provide insights in their usage and additional data that is available for them.



## Testing search querries

### Scopus 

SUBJAREA(COMP) TITLE-ABS-KEY(
(
("software test") OR
("software testing") OR
("test automation") OR
("test oracle") OR
("test generation") OR
("system test") OR
("system tests") OR
("system testing")
)
AND
(
(microservice*) OR
("micro service") OR
("micro-service")
)
)

### IEEE 

(("All Metadata": "software test") OR
("All Metadata": "software testing") OR
("All Metadata": "test automation") OR
("All Metadata": "test oracle") OR
("All Metadata": "test generation") OR
("All Metadata": "system test") OR
("All Metadata": "system tests") OR
("All Metadata": "system testing"))
AND
(("All Metadata": microservice*) OR
("All Metadata": "micro service") OR
("All Metadata": "micro-service") OR
("All Metadata": "micro-services"))


### ACM 

((
Title:("software test") OR
Title:("software testing") OR
Title:("test automation") OR
Title:("test oracle") OR
Title:("test generation") OR
Title:("system test") OR
Title:("system tests") OR
Title:("system testing"))
AND
(Title:(microservice*) OR
Title:("micro service") OR
Title:("micro services") OR
Title:("micro-service") OR
Title:("micro-services")))
OR
((
Abstract:("software test") OR
Abstract:("software testing") OR
Abstract:("test automation") OR
Abstract:("test oracle") OR
Abstract:("test generation") OR
Abstract:("system test") OR
Abstract:("system tests") OR
Abstract:("system testing"))
AND
(
Abstract:(microservice*) OR
Abstract:("micro service") OR
Abstract:("micro services") OR
Abstract:("micro-service") OR
Abstract:("micro-services")))
OR
((
Keyword:("software test") OR
Keyword:("software testing") OR
Keyword:("test automation") OR
Keyword:("test oracle") OR
Keyword:("test generation") OR
Keyword:("system test") OR
Keyword:("system tests") OR
Keyword:("system testing"))
AND
(
Keyword:(microservice*) OR
Keyword:("micro service") OR
Keyword:("micro services") OR
Keyword:("micro-service") OR
Keyword:("micro-services")))


### Springer 
(
("software test") OR
("software testing") OR
("test automation") OR
("test oracle") OR
("test generation") OR
("system test") OR
("system tests") OR
("system testing")
)
AND
(
(microservice*) OR
("micro service") OR
("micro services") OR
("micro-service") OR
("micro-services")
) 




## Monitoring search querries

### Scopus 

SUBJAREA(COMP) TITLE-ABS-KEY 
(( (benchmark OR "fault localization" OR "root cause analysis") AND
(tracing OR 
anomal* OR
"dynamic analysis" OR 
"telemetry data" OR 
"fault injection" OR 
"case study")
) 
AND 
(
(microservice*) OR 
("micro service") OR 
("micro services") OR 
("micro-services") OR 
("micro-service"))) 


### IEEE 

(
(("All Metadata": benchmark) OR
("All Metadata": "fault localization") OR
("All Metadata": "root cause analysis")) AND
(("All Metadata": tracing) OR
("All Metadata": anomal*) OR
("All Metadata": "dynamic analysis") OR
("All Metadata": "telemetry data") OR
("All Metadata": "case study") OR
("All Metadata": "fault injection") )
)
AND
(("All Metadata": microservice*) OR
("All Metadata": "micro service") OR
("All Metadata": "micro services") OR
("All Metadata": "micro-service") OR
("All Metadata": "micro-services"))


### ACM 

((
(Title: (benchmark) OR 
Title: ("fault localization") OR 
Title: ("root cause analysis")) AND (
Title: (tracing) OR
Title: (anomal*) OR
Title: ("dynamic analysis") OR
Title: ("telemetry data") OR
Title: ("case study") OR
Title: ("fault injection") )
)
AND
(Title: (microservice*) OR
Title: ("micro service") OR
Title: ("micro services") OR
Title: ("micro-service") OR
Title: ("micro-services")))
OR
((
(Abstract: (benchmark) OR 
Abstract: ("fault localization")
Abstract: ("root cause analysis")) AND (
Abstract: (tracing) OR
Abstract: (anomal*) OR
Abstract: ("dynamic analysis") OR
Abstract: ("telemetry data") OR
Abstract: ("case study") OR
Abstract: ("fault injection") )
)
AND
(
Abstract: (microservice*) OR
Abstract: ("micro service") OR
Abstract: ("micro services") OR
Abstract: ("micro-service") OR
Abstract: ("micro-services")))
OR
((
(Keyword: (benchmark) OR 
Keyword: ("fault localization")
Keyword: ("root cause analysis")) AND (Keyword: (tracing) OR
Keyword: (anomal*) OR
Keyword: ("dynamic analysis") OR
Keyword: ("telemetry data") OR
Keyword: ("case study") OR
Keyword: ("fault injection") )
)
AND
(
Keyword: (microservice*) OR
Keyword: ("micro service") OR
Keyword: ("micro services") OR
Keyword: ("micro-service") OR
Keyword: ("micro-services")))


### Springer 

( (benchmark OR "fault localization" OR "root cause analysis") AND
(tracing OR
anomal* OR
"dynamic analysis" OR
"telemetry data" OR
"case study" OR
"fault injection")
) 
AND 
(
(microservice*) OR 
("micro service") OR 
("micro services") OR 
("micro-services") OR 
("micro-service"))



## Results Testing search

### Apply Search (Step 1)

| Source   | #Studies | File                                             |
|----------|----------|--------------------------------------------------|
| ACM      | 15       | [testing/1_ACM.csv](testing/1_ACM.csv)           |
| IEEE     | 29       | [testing/1_IEEE.csv](testing/1_IEEE.csv)         |
| SCOPUS   | 129      | [testing/1_SCOPUS.csv](testing/1_SCOPUS.csv)     |
| SPRINGER | 176      | [testing/1_SPRINGER.csv](testing/1_SPRINGER.csv) |
| **SUM**  | **349**  | -                                                |


### Deduplicate & Filter Results (Step 2)

| Step          | #Studies | File                                                                     |
|---------------|----------|--------------------------------------------------------------------------|
| Deduplication | 308      | [testing/2.1_mergedDeduplicated.csv](testing/2.1_mergedDeduplicated.csv) |
| Filter        | 53       | [testing/2.2_filteredSearch.csv](testing/2.2_filteredSearch.csv)         |


### Backward & Forward Snowballing (Step 3)

Added 2992 studies.

### Deduplicate & Filter Results (Step 4)

| Step          | #Studies | File                                                                               |
|---------------|----------|------------------------------------------------------------------------------------|
| Deduplication | 2163     | [testing/4.1_snowballingDeduplicated.csv](testing/4.1_snowballingDeduplicated.csv) |
| Filter        | 101      | [testing/4.1_snowballingDeduplicated.csv](testing/4.2_finalList.csv)               |

### Extract Systems (Step 5)

| Step      | #Systems | File                                           |
|-----------|----------|------------------------------------------------|
| Extract   | 112      | [testing/5_systems.csv](testing/5_systems.csv) |



## Results Monitoring search

### Apply Search (Step 1)

| Source   | #Studies | File                                                   |
|----------|----------|--------------------------------------------------------|
| ACM      | 48       | [monitoring/1_ACM.csv](monitoring/1_ACM.csv)           |
| IEEE     | 51       | [monitoring/1_IEEE.csv](monitoring/1_IEEE.csv)         |
| SCOPUS   | 87       | [monitoring/1_SCOPUS.csv](monitoring/1_SCOPUS.csv)     |
| SPRINGER | 321      | [monitoring/1_SPRINGER.csv](monitoring/1_SPRINGER.csv) |
| **SUM**  | **507**  | -                                                      |


### Deduplicate & Filter Results (Step 2)

| Step          | #Studies | File                                                                           |
|---------------|----------|--------------------------------------------------------------------------------|
| Deduplication | 427      | [monitoring/2.1_mergedDeduplicated.csv](monitoring/2.1_mergedDeduplicated.csv) |
| Filter        | 41       | [monitoring/2.2_filteredSearch.csv](monitoring/2.2_filteredSearch.csv)         |


### Backward & Forward Snowballing (Step 3)

Added 2373 studies.

### Deduplicate & Filter Results (Step 4)

| Step          | #Studies | File                                                                                     |
|---------------|----------|------------------------------------------------------------------------------------------|
| Deduplication | 1913     | [monitoring/4.1_snowballingDeduplicated.csv](monitoring/4.1_snowballingDeduplicated.csv) |
| Filter        | 70       | [monitoring/4.2_finalList.csv](monitoring/4.2_finalList.csv)                             |

### Extract Systems (Step 5)

| Step      | #Systems | File                                                 |
|-----------|----------|------------------------------------------------------|
| Extract   | 28       | [monitoring/5_systems.csv](monitoring/5_systems.csv) |

 
## Merge & Filter Systems (Step 6)

| Step                | #Systems | File                                                         |
|---------------------|----------|--------------------------------------------------------------|
| Merge               | 134      | [6.1_systems.csv](6.1_systems.csv)                           |
| Filter availability | 32       | [6.2_available_systems.csv](6.2_available_systems.csv)       |
| Filter open-source  | 29       | [6.3_open_source_systems.csv](6.3_open_source_systems.csv)   |
| Filter microservice | 19       | [6.4_microservice_systems.csv](6.4_microservice_systems.csv) |

