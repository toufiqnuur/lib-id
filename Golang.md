#Golang
Go adalah bahasa pemrograman yang dibuat di Google pada tahun 2009 oleh Robert Griesemer, Rob Pike, dan Ken Thompson. Golang adalah bahasa pemrograman yang dihimpun dan diketik dalam bahasa C, dengan fitur pengumpulan sampah, penulisan terstruktur, keamanan memori, dan pemrograman yang konkuren serta berurutan.

##Instalasi
Instal golang ditermux menggunakan perintah
```pkg install golang```
Atau bisa juga dengan perintah
```apt install golang```

##Build
Cara menjalankan atau build golang bisa mengguanakan perintah
```go build namafile.go```
Misal saya mempunyai file hello.go yang berisi
```
package main

import "fmt"

func main() {
 fmt.Println("Hello World")
}
```
Kemudian saya build dengan perintah
```go build hello.go```
Maka setelah dijalankan akan tercetak tulisan
```Hello World```
