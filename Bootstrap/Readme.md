# Bootstrap templates

A set of live templates for bootstrap version 3.3.4

## Getting Bootstrap via CDN

### Bootstrap CSS
`bcss`

Will generate a link to the Boostrap CSS on MaxCDN

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
```

### Bootstrap JavaScript
`bjs`

Will generate a link to the Bootstrap JS on MaxCDN

```
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
```

### Container
`bcontainer`

Will generate a container block

```
<div class="container">


</div>
```

### Row
`brow`

Will generate a row

```
<div class="row">


</div>
```

### Column
`bcol`

Will generate a column

```
<div class="col-sm-X col-md-X col-lg-X">
	

</div>
```

### Table
`btable`

Will generate a table, all options are enabled by default

```
<table class="table table-hover table-bordered table-striped">

    <thead>

        <tr>

            <td>$column1title$</td>

            <td>$column2title$</td>

        </tr>

    </thead>

    <tfoot>

        <tr>

            <td>$column1title$</td>

            <td>$column2title$</td>

        </tr>

    </tfoot>

    <tbody>

        <tr>

            <td>$column1data$</td>

            <td>$column2data$</td>

        </tr>

    </tbody>

</table>
```

### Form Field
`bformfield`

Will generate a form row, wrapped in a div. The snippet will attempt to generate nice labels

```
<div class="form-group">

    <label for="$name$">$Nice_name$</label>

    <input type="$type$" class="form-control" id="$name$" placeholder="Please enter your $placeholder$">

</div>

```

### Submit button
`bsubmit`

Will generate a submit button

```
<div class="form-group">

    <button type="submit" class="btn btn-default">$buttonText$</button>

</div>
```

### Default Button
`bbutton`

Will generate a default button

```
<button type="button" class="btn btn-default">$text$</button>
```

### Primary Button
`bbuttonprimary`

Will generate a primary button

```
<button type="button" class="btn btn-primary">$text$</button>
```

### Info Button
`bbuttoninfo`

Will generate a info button

```
<button type="button" class="btn btn-info">$text$</button>
```

### Warning Button
`bbuttonwarning`

Will generate a warning button

```
<button type="button" class="btn btn-warning">$text$</button>
```

### Success Button
`bbuttonsuccess`

Will generate a success button

```
<button type="button" class="btn btn-success">$text$</button>
```

### Danger Button
`bbuttondanger`

Will generate a danger button

```
<button type="button" class="btn btn-danger">$text$</button>
```



