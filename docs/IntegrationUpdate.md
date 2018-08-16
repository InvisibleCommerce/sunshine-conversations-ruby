# SmoochApi::IntegrationUpdate

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**brand_color** | **String** | This color will be used in the messenger header and the button or tab in idle state. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**fixed_intro_pane** | **BOOLEAN** | When &#x60;true&#x60;, the introduction pane will be pinned at the top of the conversation instead of scrolling with it. The default value is &#x60;false&#x60;. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**conversation_color** | **String** | This color will be used for customer messages, quick replies and actions in the footer. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**action_color** | **String** | This color will be used for call-to-actions inside your messages. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**display_style** | **String** | Choose how the messenger will appear on your website. Must be either button or tab. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**button_icon_url** | **String** | With the button style Web Messenger, you have the option of selecting your own button icon. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**button_width** | **String** | With the button style Web Messenger, you have the option of specifying its width. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**button_height** | **String** | With the button style Web Messenger, you have the option of specifying its height. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**integration_order** | **Array&lt;String&gt;** | Array of integration IDs, order will be reflected in the Web Messenger. When set, only integrations from this list will be displayed in the Web Messenger. If unset, all integrations will be displayed (Optional) Used for *Web Messenger* integrations.  | [optional] 
**business_name** | **String** | A custom business name for the Web Messenger. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**business_icon_url** | **String** | A custom business icon url for the Web Messenger. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**background_image_url** | **String** | A custom background url for the Web Messenger. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**origin_whitelist** | **Array&lt;String&gt;** | A list of origins to whitelist. When set, only the origins from this list will be able to initialize the Web Messenger. If unset, all origins are whitelisted. The elements in the list should follow the serialized-origin format from RFC 6454 &#x60;scheme \&quot;://\&quot; host [ \&quot;:\&quot; port ]&#x60;, where scheme is &#x60;http&#x60; or &#x60;https&#x60;. (Optional) Used for *Web Messenger* integrations.  | [optional] 
**channel_id** | **String** | LINE Channel ID. Required for *line* integrations.  | [optional] 
**channel_secret** | **String** | LINE Channel Secret. Required for *line* integrations.  | [optional] 


