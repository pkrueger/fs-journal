# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
Interpolations - using the handlebars
Directives - things like v-bind: or simply :
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Less time loading full pages as you just have to swap components out.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
Runs code written inside it once the component is loaded so you have access to data and DOM elements created by the component.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
Binds input fields to values in your javascript. You can use it for forms as an easy way to submit them and provide default values for fields.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
Can be used for different events on the element such as @click or on a form with @submit
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-if-else, and v-else. v-show also works and may be a good idea for longer strings of html so you don't have to rerender them when you want to show them.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
You pass through a unique identifier for each component copy and that helps Vue when updating the component so it only renders the single component on data changes.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
If you put your component on the page with a opening and closing tag and put other data between them that data will get passed into the component and put wherever you have your <slot> element.
```