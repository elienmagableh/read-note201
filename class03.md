
# chapter3 
** lists **
* Lists are used to group together related pieces of information so they are clearly associated with each other and easy to read. In modern web development, lists are workhorse elements, frequently used for navigation as well as general content.

Lists are good from a structural point of view as they help create a well-structured, more accessible, easy-to-maintain document. They are also useful because they provide specialized elements to which you can attach CSS styles. Finally, semantically correct lists help visitors read your web site, and they simplify maintenance when your pages need to be updated. *
![list](https://media.cheggcdn.com/media%2F97a%2F97ac2705-604c-401b-b644-3910a52e7f4f%2FphpF4QzPj.png)

** There are three list types in HTML: **
- unordered list — used to group a set of related items in no           particular order
- ordered list — used to group a set of related items in a specific order
- description list — used to display name/value pairs such as terms and definitions
Each list type has a specific purpose and meaning in a web page.

* Unordered lists use one set of <ul></ul> tags wrapped around one or more sets of <li></li> tags:
<ul>
  <li>bread</li>
  <li>coffee beans</li>
  <li>milk</li>
  <li>butter</li>
</ul>
Unordered (bulleted) lists are used when a set of items can be placed in any order. An example is a shopping list:
- milk
- bread
- butter
- coffee beans *


    ![list](https://i2.wp.com/blog.thejaytray.com/wp-content/uploads/2015/04/005-Music-HTML-List-Code-Ordered-List.png)

    [example on list](https://www.w3schools.com/html/html_lists.asp) 
* Ordered (numbered) lists are used to display a list of items that should be in a specific order. An example would be cooking instructions:

* 1. Gather ingredients
  2. Mix ingredients together
  3. Place ingredients in a baking dish
  4. Bake in oven for an hour
  5. Remove from oven
  6. Allow to stand for ten minutes Serve

  Ordered lists use one set of <ol></ol> tags wrapped around one or more sets of <li></li> tags:
<ol>
  <li>Gather ingredients</li>
  <li>Mix ingredients together</li>
  <li>Place ingredients in a baking dish</li>
  <li>Bake in oven for an hour</li>
  <li>Remove from oven</li>
  <li>Allow to stand for ten minutes</li>
  <li>Serve</li>
</ol>


# chapter 13
** boxes **
In CSS, the term "box model" is used when talking about design and layout.
The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model
![boxes]( ./image/boxx.png )
In CSS we broadly have two types of boxes — block boxes and inline boxes. These characteristics refer to how the box behaves in terms of page flow, and in relation to other boxes on the page:

If a box is defined as a block, it will behave in the following ways:

The box will break onto a new line.
The box will extend in the inline direction to fill the space available in its container. In most cases this means that the box will become as wide as its container, filling up 100% of the space available.
The width and height properties are respected.
Padding, margin and border will cause other elements to be pushed away from the box
Unless we decide to change the display type to inline, elements such as headings (e.g. <h1>) and <p> all use block as their outer display type by default.

If a box has an outer display type of inline, then:

The box will not break onto a new line.
The width and height properties will not apply.
Vertical padding, margins, and borders will apply but will not cause other inline boxes to move away from the box.
Horizontal padding, margins, and borders will apply and will cause other inline boxes to move away from the box.
![box](https://img.webnots.com/2017/02/CSS-Color-Text-Box-Widget.png)
