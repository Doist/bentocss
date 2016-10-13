# bentocss

Tasty CSS, neatly organized.

## Roadmap

### Ongoing

> Permanent goals and recurrent tasks.

- Keep up with the latest standards, as well as the best practices and combined knowledge from the different methodologies and frameworks.

### Upcoming

> Work in progress. Major features and changes that are being implemented. 

- **Flex all the things**. Migrate the layout of all components to be based on `flex` instead of the current mix of `float`, `table`, `inline-block`...
- **Local reset**. Use component level reset styles instead of relying on element selectors. Remove dependency on `element-base.less` and move styles out of `element-form.less` to matching components. This would allow to create completely decoupled, cross-project reusable component templates (kind of contructors/factories) with zero dependencies and side-effects. <https://en.bem.info/faq/#why-cant-i-use-a-css-reset> 

### Todo

> Features thar are pending to be implemented.

- **License**. Choose one and add it to repo.
- **Contributing**. Start using SemVer and GitFlow as described on [UIkit REAMDE.md](https://github.com/uikit/uikit/blob/de26176a504661a2cddb859f8b1c2c2a992fe914/README.md).
- **Docs**. Markdown.

### Maybe

> Feature ideas and changes that are still under consideration or being researched.

- **Style guide generator**. Vue/React + Less.js app hosted on GitHub Pages: vars, hooks, custom styles, bookmarkable settings as in [less2css.org](http://less2css.org/).

Optionally enable these features at component level:

- **Status**. Namespace status classes, similar to how BEM handles them. For example, use `.button--is-*` instead of `.is-*`. <https://en.bem.info/faq/#mixes>

### Future

> Experimental standards, ideas and technologies that may be integrated in future versions.

- **CSS grids**.
- **CSS element queries**.
- **CSS custom properties**. Make some powerful declarative utilities combining CSS custom properties with `data-` attributes, `var()`, `attr()`, `calc()`... <https://googlechrome.github.io/samples/css-custom-properties/>
- **CSS modules**. Also known as CSS in JS, Atomic CSS, depending on the context and implementation.