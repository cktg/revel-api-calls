# Introduction #

_{domainname}/device/part\_payment.asp?_
This URL is used to send partial payment to server.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>sess_id: String - Session ID<br>
rid: Integer - Restaurant location ID<br>
amt_cash: Decimal - Cash amount<br>
amt_credit: Decimal - Credit amount<br>
credit_trans_id: Integer - Transaction ID<br>
amt_chq: Decimal - Check amount<br>
chq_num: Integer - Check number<br>
amt_gift: Decimal - Gift card amount<br>
amt_reward: Decimal - Reward card amount<br>
amt_net_payable: Decimal - Net-pay amount<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/part_payment.asp?sess_id=1234&amp;rid=123&amp;amt_cash=15&amp;amt_credit=&amp;credit_trans_id=&amp;amt_chq=25&amp;chq_num=123&amp;amt_gift=&amp;amt_reward=&amp;amt_net_payable=40<br>
</code></pre>