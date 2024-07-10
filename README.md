# awesome-energy-models

## What is this page about? 
This page is an attempt to catalogize and categorize open-source python-based models 
for planning and operations of energy systems. The focus is on frameworks, libraries ([frameworks vs libraries](https://stackoverflow.com/questions/148747/what-is-the-difference-between-a-framework-and-a-library)) 
and tutorials, over codes implementing specific energy model (e.g. accompanying a research paper). 
Even though projects with specific energy model implementations are included given the code quality is high. 

**Note**: Some things that are out of scope for this page include: IoT/connectivity projects, web/data scrapers, 
visualization tools and data models/ontologies. 

## Energy Model Categorization
The energy models are categorized according to several characteristics: code type, problem type, 
model type, energy assets included and scale. Here is an outline of all the characteristics and their 
meaning: 


| Characteristics   | Fields        |
| :---              | :---          |
| **Code type**     | 🧩 **Framework**: Defines concepts and components that are used to create a solution <br> 📚 **Library**: Functions and classes to solve a specific task, e.g. generating demand profiles. <br> 🎓 **Tutorial**: Educational walkthroughs of specific topics and concepts. <br> 📄 **Code**: Implementation of specific energy model. |
| **Problem type**  | 🎬 **Operations**: Operations problem such as dispatch or continuous trading. <br> 📝 **Planning**: Planning problems such as optimal investments or system configuration. |
| **Model type**    | 🎮 **Simulation**: Simulations of physical processes or behaviour, typically allowing for "what-if"-analysis. <br> 📝 **Prediction**: Forecasting and scenario generation. <br> ⚙️ **Optimization**: Models performing decision optimization. <br> 🤖 **Agents**: Models interacting with and learning from environments. |
| **Energy assets** | ☀️ **Solar**: Solar PV and solar thermal assets. <br> 🌬️ **Wind**: Wind turbines and wind farms. <br> 🔋 **Battery**: Electrochemical batteries. <br> 💦 **Hydro**: Electrochemical batteries. <br> 💦 **Heat pump**: <br> ⚡ **Heat pump**:  |
| **Energy assets** | ⚡ **Power transmission**: Scale of power transmission and countries. <br> 🏭 **Power plant**: Front-of-meter power plant scale. <br> 🏙️ **City/Region**: City or region scale. <br> 🏘️ **Community**: Energy community scale. <br> 🏠 **House/building**: House or building scale. <br> 🔋 **Asset**: Asset scale. |

## How to Contribute? 

1) Add a model to list
2) Update categorization and links

## Energy Models
In alphabetical order. 

|     **Name**     |  Description                                                                         |  Problem type  |   Model type   | Energy assets |     Scale     |     Links     |
| :---             |     :---                                                                             |     :---:      |     :---:      |     :---:     |     :---:     |     :---:     |
| `boptest`        | Simulate and benchmark building heat transfer.                                       | 🎬             | 🎮              | 🏠            | 🏠            | [[code]](https://github.com/ibpsa/project1-boptest), [[docs]](https://demandlib.readthedocs.io/en/latest/) |
| `demandlib`      | Generate electricity and heating demand profiles.                                    | 📝             | 🎮              | git diff      | 🏠            | [[code]](https://github.com/oemof/demandlib), [[docs]](https://demandlib.readthedocs.io/en/latest/) |
| `Hydropowerlib`  | Calculate feed-in time series of run-of-the-river hydropower plants.                 | git diff       | git diff       | git diff      | git diff      | [[code]](https://github.com/hydro-python/hydropowerlib) |
| `OpenSTEF`       | Open energy forecasting package.                                                     | 🎬             | 📈              | git diff      | 🏙️ 🏘️         | [[code]](https://github.com/OpenSTEF/openstef), [[docs]](https://openstef.github.io/openstef/), [[PyPI]](https://pypi.org/project/openstef/) |
| `OSESMO`         | Calculate power flow of distribution grids.                                          | git diff       | git diff       | git diff      | git diff      | [[code]](https://github.com/RyanCMann/OSESMO/) |
| `pandapower`     | Calculate power flow of distribution grids.                                          | 📝             | 🎮              | ⚡             | 🏙️ 🏘️         | [[code]](https://github.com/e2nIEE/pandapower), [[PyPI]](https://pandapower.readthedocs.io/en/latest/) |
| `pvlib`          | 📝             | git diff       | 🎮 📈           | ☀️             | 🔋          | [[code]](https://github.com/pvlib/pvlib-python), [[PyPI]](https://pypi.org/project/pvlib/) |
| `PYPOWER`        | 📝             | git diff       | 🎮 📈           | ⚡             | 🏙️ 🏘️        | [[code]](https://github.com/pvlib/pvlib-python), [[PyPI]](https://pypi.org/project/pvlib/) |
| `windpowerlib`   | Calculate wind power production from meteorological variables.| 📝 🎬           | 🎮 📈           | 🌬️            | 🏭 🏙️ 🔋         | [[code]](https://github.com/wind-python/windpowerlib), [[docs]](https://windpowerlib.readthedocs.io/en/stable/index.html), [[PyPI]](https://pypi.org/project/pvlib/) |

## General tools
General tools are frameworks and libraries that are not necessarily energy models but that can be useful 
for implementation of specific energy models. We categorize these tools into:
* 🎮 Physics or data driven simulation tools.
* 📈 Statistical and machine learning prediction tools.
* ☀️ Optimization tools. 

|     **Name**     |  Description                                                                         |   Tool type   |   Links     |
| :---             |     :---                                                                             |     :---:     |   :---:     |
| `catboost`       | A fast gradient boosting library with special treatment of categorical features.     | 📈            | [[code]](https://github.com/catboost/catboost), [[docs]](https://catboost.ai/en/docs/), [[PyPI]](https://pypi.org/project/catboost/) |
| `lightgbm`       | A fast gradient boosting library for tasks including regression and prediction.      | 📈            | [[code]](https://github.com/microsoft/LightGBM), [[docs]](https://lightgbm.readthedocs.io/en/latest/), [[PyPI]](https://pypi.org/project/lightgbm/) |
| `pyomo`          | An object-oriented algebraic modeling language for structured optimization problems. | ☀️             | [[code]](https://github.com/Pyomo/pyomo), [[docs]](https://pyomo.readthedocs.io/en/stable/), [[PyPI]](https://pypi.org/project/Pyomo/) |

