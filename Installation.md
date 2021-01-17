## Anaconda
  > A free and open-source distribution of Python and R. <br>
  > It comes with the Python interpreter and various packages related to machine learning and data science. <br>
  > Default Python distribution usually requires to install packages separately. <br>

- **Installation**: https://www.anaconda.com/products/individual <br>

- **Documentation**: https://docs.anaconda.com/

- **Module management**:

    - Install package: 
    ```
    conda install <package_name>
    pip install <package_name> 
    ```
    - Update package:
    ```
    conda update <package_name> 
    pip install --upgrade <package_name>
    ```
    - List packages:
    ```
    conda list
    pip list 
    ```
    - Remove packages:
    ```
    conda remove <package_name> 
    pip uninstall <package_name>
    ```
    
## Modules
### Jupyter notebook
> Standard workspace for many Python data scientists <br>
> Web application that allows you to interactively developing and presenting data science projects <br>
> Create and share documents that contain live code, equations, visualizations, and text<br>
> Each cell can be either code or markdown <br>
   >> Implement code <br>
   >> Markdown comments with formatted text <br>
   >> Visualiza results <br>
   
> Share and save in various formats: .ipynb, .py, .html <br>
> Easy reproduction <br>

- **Documentation**: https://jupyter.org/
- **Markdown**: https://www.markdownguide.org/basic-syntax/
- Jupyter notebook **extensions**: https://github.com/ipython-contrib/jupyter_contrib_nbextensions adds useful features such as:
  >> Table of contents <br>
  >> Numbered sections <br>
  >> Foldable code <br>
 
 
### numpy
> a core package for basic array operations (e.g., indexing, sorting, reshaping).
- Documentation: https://numpy.org/doc/

- Features:
    >> n-dimension arrays <br>
    >> broadcasting operations on array <br>
    >> linear algebra tools <br>
    >> random number capabilities <br>
    
![](/Lectures/Lec_01/numpy_exm.png)
   
### pandas
> python data analysis library for tabular data structure <br>

- **Documentation**: https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html
- Features
    >> JSON, CSV, Excel, SQL data loading/saving <br>
    >> Dataframe structures (named columns) <br>
    >> Missing values management <br>
    >> Groupby and statistics <br>
    >> Plotting <br>
    >> Join and merge dataframes <br>
    
![](/Lectures/Lec_01/pandas_exm.png)
   
### Matplotlib

> Visualization module for Python. <br>
> It provides low-level plotting functions and is therefore very flexible. <br>
> It requires some time to get familiar with it but it is a very powerful and vital tool.<br>

- **Documentation**: https://matplotlib.org/
- Features:
  >> Subplots <br>
  >> Colormaps <br>
  >> Axes customization <br>
  
![](/Lectures/Lec_01/matplotlib_exm.png)

### NLTK
> Natural Language Toolkit
> a platform for building python programs to work with human language data. <br>
- **Documentation**: https://www.nltk.org/
- Features:
    - Corpora and lexical resources <br>
    - Text processing libraries: classification, tokenization, stemming, tagging, parsing, and semantic reasoning <br>
 
![](/Lectures/Lec_01/nltk_exm.png)
   
### Other modules

- Progress bar:
  - tqdm: https://github.com/noamraph/tqdm
- Plotting:
  - Seaborn: https://seaborn.pydata.org/
  - Plotly: https://plot.ly/python/
  - Vega: https://github.com/vega/ipyvega/
- Data collection:
  - TwitterAPI: https://github.com/geduldig/TwitterAPI
  - Scrapy: https://scrapy.org/
- Natural Language Processing:
  - Spacy: https://spacy.io/
- Machine Learning:
    - scikit-learn: http://scikit-learn.org/stable/documentation.html
  
### Even more resources

- Curated list of Python modules: https://github.com/vinta/awesome-python
- Curated list of Machine Learning tools: https://github.com/josephmisiti/awesome-machine-learning#python
- List of data science Jupyter notebooks: https://github.com/donnemartin/data-science-ipython-notebooks
- List of public APIs: https://github.com/toddmotto/public-apis
