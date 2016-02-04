# Introduction #

_{domainname}/device/item\_move\_table\_table\_update.asp?_
This URL is used to move items from a table to another table.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>rec_id: Integer - The record ID of the item<br>
rid: Integer - Restaurant location ID<br>
table_id: Integer - New table ID<br>
sess_id: String - New session ID<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/item_move_table_table_update.asp?rec_id=323&amp;rid=123&amp;table_id=10&amp;sess_id=1234<br>
</code></pre>