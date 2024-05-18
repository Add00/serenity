## Name

xml - parse and dump XML files

## Synopsis

```**sh**
$ xml [--color] [--only-contents] [--run-tests] <file>
```

## Description

`xml` command parses the provided XML file and displays its contents in a human readable format.

## Options

* `--help`: Display help message and exit
* `--version`: Print version
* `-c`, `--color`: Syntax highlight the output
* `-o`, `--only-contents`: Only display markup and text
* `-t`, `--run-tests`: Run tests

## Examples

```sh
$ xml document.xml
<?xml version='1.0'?>
<document>
    <title>C Programming Language</title>
    <authors>Brian W. Kernighan; Dennis M. Ritchie</authors>
    <published>1978-02-22</published>
</document>
```

```sh
$ xml -o document.xml
<document>
    <title>C Programming Language</title>
    <authors>Brian W. Kernighan; Dennis M. Ritchie</authors>
    <published>1978-02-22</published>
</document>
```
