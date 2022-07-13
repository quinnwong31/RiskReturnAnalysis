# Risk-Return Analysis
## Description

The Risk-Return Analysis notebook provides examples of how one can use different statistical metrics, such as mean, standard deviation, variance, covariance and beta to analyze the performance and risk-return ration of different funds.   Python and its ecosystem provides several technologies, such as Jupyter, Python, pandas and numpy, to perform risk-return analysis on different investments.   In this example, we will be reviewing historical net asset value (NAV) data for four different funds and the S&P 500 Index.   The four funds that we are analyzing are: 

- Soros Fund Management LLC
- Paulson & Co.Inc
- Tiger Global Management LLC
- Berkeshire Hathaway INc

The notebook is divided into the following phases:

- Import - In this phase, the historical funds data is imported via csv file.
- Quantitive Analysis - This phase consists of four sub-phases: 
    - Performance - Analyze the data to determine if any of the portfolios outperform the broader stock market, which the S&P 500 represents
    - Volatility - Analyze the volatility of each of the four fund portfolios and of the S&P 500 Index by using box plots
    - Performance - Analyze the volatility of each of the four fund portfolios and of the S&P 500 Index by using box plots
    - Risk-Return - Evaluate the risk profile of each portfolio by using the standard deviation and the beta.
- Portfolio Diversification - In the last phase, we evaluate how the portfolios react relative to the broader market.




## Technologies
This example uses the following technologies:

- **pathlib** - This library is used to provides classes for filesystem paths. Please see [pathlib documentation](https://docs.python.org/3/library/pathlib.html) for more information.
- **csv** - This library is used to read and write csv files. Please see [csv documentation](https://docs.python.org/3/library/csv.html) for more information.
- **Jupyter** - Jupyter is a web-based interactive development environment for data science and analysis. Please see [Jupyter documentation](https://jupyter.org/) for more information.
- **pandas** - pandas is a software library written for the Python programming language for data manipulation and analysis. Please see [pandas documentation](https://pandas.pydata.org/) for more information.
- **numpy** - numpy is a library for the Python programming language that adds support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.




## Installation

The `pathlib` and `csv` libraries are already installed with Python 3.7.

In order to use this application, you will need to install `Jupyter` and `pandas`. Below are the instructions for installing each required library.

### Installing Jupyter

To install Jupyter, please refer to the [Jupyter Installation Guide](https://jupyter.org/install).

### Installing pandas

To install `pandas`, please refer to the [pandas Installation Guide](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html).

### Installing numpy
To install `numpy`, please refer to the [numpy Installation Guide](https://numpy.org/install/).





## Usage
### Launching the Notebook

To launch the Notebook, perform the following steps:

1. Open Terminal.

![Launch_Terminal](/images/launching_open_terminal.jpg)

2. Navigate to the location of the Notebook.
3. Enter `jupyter lab` at the Terminal prompt.

![Launch_Jupyter](/images/launching_jupyter.jpg)

4. Verify that you can access Jupyter in your browser.

![Jupyter](/images/jupyter.jpg)

### Running the Calculations

To run the calculations in the Notebook, perform the following steps:

1. Click on `risk_return_analysis.ipynb` in the left navigation panel. This will load the notebook in Jupyter.

![Click_Notebook](/images/jupyter_click_notebook.jpg)

2. Click on the 'Run' button to execute each cell. This will execute the code in each cell and display the results.

![Run_Notebook](/images/jupyter_run_notebook.jpg)

3. Exceute Import Phase. In this phase, fund data is imported via a csv file that contains data for four funds: 'Soros Fund Management LLC', 'Paulson & CO Inc', '', 'Tiger Global Management LLC', 'Berkshire Hathaway Inc' and the S&P 500.

![Import](/images/jupyter_import.jpg)

4. Execute Quantitative Analysis Phase. In this phase, The analysis has several components: performance, volatility, risk, risk-return profile, and portfolio diversification. 

![Quantitative Analysis](/images/jupyter_quantitative_analysis.jpg)

5. Execute 'Diversify the Portfolio' Phase. 

![Diversify](/images/jupyter_diversify.jpg)




## Contributors

This sample application was authored by:

Quinn Wong (quinn.wong@gmail.com)
LinkedIn: https://www.linkedin.com/in/quinnwong/




## License

The MIT License (MIT)

Copyright (c) 2022 Quinn Wong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
