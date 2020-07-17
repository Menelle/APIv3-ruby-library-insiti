# SibApiV3Sdk::CreateWebhook

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **String** | URL of the webhook | 
**description** | **String** | Description of the webhook | [optional] 
**events** | **Array&lt;String&gt;** | Events triggering the webhook. Possible values for Transactional type webhook – sent, request, delivered, hardBounce, softBounce, blocked, spam, invalid, deferred, click, opened, uniqueOpened and unsubscribed and possible values for Marketing type webhook – spam, opened, click, hardBounce, softBounce, unsubscribed, listAddition &amp; delivered | 
**type** | **String** | Type of the webhook | [optional] [default to &#39;transactional&#39;]


