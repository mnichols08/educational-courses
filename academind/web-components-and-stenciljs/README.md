# Web Components & Stencil.js - Build Custom HTML Elements

## Web Components

* What are Web Components?
  Custom HTML elements which are not built into the browser.
  ```
    <uc-modal>
      <h1 slot="title">The Modal Title</h1>
      <p>This is our first web component!</p>
    </uc-modal>
  ```
  * Web components allow developers to create custom html elements to reuse at any time.
  * Sometimes they are confused because it is a broad term.
  * Custom HTML Elements allow us to register our own HTML Tags
  * Shadow DOM is a separate DOM behind our normal DOM which allows us to scope styles
  * Templates and Slots are another important part of this specification because they define core structure
  * HTML Imports - Meant to be feature to import HTML into HTML in order to define HTML templates, however it is no longer continued into development as we use JS instead

## Why do we use Web Components?

* They allow us to encapsulate logic and structure into one element.
  * Easy to understand,
  * Easy to maintain
  * Separation of Concerns
* Re-usable across Page
  * Use it just like a normal HTML element
  * Do not worry about overlapping logic
  * Write logic and UI only once
* Re-usable between Apps and Projects
  * Use it as a normal html element

  * Re-use core UI elements across projects

  * Write logic and UI only once

  * Optional can publish and NPM package

## Web Components vs. Angular, React, Vue, jQuery

The advantages of web components are their reusability across the spectrum.
It is easy to import a library - but there are a lot if required unnecessary imports, potential version conflicts, and redundant code.
They do not replace a framework though they just give us an alternative to creating components within.

## Course Outline

* JS Refresher
* Web Components Basics
* Advanced Concepts
* Building More Complex Components
* Stencil.js Introduction
* Advanced Stencil.js
* Publishing & Sharing Web Components

### Getting the Most Out of This Course

* Watch at your Speed but watch
* Code Along and Do the Exercises - Pause / Rewind
* Use the Course Resources
* Ask in the Q & A
* Help others in the Q & A
