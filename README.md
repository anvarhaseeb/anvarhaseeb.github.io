# Heading level 1	<h1>Heading level 1</h1>	Heading level 1

## Heading level 2	<h2>Heading level 2</h2>	Heading level 2

### Heading level 3	<h3>Heading level 3</h3>	Heading level 3

#### Heading level 4	<h4>Heading level 4</h4>	Heading level 4

##### Heading level 5	<h5>Heading level 5</h5>	Heading level 5

###### Heading level 6	<h6>Heading level 6</h6>	Heading level 6



Paragraphs

Markdown	HTML	Rendered Output

I really like using Markdown.



I think I'll use it to format all of my documents from now on.	<p>I really like using Markdown.</p>



<p>I think I'll use it to format all of my documents from now on.</p>	I really like using Markdown.

I think I'll use it to format all of my documents from now on



Line Breaks

To create a line break or new line (<br>), end a line with two or more spaces, and then type return.

Markdown	HTML	Rendered Output

This is the first line.  

And this is the second line.	<p>This is the first line.<br>

And this is the second line.</p>	This is the first line.

And this is the second line.



Bold

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

Markdown	HTML	Rendered Output

I just love **bold text**.	I just love <strong>bold text</strong>.	I just love bold text.

I just love __bold text__.	I just love <strong>bold text</strong>.	I just love bold text.

Love**is**bold	Love<strong>is</strong>bold	Loveisbold



Markdown	HTML	Rendered Output

Italicized text is the *cat's meow*.	Italicized text is the <em>cat's meow</em>.	Italicized text is the cat’s meow.

Italicized text is the _cat's meow_.	Italicized text is the <em>cat's meow</em>.	Italicized text is the cat’s meow.

A*cat*meow	A<em>cat</em>meow	Acatmeow



Bold and Italic

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

Markdown	HTML	Rendered Output

This text is ***really important***.	This text is <strong><em>really important</em></strong>.	This text is really important.

This text is ___really important___.	This text is <strong><em>really important</em></strong>.	This text is really important.

This text is __*really important*__.	This text is <strong><em>really important</em></strong>.	This text is really important.

This text is **_really important_**.	This text is <strong><em>really important</em></strong>.	This text is really important.

This is really***very***important text.	This is really<strong><em>very</em></strong>important text.	This is reallyveryimportant text.



Ordered Lists

To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

Markdown	HTML	Rendered Output

1. First item

2. Second item

3. Third item

4. Fourth item	<ol>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item</li>

  <li>Fourth item</li>

</ol>	1.	First item

2.	Second item

3.	Third item

4.	Fourth item

1. First item

1. Second item

1. Third item

1. Fourth item	<ol>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item</li>

  <li>Fourth item</li>

</ol>	5.	First item

6.	Second item

7.	Third item

8.	Fourth item

1. First item

8. Second item

3. Third item

5. Fourth item	<ol>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item</li>

  <li>Fourth item</li>

</ol>	9.	First item

10.	Second item

11.	Third item

12.	Fourth item

1. First item

2. Second item

3. Third item

    1. Indented item

    2. Indented item

4. Fourth item	<ol>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item

    <ol>

      <li>Indented item</li>

      <li>Indented item</li>

    </ol>

  </li>

  <li>Fourth item</li>

</ol>	13.	First item

14.	Second item

15.	Third item

a.	Indented item

b.	Indented item

16.	Fourth item



Markdown	HTML	Rendered Output

- First item

- Second item

- Third item

- Fourth item	<ul>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item</li>

  <li>Fourth item</li>

</ul>	•	First item

•	Second item

•	Third item

•	Fourth item

* First item

* Second item

* Third item

* Fourth item	<ul>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item</li>

  <li>Fourth item</li>

</ul>	•	First item

•	Second item

•	Third item

•	Fourth item

+ First item

+ Second item

+ Third item

+ Fourth item	<ul>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item</li>

  <li>Fourth item</li>

</ul>	•	First item

•	Second item

•	Third item

•	Fourth item

- First item

- Second item

- Third item

    - Indented item

    - Indented item

- Fourth item	<ul>

  <li>First item</li>

  <li>Second item</li>

  <li>Third item

    <ul>

      <li>Indented item</li>

      <li>Indented item</li>

    </ul>

  </li>

  <li>Fourth item</li>

</ul>	•	First item

•	Second item

•	Third item

o	Indented item

o	Indented item

•	Fourth item







1. First item

2. Second item

3. Third item    

           - Indented item    

           - Indented item

4. Fourth item





The rendered output looks like this:

17.	First item

18.	Second item

19.	Third item

o	Indented item

o	Indented item



Adding Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).



Adding tittle for links on hover

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").



Adding links with font 

I love supporting the **[EFF](https://eff.org)**.This is the *[Markdown Guide](https://www.markdownguide.org)*.See the section on [`code`](#code).





Images

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")



Linking Images

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.



[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)








