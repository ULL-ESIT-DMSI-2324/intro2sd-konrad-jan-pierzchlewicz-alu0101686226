---
layout: error 
permalink: /search/
title: Search
---

<h1>Search</h1>

<form id="search-form" action="">
  <label class="label" for="search">Search term (accepts a regex):</label>
  <br/>
  <input class="input" id="search" type="text" name="search" 
        autofocus 
        placeholder="e.g. Promise" 
        autocomplete="off">

  <ul class="list  list--results" id="list">
  </ul>
</form>

< script type="text/javascript" src="/assets/src/fetch.js"></script>
< script type="text/javascript" src="/assets/src/search.js"></script>

< script type="text/javascript">
  const search = new JekyllSearch(
    '{{site.url}}/assets/src/search.json',
    '#search',
    '#list',
    '{{site.baseurl}}'
  );
  search.init(); 
</script>