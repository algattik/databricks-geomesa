# databricks-geomesa
Geospatial analytics with GeoMesa on Databricks

Includes a Maven project to build a GeoMesa uber-jar compatible with Databricks (tested with Runtime 5.5), and a sample notebook.

For more information, see the blog post at https://cloudarchitected.com/2019/07/geospatial-analytics-in-databricks-with-geomesa/.

![airport density](images/airport-density.png)

To use the library, build the project with Maven (run `mvn package` in the geomesa-spark-runtime directory) and attach the library (in the target folder) to a Databricks cluster.