# Sales Pipeline

# Objective :

Building a pipeline on sales data to create a pipeline that would **ingest**, **model** and make **query-ready** datasets

# Risks and Assumption
## Risk #1: 
  -- There is a  direction of not to use spark SQL (implying: utilize RDDs) for this exercise. However, since spark 1.6 
     and implementation of project Tungsten ( with catalyst optimizer/SIMD processing of binary rows instead of JVM bytes etc)
     ,the dataset/dataframe based approach is actually recommended by Apache Spark community/databricks. Since we are dealing with structured data hence to scale the system RDD based approach might not be optimal
     
