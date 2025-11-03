## Integrations and Database

This repository presents a solution for retrieving the number of trees in a specific city for a given year using Open Street Map.

*   A FastAPI application is implemented with a POST endpoint to get the count of trees in a specific city for a given year via the Open Street Map API.
*   The `requests` library is used to query the Open Street Map API.
*   Every successful request is logged to a PostgreSQL database.
*   A stored procedure has been implemented in the database to determine the city that has been queried most frequently in the endpoint's request history.
