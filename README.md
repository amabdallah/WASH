#Systems Modeling to Measure Performance and Evaluate Management Alternatives to Improve River and Riparian Habitat Quality and Area

Managing river systems necessarily requires an understanding of the interaction between stream ecology and hydrology. The suitability of a watershed physical habitat to support the livelihood and productivity of its biota primarily depends on managing flow. Habitat conservation and restoration efforts require an understanding and a measurement of the spatial and temporal ecological response to alterations in flow regimes. Managers use deterministic and qualitative measures such as habitat quality indexes to measure ecological response of particular species at certain locations and times to flow alterations. I propose improving habitat management decision-making by incorporating habitat quality indexes as objectives to maximize in a systems optimization model. This **Watershed Area of Suitable Habitat (WASH)** systems model uses habitat quality indexes to measure physically-available suitable habitat. WASH also adds spatial and temporal functionality to quality indexes to recommend environmental flows for riverine, floodplain and wetland habitats while maintaining water for human beneficial uses. WASH also highlights promising restoration and conservation sites. In addition, WASH proposes and ranks alternatives for managers to restore and protect natural habitat. WASH formulation is generic and adaptable to other regulated river systems and for species of concern. I apply the model to the Lower Bear River, Utah to guide existing habitat conservation efforts, recommend water allocation and show tradeoffs between human and habitat use of the available flow.

##Objectives of WASH
* Quantify suitable habitat area within the watershed by embedding habitat quality indexes in a systems model, and
* Identify strategies to allocate scare natural (e.g. water) and management (e.g. financial) resources to improve habitat quality.

##Features of WASH
1. Allocates water to maximize ecological benefits at the watershed
2. Considers multiple aquatic, floodplain and wetlands habitats
3. Accounts for competing ecological needs of water for multiple species and their different life stage-water needs
4. Considers temporal and spatial dependency between flow control structures at the watershed
5. Meets human beneficial use of available water, and
6. Is generic and adaptable to other sites and species

## WASH Formulation
WASH maximizes available and ecologically suitable area for species of concern by timely and spatially allocate water to aquatic, floodplain and wetlands habitats subject to natural, physical and management constraints. WASH model formulation adjusts the values of instream flow by controlling reservoir releases and storage volumes in addition to diversion volumes. WASH also controls riparian revegetation cover. These decision variables dictate the values of a group of state variables such as water depth, channel cross sectional area, reservoir surface area, storage and flood recurrence (Figure 1). Decision and state variables are the primary factor that managers have control over to improve habitat quality. For example, increasing reservoir releases in the summer will increase the channel water depth which consequently increases the habitat suitability for fish species. Mathematically, habitat suitability is expressed using suitability indexes and are governed by relationships with habitat conditions such as water depth. These relationships are species-dependent and are based on the tolerance of species to changes in habitat condition. We measure sub-indicators by multiplying each suitability index by an affected area. Finally, sub-indicators are aggregated together using spatial and temporal weights to determine the overall WASH value which represents the entire watershed habitat quality. WASH model works with river systems as a group of nodes and links.


![alt text](http://bearriverfellows.usu.edu/wash/ModelFormulation.jpg "Model Formulation")

**Figure 1**. A flow diagram of the WASH systems model components that shows the decision and state variables, model parameters, suitability indexes, performance indicators, objective function and constraints 




