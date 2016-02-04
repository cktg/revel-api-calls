# Introduction #

_{domainname}/device/iou\_amount.asp?_
This URL is used to update IOU data.

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
<pre><code>http://www.mydomainname.com/device/iou_amount.asp?name_first=John&amp;last_name=Smith&amp;address1=XXXX&amp;address2=XXXXX&amp;state=CA&amp;zip=12345&amp;city=&amp;phone=&amp;email=js@abc.com&amp;fax=&amp;date_iou_used=&amp;amount_iou=&amp;date_iou_payed=&amp;amount_iou_payed=&amp;balance=0<br>
</code></pre>