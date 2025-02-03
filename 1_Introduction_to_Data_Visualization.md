# Module 1: Introduction to Data Visualization


### Learning Objectives
1. Define visualization.
2. Describe key purposes of visualization.
3. Identify the data types of elements within a dataset's data.
4. Demonstrate the process of loading datasets for analysis into Python.
5. Explain data warehouses and exploratory querying.
6. Define the properties of Bertin's visual variables.
7. Identify appropriate color schemes for different data types.
8. Explain how combinations of visual variables impact the usefulness of a graphic.


## Multivariate Analysis
1. To analyze data from more than one variable
2. Curse of dimensionality# Module 1: Introduction to Data Visualization


### Learning Objectives
1. Define visualization.
2. Describe key purposes of visualization.
3. Identify the data types of elements within a dataset's data.
4. Demonstrate the process of loading datasets for analysis into Python.
5. Explain data warehouses and exploratory querying.
6. Define the properties of Bertin's visual variables.
7. Identify appropriate color schemes for different data types.
8. Explain how combinations of visual variables impact the usefulness of a graphic.


## Introduction to Data Visualization
1. The goal is to create insight, not just making a picture.
2. Visualization benefit
    1. amplifies擴大 cognition
    2. expands working memory
    3. improves pattern detection and recognition
    4. controls attention
3. Tools
    1. The user knows what they want
        1. data processing: they just need to process the data using known methods.
        2. querying: user can describe what they want
        3. navigation: user can not describe what they want
    2. The user doesn't precisely know what they want
        1. exploration: user can get an idea about the data
            1. analysis (patterns or outliers)
            2. comparison
            3. aggregation (groups and clusters)
            4. transformation
            5. visualization
4. Challenges
    1. 3Vs (big data)
        1. Volume
        2. Velocity 
        3. Variety (different form)
    2. HMLE
        1. High-dimensional (different aspect)
        2. Multi-modal
        3. Inter-linked (implicit)
        4. Evolving
    3. INS
        1. Imprecision
        2. Noise
        3. Sparsity稀疏
    4. Human


### Data Organization
1. database: collection of organized data
2. data model: a formalism (e.g., relational, object oriented...)
3. data schema: described with in the formalism corresponding to the underlying data model
4. levels of data organization
    1. structured
        1. a schema describes the structure
        2. a DBMS enforce this structure
        3. advantages
            1. query
            2. optimize
            3. explore
    2. semi-structured
        1. the constrants are more flexible
        2. advantages
            1. integrate
            2. exchange
    3. unstructured


### Vector Data
1. base vector
2. distance/similarity function

### Bertin's visual variables
1. Data types (scale of measure)
    1. nominal名目: no implied ordering
    2. ordinal順序: has a specified order, but no specified distance metric
    3. interval區間: has measurable distances
    4. ratio比例: interval with a zero point
2. visualization pipeline
    1. row data
    2. data analysis -> prepared data
    3. filtering -> focus data
    4. mapping -> geometric data
    5. rendering -> image data
3. Bertin's visual variables
    1. position
    2. size
    3. value
    4. color
    5. texture
    6. orientation
    7. shape



### Color Schemes and Design
1. qualitative color scheme
    1. e.g., rainbow
    2. not intuitive, only good for nominal data
2. sequential color schemes
    1. e.g., gray scale
    2. limited number of distinguishable colors can be represented
    3. watch out for illusions
3. divergent color schemes
    1. The center is a neutral color, with colors radiating outwards for positive and negative data.
    2. 中心為中性色，向兩端發散，適用於表示正負數據: the more dimensions in a visualization, the less effective standard computational and statistical techniques become.
3. Tools
    1. tables
        1. used to look individual value
        2. used to compare individual value
        3. precise value are required
    2. graphs
        1. the message is contained in the shape of the values
        2. used to reveal relationship among values

### Scatter Plots



### Data Organization
1. database: collection of organized data
2. data model: a formalism (e.g., relational, object oriented...)
3. data schema: described with in the formalism corresponding to the underlying data model
4. levels of data organization
    1. structured
        1. a schema describes the structure
        2. a DBMS enforce this structure
        3. advantages
            1. query
            2. optimize
            3. explore
    2. semi-structured
        1. the constrants are more flexible
        2. advantages
            1. integrate
            2. exchange
    3. unstructured


### Vector Data
1. base vector
2. distance/similarity function

### Bertin's visual variables
1. Data types (scale of measure)
    1. nominal名目: no implied ordering
    2. ordinal順序: has a specified order, but no specified distance metric
    3. interval區間: has measurable distances
    4. ratio比例: interval with a zero point
2. visualization pipeline
    1. row data
    2. data analysis -> prepared data
    3. filtering -> focus data
    4. mapping -> geometric data
    5. rendering -> image data
3. Bertin's visual variables
    1. position
    2. size
    3. value
    4. color
    5. texture
    6. orientation
    7. shape



### Color Schemes and Design
1. qualitative color scheme
    1. e.g., rainbow
    2. not intuitive, only good for nominal data
2. sequential color schemes
    1. e.g., gray scale
    2. limited number of distinguishable colors can be represented
    3. watch out for illusions
3. divergent color schemes
    1. The center is a neutral color, with colors radiating outwards for positive and negative data.
    2. 中心為中性色，向兩端發散，適用於表示正負數據