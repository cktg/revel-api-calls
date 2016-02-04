# Introduction #

_{domainname}/device/deposit\_amount.asp?_
This URL is used to update deposit amount.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>name_first: String - First name<br>
last_name: String - Last name<br>
address1: String - Address line 1<br>
address2: String - Address line 2<br>
state: String - State name<br>
zip: Integer - Zip code<br>
city: String - City name<br>
phone: String - Phone number<br>
email: String - E-mail address<br>
fax: String - Fax number<br>
party_name: String - Party name<br>
date_party: DateTime - Party date<br>
amount_depoist: Decimal - Deposit amount<br>
amount_used: Decimal - Amount used<br>
balance: Decimal - Balance<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/deposit_amount.asp?name_first=John&amp;last_name=Smith&amp;address1=XXXX&amp;address2=XXXXX&amp;state=CA&amp;zip=12345&amp;city=&amp;phone=&amp;email=js@abc.com&amp;fax=&amp;party_name=&amp;date_party=&amp;amount_deposit=50&amp;amount_used=50&amp;balance=0<br>
</code></pre>