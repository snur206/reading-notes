# [Class 5 Reading Notes](https://github.com/snur206/reading-notes/blob/main/102/class5notes.md)
**CSS**

*What is CSS*
Cascading Style Sheets allows you to create great-looking web pages.
CSS is a language for specifying how documents are presented to users

HTML used to mark up documents where it will be readable in a web browser.

***Using CSS you can an control exactly how HTML elements look in the browser, presenting your markup using whatever design you like.***

**What is it used for?**
CSS can be used for very basic document text styling. Like changing the color and size of the headings and links. Can also be used to create a layout.

**CSS Syntax**
CSS is a rule-based language. You define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

***CSS Rule that wouldshows the page styling of the main heading as large red text***
h1 {
  color: red;
  font-size: 5em;
}
CSS rule opens with a selector. This selects the HTML element that is going to style.
<h1> is styling level one heading.
{ } is next where inside the brackets will be one or more declarations that take the form of propery and value pairs.
CSS properties have different allowable values. Depends on which property is being specified. Like in the example above color is the a property that can take various color values.
Also, teh font-size property can take various size units as a value.
A CSS stylesheet will contain many such rules, written one after the other.
  
h1 {
  color: red;
  font-size: 5em;
}

p {
  color: black;
}

**CSS Modules**
Language is broken down into modules.
 Background-color and border-color properties
  
**CSS Specification**
All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (specs)  
Publishes by standard organizations like W3C, WHATWG, ECMA, OR Khronos. Defines how those technologies are supposed to behave.
CSS is not different, its is developed by a group within the W3C called the ***CSS Working Group***
They are made of representatives of browser vendors and other companies who have an interest in CSS. 
*Invited experts* act as independent voices; they are not linked to a member organization.
New CSS features are developed or specified by the CSS Working Group.
CSS IS constantly developing with new features becoming available. 
Important thing about CSS is that everyone works very hard to never change things in a way that would break old websites.  
**Browser Support Info**
When a CSS feature is specifed, it is only useful in developing web pages if one or more browsers have been implemented the feature.
Meaning that the code has been written to turn the instruction in our CSS file into something that can be output to the screen.

**THREE WAYS TO INSERT CSS**
  -External CSS
  -Internal CSS
  -Inline CSS
**EXTERNAL CSS**
With external style sheet, you can change the look of an entire website by changing just one file.
Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.
Example
External styles are defined within the <link> element, inside the <head> section of an HTML page:
An external style sheet can be written in any text editor, and must be saved with a .css extension.
External .css file should not contain any HTML tags.
  
**Internal CSS**
An internal style sheet may be used if one single HTML page has a unique style.
The internal style is defined inside the <style> element, inside the head section.

**Inline CSS**
Inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
Inline styles are defined within the "style" attribute of the relevant element.

*Multiple Style Sheets**
  If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.
**Cascading Order**
All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority
-Inline style (inside an HTML element)
-External and internal style sheets (in the head section)
-Browser default
  
**CSS Syntax**
 color: color initial inherit
  
 **Property Values**
Color: Specifies the text color. Look at CSS Color Values for a complete list of possible color values.
Initial: Sets this property to its default value. 
Inherit: Inherits this property from its parent element.
 
  
