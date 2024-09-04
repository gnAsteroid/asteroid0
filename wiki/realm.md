## Realms

**Realms** are how stateful [packages](packages.md) are called in the [GNO](GNO.md) language.

Here is a short example (TODO improve):

```go
package hello

function Render(path string) string {
    s := "Hello world. This is my TODO list:\n"
    s += "\n"
    s += "* [ ] write GNO apps\n"
    s += "* [ ] conquer the world\n"
    return s
}
```

The Render function returns a string in [Markdown](markdown.md). 

This would be rendered as:

----

Hello world. This is my TODO list:

* [ ] write GNO apps
* [ ] conquer the world

-----

You may copy-paste the above and experiment on https://play.gno.land
