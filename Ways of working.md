Vue ways of working

Principles:
- Don't expose complexity
- Build highly reusable dumb components for rendering
- Read the doc first and see how others solve similar problems (vuejs.org, aligator)
- Write the code (or tests) that will consume your API/Components/service in the first
place

Best practices:
- Don't manipulate DOM (without ref)
- Lint your code on save
- Use a mock server (SPA)
- Use single file components
- Let vue-cli / vite scaffold your project

Tips
- >>> v-deep()

Advanced topics
- Vuex, xstate, provide/inject
- Bus
- Multiple Vue instances on the same page
- Use composition-api