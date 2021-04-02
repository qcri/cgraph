# Quick Start

## cGraph: Color codes of the Network Graph

There can be 4 types of domain nodes in our graph.
<ol>
<li>Benign - These are clean sites</li>
<li>Compromised - These are used to be clean site but now hacked by attackers</li>
<li>Malicious - These are attack sites created by attackers</li>
<li>Unknown - The status of the site is not known (as we do not have sufficient information)</li>
</ol>

We are using Diffrent color nodes for these for domain types.
<ol>
<li>Benign domains
</li>
We mark a domain as benign if all of the following conditions are satisfied
<ul>
<li>Alexa rank is below 100K and appeared in Alexa top 1m for at least two weeks</li>
<li>Domain or URL(s) does not have VT positive (VT >= 1) for the day</li>
</ul>

If the above conditions are satisfied we are using the color <span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #0e6b0e;"></span>


<li>Compromised domains</li>
We mark a domain as Compromised if all of the following conditions are satisfied

<ul>
<li>Alexa rank is below 100K and appeared in Alexa top 1m for at least two weeks</li>
<li>Domain or URL(s) has VT positive (VT >= 1) for the day</li>
</ul>

If the above conditions are satisfied we are using the color <span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #FFA500;"></span>


<li>Malicious domains</li>
We will consider only VT >= 2 as malicious. Further, these domains do not have Alexa rank below 100k for at least two weeks.
<ul>
<li><span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #EA3B52;"></span> For VT = 2.</li>
<br />
<li><span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #FF2400;"></span> For VT 3 and 4.</li>
<br />
<li><span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #BA110C;"></span> For VT between 5 and 9.</li>
<br />
<li><span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #800000;"></span> VT 10 or more.</li>
<br />
</ul>
</ol>
<br />
<span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #767676;"></span> For Unkown Domains.
<br />
<span style="height: 25px;width: 25px; border-radius: 50%;display: inline-block;background-color: #1f49f0;"></span> For IP address.
<br />
<br />

