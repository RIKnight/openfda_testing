## openFDA testing: foodevent track

This track was designed to help validate the connection of the openFDA Elasticsearch container with the Rally container.  If the challenges in this track can run properly, then the containers are properly connected.

### Example Document

```json
{
    "_index" : "foodevent",
    "_type" : "rareport",
    "_id" : "NWxTmX0BrLBduk9hCHoY",
    "_score" : 0.38472205,
    "_source" : {
        "report_number" : "2019-CFS-006533",
        "outcomes" : [
            "Medically Important"
        ],
        "date_created" : "20190625",
        "reactions" : [
            "OVARIAN CANCER"
        ],
        "date_started" : "19910101",
        "consumer" : {
            "age" : "52",
            "age_unit" : "year(s)",
            "gender" : "F"
        },
        "products" : [
            {
                "role" : "CONCOMITANT",
                "name_brand" : "EXEMPTION 4",
                "industry_code" : "",
                "industry_name" : ""
            },
            {
                "role" : "SUSPECT",
                "name_brand" : "EXEMPTION 4",
                "industry_code" : "53",
                "industry_name" : "Cosmetics"
            }
        ]
    }
}
```

### Parameters

This track allows to overwrite the following parameters with Rally 0.8.0+ using `--track-params`:

None.  This track does not use parameters in this way.

### License

Same license as the original data from openFDA.
