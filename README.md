# Yelper

Checkout out this report here: https://lahn-yop.github.io/yelper/initial_analysis.html

## Data

Collecting data using the [Yelp API](https://www.yelp.com/developers/documentation/v3)

Follow [these directions](https://www.yelp.com/developers/documentation/v3/authentication) to create an application.  This is used to generate an API key that will be used to access the Yelp API. 

Once your token is created, create an empty file called `yelp.yaml` store in somewhere safe on your machine. Using the example below, enter the credentials you received when creating your application. When inserting your information into `yelp.yaml`, do not inlcude the `<` or `>`.

```
yelp.com
- client_id: <INSERT CLIENT ID HERE>
  key: <INSERT API KEY HERE>
```
