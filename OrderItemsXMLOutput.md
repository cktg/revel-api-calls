# Introduction #

_{domainname}/device/xmloutput/items.asp?_
This URL is used to get all items that belong to an order as XML.

### Notes: ###
  * All parameters are exclusive. Only one parameter is sent per request.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>sess_id : GUID - The unique ID sent from the device (session ID)<br>
order_id: Integer - Order ID<br>
kichtendone: Boolean - Send 1 if the URL used for kitchen, 0 otherwise. If the value found is 0, it will only show the items which are not done in kitchen<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/items.asp?order_id=111<br>
</code></pre>