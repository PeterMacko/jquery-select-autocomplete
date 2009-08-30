# jQuery Select Autocomplete

jQuery Select Autocomplete lets you turn an HTML `<select>` tag into an auto-complete text input box.

You use it like this: $(select.autocomplete).select-autocomplete();

You can also pass in options that are passed on to jquery.autocomplete, including a 'url' option, for using an Ajax request for the data, rather than the select's option list.  To use this you will probably want to set the dataType option to 'json' and provide the parse option to convert the json for jquery.autocomplete.

### Example

See `index.html` for a working example.

## License

License is MIT. See LICENSE file.

## Todo

* figure out if there's a way to automagically manage the dependency on jquery.autocomplete
