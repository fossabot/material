# Cards

Cards are a convenient means of displaying content composed of different types of objects. They’re also well-suited for presenting similar objects whose size or supported actions can vary considerably, like photos with captions of variable length.

## Usage

> NOTE: Cards don't come with a predefined width or height. They expand horizontally to fill all available space, and vertically to fit their contents.

```html
<div class="card">
  <section class="card-primary">
    <h1 class="card-title card-title-large">Title goes here</h1>
    <h2 class="card-subtitle">Subtitle here</h2>
  </section>
  <section class="card-supporting-text">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
  </section>
  <section class="card-actions">
    <button class="button button-compact card__action">Action 1</button>
    <button class="button button-compact card-action">Action 2</button>
  </section>
</div>
```

### Content blocks

Cards are composed of different content blocks, which are typically laid out in vertical succession.


#### Rich media

```css
#example .card-media {
  background-image: url("image.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  height: 100px;
}
```

```html
<section class="card-media"></section>
```

This area is used for showing rich media in cards, and optionally as a container. Use the `card-media` CSS class.


#### Actions

```html
<section class="card-actions">
  <button class="button button-compact card-action">Action 1</button>
  <button class="button button-compact card-action">Action 2</button>
</section>
```

This area is used for showing different actions the user can take. It's typically used with buttons, as in the example
above, or with icon buttons, as below:

You can use the `card-actions-vertical` option to lay actions out vertically instead of horizontally:

```html
<section class="card-actions card-actions-vertical">
  <button class="button button-compact card-action">Action 1</button>
  <button class="button button-compact card-action">Action 2</button>
</section>
```

Be sure to include the `card-action` class on every action for correct positioning. Also, be sure to include the
`button-compact` class on buttons for correct alignment.


#### Primary title / text

```html
<section class="card-primary">
  <h1 class="card-title card-title-large">Title goes here</h1>
  <h2 class="card-subtitle">Subtitle here</h2>
</section>
```

This area is used for titles and subtitles:

| Class                    | Description                                     |
| ------------ | ------------------------ |
| `card-primary`      | Defines the primary text / title content block. |
| `card-title`        | A title block.                                  |
| `card-title-large` | An option for the title, to make it larger.     |
| `card-subtitle`     | A subtitle block.                               |

Note that the title and subtitle classes can also be used outside of the primary title / text content block.


#### Supporting text

```html
<section class="card-supporting-text">
  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
  veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
  commodo consequat.
</section>
```

This area is used for displaying the bulk of the textual content of the card. Use the `card-supporting-text` CSS
class.
