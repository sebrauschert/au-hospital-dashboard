# Placeholder content

Some text.

## Notes

The API hierarchy and mapping logic all based on the [Myhospital website](https://www.aihw.gov.au/reports-data/myhospitals/content/api)

```
# Info and code for the hospitals; can be mapped back to the individual data sets
url <- "https://myhospitalsapi.aihw.gov.au//api/v1/reporting-units"

# Below returns all data items for data set ID 1; to list all the names and what is reported for the data-items, use datasets only
ending <- "datasets/1/data-items"
url <- paste0("https://myhospitalsapi.aihw.gov.au//api/v1/", ending)
```