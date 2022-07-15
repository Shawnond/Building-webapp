# Building-webapp
frontend learning
## what happens when you click a search botton?
1.web browser send request for index.html file located at http://www.google.com address.

2.web server looks up its directory content for the specific file, opens it, sending content of that file back to web browser.

3.web browser then revieves content of index.html file, which is text marked up with HTMl codes, and renders the contents based on these HTML codes.

```
<img alt="Google" src="/images/srpr/logo4w.png"
    width="275" height="95">    
```
              
The <img> tag provides attributes that tell the browser the file source location (src), alternate text (alt), width (width), and height (height) necessary to display the logo.

4.browser will check src attribute in <img> tag to find source location the image in logo4w.png can be found in the images directory at the same web address (www.google.com) from which the browser retrieved the HTML file

5.interms of resource file like img or video, the browser will also send request to webserver under address 
```
 http://www.google.com/images/srpr/ logo4w.png.
```

6. webserver interprets this request and respond contents that the browser requests.

7. image contents appeares in browser.

