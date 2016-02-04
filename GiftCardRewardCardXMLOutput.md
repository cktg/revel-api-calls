# Introduction #

_{domainname}/device/xmloutput/cards.asp?_
This URL is used to get gift cards and reward cards information as XML.

### Notes: ###
  * If any parameter is not sent or sent blank, it will be ignored while searching.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>card_id: Integer - Card ID<br>
card_type: Integer - Card type (0 for gift card and 1 for reward card)<br>
balance: Decimal - Card balance<br>
l_name: String - Last name<br>
f_name: String - First name<br>
address1: String - Address line 1<br>
address2: String - Address line 2<br>
state: String - State name<br>
city: String - City name<br>
zip: Integer - Zip code<br>
phone: String - Phone number<br>
email: String - E-mail address<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/cards.asp?card_id=123<br>
</code></pre>