# Optimize Media Assets

- There are three tools to consider when using media, such as images, on your web pages: the size, the format, and the compression.

## Size:

- Let's talk about the size of your images first. 
- When we are building a website, we'll often style images to display in a specific size. For example, we might have an image display at a 
`640x480` resolution. `640 represents the width` while `480 represents the height` in pixels. When preparing our image we want to scale it to 
a `640x480 `size to match that styling. If we serve an image that is `1920x1080` but you are styling it to be much smaller, we're requiring our 
users to download unnecessary data. A smaller resolution results in a smaller file size.


## File Format:

- The next thing to consider is your file format. Two of the most common file formats are PNG and JPG, but these are no longer the most 
ideal formats for serving images. Unless you need support for older browsers, you should consider using a more optimized format, 
like WEBP or AVIF.


## Compression Algorithm

- Finally, we can run compression algorithms on our images. A compression algorithm is used to reduce the size for files or data. 
There are options like `pngcrush` to compress our images locally, or we can use online compression tools. However, it's worth noting that 
specific file formats, such as JPG, are not lossless. Lossless means that the original data can be perfectly reconstructed from the 
compressed data. If you try to compress a JPG image, it will result in a degraded quality. we should keep all these things in mind when 
selecting images for your web pages.

