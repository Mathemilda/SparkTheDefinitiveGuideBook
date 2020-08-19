# "Spark: The Definitive Guide" Book Study
The book ("Spark: The definitive guide" by Bill Chambers, Matei Zaharia(O'Reilly), Copyright 2018 Databricks, Inc., 978-1-491-91221-8) is abberviated as STDG in this repository.

Here is my practice for the book. Authors provided PySpark and Scala notebooks in a following repository: 

[https://github.com/databricks/Spark-The-Definitive-Guide](https://github.com/databricks/Spark-The-Definitive-Guide)

A few of the notebooks missed lines which are provided in STDG, so I've added them. In several places in the book and in the repository we can see code for Python 2 while I use Python 3. I changed everything to Python 3. There were places where code does not work anymore, may be depreciated after updates. Although it looks like it was copied from corresponding Scala scripts and not adapted to PySpark. I tried to fix it as much as I can. In my noteboooks I added comments if I introduced code lines, and sometimes I added my notes about the code as well.

Datasets which were used in the book are mounted to the Databricks File System:
https://docs.databricks.com/getting-started/databricks-datasets.html
They could be accessed directly from a databrick notebook.

I found an interesting text: "Things I Wish I'd Known About Spark When I Started (One Year Later Edition)" and decided to keep a link to it here: https://www.enigma.com/blog/things-i-wish-id-known-about-spark
