# alfa-databinding

### databinding for HTML Elements

A value can be bound to any HTML Element. When user enters a value into <input> box, all other HTML Elements with the same bound_path will display the value.

```html
<input bound_path="ds.arg01"> 
<span bound_path="ds.arg01">
```

A value selected from dropdown will be assigned to all HTML Elements matching bound_path_out

```html
<input type="search" list="data-lst" bound_path_out="ds.selected">
<span bound_path="ds.selected">
```

## how it works

<img src="./docs/alfaDatabinding 1-initialization.png">

<img src="./docs/alfaDatabinding 2-notifySubscribers.png">
