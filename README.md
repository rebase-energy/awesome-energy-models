<h1 align="center">
    📚 awesome-energy-models
    <br>
</h1>

<p align="center">
    <strong>A catalogue and categorization of open-source, Python-based energy models for energy system planning and operations.</strong>
</p>

## Table of Contents  
* [What is this page about?](#what-is-this-page-about)  
* [How to Contribute?](#how-to-contribute)  
* [Energy Model Categorization](#energy-model-categorization)  
* [Energy Models](#energy-models)  
* [General Tools](#general-tools)  

## What is this page about? 
This page is an attempt to catalogize and categorize open-source python-based models 
for planning and operations of energy systems. The focus is on frameworks, libraries ([frameworks vs libraries](https://stackoverflow.com/questions/148747/what-is-the-difference-between-a-framework-and-a-library)) 
and tutorials, over codes implementing specific energy model (e.g. accompanying a research paper). 
Even though projects with specific energy model implementations are included given the code quality is high. 

**Note**: Some things that are out of scope for this page include: IoT/connectivity projects, web/data scrapers, 
visualization tools and data models/ontologies. 

## How to Contribute? 

1) Add a model to list
2) Update categorization and links

## Energy Model Categorization
The energy models are categorized according to several characteristics: code type, problem type, 
model type, energy assets included and scale. Here is an outline of all the characteristics and their 
meaning: 


| Characteristics   | Fields        |
| :---              | :---          |
| **Code type**     | 🧩 **Framework**: Defines concepts and components that are used to create a solution <br> 📚 **Library**: Functions and classes to solve a specific task, e.g. generating demand profiles. <br> 🎓 **Tutorial**: Educational walkthroughs of specific topics and concepts. <br> 📄 **Code**: Implementation of specific energy model. |
| **Problem type**  | 🎬 **Operations**: Operations problem such as dispatch or continuous trading. <br> 📝 **Planning**: Planning problems such as optimal investments or system configuration. |
| **Model type**    | 🎮 **Simulation**: Physical or behaviour simulations, typically allowing for "what-if"-analysis. <br> 📈 **Prediction**: Forecasting and scenario generation. <br> ⚙️ **Optimization**: Models performing decision optimization. <br> 🤖 **Agents**: Models interacting with and learning from environments. |
| **Energy assets** | ☀️ **Solar**: Solar PV and solar thermal assets. <br> 🌬️ **Wind**: Wind turbines and wind farms. <br> 🔋 **Battery**: Electrochemical batteries. <br> 💦 **Hydro**: Electrochemical batteries. <br> 💦 **Heat pump**: <br> ⚡ **Power grid**:  |
| **Scale**         | ⚡ **Power transmission**: Scale of power transmission and countries. <br> 🏭 **Power plant**: Front-of-meter power plant scale. <br> 🏙️ **City/Region**: City or region scale. <br> 🏘️ **Community**: Energy community scale. <br> 🏠 **House/building**: House or building scale. <br> 🔋 **Asset**: Asset scale. |

## Energy Models (Frameworks and libraries)
In alphabetical order. 

| Name | Description | Problem Type | Model Type | Energy Assets | Links |
| :--- | :--- | :---: | :---: | :---: | :---: |
|`alite`|Calculate renewable power potentials and time series.|📝|🎮|☀️ 🌬️|[[code]](https://github.com/pypsa/atlite), [[docs]](https://alite.readthedocs.io/en/latest/), [[pypi]](https://pypi.org/project/alite/), [[website]](https://pypsa.org/)|
|`boptest`|Simulate and benchmark building heat transfer.|🎬|⚙️ 🎮|🏠|[[code]](https://github.com/ibpsa/project1-boptest)|
|`calliope`|A multi-scale energy systems modelling framework.|📝|🎮|🔋 🏭 ⚡ ☀️ 🌬️|[[code]](https://github.com/calliope-project/calliope), [[docs]](https://calliope.readthedocs.io/en/stable/), [[pypi]](https://pypi.org/project/calliope/), [[website]](https://www.callio.pe/)|
|`demandlib`|Generate electricity and heating demand profiles.|📝|🎮|🏠|[[code]](https://github.com/oemof/demandlib), [[docs]](https://demandlib.readthedocs.io/en/latest/), [[pypi]](https://pypi.org/project/demandlib/)|
|`Grid2Op`|A framework to model sequential decision making in power grid operations.|🎬|🤖 ⚙️ 📈 🎮|⚡|[[code]](https://github.com/rte-france/Grid2Op), [[docs]](https://grid2op.readthedocs.io/en/latest/), [[pypi]](https://pypi.org/project/Grid2Op/), [[website]](https://l2rpn.chalearn.org/)|
|`HOPP`|Assess optimal designs for the deployment of utility-scale hybrid energy plants.|📝|🎮|🔋 ☀️ 🌬️|[[code]](https://github.com/NREL/HOPP), [[docs]](https://hopp.readthedocs.io/en/latest/), [[pypi]](https://pypi.org/project/HOPP/)|
|`Hydropowerlib`|Calculate feed-in time series of run-of-the-river hydropower plants.|📝|🎮|💦|[[code]](https://github.com/hydro-python/hydropowerlib)|
|`OpenSTEF`|Open energy forecasting package.|🎬|📈|☀️ 🌬️|[[code]](https://github.com/OpenSTEF/openstef), [[docs]](https://openstef.github.io/openstef/), [[pypi]](https://pypi.org/project/openstef/)|
|`OSESMO`|Calculate power flow of distribution grids.|📝|🎮|⚡|[[code]](https://github.com/RyanCMann/OSESMO/)|
|`pandapipes`|Calculate fluid flow of pipe systems.|📝|🎮|♨️|[[code]](https://github.com/e2nIEE/pandapipes), [[docs]](https://pandapipes.readthedocs.io/en/latest/), [[pypi]](https://pypi.org/project/pandapipes/), [[website]](https://www.pandapipes.org/)|
|`pandapower`|Calculate power flow of distribution grids.|📝|🎮|⚡|[[code]](https://github.com/e2nIEE/pandapower), [[docs]](https://pandapower.readthedocs.io/en/latest/), [[pypi]](https://pypi.org/project/pandapower/)|
|`proloaf`|Probabilistic electricity load forecasting using recurrent neural networks.|🎬|📈|⚡|[[code]](https://github.com/sogno-platform/proloaf), [[pypi]](https://pypi.org/project/proloaf/)|
|`pvlib`|Functions for simulating and forecasting photovoltaic energy systems.|📝|📈 🎮|☀️|[[code]](https://github.com/pvlib/pvlib-python), [[docs]](https://pvlib-python.readthedocs.io/en/stable/), [[pypi]](https://pypi.org/project/pvlib/)|
|`pyCity`|Python package for data handling and scenario generation of city districts.|📝|🎮|🔋 🏠 ☀️ 🌬️|[[code]](https://github.com/RWTH-EBC/pyCity), [[pypi]](https://pypi.org/project/pycity-base/)|
|`PYPOWER`|Power flow and Optimal Power Flow (OPF) solver. Port from MATPOWER to Python.|📝|🎮|⚡|[[code]](https://github.com/rwl/PYPOWER), [[docs]](https://rwl.github.io/PYPOWER/api/), [[pypi]](https://pypi.org/project/PYPOWER/)|
|`pysam`|Python Wrapper for the System Advisor Model (SAM).|📝|🎮|🔋 🏠 ☀️ 🌬️|[[code]](https://github.com/NREL/pysam), [[docs]](https://nrel-pysam.readthedocs.io/en/main/), [[pypi]](https://pypi.org/project/pysam/)|
|`TEASER`|Tool for Energy Analysis and Simulation for Efficient Retrofit.|📝|🎮|🏠|[[code]](https://github.com/RWTH-EBC/TEASER), [[pypi]](https://pypi.org/project/teaser/)|
|`windpowerlib`|Calculate wind power production from meteorological variables.|📝|📈 🎮|🌬️|[[code]](https://github.com/wind-python/windpowerlib), [[docs]](https://windpowerlib.readthedocs.io/en/stable/index.html), [[pypi]](https://pypi.org/project/windpowerlib/), [[website]](https://oemof.org/)|

## Tutorials and examples

## General tools
General tools are frameworks and libraries that are not necessarily energy models but that can be useful 
for implementation of specific energy models. We categorize these tools into:
* 🎮 Physics or data driven simulation tools.
* 📈 Statistical and machine learning prediction tools.
* ☀️ Optimization tools. 
* 🤓 Explainability and interpretability tools. 

|     **Name**     |  Description                                                                         |   Tool type   |   Links     |
| :---             |     :---                                                                             |     :---:     |   :---:     |
| `autogluon`      | Fast and Accurate ML in 3 Lines of Code.                                             | 📈            | [[code]](https://github.com/autogluon/autogluon), [[docs]](https://auto.gluon.ai/stable/index.html), [[PyPI]](https://pypi.org/project/autogluon/) |
| `catboost`       | A fast gradient boosting library with special treatment of categorical features.     | 📈            | [[code]](https://github.com/catboost/catboost), [[docs]](https://catboost.ai/en/docs/), [[PyPI]](https://pypi.org/project/catboost/) |
| `cvxopt`         | Framework for convex optimization in python.                                         | ⚙️             | [[code]](https://github.com/cvxopt/cvxopt), [[docs]](https://cvxopt.org/userguide/), [[PyPI]](https://pypi.org/project/cvxopt/) |
| `cvxpy`          | Framework for convex optimization in python.                                         | ⚙️             | [[code]](https://github.com/cvxpy/cvxpy), [[docs]](https://www.cvxpy.org/), [[PyPI]](https://pypi.org/project/cvxpy/) |
| `darts`          | A fast gradient boosting library for tasks including regression/prediction.          | 📈            | [[code]](https://github.com/unit8co/darts), [[docs]](https://unit8co.github.io/darts/), [[PyPI]](https://pypi.org/project/darts/) |
| `gluon`          | A fast gradient boosting library for tasks including regression/prediction.          | 📈            | [[code]](https://github.com/cvxopt/cvxopt), [[docs]](https://cvxopt.org/userguide/), [[PyPI]](https://pypi.org/project/lightgbm/) |
| `lightgbm`       | A fast gradient boosting library for tasks including regression/prediction.          | 📈            | [[code]](https://github.com/cvxopt/cvxopt), [[docs]](https://cvxopt.org/userguide/), [[PyPI]](https://pypi.org/project/lightgbm/) |
| `pycaret`        | An open-source, low-code machine learning library in Python.                         | ⚙️             | [[code]](https://github.com/pycaret/pycaret), [[docs]](https://pycaret.gitbook.io/docs), [[PyPI]](https://pypi.org/project/pycaret/) |
| `pyomo`          | An object-oriented algebraic modeling language for structured optimization problems. | ⚙️             | [[code]](https://github.com/Pyomo/pyomo), [[docs]](https://pyomo.readthedocs.io/en/stable/), [[PyPI]](https://pypi.org/project/Pyomo/) |
| `scikit-learn`   | The go-to machine learning library for Python.                                       | 📈            | [[code]](https://github.com/scikit-learn/scikit-learn), [[docs]](https://scikit-learn.org/stable/), [[PyPI]](https://pypi.org/project/scikit-learn/) |
| `shap`           | A game theoretic approach to explain the output of any machine learning model.       | 📈            | [[code]](https://github.com/shap/shap), [[docs]](https://shap.readthedocs.io/en/latest/), [[PyPI]](https://pypi.org/project/shap/) |
| `rsome`          | Robust Stochastic Optimization Made Easy.                                            | ⚙️             | [[code]](https://github.com/XiongPengNUS/rsome), [[docs]](https://xiongpengnus.github.io/rsome/), [[PyPI]](https://pypi.org/project/rsome/) |
| `xgboost`        | Extreme gradient boosting algorithm for tasks including regression/prediction.       | 📈            | [[code]](https://github.com/dmlc/xgboost), [[docs]](https://xgboost.readthedocs.io/en/stable/), [[PyPI]](https://pypi.org/project/xgboost/) |