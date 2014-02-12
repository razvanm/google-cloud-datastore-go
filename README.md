# Go library for Google Cloud Datastore

Google Cloud Datastore is a fully managed, schemaless, non-relational
datastore accessible through Google APIs infrastructure. It provides
a rich set of query capabilities, supports atomic transactions, and
automatically scales up and down in response to load.

This repository contains the Go library only for the protocol buffers
API for Google Cloud Datastore. Please see
[GoogleCloudPlatform/google-cloud-datastore][1] for other languages.
Generic Go JSON support for many Google APIs is provided by
[google-api-go-client][2]. Note that the datastore JSON support doesn't
work properly ([issue #54][3] and [discussion][4]).

## Contributing changes

- See [CONTRIB.md][4]

## Licensing

- See [LICENSE][5]

[1]: https://github.com/GoogleCloudPlatform/google-cloud-datastore
[2]: http://code.google.com/p/google-api-go-client/
[3]: https://code.google.com/p/google-api-go-client/issues/detail?id=54
[4]: https://groups.google.com/d/msg/golang-nuts/nDlN99pRH74/3NEY0odNVjgJ
[4]: CONTRIB.md
[5]: LICENSE
