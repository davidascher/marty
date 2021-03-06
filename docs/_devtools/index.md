---
layout: default
sectionid: devtools
---

<div class="container devtools">
  <h1>Marty Developer Tools (Beta)</h1>
  <a href="https://chrome.google.com/webstore/detail/marty-developer-tools/fifcikknnbggajppebgolpkaambnkpae?hl=en">Marty Developer Tools</a> is an extension to Chrome's developer tools. It shows you the current state of your stores and how actions flow through the stores to the views.

  <p style="text-align:center; margin-top: 20px">
    <a class="btn btn-default" href="https://chrome.google.com/webstore/detail/marty-developer-tools/fifcikknnbggajppebgolpkaambnkpae?hl=en">Download from Chrome Web Store</a>
  </p>

  <img src="/img/devtools-data-flow.png" alt="Marty Developer Tools"/>

  For Marty Developer Tools to work, you add Marty to the window object (<code>window.Marty = require('marty')</code>). Once you've done that, open your app in Chrome and open Chrome Developer Tools. You should see a new 'Marty' tab which gives you a view into what your application is doing.

</div>