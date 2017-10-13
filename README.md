# forecast [![](https://godoc.org/github.com/glac20/forecast?status.svg)](https://godoc.org/github.com/glac20/forecast)
A Forecast ([forecastapp.com](https://www.forecastapp.com)) API Client For Go.

## Usage

To use the Forecast API, you need:

* The URL: https://api.forecastapp.com
* Your Account ID: `https://forecastapp.com/YOUR-ACCOUNT-ID-IS-HERE/projects`
* An [Access Token](http://help.getharvest.com/api-v2/authentication-api/authentication/authentication/): create one [here](https://id.getharvest.com/developers)

Next, construct an API:

```golang
api := forecast.New(
  "https://api.forecastapp.com",
  "your-accountid-here",
  "your-accesstoken-here"
)
```

Then, make use of the API. Consult [godoc](http://godoc.org/github.com/glac20/forecast) for detailed API documentation.

## License

[Apache 2.0](https://github.com/glac20/forecast/blob/master/LICENSE)
