# HTML - designinig a website

Every website should be designed for the target audience. Who will visit the site. Think abount the demographic of the sample of target audience.

Exaples of target audience:
-Individuals (age, gender, urban or rural, average income, occupation) 
- Companies (what size, positon in company of visiting people, how big the budget they control)

## Questions to answer when designing the website:
1. Who is this site for (create a buch of fictional persons)
2. Why people visit the website? (key motivations or specific goal)
3. What informationthe need?
4. How often will people visit the website?

## Organizing the information - site map

Site map - a diagram o the pages that will be used to stucture the site.

#####  Way to do that:
Card sorting - placing each relevant info on separate piece of paper and then grouping releted info together. Each group can make a different section of the website:

##### Example of the site

Homepage:
  - About:
    - History
    - Foundation
    - Future plans 
  - Articles:
    - News
    - Book reviews
    - Press
  - Visit: 
    - Location
    - Opening times
    - Tickets

### Wireframe:
A sketch of the key information that goes into each page of the site. Hierarhy of information, and how much space it needs. It helps to prioritaze and organize information.

#### What to consider when building a website?

##### Visual Hierarchy - helps focus on key information

Ways to do it:
- Size - bigger headings catches an eye
- Color - to distinct  from surrounding content
- Style

 Grouping (related info grouped together into blocks) and similarity (similar style):
- proximity
- closure
- continuace
- White space
- Color 
- Borders

Designing and Navigation:
- Consise
- Clear 
- Selective
- Context
- Interactive
- Consistent


## HTML Layout Elements:

```
<header> and <footer>
```
- The **main** header and footer appear on top and the bottom 
- A `<header>` and `<footer>` for an individual `<article>` or `<section>`  

```
<nav> - Navigation
```
- Used to contain the major navigational blocks such as primary site navigation

```
<article>
```
This element acts as a container for any section of a page that could stand alone and potencially be syndicated.

```
<aside>
```
Could be inside an `<article>` or outside it. It has then different purposes
**Inside** - could contain info related to the article but not essential to it.
**Outside** - acts as a container of info related to the entire page.

```
<section>
```
This element groups related content together. Typically each section wpild have its own heading.

```
<hgroups> - heading groups
```
The purpose of the `<hgroup>` element is to group toghether a set of one or more `<h1>` through `<h6>` elements so that they are treated as one single heading.

```
<figure> and <figcation>
```
`<figure>` can be used to contain any content that is referenced from the main flow of an article. 
Examples:
- Images
- Videos
- Graphs
- Diagrams
- Code samples
`<figcaption>` - should be contained in `<figure>` because it provides a text description for the content of the latter. 

## Extra Markup

HTML 5 `<!DOCTYPE html>` - tells browser which version of HTML the page is using

Comments `<!-- -->` = CTRL+/

ID attribute - used to uniquely identify the element from other elements ont he page. 

Class artibute - helps identify several elements as being different from other elements on the page. 

Block elements - some elements like `<h1>` `p` `ul` are displayed starting on a new line in the browser. 

Inline elements - some elements as `<a>` `<b>` `<em>` will always appear to continue on the same line as their neighbouring elements

`<div>` - allows to group a sets of elements together in one block-level box

`<span>` - acts like an inline equivalent of `<div>`. 
Could be used to:
- Contain a section of text where there is no good element to differentiate them form the surroundings 
- Contain a number of inline elements.

`<iframes>` - inline frame, like a little window inside the page; common used to embed a Google map into a page.
Attributes it uses:
- src
- height
- width
- seamless

`<meta>` - info about the page, inside the `<head>`, self-closing tag