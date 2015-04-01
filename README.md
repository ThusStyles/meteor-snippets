# Meteor snippets for atom editor

Basic snippets to make meteor development faster in atom

Works with Javascript + Coffeescript!

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

**cola**

```javascript
Collection.allow({
  insert: function (...) {
    ...
  },
  update: function (...) {
    ...
  },
  remove: function (..) {
    ...
  }
  ...
});
```

**colde**

```javascript
Collection.deny({
  update: function (...) {
    ...
  },
  remove: function (...) {
    ...
  }
  ...
});
```

**mcol**

```javascript
Collection = new Meteor.collection("collection");
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

**mmeth**
```javascript
Meteor.methods({
  "name": function (argument) {
    ...
  }
});
```

**mren**

```javascript
Template.name.onRendered(function(){
  ...
});
```

**mcre**

```javascript
Template.name.onCreated(function(){
  ...
});
```

**mdes**

```javascript
Template.name.onDestroyed(function(){
  ...
});
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
