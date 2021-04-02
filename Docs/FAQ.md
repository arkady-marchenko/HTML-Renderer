**Why SVG images are not working?**
.NET doesn't support SVG format.
A workaround is to convert SVG to PNG during rendering, see [Rendering SVG images](Rendering-SVG-images).

**WPF support?**
Yep, WPF is fully supported.

**Mono support?**
Yep, Mono is fully supported.

**Silverlight support?**
Not currently but as WPF supported it won't be too hard to add, care to contribute?

**Metro, Xamarin, Unity or XNA support?**
I believe it can be done and won't be very hard.
Is it something that enough people would like to see?

**What about Java Script?**
Java script is extremely hard to support so it is not on the road-map.

**Why can't I navigate to a URL?**
HTML Renderer is not a web-browser.

**Can I generate image from HTML?**
Yep, see [Image generation](Image-generation).

**Can I generate PDF document from HTML?**
Yep, see [PDF generation](PDF-generation).
Currently powered by [PdfSharp](http://www.pdfsharp.net/?AspxAutoDetectCookieSupport=1) but it is quite easy to add more frameworks like [iTextSharp](http://sourceforge.net/projects/itextsharp/)

**Can you sign the library with strong-name?**
No, strong name is the devil ([Strong Name signing is a huge religious war](https://github.com/octokit/octokit.net/issues/405)).
You can sign the dll yourself, see [Adding a Strong Name to an existing DLL](http://www.geekzilla.co.uk/ViewCE64BEF3-51A6-4F1C-90C9-6A76B015C9FB.htm).

**Can I contribute?**
Sure! go to [ArthurHub/HTML-Renderer](https://github.com/ArthurHub/HTML-Renderer) on GitHub and fork away.


