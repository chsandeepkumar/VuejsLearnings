# Introduction

Vue.js is a progressive framework through which we can develop the client-side dynamic web applications like other java script frameworks (angular) and javascript libraries like Jquery. This Repository contains hello-world application

## How to add the VueJs in your Html Page using CDN?

```bash
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
```

## How to bind the Textbox value property using vue.js one-way data binding

```index.html
<input type="text" :value="email" class="form-control form-control-lg">

here ':value' is vue-bind directive to bind the value of vue data property (i.e. email)
the binding from java script to the view => is called one way binding.

```

```myvue.js

<script>
   new Vue({
        el:'#app',
        data:{
            email:'chsandeepreddy544@gmail.com'
        }
    })
</script>
```

## License
[MIT](https://choosealicense.com/licenses/mit/)