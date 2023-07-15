# fullstack-dev-scenario-exam

Technical exam from Acquire BPO:

Write an express middleware application that uses VueJS as a rendering engine (2.x.x is acceptable but 3.x.x preferred)

In this application, Vue templates need to be:

1. Read from local vue template - e.g. /views/vue/some_template.vue
2. Rendered, and returned to the frontend using SSR
3. Hydrated on the frontend - allowing interactivity with rendered components

The Vue template should include:

- A basic form with:
  - First Name
  - Last Name
  - Email
  - Phone
  - Submit button
- Submission logic for the form using Vue lifecycle hooks
- Template script should work when rendered on the frontend

Outputs:

1. Git repo for all code for the above solution
2. Any notes or finding while working
3. Bonus:
   a. JSDoc function comments
   b. Form validation
   c. Basic API unit testing
