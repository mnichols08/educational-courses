# Learn Svelte

What is Svelte?
Framework?
Compiler?
Language?

It is all 3 but it is a compiler.

## Benefits

* Smaller Bundle
* No virtual DOM
* Extendable (can grow to have more features without increasing bundle size)

## Why is Svelte so special for Developers?

* Less Code
* Reactive
* Simple

## Should you learn Svelte?

1. For self starters

* Faster Development
* Faster Web Pages
* Happier =)

2. For job hunters

* Makes you stand out
* Can help in interviews
* Investment in future

## Course Outline

\[ ] Components
\[ ] Templating
\[ ] Events
\[ ] Reactivity
\[ ] Bindings

* * Many challenges and a final project!

Anatomy of a svelte component

```
<script>
    let say = 'hi';
    setTimeout(() => {
        say = 'bye';
    }, 1000)
</script>

<style>
    div {
        color: red;
    }
    :global(div) {
        background: blue
    }
</style>

<div>
    Say: {say}
<div>
```
No longer free =(