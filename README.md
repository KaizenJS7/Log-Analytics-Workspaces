# Log-Analytics-Workspaces

Let's have a look at the practical application of log analytics workspace and for that we simply select/search for <b>Log Analytics Workspaces</b>, and we select the workspace we created and look at the resource.

 <img src="https://i.imgur.com/gTuPSB5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

What we see is all metadata regards to our log analytics workspace. That is for example the resource group, subscription, tags, workspace ID, pricing tier, and so on. That is the case for every Azure resource but Log Analytics is a bit different in the sense that we of course not only see metadata, but of course we also want to work with logs that we ingest. And for that we can click on <b>Logs</b>.

 <img src="https://i.imgur.com/QDgINvp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

What we see is the representation of the tables that we decided to ingest already in Sentinel. What we can do from here is we can select a table, for example the <b>Threat Intelligence Indicator</b> table and double click it. Then the table will be pre-provisioned as part of a query. We can click <b>Run</b> to execute the query and we will get results for them.

 <img src="https://i.imgur.com/pE2c736.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
