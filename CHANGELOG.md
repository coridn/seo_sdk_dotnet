# Changelog

## 2.3.0.0

* Added support for bvstate parameter.
* Fixed 'sp_mt' metadata.

## 2.2.0.3

* Release notes and version update.

## 2.2.0.2

* Cleaned Spotlights unit tests.
* Fixed footer metadata.
* Disabled debug logging in BVLog4Net.config.

## 2.2.0.1

* Support for Spotlight content type has been added.
* QA support for internal purpose only.
* Fixed ct_st meta data tag in footer.
* Fixed master footer text.
* Unit tests are updated.

## 2.1.0.1

* BVParameters.pageNumber has been added. When used, this parameter will
override page number variables extracted from PageURI.
* BVClient.BOT_DETECTION has been removed. Bot detection functionality now only
applies to execution timeouts.
* BVClinet.EXECUTION_TIMEOUT_BOT has been added with default value of 2000ms,
which is the execution timeout intended for search bots. The minimum
configurable value for this timeout is 100ms.
* Default value for BVClient.EXECUTION_TIMEOUT is set to 500ms from its
original 3000ms. If this value is set to 0ms, no connection attempts will
occur.
* Default value for CONNECT_TIMEOUT and SOCKET_TIMEOUT is increased to 2000ms
(to match BVCLIENT.EXECUTION_TIMEOUT_BOT).
* Error handling for EXECUTION_TIMEOUT and EXECUTION_TIMEOUT_BOT
implementation.

## 2.1.0.0-beta-1

* Supports all version of .NET Framework from 2.0 and above.
* Property driven using default bvclient properties.
* Override bvclient properties option.
* Multiple configuration support to override bvclient properties.
* Parameters as object when accessing Bazaarvoice content API.
configuration.
scenarios.
complete job is not finished in a given time, and cancel action and a display
a comment tag.
user can set plain agent pattern in BVConfiguration. For multiple agent crawler
text, separate with `|` delimiter.
Parameters and for displaying debug information (with bvreveal=debug parameter
in the query string).
can be configured in BVConfiguration using BVClientConfig.CHARSET property.