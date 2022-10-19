[[DE]](README.md)/[[EN]](README_en.md)


[![.github/workflows/openapi_check.yaml](https://github.com/t-huyeng/thw-pegel-api/actions/workflows/openapi_check.yaml/badge.svg)](https://github.com/t-huyeng/thw-pegel-api/actions/workflows/openapi_check.yaml) [![.github/workflows/schemathesis.yaml](https://github.com/t-huyeng/thw-pegel-api/actions/workflows/schemathesis.yaml/badge.svg)](https://github.com/t-huyeng/thw-pegel-api/actions/workflows/schemathesis.yaml)


# THW Pegel API

The German Federal Agency for Technical Relief (THW) uses measuring cases, so-called "Mobile-Pegel", to measure water levels at various locations. The data is made available on the associated page ([gauge map](http://www.thw-pegel.de/pegelkarte.php)).


The associated API returns the data of the respective level. However, the specific  level cannot be selected, but the data for the level selected in the frontend is returned on the server side. The API also does not have an `Access-Control-Allow-Origin: *` header, so retrieving it from another frontend such as the Swagger UI is not possible without a proxy server. A free proxy server can be selected in the server selection to test the API. This server may have a low transfer speed.



This specification is not an official specification of THW. If you have any questions about the mobile level, contact THW directly.
