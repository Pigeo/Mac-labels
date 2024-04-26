# Mac-labels

Ever wondered what does `MBA 15 SPG/8C CPU/10C GPU/16GB/1TB/KB-SF/BEL` means on the label sticker glued at the rear of your Mac's carton packaging?
![Understanding mac boxes labels](/build/Identifying%20Mac%20model%20and%20options%20from%20the%20package%20box%20label.jpg)

Be it for checking the hardware specifications of a second-hand Mac before buying it on the web, or verifying that the brand-new computer just delivered to you is exactly what was ordered from the supplier, this repository if for you!

## Contributing

1. Fork this repository
2. Update the `database.yml` with your examples
3. Send me a pull request

To avoid duplicating projects or initiatives, and to join our forces, if you know any other places on internet where such kind of information can be found, please let me know. 

TODO: would be nice if someone would take the time to program an automated way to generate the PDF in the `build/` folder from the content of the `database.yml` (and even nicer to automatically trigger update of the PDF each time a new commit is done on the main branch, thanks to GitHub actions...)

## About the Language Keyboard Codes

Unfortunately, the [Language Keyboard Codes](https://discussions.apple.com/docs/DOC-250006841) that can be found at the end of the Part Number (the two letters before the /A in the Part Number) are NOT the same thing.

For instance, a Mac sold in the USA with a US keyboard typically has its Part Number ending with `…LL/A` (`LL` = US English), whereas the label sticker on the carton packaging doesn't always mention the Part Number: it just says `MBA 15 SPG/16GB/1TB/KB-US`… On this particular example, it's pretty easy to determinate that it's the same thing, but on other keyboard layouts it's sometime a lot more difficult: how to determinate if `KB-SF/BEL` is the same than `…FC/A`? 

