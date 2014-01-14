bootstrap-tag-cloud
===================

A simple Twitter Bootstrap style tag cloud generator. Initial version was written by CollectivePush.com

Example
-------
![](example.html)

![] (https://dl.dropboxusercontent.com/u/15923556/img/bootstrap-tag-cloud.jpg)


<p>Add and remove tags. Add an <code>id</code> of <code>id="tag"</code>, <code>id="tag-info"</code>, <code>id="tag-success"</code>, <code>id="tag-warning"</code>, <code>id="tag-danger"</code>, or <code>id="tag-inverse"</code> to the surrounding <code>&lt;div&gt;</code> of the <code>&lt;input&gt;</code> and <code>&lt;button&gt;</code> for bootstrap tag cloud styles.</p>

```HTML
<div id="tag-info" class="input-append" data-cloud-name="tag-cloud2">
  <input type="text">
  <button class="btn" type="button">Add <i class="icon-plus"></i></button>
</div>
<ul id="tag-cloud2"></ul>
```
Include bootstrap-tag-cloud.css in the &lt;head&gt;

```HTML
<link href="assets/css/bootstrap-tag-cloud.css" rel="stylesheet">
```

Include bootstrap-tag-cloud.js in the &lt;head&gt; or at the bottom of the page within the &lt;body&gt; for faster loading.

```HTML
<script src="assets/js/bootstrap-tag-cloud.js"></script>
```
