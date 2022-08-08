# Satellite Derived Bathymetry with IceSAT-2 LiDAR Data : Case Study in the coast of Thailand
SATELLITE DERIVED BATHYMETRY modeling study using satellite imagery and level values from satellite Lidar. Case studies of coastal areas of Thailand
Engineering project for the academic year 2021 of Mr. Thepchai Srinoi and Assoc. Prof. Dr. Paisan Santithamnon Department of Surveying Engineering Faculty of Engineering Chulalongkorn University

![Screenshot (419)](https://user-images.githubusercontent.com/88705136/171320963-0ac44fd4-2d7f-4b20-82e5-cd66bb4cf946.png)

To study the modeling of shallow water depth (Bathymetry Model) in the coastal area of ​​Thailand. Based on Sentinel-2 satellite imagery and levels from the ICESat-2 Lidar system through python programming, data manipulation and modeling. By importing the image data from the Google Earth Engine system.

The sample depth is obtained by selecting the water level and surface values ​​from the point cloud from the ATLAS LiDAR on the ICESat-2 satellite. The raw data is imported into the pandas dataframe. If the initial data is loaded as hdf5 file, import python with library h5py, and then import the dataframe to ease of management

The subjects of interest were the Stumpf or Lyzenga Algorithm and the Sun Glint or Dark Object Subtraction Atmospheric Correction in Hat Chao Samran Study Area. Phetchaburi Province Thai Mueang Beach, Phang Nga Province and Koh Mak, Trat Province

As a preliminary result, the Lyzenga Algorithm is suitable for the first area and the Stumpf Algorithm is suitable for the latter two areas. By selecting images without editing for better results. Therefore, choose images well from the start. You can import it to make a model. Accuracy is on the scale of 1 to 3 meters.

This study also has many areas that can be further studied. Both research bias reduction, manual selection avoidance, image correction and level improvements are ready for modeling. The algorithm model is more natural than the two algorithms researched.

Thepchai Srinoi is currently a master's degree student. Department of Surveying Engineering Faculty of Surveying Engineering Chulalongkorn University Interested in research in Remote Sensing for the physical environment. both in terms of water resources, cities, land use and land cover world science He is also interested in Geodesy and Cartography.
Ways to contact the owner of the work thepchaisrinoi@gmail.com
