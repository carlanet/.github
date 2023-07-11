# CARLANeT

CARLANeT is a powerful open source project that allows co-simulation between OMNeT++ and CARLA. It allows developers to create realistic simulations of vehicular services by leveraging network communication. With CARLANeT, the integration of OMNeT++ and CARLA becomes simple, allowing for comprehensive testing and analysis of various vehicular scenarios.

<p align="center">
 <img src="https://github.com/carlanet/.github/blob/main/images/carlanet_structure.png" width="75%" width="75%" alt>
</p>

## Architecture

CARLANeT is composed of two different libraries that are essential for a fully working co-simulation between CARLA and OMNeT++:

- [pyCARLANeT](https://github.com/carlanet/pycarlanet): This library needs to be included and adapted in the Python code that communicates with the CARLA simulator and simulates the physics world.

- [CARLANeTpp](https://github.com/carlanet/carlanetpp): This library needs to be included and adapted in the OMNeT++ code that is used to define the communication network.

Please see the respective repositories for more information on how to use them.

