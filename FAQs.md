# FAQs about EuroCrops
## 1. Demo Dataset?
Last year we have already released a demo dataset, called **TinyEuroCrops**, covering areas in Austria, Slovenia and Denmark. This dataset was harmonised with a different, simpler taxonomy (HCATv1).
### Access
The dataset and some information about it are available on our [website](https://www.eurocrops.tum.de/downloads.html).
### Shape
We released the data in several ways:
- CSV files (just the labels)
- HDF5 files including the Sentinel-2 reflectance value for a representative pixel (median) of each parcel for one entire year
- GeoJSONs (Geo-referenced parcel polygons including the crop information)
### More about it
Please have a look at our [BIDS22 paper](https://arxiv.org/abs/2106.08151) for more details on the dataset.
## 2. How many crops per year?
As we only include data collecting within the subsidy control, we usually have **only one** type of crop per parcel per year in our dataset. Some countries (e.g. [Austria](https://github.com/maja601/EuroCrops/blob/main/csvs/country_mappings/at_2021.csv) and [Portugal](https://github.com/maja601/EuroCrops/blob/main/csvs/country_mappings/pt_2021.csv)) submit multiple crops per field, which can be extracted if you have a closer look at the attribute tables or our [country mappings](https://github.com/maja601/EuroCrops/tree/main/csvs/country_mappings).
## 3. Crop yield?
We do not have any information about the crop yield. We know, it would be cool, but it's unfortunately not in the data we're given.
## 4. Access to the data?
You can download our harmonised shapefiles from our [Sync&Share](https://syncandshare.lrz.de/getlink/fiAD95cTrXbnKMrdZYrFFcN8/) platform or in raw format from the county websites which you find in our Wiki. As we provide the [mappings](https://github.com/maja601/EuroCrops/tree/main/csvs/country_mappings) from the raw data to our harmonised taxonomy, you can also use these to harmonise data from years which are currently not represented in EuroCrops.
## 5. Multiple years?
Right now, we only harmonised one year per country, but we will proceed to add more within the next year.
