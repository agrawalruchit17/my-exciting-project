Return the name of the Country when the name of the Capital City is provided.

HTTP request
GET https://example.com/country-capital/<query-params>

The URL uses ASGI server Uvicorn.

Languages used :-
Python
Flask

Parameters:-

Capital City	
string
Required. The name of capital city required to get the country name.

Request body
The request body must be empty.

Response body
If successful, the response body contains data with the following structure:

JSON representation

{
  "Country": string
}