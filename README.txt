The program is on the databricks using pyspark. And the link of the notebook has been published  in the coverPage.
To run it, you can copy or import it to your notebook on databricks.
Before running the program, make sure that the GraphFrame Spark package matching your cluster configuration has been installed on your cluster.
The input file is on GitHub and the output is published on S3 bucket. 
You can change the input path and the output path, but make sure that the paths can match the read and write queries in the program.
You can view the results shown in the program or check the output files.
Calcualting connectedComponents takes a really long time (over 15 minutes)
pagerank and triangleCount takes a few minutes (no more than 5 minutes)
indegrees and outdegrees just take a few seconds.