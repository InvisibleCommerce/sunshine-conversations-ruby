# SunshineConversationsClient::MatchCriteriaWhatsappAllOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **String** | The channel type. | [optional] [default to &#39;whatsapp&#39;]
**phone_number** | **String** | The user’s phone number. It must contain the + prefix and the country code. Examples of valid phone numbers: +1 212-555-2368, +12125552368, +1 212 555 2368. Examples of invalid phone numbers: 212 555 2368, 1 212 555 2368.  | 

## Code Sample

```ruby
require 'SunshineConversationsClient'

instance = SunshineConversationsClient::MatchCriteriaWhatsappAllOf.new(type: null,
                                 phone_number: +15550001234)
```


