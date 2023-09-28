# SOLUTION

## HTML Entities

- Some characters are reserved in HTML.
- HTML entities are special codes or sequences of characters used to represent characters or symbols in HTML documents. 
- They are necessary because some characters have special meanings in HTML, and using their raw form may lead to parsing errors or unintended rendering. 
- HTML entities start with an ampersand (&) and end with a semicolon (;).
- If you use the less than (<) or greater than (>) signs in your text, the browser might mix them with tags.
- Character entities are used to display reserved characters in HTML.

- A character entity looks like this:

                &entity_name;
                OR
                &#entity_number;

- To display a less than sign (<) we must write: `&lt;` or `&#60;`

### LIST OF 5 COMMONLY USED HTML ENTITY ARE :-

1 - **`&lt;` `(&#60;)` -** Represents the less-than sign (<). This is used to display the < character without starting an HTML tag.**

2 - **`&gt;` `(&#62;)` -** Represents the greater-than sign (>). This is used to display the > character without ending an HTML tag.

3 - **`&amp;` `(&#38;)` -** Represents the ampersand itself (&). This is used to display the & character without interpreting it as the start of an entity.

4 - **`&quot;` `(&#34;)` -** Represents double quotation marks ("). This is used to display double quotes within an attribute value enclosed by double quotes.

5 - **`&copy;` `(&#169;)` -** Represents the copyright symbol (©). This is used to display the copyright symbol in web content.

These entities are frequently used in HTML to ensure proper rendering and to prevent interpretation of special characters as part of HTML markup.





