# PagerTree API Swagger Docs
This repository is meant to be used as a tool to generate client libraries for the [PagerTree API](https://apidocs.pagertree.com/).

## Generating SDKs
You can use the [Swagger Editor](https://editor.swagger.io/) to generate any client libraries you might need.

If your language is not supported using the Open API spec, you can use the [API Spec Converter](https://lucybot-inc.github.io/api-spec-converter/) to convert between Open API 3.0 and Open API 2.0 (Swagger)
![Convert from Open API 3.0 and Open API 2.0 (Swagger)](/img/convert.png)

You might need to remove the Authentication section of the Open API 3.0. If you do, make sure you add the `Authorization` header to your requests as [described in the documentation](https://apidocs.pagertree.com/#introduction).
