# go

The **go** language (Golang) was created at Google by Griesemer, Pike & Thompson and launched in 2009. While it originated at Google, Go is now an open-source language and has a broad community of users and contributors outside of Google. 

Go is both beginner-friendly and usable by professionals. 

Here is a sample go program:
```go
package main

import (
        "fmt"
        "time"
)

func main() {
        // Create a whimsical greeting
        greeting := "🌟 Hello, World! 🌍"

        // Add a touch of magic with a delay
        fmt.Println("✨ Preparing to say hello...")
        time.Sleep(2 * time.Second)

        // Display the greeting
        fmt.Println(greeting)

        // A professional touch with a closing statement
        fmt.Println("This message is brought to you by the wonders of Go programming!")
}
```

Official link: https://go.dev
