# Laravel 5 PHP Templates

A set of templates to help you with you Laravel 5 development specifically for PHP code

### Die and Dump
`dd`

Will generate a Laravels Die and Dump block

```
dd( $var$ );
```

## Routing

### Route to method
`route`

Will generate a route call to a method

```
Route::get('$path$', [ 'uses' => '$controller$' , 'as' => '$routeName$'] );
```

### Route Post
`routepost`

Will generate a route call to a method after a post

```
Route::post('$path$', [ 'uses' => '$controller$' ] );
```

### Route Closure
`routeclosure`

Will generate a route closure

```
Route::get('$path$', function()

{

    return '$END$';

});
```

### Route Group
`routegroup`

Will generate a route group

```
Route::group(['middleware' => '$middleware$' , 'prefix' => '$prefix$' ], function()

{

	$END$

}
```