# Introduction

Vue.js is a progressive framework where we can built the client-side dynamic web applications like other java script framewors (angular) and javascript libraries like Jquery. This Repository contains hello-world application

## How to add the VueJs in your Html Page using CDN?

```bash
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
```

## VueJs data bind 

```python
<div id="app"> #root app Id
<h1> {{greeting}}</h1> # greeting is a databind property defined in Vue instance
</div>
<script>
    new Vue({ # creating Vue Instance for existing HTML element that is "app" is an Id attribute. 
        el:"#app",
        data:{
            greeting:"welcome to the vuejs world" # assigning a data to the greeting propery
        }
    })
</script>
```

## License
[MIT](https://choosealicense.com/licenses/mit/)