# native_plant_database
a database of plants native to SC, use for planning gardens

3 tables:
Plant Info
Animal Info (what plant supports)
Companion Plants

plant_index_id; common_name; latin_name; height; width; bloom_time; bloom_color; preferred_location; 
animal_index_id; plant_index_id; animal_name
companion_index_id; plant_index_id; plant_index_id


# garden planner
input bed info (size, shape, location (sun, shade, etc), soil_type, num_plant_types_desired 
use native_plant_database to create
outputs plant list and location (in bed)

# resources  
https://recology.info/2016/10/usda-plants-database-r/  
https://data.nal.usda.gov/dataset/usda-plants-database-api-r
