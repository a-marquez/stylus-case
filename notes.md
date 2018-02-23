NOTES:
- there exist references to this being a boilerplate specifically for an application, would like to make it more general for any use
  - can have different flavors to the boilerplate such as for an embedded application or a single page app (can separate these in branches that rebase off the latest master)
- this is currently half boilerplate and half library perhaps, it should be split up
- it is actually not unassuming right now, has to be used in full with some suggestive naming conventions (app.styl, .root, .app, .app-body)
- atomic implies two separate things
  - atomic design - a design approach that encourages construction of component systems with an emphasis on simple building blocks that put the responsibility of complexity on their groupings
  - Atomic CSS - a framework that features neat and terse shorthands in the name of productivity
- atomic design is an inspiration for this tool, the terse shorthands of Atomic CSS run counter to this tool's endevours of transparency and obvious naming
- revisit stylus specific hash usage (example border-link and colors)
- would be nice if boilerplate version of this were usable with npx

TODOS:
- breakdown utilities.styl, make them importable piecemeal in other styling projects
- change long and wide references to horizontal and vertical
- example page (documentation page, more in-depth than readme)
  - sample font (maybe generic block text meant for markup)
  - sample atom class (maybe dialog)
- consider multipage usage, current implementation is only targeting single page applications

REFERENCES:
- http://bradfrost.com/blog/post/atomic-web-design/
- http://atomicdesign.bradfrost.com/chapter-2
- https://www.lullabot.com/articles/bem-atomic-design-a-css-architecture-worth-loving
