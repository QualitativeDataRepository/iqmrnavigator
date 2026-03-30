---
layout: page
title: Search
---

<link href="/pagefind/pagefind-ui.css" rel="stylesheet" />

<div id="search" class="mt-3"></div>

<script>
  function initSearch() {
    new PagefindUI({
      element: '#search',
      showImages: false,
      excerptLength: 30
    });
    var q = new URLSearchParams(window.location.search).get('q');
    if (q) {
      setTimeout(function () {
        var input = document.querySelector('.pagefind-ui__search-input');
        if (input) {
          input.value = q;
          input.dispatchEvent(new Event('input', { bubbles: true }));
        }
      }, 50);
    }
  }

  function searchUnavailable() {
    document.getElementById('search').innerHTML =
      '<p class="text-muted">Search index not available in local development. ' +
      'Run <code>bundle exec jekyll build &amp;&amp; npx pagefind --site _site</code> to enable search.</p>';
  }
</script>
<script src="/pagefind/pagefind-ui.js" onload="initSearch()" onerror="searchUnavailable()"></script>
