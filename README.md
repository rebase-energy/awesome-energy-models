# awesome-energy-models

## Constraints
* Python
* Open-source
* Models
* What it is not: IoT/connectivity, web scrapers, visualization tools, 
* Focus on frameworks over codes / stand-alone models
* Framework, Code, Tutorial. 

## Energy Model Categorization

| Name         | Categories     |
| :---         |     :---:      |
| **Problem type:**    | 🎬 = Operations, 📝 = Planning |
| **Model type:**      | 🎮 = Simulation, 📈 = Forecasting, ⚙️ = Optimization, 🤖 = Agent |
| **Energy assets:**   | ☀️ = Solar, 🌬️ = Wind, 🔋 = Battery, 💦 = Hydro, ♻️ = Heat pump, ⚡ = Power grid |
| **Scale:**           | ⚡ = Power transmission, 🏭 = Power plant, 🏙️ = City/Region, 🏘️ = Community, 🏠 = House or building, 🔋 = Asset |

"Model tags" according to: 
Power flow, UBEM, heat transfer ?

## How to Contribute? 

1) Add a model to list
2) Update categorization and links

## Energy Model List
In alphabetical order. 

|     **Name**     |  Description                                                  |  Problem type  |   Model type   | Energy assets |     Scale     |     Links     |
| :---             |     :---                                                      |     :---:      |     :---:      |     :---:     |     :---:     |     :---:     |
| `boptest`        | Simulate and benchmark building heat transfer.                | 🎬             | 🎮              | 🏠            | 🏠            | [[code]](https://github.com/ibpsa/project1-boptest), [[docs]](https://demandlib.readthedocs.io/en/latest/)    |
| `demandlib`      | Generate electricity and heating demand profiles.             | 📝             | 🎮              | git diff      | 🏠            | [[code]](https://github.com/oemof/demandlib), [[docs]](https://demandlib.readthedocs.io/en/latest/)    |
| `OSESMO`         | Calculate power flow of distribution grids.                   | git diff       | git diff       | git diff      | git diff      | [[code]](https://github.com/RyanCMann/OSESMO/)    |
| `pandapower`     | Calculate power flow of distribution grids.                   | 📝             | 🎮              | ⚡             | 🏙️ 🏘️         | [[code]](https://github.com/e2nIEE/pandapower), [[PyPI]](https://pandapower.readthedocs.io/en/latest/) |
| `pvlib`          | 📝             | git diff       | 🎮 📈           | ☀️             | 🔋            | [[code]](https://github.com/pvlib/pvlib-python), [[PyPI]](https://pypi.org/project/pvlib/) |
| `PYPOWER`        | 📝             | git diff       | 🎮 📈           | ⚡             | 🏙️ 🏘️         | [[code]](https://github.com/pvlib/pvlib-python), [[PyPI]](https://pypi.org/project/pvlib/) |
