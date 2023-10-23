# Triangle Counting in PySpark

This README provides detailed instructions for compiling and run the PySpark code for triangle counting on a graph.

## Prerequisites

Before running the code, ensure that you have the following prerequisites installed:

- Python (3.x recommended)
- Apache Spark (Install using `pip install pyspark`)
- Jupyter Notebook (Optional but recommended for interactive exploration)

## Running the Code

1. **Open a Terminal or Command Prompt**: Begin by opening a terminal or command prompt on your local machine.

2. **Start the PySpark Shell**: To start the PySpark shell, enter the following command:

   pyspark

3.Copy and Paste the Code: Find the Python code for triangle counting in the provided ipynb.
4.Execute the Code: Paste the code into the PySpark shell or a Jupyter Notebook. Execute the code to perform triangle counting on the provided sample data. The results will be shown in the console.
5.Using Custom Input Data: If you wish to run the code with your custom input data, replace the sample_data and few-edges in the code with your dataset. Ensure that your data is loaded into an RDD.

##  Understanding the Code

*Initialization: The code initializes a PySpark environment for distributed computing.
*Data Preparation: It creates an RDD from the sample data and prepares it for triangle counting.
*Triangle Counting: The code performs triangle counting on the graph data.
*Results Display: The results, including the total number of triangles and the average nodes involved in triangles for each node, are printed to the console.

## Termination
After running the code, it's important to terminate the PySpark application. This is by executing this command in the PySpark shell:

sc.stop()

