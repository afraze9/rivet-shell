---
layout: layouts/base.njk
title: Rivet shell
---
{% include rivet-shell-switcher.njk %}

## Shell base
The default Rivet layout shell comes ready to use with any of the Rivet header variations and the Rivet footer. The _stage_ area will fill up the remaining vertical space and push the footer to the bottom of the browser window.

```html
<div class="rvt-shell">
  <div class="rvt-shell__stage">
    <!-- Main content "Stage" -->
  </div>
</div>
```

[Shell base demo](./rivet-shell-empty)

## Shell with page header
The shell also includes a pre-configured page-level header. The shell page header has a space for a page title, back/breadcrumb navigation, and an _actions_ area where you can use other Rivet controls like buttons and form inputs.

```html
<div class="rvt-shell">
  <div class="rvt-shell__stage">
    <div class="rivet-page-header">
      <!-- Page header content -->
    </div>
    <div class="rvt-p-all-md">
      <!-- Main content "Stage" -->
    </div>
  </div>
</div>
```

[Shell with page header demo](./rivet-shell-page-header-only)

## Shell sidebar
To offer even more flexibility, the Rivet shell also comes with a sidebar component that can be used to help layout out navigation and content.

```html
<div class="rvt-shell">
  <div class="rvt-shell__sidebar">
    <!-- Sidebar content -->
  </div>
  <div class="rvt-shell__stage rvt-p-all-md">
    <!-- Main content "Stage" -->
  </div>
</div>
```

[Shell sidebar demo](./rivet-shell-sidebar)

## More docs coming soon...