<!-- Geo JSON source -->
https://hifld-geoplatform.opendata.arcgis.com/datasets/6ac5e325468c4cb9b905f1728d6fbf0f_0


<!-- hospital bed count in CA -->
http://www.communitybenefitinsight.org/api/get_hospitals.php?state=CA
save as: hospital_beds (JSON)

<!-- low income providers -->
<!-- change map to show income to see if the low income hospitals are distributed according to actual low income-->
https://data.ca.gov/dataset/directory-of-service-providers1/resource/2b77a934-7425-4539-9caf-fa05bbabbe59
save as: medical_county (JSON)


<!-- medically underserved areas -->
https://data.chhs.ca.gov/dataset/medically-underserved-areas
Medically_Underserved_Areas_JSON(GEOJSON)

<!-- JOIN ABOVE AND BELOW -->

<!-- low income -->
https://data.chhs.ca.gov/dataset/living-wage/resource/f5a57e7a-e0fe-4d80-b0f6-92d66ecb907f


FEATURES
- Convert JSON files to GEO JSON with pandas to clean up and format to GEO JSON

INSTALLATONS  

WHAT TO DO NEXT TIME:

- clean up date using pandas
    - cleaned_lowincomegrouped.csv
    - cleaned_lowincome.csv
- upload to mongo


