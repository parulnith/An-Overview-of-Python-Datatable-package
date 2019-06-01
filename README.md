# An Overview of Python's Datatable package
Python library for efficient multi-threaded data processing, with the support for out-of-memory datasets.

If you are an R user, chances are that you have already been using the data.table package. Data.table is an extension of the data.frame package in R. It's also the go-to package for R users when it comes to the fast aggregation of large data (including 100GB in RAM).
The R's data.table package is a very versatile and a high-performance package due to its ease of use, convenience and programming speed. It is a fairly famous package in the R community with over 400k downloads per month and almost 650 CRAN and Bioconductor packages using it(source).
So, what is in it for the Python users? Well, the good news is that there also exists a Python counterpart to thedata.table package called datatable which has a clear focus on big data support, high performance, both in-memory and out-of-memory datasets, and multi-threaded algorithms. In a way, it can be called as data.table's younger sibling.


## Installation

On MacOS systems installing datatable is as easy as
```sh
pip install datatable
```

On Linux you can install a binary distribution as
```sh
# If you have Python 3.5
pip install https://s3.amazonaws.com/h2o-release/datatable/stable/datatable-0.8.0/datatable-0.8.0-cp35-cp35m-linux_x86_64.whl

# If you have Python 3.6
pip install https://s3.amazonaws.com/h2o-release/datatable/stable/datatable-0.8.0/datatable-0.8.0-cp36-cp36m-linux_x86_64.whl
```

On all other platforms a source distribution will be needed. For more
information see [Build instructions](https://datatable.readthedocs.io/en/latest/install.html).




## References
* [Documentation](https://datatable.readthedocs.io/en/latest/?badge=latest)
