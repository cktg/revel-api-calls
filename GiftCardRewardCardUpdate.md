# Introduction #

_{domainname}/device/cards.asp?_
This URL is used to update gift cards and reward cards.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>card_id: Integer - Card ID<br>
card_type: Integer - Card type (0 for gift card and 1 for reward card)<br>
l_name: String - Last name<br>
f_name: Strig - First name<br>
address1: String - Address line 1<br>
address2: String - Address line 2<br>
state: String - State name<br>
city: String - City name<br>
zip: Integer - Zip code<br>
email: String - E-mail address<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/cards.asp?card_id=123&amp;card_type=1&amp;l_name=Smith&amp;f_name=John&amp;address1=123Street&amp;address2=Apt12&amp;state=CA&amp;city=MyCity&amp;zip=12345&amp;email=js@abc.com<br>
</code></pre>