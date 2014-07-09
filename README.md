# Meteor snippets for atom editor

Basic snippets to make meteor development faster in atom

## Examples

**mtp**

```html
<template name="name">
  ...
</template>
```

**mea**

```handlebars
{{#each collection}}
  ...
{{/each}}
```

**mif**

```handlebars
{{#if statement}}
  ...
{{/if}}
```

**mife**

```handlebars
{{#if statement}}
  ...
{{else}}
  ...
{{/if}}
```

**mpub**

```javascript
Meteor.publish("name", function(argument){
  ...
});
```

**msub**

```javascript
Meteor.subscribe("name", argument);
```

**mren**

```javascript
Template.name.rendered = function(){
  ...
}
```

**mcre**

```javascript
Template.name.created = function(){
  ...
}
```

**mhel**

```javascript
Template.name.helpers({
  helper: function(){
    ...
  }
});
```

**mevn**

```javascript
Template.name.events({
  'event': function(e, t){
    ...
  }
});
```
