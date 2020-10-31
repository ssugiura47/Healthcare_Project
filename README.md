<!-- Geo JSON source -->
https://hifld-geoplatform.opendata.arcgis.com/datasets/6ac5e325468c4cb9b905f1728d6fbf0f_0
https://www.arcgis.com/home/webmap/viewer.html?panel=gallery&suggestField=true&url=https%3A%2F%2Fservices1.arcgis.com%2FHp6G80Pky0om7QvQ%2Farcgis%2Frest%2Fservices%2FHospitals_1%2FFeatureServer%2F0
saved as: Hospitals (GEO JSON)

<!-- hospital bed count in CA -->
http://www.communitybenefitinsight.org/api/get_hospitals.php?state=CA
saved as: hospital_beds (JSON)

<!-- low income providers -->
<!-- change map to show income to see if the low income hospitals are distributed according to actual low income-->
https://data.ca.gov/dataset/directory-of-service-providers1/resource/2b77a934-7425-4539-9caf-fa05bbabbe59
saved as: medical_county (JSON)

<!-- JOIN THREE FILES BELOW -->

<!-- medically underserved areas -->
https://data.chhs.ca.gov/dataset/medically-underserved-areas
saved as: Medically_Underserved_Areas_JSON(GEOJSON)

<!-- low income -->
https://data.chhs.ca.gov/dataset/living-wage/resource/f5a57e7a-e0fe-4d80-b0f6-92d66ecb907f
saved as: hci_living_wage_full_data (CSV)

<!-- CA counties -->
https://eric.clst.org/tech/usgeojson/
saved as: ca_counties (JSON)

FEATURES
- Convert JSON files to GEO JSON with pandas to clean up and format to GEO JSON

INSTALLATONS  

WHAT TO DO NEXT TIME:

- clean up date using pandas
- upload to mongo