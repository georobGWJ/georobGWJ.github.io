# georobGWJ.github.io README
GitHub Pages Repository

For Dev Bootcamp Solo Challenge 2.5, I created a website about the Bay Bridge. The bulk of the content lives inside of index.html. A second page, caltrans_site_eval.html, was created in order to evaluate a similar website and is linked to from index.html.

The meanings of tags and attributes that I used are described below.

```
<!DOCTYPE html>
<html lang="en">
```

This is a standard html page opening. DOCTYPE tells a browser or interpreter that the page is html. lang="en" tells the browser that the language is english.

```
  <head>
    <title>Bay Bridge</title>
  </head>
```

Standard html head tag. This title is what the browser tab will be labeled.

```<body>
```

The body tag opens the main body of the page.

```
<h1>San Francisco - Oakland Bay Bridge:<br />
        The Best Bridge in the Bay Area</h1>
```

I used Header 1 to make the primary title for the page content.

```
    <section>
      <h2>Description</h2>
      <p>
        words
      </p>
    </section>
```

The section tag creates sections in a document, such as chapters, headers, footers, or any other sections of the document. Since I had four main pieces of content, I encapsulated them in sections. h2 is Header 2 and p is a paragraph.

 
```   <figure>
        <img src="images/bay_bridge_at_night.jpg" alt="Bay Bridge at Dusk" height="640" width="955" />
        <figcaption>Bay Bridge at Dusk</figcaption>
      </figure>
```

The figure can tag specifies self-contained images. It can also encapsulate content like illustrations, diagrams, code listings, and more.

The img tag inserts an image file. I added height and width attributes to resize the image since the original image was too wide to fully display on my screen.

The figcaption tag created a caption for an associated image. If img and figcaption are used together they must be encapsulated in a figure tag block.

```<hr>
```

The hr tag creates a horizontal rule like. I used it to make it easier to see where sections ended.

  
```   
      <table border = 1>
        <tr>
          <th colspan = 4>West Bay Suspension Bridge</th>
        </tr>
        <tr>
          <th>Length</th>
          <th>Vertical Clearance</th>
          <th>Span Length</th>
          <th>Tower Height</th>
        </tr>
        <tr>
          <td align="center">9,260 ft</td>
          <td align="center">220 ft </td>
          <td align="center">2,310 ft</td>
          <td align="center">526 ft</td>
        </tr>
      </table>
```

This is the code for a table. The table tag encapsulates the table. tr tags are rows. th tags are column headers. The colspan attribute tells the browser how many columns the element should span. The align attribute tells the browser how to position the content within the element.

        

```   <ul>
        <li>Deepest Bridge Pier: 242 feet below water level - 396 feet high</li>
        <li>Tunnel: Largest bore tunnel in the world: 76 ft wide, 58 ft high, 1700 ft long</li>
        <li>Opened: November 12, 1936</li>
        <li>Cost: $77 million (Including Transbay Transit Terminal)</li>
        <li>Avg. Daily Traffic: 270,000 vehicles</li>
      </ul>
```

ul creates an unordered list and li encapsulates list elements.



```   
      <form action="http://httpbin.org/get">
        <b>Did this site provide the information you wanted?</b><br />
        <input type="radio" name="info_rating" value="yes"> Yes!<br />
        <input type="radio" name="info_rating" value="maybe"> Kind of...<br />
        <input type="radio" name="info_rating" value="no"> Nope.<br /><br />
        <b>What would you recommend to improve the site?</b><br />
        <input type="text" name="suggestions" size="120"><br /><br />
        <button type="submit">Submit</button>
      </form>
```

I created a simple form block for a page rating form. The action attribute tells the browser where to pass the data to and go to once the form is submitted. The input tag defines user input elements. The type attribute indicates the kind of input (radio buttons, text, passwords, etc.). The name attribute is the 'variable' name that will be passed to the page defined by the action tag. The value tag for radio buttons indicates the content of the 'variable', in this case it will pass "yes", "maybe", or "no". For the text input field the size attribute indicates the maximum length that the input can be. The button tag provides a means of submitting the form since type="submit". This triggers the action page.

``` <nav>
      <h2>Additional Links</h2>
      <a href="caltrans_site_eval.html"><b>My Evaluation of a Similar Bay Bridge Website</b></a>
    </nav>
```

nav blocks are typically used to provide links or other navigational items. The a tag encapsulates links


```<footer>
     <h3>Image Sources</h3>
     <cite>
       <p>
         Thanks to <a href="http://baybridgeinfo.org/visit-bridge">Caltrans</a> for the image of the <a href="http://baybridgeinfo.org/sites/default/files/imagecache/fullscreen_bg/images/background/front/new_front4.jpg">Bay Bridge at Dusk</a>
       </p>
     </cite>
   </footer>
```

The footer tag semantically tags the block as a footer and the cite tag semantically tags the contents it encapsulates as citations.
