# Introduction #

_{domainname}/device/xmloutput/order\_lookup.asp.asp?_
This URL is used to return order lookup in XML format.

### Notes: ###
  * Send the parameters to search. If any parameter is not sent or sent blank, it will be ignored while searching.
  * from\_date and to\_date parameters are either both set or none!

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>cust_email: String - Customer e-mail address<br>
cust_phone: String - Customer phone number<br>
order_time: String - Order time<br>
f_name: String - First name<br>
l_name: String - Last name<br>
pin_number: Integer - Employee PIN<br>
address1: String - Address line 1<br>
address2: String - Address line 2<br>
state: String - State name<br>
city: String - City name<br>
zip: Integer - Zip code<br>
date_anaversary: DateTime - Anniversary date<br>
bithday: DateTime - Birthday<br>
from_date: DateTime - From date range<br>
to_date: DateTime - To date range<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/order_lookup.asp.asp?cust_email=js@abc.com&amp;l_name=Smith<br>
</code></pre>