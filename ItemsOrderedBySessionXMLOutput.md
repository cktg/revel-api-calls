# Introduction #

_{domainname}/device/xmloutput/products\_menus.asp?_
This URL is used to get all items ordered from a restaurant by session as XML.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>sess_id : GUID - The unique ID sent from the device (session ID)<br>
rest_id: Integer - Restaurant ID<br>
kichtendone: Boolean - Send 1 if the URL used for kitchen, 0 otherwise. If the value found is 0, it will only show the items which are not done in kitchen<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/products_menus.asp?sess_id=XX&amp;restid=2&amp;kitchendone=1<br>
</code></pre>