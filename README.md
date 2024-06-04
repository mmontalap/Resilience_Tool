# iPlug Task 1.4 Network Resilience

[<img src="https://iplug-he.eu/wp-content/uploads/2023/03/Logo_blue_orange.png" height="128px" align="center" alt="iPlug logo">](https://iplug-he.eu/)

Welcome to the iPlug Task 1.4 Network Resilience. This tool is a part of the [iPlug project](https://iplug-he.eu/) on distributed multiport converters for integration of renewables, storage systems and loads while enhancing performance and resilience of modern distributed networks.

The Task 1.4 Network Resilience is aimed to evalaute and increase **network's resilience** in order to ensure secure, efficient, reliable, sustainable... Three complementary QGIS plug-is are developed to:
* **Hazards Combination**, resilience analysis should consider all events that might affect the network even the ones with low probability. Events that can simultaneously occur should be considered. The plug-in allows the combination of various hazards's layers as depedent or independents events. 
* **Impact Evaluation**, resilience should also consider the vulnerabilities of the nework. This plug-in allows the calculation the each element's impact through an OPF approach. 
* **Risk Assesment and Resilience Index**, considering hazards that might affect a network and its vulnerabilities, this plug-in allows the identification of the amount of energy at risk in each element and the resilience index of the whole network.  

All plug-ins are developed [PyQGIS](https://docs.qgis.org/3.34/en/docs/pyqgis_developer_cookbook/index.html) and run in [Python](https://www.python.org/)

[<img src="https://autogis-site.readthedocs.io/en/2019/_images/L7-01-overview-01-pyqgis.svg" height="50px" align="left" alt="Python logo">](https://docs.qgis.org/3.34/en/docs/pyqgis_developer_cookbook/index.html) [<img src="https://www.python.org/static/img/python-logo.png" height="50px" align="left" alt="Python logo">](https://www.python.org/)

<br>
<br>
<br>

*iPlug is supported by the European Union’s Horizon Europe programme under agreement 101069770.*

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)


## Installation

### General Requirements

* **QGIS $\geq$ 3.0**: Download from the [official site](https://www.qgis.org/es/site/forusers/download.html)

### Recommended additional plugins:

* **Plugin Reloader**: Dowload from the [official site](https://plugins.qgis.org/plugins/plugin_reloader/)

### Specific requirements for $\rightarrow$ Impact Evaluation: 

* **Pandapower $\geq$ 6.4**: 
	* Open OSGeo4W shell (packed with QGIS in the start menu)
	* Install the library using ``pip``, following the instructions at the [official site](https://www.pandapower.org/start/). 

		```
		$ pip install pandapower
		```
### Plugin Installation steps: 

* Download from this repository the required plugin.
* Unzip the folder
* Save the folder in the QGIS' Active User Profile.
 
	* Linux: ``C:\Users\USER\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins\ORStools``
	* Windows: ``C:\Users\USER\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins\ORStools``
	* Mac OS: ``Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/ORStools``

If not found, the QGIS' Active User Profile Folder can be accessed throug ``QGIS`` $\blacktriangleright$ ``Settings`` $\blacktriangleright$ ``User Profile`` $\blacktriangleright$ ``Open Active Profile Folder``

## Usage

Before using a plugin, using the Reload Plugin through ``Plugin Reloader`` is recommended. 

Find usage guide at ``./ResilienceUserGuide.pdf`` ([here]()) ([here](./ResilienceUserGuide.pdf))
## Contributors

In alphabetical order:

* Marc Cheah Mañé (marc.cheah@upc.edu)
* Oriol Gomis-Bellmunt (oriol.gomis@upc.edu)
* Montserrat Montalà-Palau (montserrat.montala@upc.edu)

[<img src="https://citcea.upc.edu/ca/shared/logos/logocitceaupc.png" height="64px" align="center" alt="CITCEA-UPC logo">](https://citcea.upc.edu/ca)


## License
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 
