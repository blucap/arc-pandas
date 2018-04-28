### Pandas and Hierarchical Indexing ###

#### Context ####

Pandas' ability to index data offers additional power to the way you work with data. More interesting is pandas' hierarchical indexing feature, it allows you to slice and dice data in convenient ways.

Python and pandas allow you to manage data way more efficiently and effectively than, say, Stata. One important problem with Stata is that you have all your data in one large file. As a result your work-file tends to grow, and thus gets messy.

#### Efficient data management ####

Python and pandas store data in various ways, e.g. in lists, tuples, sets, dictionaries, DataFrames and Series. This is super efficient: each data item can be stored in its most efficient form.

On top of that, for pandas there is indexing and hierarchical indexing. These features offers you the ability to focus on specific data sets within a single DataFrame. For example, your DataFrame may contain firm identification information, such as names and permcos, adjacent to numerical data. If you want to analyze the numbers, items such as names and permcos stand in the way. Hierarchical Indexing offers you a solution: you can set an index in such a way that your analysis only examines the numbers and ignore names and other non-numerical data.

Indexing also allows you to quickly produce tables, (which then can be used as new DataFrames, etc).

An additional feature of indexing is that you can use it to merge files quickly.
