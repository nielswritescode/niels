---
title: 🔒Restricted Section
layout: default
parent: Missing Manual (in development)
---
<div id="rg-gate">
  <p style="font-weight:600;margin-bottom:8px;">Before you read on</p>
  <p style="margin-bottom:20px;">Simply knowing about this content might be triggering. Please make a conscious decision whether you want to view this page.</p>
  <button onclick="rgReveal()" style="padding:8px 20px;cursor:pointer;">I understand, show the page</button>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var gate = document.getElementById('rg-gate');
  var el = gate.nextElementSibling;
  while (el) { el.style.display = 'none'; el = el.nextElementSibling; }
});
function rgReveal() {
  var gate = document.getElementById('rg-gate');
  var el = gate.nextElementSibling;
  while (el) { el.style.display = ''; el = el.nextElementSibling; }
  gate.style.display = 'none';
}
</script>

_This page was last updated on: 20th of June 2026_

There are some MM pages that I wouldn't want to post publicly. Feel free to request them personally - but they do need trust building first :). (I haven't actually written them yet but would love to talk more about these topics)

Restricted pages:

- My relationship to suicide
- Conscious kink exploration