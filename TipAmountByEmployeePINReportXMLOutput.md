# Introduction #

_{domainname}/device/xmloutput/report\_tip\_amount\_by\_pin.asp?_
This URL is used to get tip amount by employee PIN report in XML format.

### Notes: ###
  * Send the parameters to search. If any parameter is not sent or sent blank, it will be ignored while searching.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>rid: Integer - Restaurant location ID<br>
to_date: DateTime - To date (UNIX date)<br>
from_date: DateTime - From date (UNIX date)<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/report_tip_amount_by_pin.asp?rid=123&amp;to_date=12-12-2011&amp;from_date=10-10-2011<br>
</code></pre>