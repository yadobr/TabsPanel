# TabsPanel
TabsPanel it's a simple and lightweight tabs panel script written in pure javascript.
Only ~1.3kb!

[DEMO](https://yadobr.github.io/tabspanel/)

# Getting Started
 - In your HTML:
```html
<!-- css -->
<link href="css/TabsPanel.css" rel="stylesheet">

<!-- js -->
<script src="js/TabsPanel.js"></script>

<!-- html -->
<div class="tabs-panel">
	<!-- TABS TITLES -->
	<div class="tab-title tab-title-active">Document</div>
	<div class="tab-title">Font and Text</div>
	<div class="tab-title">Images and Figures</div>
	<div class="tab-title">Tables</div>
	<!-- TABS CONTENT -->
	<div class="tab-content tab-content-active">Document</div>
	<div class="tab-content">Font and Text</div>
	<div class="tab-content">Images and Figures</div>
	<div class="tab-content">Tables</div>
</div>
```
 - Call the script:
```js
<script>
window.onload = function()
{
	// CREATE A TABS PANEL
	tabsPanel = new TabsPanel();
}
</script>
```
# License
MIT
