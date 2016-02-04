# Introduction #

_{domainname}/device/split\_bills.asp?_
This URL is used to split a bill.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>rid: Integer - Restaurant location ID<br>
sess_id: String - Session ID<br>
order_id: Integer - Order ID<br>
how_many_persons: Integer - Total number of persons<br>
person_number: Integer - A number given to a person<br>
paid: Boolean - Is the bill paid? (1 for yes and 0 for no)<br>
pmt_amt: Decimal - Payment amount<br>
pmt_mode: String - Payment type<br>
trans_id: Integer - Transaction ID<br>
person_name: String - Person's name (person paying)<br>
tip: Decimal - Tip amount<br>
total_amt_person: Decimal - Total amount per person<br>
total_amt_order: Decimal - Total order amount<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/split_bills.asp?rid=123&amp;sess_id=1234&amp;order_id=123&amp;how_many_persons=2&amp;paid=1&amp;pmt_amt=100&amp;tip=10&amp;total_amt_person=55&amp;total_amt_order=110<br>
</code></pre>