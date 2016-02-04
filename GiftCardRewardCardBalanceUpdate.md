# Introduction #

_{domainname}/device/cards\_balance\_update.asp?_
This URL is used to update gift cards and reward cards balances.

### Notes: ###
  * Balance will be added to the previous balance. If to be deducted, send a negative value.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>card_id: Integer - Card ID<br>
card_type: Integer - Card type (0 for gift card and 1 for reward card)<br>
balance: Decimal - Card balance<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/cards_balance_update.asp?card_id=123&amp;card_type=0&amp;balance=50<br>
</code></pre>