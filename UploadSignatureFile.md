# Introduction #

_{domainname}/device/signature\_image.asp?_
This URL is used to upload a signature file.

### Notes: ###
  * All images will be in PNG format.

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>sess_id: String - Session ID<br>
upfile: String - Name of uploaded file<br>
tip: Decimal - Tip amount<br>
trans_id: Integer - Transaction ID<br>
gateway: String - Transaction gateway<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/signature_image.asp?sess_id=1234&amp;upfile=MySign&amp;tip=5.5&amp;trans_id=123<br>
</code></pre>