<h1 align="center">Readme Boilerplate 💕</h1>

<h5 align="center">This repository is a README boilerplate. It's open source. Updates and suggestions are appreciated.</h5>

---

<p align="center">
  <a href="#standards">Stardards</a>&nbsp;&nbsp;
  <a href="#headers">Headers</a>&nbsp;&nbsp;
  <a href="#navigation">Navigation</a>&nbsp;&nbsp;
  <a href="#api-documentation">API Documentation</a>&nbsp;&nbsp;
  <a href="#cite">Cites & Thanks</a>
</p>

---

Readmes are used to describe the contents of code repositories. Besides the title, description, and code directory, readmes are the first thing users see. This boilerplate contains items to assist in writing readmes. 

<h2 id="standards">Standards</h2>

The standard section is the core section of the readme-boilerplate. It contains definitions and context for the rest of the readme-boiler-plate.

###  Headers

Headers for `readme`'s should include a title `h1`, a sub-description `h5`, and a description `p`. After the header, the readme should contains sections that contain titles `h2` and sub-titles `h3`. 

---

The readme boiler plate writes out the title with the `<h1>` tag rather than `markdown` so that the element is centered using the `align` attribute.

```html
<h1 align="center">This a header 💕</h1>
```

The pre-description is added before a full description. It is written on like this.

```html
<h5 align="center"This is a pre-description</h5>
```

The description should describe the product. It follows and linebreak `---`.

```markdown
---

A description 
```


--- 


All together, this is a header that can be copied.

```html
<h1 align="center">This a header 💕</h1>

<h5 align="center"This is a pre-description</h5>

---

A description 
```

### Navigation

Navigation can be provided if the is more than 1 section to a `readme` or `document`. Navigation links to sections within the `readme` and `document`.

Here is how navigation is written.

```html
<p align="center">
  <a href="#section">section</a>&nbsp;&nbsp;
  <a href="#section">section</a>&nbsp;&nbsp;
  <a href="#section">section</a>
</p>
```


### API Documentation

There is more than 1 way to approach API documentation. For smaller APIs, readmes can document APIs using [tables](#table-format) or [lists](#list-format). 

#### Table Format

| Name | Default | Description |
|---|---|---|
| initiate | `function(){}` | it is initiated |
| start | `function(){}` | it is started |

```md
| Name | Default | Description |
|---|---|---|
| initiate | `function(){}` | it is initiated |
| start | `function(){}` | it is started |
```

### List Format

- **API**
  - **initiate:** `f`
     - `function(){}`
     - _example:_ an example
     - a description
  - **start:** `f`
     - `function(){}`
     - _example:_ an example
     - a description

```md
- **API**
  - **initiate:** `f`
     - `function(){}`
     - _example:_ an example
     - a description
  - **start:** `f`
     - `function(){}`
     - _example:_ an example
     - a description
```


<h2 id="cite">Cites & Thanks</h2>

The Heartly project is a set of lists and tools to help make the online code discussions more friendly. It moves forward with inspiration from discussions with [Brian Gonzolez](https://www.briangonzalez.org/), [Jason Farmer](https://github.com/jacefarm), [Patrick Fisher](https://github.com/pwfisher), and [Arjan Singh](https://github.com/arjansingh).

