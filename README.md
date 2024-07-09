# COVID-19_TRACKER


Creating responsive website usug HTML, CSS and JS
<br/>
It will track Covid-19 statistics for the country(based on the IP address of the user) and will show live stats(total Cases, Recovered and Total Deaths) by country.
<br/>
Search option have long list of country and user can use the search box to search for the country.
<br/>
Website Will Use GeoPlugin API(by adding the script tag given by them into our HTML code) which will use IP address to return the country code(2 digit ISO) of the user. <br/>
Now using this country code we will send country name to the Fetch API and get all the statistics in the form of HTTP response and then exracting the live data using .json method for that country back to the user.
