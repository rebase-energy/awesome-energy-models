# awesome-energy-models

## What is this page about? 
This page is an attempt to catalogize and categorize open-source python-based models 
for planning and operations of energy systems. The focus is on frameworks, libraries ([frameworks vs libraries](https://stackoverflow.com/questions/148747/what-is-the-difference-between-a-framework-and-a-library)) 
and tutorials, over codes implementing specific energy model (e.g. accompanying a research paper). 
Even though projects with specific energy model implementations are included given the code quality is high. 

Some things that are out of scope for this page include: IoT/connectivity projects, web/data scrapers, 
visualization tools and data models/ontologies. 

## Energy Model Categorization
The energy models are categorized according to several characteristics: code type, problem type, 
model type, energy assets included and scale. Here is an outline of all the characteristics and their 
meaning: 


| Characteristics | Fields        |
| :---            |     :---      |
| **Code type**   | 🧩 **Framework**: Defines concepts and components that are used to create a solution <br>  📚 **Library**: Functions and classes to solve a specific task, e.g. generating demand profiles. <br> 🎓 **Tutorial**: Educational walkthroughs of specific topics and concepts. <br> 📄 **Code**: Implementation of specific energy model. |

| Name         | Categories     |
| :---         |     :---:      |
| **Code type:**       | 🧩 = Framework, 📚 = Library, 🎓 = Tutorial, 📄 = Code |
| **Problem type:**    | 🎬 = Operations, 📝 = Planning |
| **Model type:**      | 🎮 = Simulation, 📈 = Forecasting, ⚙️ = Optimization, 🤖 = Agent |
| **Energy assets:**   | ☀️ = Solar, 🌬️ = Wind, 🔋 = Battery, 💦 = Hydro, ♻️ = Heat pump, ⚡ = Power grid |
| **Scale:**           | ⚡ = Power transmission, 🏭 = Power plant, 🏙️ = City/Region, 🏘️ = Community, 🏠 = House/building, 🔋 = Asset |

"Model tags" according to: 
Power flow, UBEM, heat transfer ?

## How to Contribute? 

1) Add a model to list
2) Update categorization and links

## Energy Model List
In alphabetical order. 

|     **Name**     |  Description                                                                         |  Problem type  |   Model type   | Energy assets |     Scale     |     Links     |
| :---             |     :---                                                                             |     :---:      |     :---:      |     :---:     |     :---:     |     :---:     |
| `boptest`        | Simulate and benchmark building heat transfer.                                       | 🎬             | 🎮              | 🏠            | 🏠            | [[code]](https://github.com/ibpsa/project1-boptest), [[docs]](https://demandlib.readthedocs.io/en/latest/)    |
| `demandlib`      | Generate electricity and heating demand profiles.                                    | 📝             | 🎮              | git diff      | 🏠            | [[code]](https://github.com/oemof/demandlib), [[docs]](https://demandlib.readthedocs.io/en/latest/)    |
| `Hydropowerlib`  | Calculate feed-in time series of run-of-the-river hydropower plants.                 | git diff       | git diff       | git diff      | git diff      | [[code]](https://github.com/hydro-python/hydropowerlib)    |
| `OSESMO`         | Calculate power flow of distribution grids.                                          | git diff       | git diff       | git diff      | git diff      | [[code]](https://github.com/RyanCMann/OSESMO/)    |
| `pandapower`     | Calculate power flow of distribution grids.                                          | 📝             | 🎮              | ⚡             | 🏙️ 🏘️         | [[code]](https://github.com/e2nIEE/pandapower), [[PyPI]](https://pandapower.readthedocs.io/en/latest/) |
| `pvlib`          | 📝             | git diff       | 🎮 📈           | ☀️             | 🔋          | [[code]](https://github.com/pvlib/pvlib-python), [[PyPI]](https://pypi.org/project/pvlib/) |
| `PYPOWER`        | 📝             | git diff       | 🎮 📈           | ⚡             | 🏙️ 🏘️        | [[code]](https://github.com/pvlib/pvlib-python), [[PyPI]](https://pypi.org/project/pvlib/) |
| `windpowerlib`   | Calculate wind power production from meteorological variables.| 📝 🎬           | 🎮 📈           | 🌬️            | 🏭 🏙️ 🔋         | [[code]](https://github.com/wind-python/windpowerlib), [[docs]](https://windpowerlib.readthedocs.io/en/stable/index.html), [[PyPI]](https://pypi.org/project/pvlib/) |

https://github.com/wind-python/windpowerlib