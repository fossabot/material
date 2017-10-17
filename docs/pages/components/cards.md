# Cards

## Usage
Cards are a convenient means of displaying content composed of different types of objects. They’re also well-suited for presenting similar objects whose size or supported actions can vary considerably, like photos with captions of variable length.


Cards don't come with a predefined width or height. They expand horizontally to fill all available space, and vertically
to fit their contents.

```html
<div class="card">
  <section class="card-primary">
    <h1 class="card-title card-title-large">Title goes here</h1>
    <h2 class="card-subtitle">Subtitle here</h2>
  </section>
  <section class="card-supporting-text">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
    veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
    commodo consequat.
  </section>
  <section class="card-actions">
    <button class="button mdc-button-compact card__action">Action 1</button>
    <button class="button button-compact card-action">Action 2</button>
  </section>
</div>
```
