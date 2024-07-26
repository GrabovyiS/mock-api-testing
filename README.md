# Testing 3d party API unit

We have a unit dedicated to fetching data from a third-party API. It contains I/O (fetch) with minimal logic to process the fetched data. I use a mock and dependency injection to test it. A mock is made by faking the structure of the http response from the API.
