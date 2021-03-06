

# QuoteSeriesId

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **String** | The platform or vendor that provided the quote, e.g. &#39;DataScope&#39;, &#39;LUSID&#39; etc. | 
**priceSource** | **String** | The source or originator of the quote, e.g. a bank or financial institution. |  [optional]
**instrumentId** | **String** | The value of the instrument identifier that uniquely identifies the instrument that the quote is for, e.g. &#39;BBG00JX0P539&#39;. | 
**instrumentIdType** | [**InstrumentIdTypeEnum**](#InstrumentIdTypeEnum) | The type of instrument identifier used to uniquely identify the instrument that the quote is for, e.g. &#39;Figi&#39;. | 
**quoteType** | [**QuoteTypeEnum**](#QuoteTypeEnum) | The type of the quote. This allows for quotes other than prices e.g. rates or spreads to be used. | 
**field** | **String** | The field of the quote e.g. bid, mid, ask etc. This should be consistent across a time series of quotes. The allowed values are dependant on the specified Provider. | 



## Enum: InstrumentIdTypeEnum

Name | Value
---- | -----
LUSIDINSTRUMENTID | &quot;LusidInstrumentId&quot;
FIGI | &quot;Figi&quot;
RIC | &quot;RIC&quot;
QUOTEPERMID | &quot;QuotePermId&quot;
ISIN | &quot;Isin&quot;
CURRENCYPAIR | &quot;CurrencyPair&quot;



## Enum: QuoteTypeEnum

Name | Value
---- | -----
PRICE | &quot;Price&quot;
SPREAD | &quot;Spread&quot;
RATE | &quot;Rate&quot;



