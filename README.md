# api-24sea-get-data-example

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pietrodantuono/api-24sea-get-data-example/main)

Example Jupyter Notebook to get data from the 24Sea API.

## Which data can I access?

**10-minute metric signals** that are collected by the 24SEA SHM system. The 10-minute metric signals (from now on addressed as metrics) are the cleaned and aggregated data calculated on a 10-minute basis. The metrics are calculated from the high-frequency raw data collected by the 24SEA SHM system. 24SEA does not provide direct access to the raw data as it needs to be processed and aggregated to be useful.

*We chose 10 minutes as the aggregation period because it has become an industry standard for SHM systems, since it is a good balance between the need for high temporal resolution and the need for a manageable amount of data.*

Users can verify which metrics they can access by inspecting their Datasignals App UI at https://api.24sea.eu/datasignals.

API documentation at https://api.24sea.eu/redoc/v1#section/Introduction.

## Contact

For any questions or issues, please contact us at [support.api@24sea.eu](mailto:support.api@24sea.eu).
