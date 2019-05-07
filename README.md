# ![LOGO](logo.png) Cloud Text-to-Speech **flow**ground Connector

## Description

A generated **flow**ground connector for the Cloud Text-to-Speech API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/texttospeech/v1/swagger.json<br/>
Generated at: 2019-05-07T17:42:04+03:00

## API Description

Synthesizes natural-sounding speech by applying powerful neural network models.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Synthesizes speech synchronously: receive results after all text input<br/>
> has been processed.

*Tags:* `text`

#### Input Parameters
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

### Returns a list of Voice supported for synthesis.

*Tags:* `voices`

#### Input Parameters
* `languageCode` - _optional_ - Optional (but recommended)
[BCP-47](https://www.rfc-editor.org/rfc/bcp/bcp47.txt) language tag. If
specified, the ListVoices call will only return voices that can be used to
synthesize this language_code. E.g. when specifying "en-NZ", you will get
supported "en-*" voices; when specifying "no", you will get supported
"no-*" (Norwegian) and "nb-*" (Norwegian Bokmal) voices; specifying "zh"
will also get supported "cmn-*" voices; specifying "zh-hk" will also get
supported "yue-*" voices.
* `access_token` - _optional_ - OAuth access token.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.
* `callback` - _optional_ - JSONP
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").

## License

**flow**ground :- Telekom iPaaS / googleapis-com-texttospeech-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
