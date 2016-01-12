# MyClippings
Work with Amazon Kindle bookmarks and highlights in InterSystems Caché

## Installation

Import [MyClippings.Item](https://raw.githubusercontent.com/eduard93/MyClippings/master/MyClippings/Item.cls.xml) into any namespace and compile it.

## Use

1. Import your MyClippings.xml via `Write ##class(MyClippings.Item).Import(/path/to/MyClippings.txt)
2. Work with imported items via SQL, globals, objects. Try: `Do ##class(MyClippings.Item).Beautify()`
3. Export results  with: `Write ##class(MyClippings.Item).Export(/path/to/MyClippings.txt)`
