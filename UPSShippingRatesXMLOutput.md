# Introduction #

_{domainname}/device/xmloutput/ups\_rate.asp?_
This URL is used to get UPS shipping rates in XML format.

### Notes: ###
  * The following are valid UPS shipping products:
    * 1DM: Next Day Air Early AM
    * 1DA: Next Day Air
    * 1DP: Next Day Air Saver
    * 2DM: 2nd Day Air Early AM
    * 2DA: 2nd Day Air
    * 3DS: 3 Day Select
    * GND: Ground
    * STD: Canada Standard
    * XPR: Worldwide Express
    * XDM: Worldwide Express Plus
    * XPD: Worldwide Expedited

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>product: String - UPS shipping method (see the list above for valid values)<br>
origCountry: String - Origination country<br>
origPostal: Integer - Origination zip code<br>
destPostal: Integer - Destination zip code<br>
destCountry: String - Destination country<br>
weight: Decimal - Package weight<br>
residential: Integer - Is this residential address? (1 for residential and 2 for commercial)<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/ups_rate.asp?product=1DM&amp;origCountry=US&amp;origPostal=12345&amp;destPostal=54321&amp;destCountry=US&amp;weight=2.5&amp;residential=1<br>
</code></pre>