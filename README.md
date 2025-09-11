# MyScenariosRepo

## Running the Scenarios with Esmini

To run the scenarios, make sure the following steps are completed:

1. **Models**  
   Ensure that all models referenced in the `.xosc` files (e.g., `.osgb` for `SceneGraphFile` in `RoadNetwork` or vehicles referenced via catalog) are present in `esmini/resources/models`.

2. **Maps**  
   Ensure all OpenDRIVE map files (`.xodr`) referenced in the `.xosc` files (`LogicFile` in `RoadNetwork`) are available in `esmini/resources/maps`.

3. **Scenarios**  
   Copy `.xosc` scenario files from `scenarios/` to `esmini/resources/xosc`.

4. **Catalogs**
   Ensure all files in Catalogs are present in your `esmini/resources/xosc/Catalogs`.

Once these are in place, you can launch Esmini and select the scenario from the GUI or run it via command line:

```bash
bin/esmini --osc ./resources/xosc/<scenarioName>.xosc
````

> Note: The Esmini engine itself is **not included** in this repository. Please install Esmini separately following the [official instructions](https://github.com/esmini/esmini).

