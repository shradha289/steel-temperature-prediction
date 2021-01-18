# steel-temperature-prediction
In order to optimize production costs, the steel plant Steelproof decided to reduce their energy consumption at the steel processing stage. We have to develop a model that will be able to predict the temperature of the metal.
### **The Steps of Steel Processing:**
Steel is processed in a metal ladle that has a capacity of about 100 tons. In order for the ladle to withstand high temperatures, it is lined with refractory bricks on the inside. Molten steel is poured into the ladle and heated to the desired temperature with graphite electrodes located on the lid.
Sulfur is removed from the metal through the process of desulfurization. The steel's chemical composition is corrected (by adding alloys in the form of bullions from the bunker with bulk materials or with the help of a wire feeder), and the necessary samples are taken.
Before alloying elements are included, the temperature of the steel is measured and its chemical composition is analyzed. The temperature is then raised for a few minutes, the alloying elements are added, and the alloy itself is purged with an inert gas. After that, the alloy is stirred and its temperature is measured again. This cycle repeats itself until the desired chemical composition and the optimal melting temperature are achieved.
The molten steel is then refined or transferred into a continuous casting machine which solidifies the steel into slabs.
### **Data Description**
The data consists of files obtained from different sources:
- `data_arc_en.csv`-electrode data
- `data_bulk_en.csv`- bulk material supply data (volume)
- `data_bulk_time_en.csv`- bulk material delivery data (time)
- `data_gas_en.csv` — gas purge data
- `data_temp_en.csv` — temperature measurement results
- `data_wire_en.csv` — wire materials data (volume)
- `data_wire_time_en.csv` — wire materials data (time)
In each file, the key column contains the batch number.
There may be several rows with the same `key` value in the files. These values correspond to different processing iterations.
