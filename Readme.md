# PHP Storm Live Templates

##Installation

Place the XML file in the following folder depending upon your operating system.

OS X: ~/Library/Preferences/WebIde80/templates

Windows: &lt;your home directory&gt;\.&lt;product name&gt;&lt;version number&gt;\config\templates

Linux: ~/.&lt;product name&gt;&lt;version number&gt;/config/templates

I have not tested these paths on either Windows or Linux.

Once the file is in the correct place open PHP Storm. If it's open you'll probably have to restart it.

The templates should now work for you.
To check them out go to Preferences &gt; Editor &gt; Live Templates

##The Templates

###dd
Die and Dump

```
dd( $var );
```

###fform
Start a new Blade form

```
{!! Form::open() !!}

    $cursor$

{!! Form::close() !!}
```

###ftext
Text form field

```
<p>
    {!! Form::label('$name$' , '$label$') !!}
    {!! Form::text('$name$' , old('$name$') ) !!}
</p>
```

###femail
Email form field

```
<p>
    {!! Form::label('$name$' , '$label$') !!}
    {!! Form::email('$name$' , old('$name$') ) !!}
</p>
```

###ftel
Telephone form field

```
<p>
    {!! Form::label('$name$' , '$label$') !!}
    {!! Form::tel('$name$' , old('$name$') ) !!}
</p>
```

###fpassword
Password form field

```
<p>
    {!! Form::label('$name$' , '$label$') !!}
    {!! Form::password('$name$' , old('$name$') ) !!}
</p>
```

###fforeach
A Blade foreach block

```
/*
* Loop through the $things$ array
*/
@foreach ( $$$thing$s as $$$thing$ )

    $cursor$

@endforeach
```

##Whats missing?
I know there are a load of things I could add in and I will as I go.
Feel free to shout up.