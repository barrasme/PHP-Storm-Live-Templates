# Laravel 5 Blade Templates

A set of templates to help you with you Laravel 5 development specifically for Blade

### Blade Yield
`bladeyield`

Will generate a yield command to be used in a layout or master view

```
@yeild('content')
```

### Blade Section
`bladesection`

Will generate a section command

```
@section('content')

    $END$
    
@stop
```

### Blade Extend
`bladeextend`

Will generate the command to extend a master view or layout

```
@extends('app')
```

### Blade Include
`bladeinclude`

Will generate a blade syntax include function

```
@include('')
```

### Blade Form
`bladeform`

Will generate an empty form in the blade syntax

```
{!! Form::open() !!}

    $END$

{!! Form::close() !!}
```

### Blade Form Field
`bladeformfield`

Will generate a form field, wrapped in a paragraph and include an error block, you can also apply classes to each element.

```
<p class='$rowCLass$'>

    {{ Form::label('$name$', '$Nice_name$') }}

    {{ Form::$type$('$name$', null , array( 'class' => '$inputClass$')) }}

    {{ $errors->first('$name$', '<p class="$errorClass$">:message</p>') }}

</p>

```

### Blade Submit Button
`bladesubmit`

Will generate a submit button for your form

```
<p>

    {!! Form::submit('$label$') !!}

</p>
```


### Blade Errors
`bladeerrors`

Will generate an error block to be used in any of your views.

```
@if (count( $errors ) > 0)

    <div class="form-errors">

        <p>

            <strong>Whoops!</strong> Something went wrong.

        </p>


        <ul>

            @foreach ($errors->all() as $error)

            	<li>{{ $error }}</li>

            @endforeach

        </ul>

    </div>
    
@endif
```

### Blade Foreach
`bladeforeach`

Will generate a foreach block in blade syntax

```
/*

* Loop through the $things$ array

*/

@foreach ( $$$thing$s as $$$thing$ )

    $END$

@endforeach
```

### Blade For
`bladefor`

Will generate a For loop

```
@for ($i = 0; $i < $counter$; $i++)

    $END$

@endfor
```

### Blade While
`bladewhite`

Will generate a While loop

```
@while ( $condition$ )
    
    $END$
    
@endwhile
```

### Blade If
`bladeif`

Will generate an IF block

```
@if ( $condition$ )

	$END$

@endif
```

### Blade If / Else
`bladeifelse`

Will generate an IF ELSE block

```
@if ( $condition$ )

	$END$

@else


@endif
```

### Blade Unless
`bladeunless`

Will generate an unless block

```
@unless ( $condition$ )
    
    $END$
    
@endunless
```

### Blade Comment
`bladecomment`

Will generate a comment block that will not be rendered in HTML

```
{{-- $comment$ --}}
```
