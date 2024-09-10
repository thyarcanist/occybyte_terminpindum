# About this Notebook

### References:
- [NASA Planetary Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/)

### Overview:
This notebook simulates the creation and classification of planets using the **SOL System** as a basis and integrates resource management for the **Terminus Space Station** and other realms like **Hellenia**. We use planetary data from the NASA Planetary Fact Sheet to create interactive simulations of planets and satellite classes (solid, gas, water, and satellites), allowing users to adjust and manage resources dynamically across different realms.

### Planetary Classes:
The planets and satellites are categorized as follows, based on their type and structure:

- **GAS**: Jupiter, Saturn, Uranus
- **WATER**: Neptune
- **SATELLITE**: Moon, Ganymede, Pluto
- **SOLID**: Mercury, Venus, Earth, Mars

### Terminus Space Station:
The **Terminus Space Station** is central to this simulation and has a population of approximately **10,000** (modifiable). The space station is responsible for managing the import and export of resources like **Ore**, **Water**, **Gas**, and **Minerals** between Terminus and realms like **Hellenia**.

### Supply and Demand Simulation:
The notebook simulates **SUPPLY** and **DEMAND** based on real-time updates of the following parameters for each realm:
- **STORED**: The current stock of resources available.
- **EXCESS**: Any surplus beyond what is currently consumed.
- **CONSUMPTION RATE**: The rate at which the population consumes a resource, dynamically updated based on population size.

### Key Features:
1. **Planet Generation**: Simulate the creation of new planets and satellite structures, using planetary properties derived from the NASA factsheet.
   
2. **Population-Driven Resource Management**: The population of Terminus and Hellenia directly affects the consumption rate of resources, ensuring that as populations grow, so do resource needs.

3. **Import/Export Logic**: Automatically checks if a realm has a deficit (requiring imports) or a surplus (allowing exports) of a resource based on real-time data.

4. **Fracking Operations**: Simulate resource extraction (fracking) from different types of planets (solid and gas) to replenish resource stocks in Terminus and Hellenia.

### Interactive Elements:
- **Adjust Population**: Users can modify the population of Terminus and Hellenia, which dynamically changes the consumption rates for each resource.
- **Monitor Resource Needs**: Real-time checks for import/export needs based on stored, excess, and consumption rates.
- **Simulate Resource Extraction**: Fracking simulations allow users to extract resources from various planetary bodies, adding them to Terminus or Hellenia’s stock.


