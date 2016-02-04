# Introduction #

_{domainname}/device/order.asp?_
This URL is used when the order is completed.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>sess_id : GUID - The unique ID sent from the device<br>
totalprice: Decimal - Total price<br>
totaldisc: Decimal - Total discount<br>
totaldisc_text: String - Reason for discount<br>
totaltax: Decimal - Total tax<br>
tip: Decimal - Tip amount<br>
payable: Decimal - Net pay (totalprice - totaldics + totaltax + tip)<br>
restaurantid: Integer - Restaurant ID<br>
delivery_process: String - This is one of the following options: Takeout, Delivery, Eat in<br>
delivery_charge: Decimal - Delivery charge (Default value is 0)<br>
cust_email: String - Customer e-mail<br>
cust_phone: String - Customer phone<br>
order_time: String - Order time (This is an optional parameter)<br>
deliv_time: String - Delivery time (The values are either "Ready Now" or time value in HH:MM AM/PM format)<br>
pmt_method: String - Method of payment<br>
paid: Boolean - Has the order been paid? (Values are either 0 for false or 1 for true)<br>
comment: String - Comment or general instruction about the order<br>
device: Character - The device used to place the order (Values are 'i' for iPhone and 'p' for iPad)<br>
f_name: String - Customer first name<br>
l_name: String Customer last name<br>
show_in_xml: Boolean - Show in XML? (Values are either 0 for false or 1 for true)<br>
pin_number: Integer - User's PIN<br>
amt_cash: Decimal - Amount paid in cash<br>
amt_credit: Decimal - Amount paid with a credit card<br>
cheque_no: Integer - Check number<br>
chq_issue_bank: String - Issuing bank of the check<br>
cr_card_type: String - Credit card type<br>
trans_id: Integer - Transaction ID<br>
address1: String - Customer address1<br>
address2: String - Customer address2<br>
state: String - Customer state<br>
city: String - Customer city<br>
zip: Integer - Customer zip code<br>
date_anaversary: DateTime - Customer anniversary date<br>
bithday: DateTime - Customer birthday<br>
surcharge: Decimal - Surcharge (This is an optional parameter)<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/order.asp?sess_id=XX&amp;totalprice=55&amp;totaldisc=&amp;totaldisc_text=&amp;totaltax=5.50&amp;tip=5&amp;payable=65.50&amp;restaurantid=1234&amp;delivery_process=Takeout&amp;delivery_charge=0&amp;cust_email=&amp;cust_phone=&amp;deliv_time=Ready Now&amp;pmt_method=Cash&amp;paid=0&amp;comment=&amp;device=p&amp;f_name=John&amp;l_name=Smith&amp;show_in_xml=1&amp;pin_number=&amp;amt_cash=65.50&amp;amt_credit=&amp;cheque_no=&amp;chq_issue_bank=&amp;cr_card_type=&amp;trans_id=&amp;address1=&amp;address2=&amp;state=&amp;city=&amp;zip=&amp;date_anaversary=&amp;bithday=<br>
</code></pre>