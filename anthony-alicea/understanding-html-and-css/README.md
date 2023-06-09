# Understanding HTML and CSS

## Section 1 - Introduction

Don't Imitate, UNDERSTAND

### Tools and Setup

[Download Visual Studio Code](https://code.visualstudio.com/)

* Install Live-Server Extension

#### Downloading Code for this Course

* We will write lots of HTML and CSS in this course. I strongly encourage you to write the code for yourself, however you may also download the code written in this course as a reference.
  [Source Code](./resources/) or on [Github](https://github.com/AnthonyPAlicea/htmlcss)

#### How to Use the source code files

Each folder corresponds to a lecture, and has an alphabetical prefix so the folders sort in the proper order. The name of the folder has the structure of ALPHA\_SECTIONNAME\_LESSONNAME.

Inside each folder, you will find a "Begin" and "Finished" folder. The "Begin" folder contains the source code you should have when the lecture begins, and the "Finished" folder contains the source code you should have when the lecture ends.

__Please note, not every lecture has source code.__

## Section 2 - Trees

### Conceptual Aside

__Data Structures__ - A particular way to organize and store data so that a computer can quickly and efficiently access and modify it.
__Doubly Linked List__ - When boxes point to other boxes and back and forth which is just one of many types of data structure
__Linked Lists__
__Arrays__
__Trees__ - In this course, we will be learning about trees inside and out.

#### Tree Data Structures

Usually an upside down tree when illustrated on screen.

* Also resembles a family tree
* Particular item of a tree is a node, which can have siblings, children, parent, etc.
* root
* ancestors

<!---->

* parent
* siblings
* children
* descendents
* node

#### Implementation

The process of putting a plan into effect.

Trees are implemented differently than doubly-linked lists, they pass properties along and create copies of themself as the program grows.

##### Traversal and Search

__Traverse__ - To travel across or through. To move around from block of data to block of data.

__Search__ - We can ask the computer to traverse the document to query for our data.

## Section 3: HTML

In this section we are introduced to HTML. __Hyper Text Markup Language__

* A Document contains content. An html document is simply a text document.

### Conceptual Aside

__User Agents__

* Agent - something that acts on someone else's behalf
* User Agent - Software which acts on the user's behalf
  The user agent sits between a user and the browser. There are various types of user agents. Such as:
* Browsers
* Screen Readers
* Googlebot

#### No Browser Until We Are Ready

* Build Good Babits
* Break Bad Habits

### The M in HTML

#### Markup: Describing Content

With `html` we markup using less than and greater than symbols along with some name within. We also use a `/` to identify a closing tag

### The L in HTML

#### Language

* Consistent Vocabulary
* Can Convey meaning clearly
* Exists to facilitate communication
* When learning, can go to a dictionary and look it up!
* Provides Consistent Meaning
* Everyone using HTML should be using proper elements to convey meaning

### Conceptual Aside - Semantics and Authoring

__Semantics__ - Having to do with meaning.
__Authoring__ - To contribute to writing a document.
Adding meaning (being concerned with semantics) is a part of authoring.

* By writing HTML even if we did not write the content, we are authoring the markup of the document.

### Tags, Attributes, and Elements

#### Tags

__Tags__ are defines as the element that we are creating the first word after less than sign. They are about meaning. They can add meaning other than related pieces of languge

#### Attributes

__Attributes__ are other related pieces of information or instructions

#### Elements

__Elements__ are the conbination of both, the entirety of the block.

### Elements and Trees

__Nested__ - Placed inside something else.
Markup is not just designed for computers to read. It is also designed for humans to read.
As long as we follow the rules of the markup language, we can arrange the content in any which way we deem fit.

* Markup is everywhere but in this course we will learn Hyper Text
  __Specification__ - A standard of precise requirements
* Internet technologies are governemd by many specifications.
* Sometimes we just call it the "spec".'

### The HTML Specification

* The dictionary
  Googling leads you to [html-spec.whatwg.org](https://html.spec.whatwg.org/multipage/)
  __Normative__ - Establishing a standard.
  __Non-Normative__ -- Not part of establising a standard.

<!---->

* The term "HTML5" is widely used as a buzzword to refer to modern web technologies
* The background of HTML is the World Wide Web's core markup language. Originally primarily designed as a langauge for semantically describing scientific documents. Its general design, however, has enabled it to be adapted, over the subsequent years, to describe a number other types of documents and even applications.

### Document Object Model Specification

Elements, attributes, and attribute values in HTML are defined (by this specification) to have certain meanings (semantics). For example, the ol element represents an ordered list, and the lang attribute represents the language of the comtent.

These definitions allow HTML processors, such as web browsers or search engines, to present and use docuemtns and applicatiosn in a wide variety of contexts that the author might not have considered.

### Conceptual Aside - Author vs. Implementor

This specification is intended for _authors of documents_ and scripts that use the features defined in this specification, _implementors of tools_ that operate on pages that use the features defined in this specification, and _individuals wishing to establish the correctness of documents_ or implementations with respect to the requirements of this specification.
__Author__: Writes and adds meaniing to the document
__Implementor__: Creating a _user agent_ which will communicate the document to the user.
_This is the same specification that the people writing Google Chrome and Firefox are reading and following._

### Content Models and Kinds of Content

* Standard Types
  __Content Model__ - A description of the elment's intended contents.
  * In other words when we are looking at an element - we know that it includes the entire element, including the content. So what do we agree can go within each element? Each element has a content model.

#### Kinds of Content

Each element in HTML falls into zero or more __categories__ that group elements with similar characteristics together. The following broad categories are used in this specification:

* Metadata Content
* Flow Content
* Sectioning Content
* Heading Content
* Phrasing Content
* Embedded Content
* Interactive Content
  Note: Some elements also fall into other categories, which are defined in other parts of the specification

## Section 4: The Document

### DOCTYPE

* DOCTYPEs are required for legacy reasons. When omitted, browsers tend to use a different rendering mode that is incompatible with some specifications. Including the DOCTYPE ina document ensures that the browser makes a best-eford at following the relevant specifications.

### Root

* The very first element listed within the HTML specification is naturally the `<html>` element.

<!---->

* The html element represents the root of an HTML document.

Authors are encouraged to _specify a lang attribute_ on the root html element, giving the document's language. This aids speech _synthesis tools_ to determine waht pronunciations to use, _translation tools_ to determine what rules to use, and so forth.

### Metadata

A set of data that provides information bout other data.

The primary metadata within an html document is the `<head>` element.

The `<title>` element represents the docuement's title or name. _Authors_ should use titles that identify their documents even when _they are used out of context_, for example in a user's history or bookmarks, or in search results. The document's title is often different from it's first heading, since the first heading does not have to stand alone when taken out of context.

There must be no more than one title element per document. The title element should go inside of the head element.

#### Character Set

A set of supported characters (numbers, letters, symbols). UTF-8 covers almost everything in every language!

### Body Element

The body element represents the contents of the document. In conforming documents, there is only one body element. The `document.body` IDL attribute provides scripts with easy access to a document's `body` element.
