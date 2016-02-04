# Introduction #

_{domainname}/device/xmloutput/IOU.asp?_
This URL is used to return IOU in XML format.

### Notes: ###
  * Send the parameters to search. If any parameter is not sent or sent blank, it will be ignored while searching.

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
date_iou_used: DateTime - Date IOU was used<br>
amount_iou: Decimal - IOU amount<br>
date_iou_payed: DatTime - Date IOU was paid<br>
amount_iou_payed: Decimal - IOU amount paid<br>
balance: Decimal - Balance<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/IOU.asp?name_first=John&amp;last_name=Smith<br>
</code></pre>