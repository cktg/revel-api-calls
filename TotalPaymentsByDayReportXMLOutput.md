# Introduction #

_{domainname}/device/xmloutput/report\_total\_payment\_cash\_credit\_tip\_by\_day.asp?_
This URL is used to return total payments by day report in XML format.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>rid: Integer - Restaurant location ID<br>
table_id: Integer - Table ID<br>
days: Integer - 0 for current date; 1 for last 2 days i.e. today and yesterday together<br>
pin: Integer - Employee PIN<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/report_total_payment_cash_credit_tip_by_day.asp?rid=123&amp;table_id=12&amp;days=0&amp;pin=12345<br>
</code></pre>