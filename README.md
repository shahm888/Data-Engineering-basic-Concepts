
# Basic Data Concept

1.**What is Data Mining?**

Data mining is the process of discovering interesting patterns and knowledge from large amounts of data. The data sources can include databases, data
warehouses, the Web, other information repositories, or data that are streamed into the system dynamically.

2.**What Kinds of Data Can Be Mined?**
 
As a general technology, data mining can be applied to any kind of data as long as thedata are meaningful for a target application.The most basic forms of data for mining applications are database data, data warehouse data,and transactional data.Data mining can also be applied to other forms of data (e.g.data streams, ordered/sequence data, graph or networked data, spatial data, text data,multimedia data, and the WWW

3.**What is Data Warehousing Systems?**

A data warehouseis a repository of information collected from multiple sources, stored under a unified schema, and usually residing at a single site. Data warehouses are constructed via a process of data cleaning, data integration, data transformation, data loading, and periodic data refreshing. 

To facilitate decision making, the data in a data warehouse are organized aroundmajor subjects (e.g., customer, item, supplier, and activity). The data are stored to provide information from a historical perspective, such as in the past 6 to 12 months, and are typically summarized. For example, rather than storing the details of each sales transaction, the data warehouse may store a summary of the transactions per item type for each store or, summarized to a higher level, for each sales region.A data warehouse is usually modeled by a multidimensional data structure, called a
data cube, in which each dimension corresponds to an attribute or a set of attributesin the schema, and each cell stores the value of some aggregate measure such as count or sum(sales amount). A data cube provides a multidimensional view of data and allows
the precomputation and fast access of summarized data.

4.**What kind of patterns can be mined?**

There are a number of data mining functionalities. These include characterization
and discrimination; the mining of frequent patterns, associations, and correlations; classification and regression; clustering analysis; and outlier analysis. Data mining functionalities are used to specify the kinds of patterns to be found in data mining tasks. In general, such
tasks can be classified into two categories: descriptive and predictive. 
Descriptive mining tasks characterize properties of the data in a target data set.
Predictive mining tasks perform induction on the current data in order to make predictions.

5.**What is data objects and Attributes type?**

Data sets are made up of data objects. A data object represents an entity—in a sales database, the objects may be customers, store items, and sales; in a medical database, the objects may be patients; in a university database, the objects may be students, professors, and courses. 
Data objects are typically described by attributes. Data objects can also be referred to as samples, examples, instances, data points, or objects. If the data objects arestored in a database,they are data tuples. That is, the rows of a database correspond to the data objects, and the columns correspond to the attributes. 

 6.**What is Attributes?**

An attribute is a data field, representing a characteristic or feature of a data object.

7. **Major Three elements define data Quality**
 
 accuracy, completeness, and consistency of Data.
 
8. What types of error define data are inaccurate, in consistent and incompletness?
 
 1.Users may purposely submit incorrect data values for mandatory fields when they do not wish to submit personal information (e.g., by choosing
 the default value “January 1” displayed for birthday). This is known as disguised missing data.
 2.There may be technology limitations such as limited buffer size for coordinating synchronized data transfer and consumption. Incorrect data may also result from inconsistencies in naming conventions or datacodes, or inconsistent formats for input fields (e.g., date)
 
 

