# fuseautocomplete README

Fuse Markup AutoComplete.
Type the name of the tag you want to use. Like: StackPanel. 
FuseAutoComplete will generate the following code:

Example:

Type `StackPa` then select the StackPanel option:

```
<StackPanel|>
    |
</StackPanel>
```

Your typing cursor will be on two positions. By default it will appear on the first pipe. If you press the tab button, your cursor will move to the second pipe on the example

If you type the tag name with `\` at beginning like: `\StackPanel` you will get a single tag:

```
<StackPanel />
```

Type properties for ux:Class, are able to autocomplete like writing `string` will turn into:

```
<string ux:Property="|" />
```

UX atributes, like `ux:Class` are also able to autocomplete with a list. Writing `ux:` you will get a list with: `ux:Name, ux:Class, ux:Property` etc.

## Features

- Auto complete and indexing tags.

## Requirements

Please, note that to the markup be highlight you need to use Fuse language extension

## Known Issues

No one

## Repository

https://github.com/JonataCSantos/FuseAutoComplete

## Release Notes

Type tags from Fuse UX to autocomplete.

### 1.0.0

Initial release of Fuse Auto Complete Markup

