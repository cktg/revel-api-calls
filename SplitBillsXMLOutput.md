# Introduction #

_{domainname}/device/xmloutput/split\_bills.asp?_
This URL used to return splitting a bill in XML format.

### Notes: ###
  * The parameters sess\_id and order\_id are mutually exclusive.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>rid: Integer - Restaurant location ID<br>
sess_id: String - Session ID<br>
order_id: Integer - Order ID<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/split_bills.asp?rid=123&amp;sess_id=1234<br>
</code></pre>