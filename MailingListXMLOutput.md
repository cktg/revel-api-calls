# Introduction #

_{domainname}/device/xmloutput/email\_list.asp?_
This URL is used to add contacts to a mailing list as XML.

### Notes: ###
  * If any parameter is not sent or sent blank, it will be ignored while searching.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>lastname: String - Last name<br>
firstname: Strig - First name<br>
address1: String - Address line 1<br>
address2: String - Address line 2<br>
state: String - State name<br>
city: String - City name<br>
zip: Integer - Zip code<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/email_list.asp?lastname=Smith&amp;firstname=John&amp;address1=123Street&amp;address2=Apt12&amp;state=CA&amp;city=MyCity&amp;zip=12345<br>
</code></pre>