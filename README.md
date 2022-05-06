## What is Spheroid?
Spheroid is a JavaScript framework for defining user interfaces using pure JavaScript/TypeScript. This is a work in progress.

## Basic syntax example
This won't work yet, but I'm sort of using this as a basic "specification" of what I want to get to. This may change.
```
// basic defining of a static web component:
Spheroid.define({`
  <h1>{text}</h1>
`,
  {
    parameters: {
      text: function(text): Spheroid.Bind {
        bind = new Spheroid.Bind();
        bind.
      }
    }
  }
});
```
