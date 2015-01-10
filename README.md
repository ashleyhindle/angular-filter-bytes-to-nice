# angular-filter-bytes-to-nice
Filter to convert bytes to nice (X MB, X GB, X TB)


## Installation
`bower install theahindle/angular-filter-bytes-to-nice`

Add to `<head>`:
```
<script src="components/angular-filter-bytes-to-nice/angular-filter-bytes-to-nice.js"></script>
```

Add 'bytesToNice' to `angular.module("myApp", ['bytesToNice'])`:

## Usage

**Use it!**: `{{ usedDiskSpaceInBytes | bytesToNice }}`


### Options
You can pass two arguments to bytesToNice
```
{{usedDiskSpaceInBytes | bytesToNice:precision, unitSize
```
`precision` defaults to 1 and `unitSize` defaults to 1024
