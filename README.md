# ut-google-bigquery
<h1 id="Introduction" data-renderer-start-pos="1286">Introduction</h1>
<p data-renderer-start-pos="1300">This Universal Task&nbsp;allows&nbsp;Stonebranch&nbsp;users&nbsp;to schedule, trigger, monitor, and orchestrate the Google BigQuery process&nbsp;directly&nbsp;from the Universal&nbsp;Controller.&nbsp;&nbsp;</p>
<h1 id="Overview" data-renderer-start-pos="1464">Overview</h1>
<ul class="ak-ul" data-indent-level="1">
<li>
<p data-renderer-start-pos="1476">This task uses&nbsp;python modules google-cloud-bigquery <span data-renderer-mark="true">and </span>google-auth to make REST-API calls to Google BigQuery</p>
</li>
<li>
<p data-renderer-start-pos="1589">This task will use the GCP Project ID, BigQuery SQL or Schema, Dataset ID, Job ID, Location, Table ID, Cloud Storage URI, <span data-renderer-mark="true">and </span>Source File Format as parameters of BigQuery function<span data-renderer-mark="true">,</span> and GCP KeyFile (API KEY) of Service account for authenticating the REST-API calls to Google BigQuery.</p>
</li>
<li>
<p data-renderer-start-pos="1876">User can perform the <span data-renderer-mark="true">following </span>Google BigQuery operations:</p>
<ul class="ak-ul" data-indent-level="2">
<li>
<p data-renderer-start-pos="1938">BigQuery SQL</p>
</li>
<li>
<p data-renderer-start-pos="1954">List dataset</p>
</li>
<li>
<p data-renderer-start-pos="1970">List tables in dataset</p>
</li>
<li>
<p data-renderer-start-pos="1996">View job information</p>
</li>
<li>
<p data-renderer-start-pos="2020">Create a dataset</p>
</li>
<li>
<p data-renderer-start-pos="2040">Load local file to a table</p>
</li>
<li>
<p data-renderer-start-pos="2070">Load cloud storage data to a table</p>
</li>
<li>
<p data-renderer-start-pos="2108">Export table data</p>
</li>
</ul>
</li>
</ul>  
<p>&nbsp;</p>
Please visit this link to find key features, prerequisites, installation instructions, configuration instructions, and examples of how to use this integration. 
<a href="https://docs.stonebranch.com/confluence/display/UC69/UAC+-+Google+BigQuery">Google BigQuery</a>.&nbsp;</li>
