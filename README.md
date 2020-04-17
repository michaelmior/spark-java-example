# Apache Spark Java example

This is a simple example taken from the Apache Spark code base.
Once you have compiled the program to produce a JAR file, you can run the program as follows:

    /path/to/spark-submit --class edu.rit.cs.mmior.spark.JavaWordCount /path/to/spark-example-1.0-SNAPSHOT.jar <file_to_count>

You should replace the paths above with the path to your Spark installation directory, the compiled JAR file, and the file the word count should be run on.
