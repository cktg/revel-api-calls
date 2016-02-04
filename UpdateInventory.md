# Introduction #

_{domainname}/device/stockupdate.asp?_
This URL is used to update inventory items.

### Notes: ###
  * Every field should be posted in `'_sep'` delimited format. Make sure each value contain same number of `'_sep'` char-set.
  * `'_sep'` is the separator for the delimited values

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>locationid: Integer - Inventory location ID<br>
itemid: Integer - Inventory item ID<br>
stock: Integer - Amount to stockup<br>
_sep : String - Separator for the values<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/stockupdate.asp?locationid=1&amp;itemid=123&amp;stock=15<br>
</code></pre>