# Create DataTables
Create your own DataTables with Vanilla JavaScript.

[Demo](https://jsfiddle.net/aalfiann/d0kpbwzt/30/)

### Why ?
Because DataTables.net is :
- Sticky with jQuery.
- Have no protection for XSS.
- Too Bloated, css 2.1 kB + js 29.7 kB + jQuery 30.8 kB, size around 62.6 kB (minified and gzipped).
- Size will increase more if you are using any extensions.

### Library used in this example
- [Bulma Template](https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/hero.html)
- [Reef.js (2.6 kB)](https://github.com/cferdinandi/reef)  
- [Ajax (1 kB)](https://github.com/fdaciuk/ajax)
- [Fly Json ODM (4.7 kB)](https://github.com/aalfiann/fly-json-odm)
- [Chunk Handler (1,9 kB)](https://github.com/aalfiann/chunk-handler)

Total size is 10.2 kB (minified and gzipped).

### Benefit of using this
- Reactive UI (Modern way, alternative to Vue and React).
- Ajax (support all method and header).
- Manipulation json (Able to search all field or single field, sorting, etc).
- Size is small, fast performance.
- Safe from XSS attack.
- Flexible, you design it by yourself.
- Etc

### Cons of using this
- You required to learn all libraries in this example.
- This is only simple example to make you easier to understanding code. So you have to modify this by yourself.

### Alternative
[Simple-DataTables (13 kB)](https://github.com/fiduswriter/Simple-DataTables).

I would say that this Simple-DataTables is better. All the most important features has been there but in my opinion still not flexible, I have read all the documentation and maybe I just can't understanding it well because it's lack of examples. This depends on how complicated your current project.