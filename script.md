# Jim - Data Analyst

-   ArcGIS Online:

    -   WSRL ArcGIS - RWZI punten (`wsrl_arcgis_rwzi_punten`)
    -   Aanvullende data (`rwzi_energy_today`)

-   Power BI:

    -   Rapportage Data Analyst

-   Denodo:

    -   View van energieverbuik (`rwzi_energy`)
    -   View van energieverbuik vandaag (`rwzi_energy_today`):
        -   Query; sensitive columns:
            -   `fieldaliases`
            -   `fields`
    -   Lineage
    -   Data Catalog (`energyusage_kwh`)

# Pieter - Data Engineer

-   Denodo:

    -   Lineage (`rwzi_energy_today`)
    -   Bron-koppelingen
    -   Endpoints

-   On the fly:

    -   Sources:
        -   `test.json`
        -   `test_wkt.json`
    -   Base Views
    -   Flatten
    -   Join
    -   Endpoint:
        - `http://localhost:8999/geojson/mike/views/f_test_json_j_f_test_wkt?$geometry=location_point`
        - `http://localhost:8999/geojson/mike/views/f_test_json_j_f_test_wkt?$geometry=location_polygon`
    -   ArcGIS Online:
        - `denodo_geojson_point`
        - `denodo_geojson_polygon`

# Hanna - Data Scientist

-   Denodo:

    -   Detials over MindDB modellen (`model_energy_usage`)
    -   Voorspelling view (`energy_usage_prediction_today`)

-   ArcGIS Online:

    -   Voorspelling (`energy_usage_prediction_today`)

-   Power BI:

    -   Rapportage Data Scientist
