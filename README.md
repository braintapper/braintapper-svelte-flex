# braintapper-svelte-flex

Some Flexbox components for svelte.

Inspired by the [layout components](https://material.angularjs.org/latest/layout/introduction) of [AngularJS Material](https://material.angularjs.org/). 

Unlike the AngularJS layout components, these have no responsive breakpoints and don't have a flex-order attribute.

## Usage


### Component Import

Import the components you need in your `<script>` tag:

```
  import { FlexColumn, FlexColumnCell, FlexRow, FlexRowCell } from "braintapper-svelte-flex";
```


### Example Markup

```
  <!-- this creates a row with 3 cells -->
  <FlexRow>
    <FlexRowCell flex="initial" >
      some content here
    </FlexRowCell>
    <FlexRowCell flex>
      some content here
    </FlexRowCell>
    <FlexRowCell flex="initial">
      some content here
    </FlexRowCell>
  </FlexRow>
```


### Flex Prop Values

The `<FlexRowCell>` and `<FlexColumnCell>` take a flex prop/attribute.


#### Example `flex` attribute values


0 - 100 in increments of 5 translate to width in %

Example: `<FlexRowCell flex={85}>`

---

33 and 66 for three row/column layouts

Example: `<FlexRowCell flex={33}>`

---

When flex is present with an unmatched value in its CSS, it will fill the row/cell as required:

Example: `<FlexRowCell flex>`

---

When flex is `initial`, retains the initial height or width

Example: `<FlexRowCell flex="initial">`

---

When flex is `auto`, starts with its initial height or width but will grow or shrink as needed

Example: `<FlexRowCell flex="auto">`

--- 

When flex is `grow`, will shrink/grow as needed. Starts with a size of 100%. Same as `flex="100"`

Example: `<FlexRowCell flex="grow">`

---

When flex is `nogrow`, starts with its initial height or width but will only shrink as needed

Example: `<FlexRowCell flex="nogrow">`

---

When flex is `noshrink`, starts with its initial height or width but will only grow as needed

Example: `<FlexRowCell flex="noshrink">`

License: MIT