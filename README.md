# bentocss

Tasty CSS, neatly organized.

## Roadmap

### Ongoing

Permanent goals and recurrent tasks.

- Keep up with the latest standards, as well as the best practices and combined knowledge from the different methodologies and frameworks.

### Upcoming

Work in progress. Major features and changes that are being implemented. 

### Todo

Features thar are pending to be implemented.

- **Docs**. Markdown on GitHub.
- **Style guide generator**. Vue/React + Less.js app hosted on GitHub Pages: vars, hooks, custom styles, bookmarkable settings as in [less2css.org](http://less2css.org/).

### Maybe

Feature ideas and changes that are still under consideration or being researched.

Optionally enable these features at component level:

- **Status**. Namespace status classes, similar to how BEM handles them. For example, use `.button--is-*` instead of `.is-*`. <https://en.bem.info/faq/#mixes>
- **Local reset**. Use local/per-component reset styles instead of a global one. Remove dependency from `element-base.less`. This would allow to create completely decoupled, cross-project reusable component templates/contructors/factories with zero dependencies and side-effects. <https://en.bem.info/faq/#why-cant-i-use-a-css-reset> 

### Future

Experimental standards, ideas and technologies that may be integrated in future versions.

- **Flex all the things**. Migrate the layout of all components to be based on flex instead of float, table, inline-block...
- **CSS grids**.
- **CSS element queries**.
- **CSS custom properties** combined with data attributes, var(), attr(), calc()... <https://googlechrome.github.io/samples/css-custom-properties/>
- **CSS modules**. Also known as CSS in JS, Atomic CSS, depending on the context and implementation.