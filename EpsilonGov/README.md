## Team EpsilonGov
### CUSP Alumni Hack Day - Saturday, 8th April, 2017.
### Sponsored by - BetaGov and District Attorney's Office
- Henry Lin
- Nurvirta Monarizqa
- Shay Lehmann
- Priyanshi Singh
- Achilles Saxby

Structure of this repository: 

    .
    ├── EpsilonGov.pptx
    ├── README.md
    ├── data
    │   ├── charge.csv
    │   ├── fact_to_whole_data_set.csv
    │   ├── hackathon-CUSP-WI_clean.csv
    │   ├── hackathon-CUSP-WI_clean.xls
    │   ├── heatmap_incdient.png
    │   ├── prepocessed_data.csv
    │   ├── spatial_countries.csv
    │   ├── spatial_visual.csv
    │   └── wi_centroid.csv
    ├── image
    │   ├── Charges_HeatMap.png
    │   ├── Incidents_HeatMap.png
    │   ├── Maps\ -\ Severity:Class
    │   ├── PresecutionIssued.png
    │   ├── incident\ density\ by\ defendant\ zip.JPG
    │   └── incident\ density\ by\ incident\ zip.JPG
    └── notebook
        ├── Data_Cleaning_Code.ipynb
        ├── EDA.ipynb
        ├── Epsilon.ipynb
        ├── Mixing_Matching_Severity_Class.ipynb
        └── PCA.ipynb



#### Data Preprocessing:
Here is some fact about the dataset: 
- DA case status: NOT A HELPFUL FIELD. Exclude.
- Exclude the following Codes in Summary Charge Statute # (equivalent column to Summary charge desc)
  
  - 973.076(2)(a) 
  - 343.44(1)(b)&(2)(ar)2
  - 976.03

- Drop last year. Try to use Charge status and/or Charge dispo as proxies.

- Use Referral Type instead of Arrest status  (but try to see how do they match)
#### Original Dataset and Codes that have any relation to any results found within the presentation (also posted here), is located within this repository.

#### Most of the mapping images and other visualizations (if not otherwise mentioned or found in any code), has been created on CartoDB.

#### IBM Watson Analytics tool used to find a direction to proceed with the hack day project.
