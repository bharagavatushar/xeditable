# XEditable Lite
_A drop-in replacement for Bootstrap x-editable — modern popups & inline editing, searchable selects, AJAX, and more._

See `docs/` for API and usage. Examples are under `examples/`.

## Quick start
```html
<script src="xeditable.js"></script>
<span class="editable" data-type="text" data-name="username" data-title="Username">superuser</span>
<script>$('.editable').editable({ url: '/api/save' });</script>
```
