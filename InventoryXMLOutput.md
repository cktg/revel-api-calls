# Introduction #

{domainname}/device/xmloutput/stockupdate.asp? This URL is used to output the inventory items in XML format.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>locationid: Integer - Inventory location ID<br>
enteredon: DateTime - Date the inventory was entered/updated. This is a UNIX based time-stamp of a pure date (no hours, minutes, or seconds).<br>
If enteredon is not sent then only the records with current enteredon values will be shown.<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/stockupdate.asp?locationid=1<br>
</code></pre>