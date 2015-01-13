<h2>The STS9 equivalent of <a href="http://allthings.umphreys.com">All Things Umphreys</a></h2>
<p>Current plan is a Rails backend API with a Javascript frontend, unless someone has a good reason to do something different.</p>
<p>This is just an initial commit.  Currently, there's the beginning of a 1320 records site scraper (lib/tasks/scrape.rake) to pull the setlists from each STS9 show hosted there.  Maybe don't actually run it right now because it will hit their site 1376 times.  Next step is a parser for the setlist, as well as actual data modeling</p>
<h3>TODO</h3>
<ul>
  <li>Data Modeling/Schemas (Shows, Venues, Songs, etc)</li>
  <li>Scrapers for additional sites</li>
  <li>Strategies for conflict resolution when different site setlists don't match</li>
  <li>Testing</li>
  <li>Pick a frontend framework (probably AngularJS)</li>
</ul>

