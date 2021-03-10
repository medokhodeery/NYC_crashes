
# NYC_crashes
data cleaning

nyc car accidents dataframe, 
-columns 'langitude' and 'latitude' were duplicate info and removed.
-id accident is not important information for machine learning
- tried to reduce the number of different vechile types types  
- dropped duplicate entries
- dropped entries where niether location or zip_code or street were given
because it won't help to learn which streets are more dangerous.
- replace null values with zeros where possible
-create new feature called accident index to show the severity of the accidents.

