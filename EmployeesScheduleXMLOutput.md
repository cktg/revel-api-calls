# Introduction #

_{domainname}/device/xmloutput/timesheet.asp?_
This URL is used to get employees time schedule as XML.

### Notes: ###
  * LocationID parameter is mandetory
  * If pin is sent, only the relevent data will be shown; else all data
  * Data output will show only dates ranging from yesterday and 14 days ahead

<br>

<h1>Details</h1>

URL parameters are:<br>
<pre><code>locationid : Integer - Location ID<br>
flag: Integer - Type of data (1 for timesheet and 2 for timeworked)<br>
pin: Integer - Employee PIN number<br>
nextweek: Boolean - Is this report for next week? (0 for current week and 1 for next week)<br>
</code></pre>

<h3>Example</h3>
<pre><code>http://www.mydomainname.com/device/xmloutput/timesheet.asp?locationid=111&amp;flag=1&amp;pin=123456&amp;nextweek=1<br>
</code></pre>