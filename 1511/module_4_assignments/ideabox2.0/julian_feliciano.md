# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/julsfelic/revenge_of_idea_box)

### Link to the Deployed Application
[Your Application](https://floating-taiga-96250.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/julsfelic/revenge_of_idea_box/commits/master)

### Provide a Screenshot of your Application
![spacejam](images/julian_idea_box.png)

## Completion

### Were you able to complete the base functionality?
* Did not get to idea body truncation

### Which extensions, if any, did you complete?
* Idea searching, I implemented a fuzzy search that uses an algorithm instead
of a straight letter for letter search similar to Atom's fuzzy searching. This
allows for a better searching experience that most users are used to.

![fuzzysearch](images/julian_fuzzy_search.gif)

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Idea JavaScript Class](https://github.com/julsfelic/revenge_of_idea_box/blob/66467decb241e4d0a8dff5376050a56c3a6dc7b3/app/assets/javascripts/idea.js.es6#L1-L65)

* Without knowing it, I was able to semi-recreate the idea of an Idea model on the
front-end. This snippet also includes ES6 which was the main focus of this project
for myself. Now that I have gone through this project once, I can see how we could
apply different patterns (like MVC) to the front-end JS as well to have a cohesive set of
code that relates from front to back.


### Link to a specific block of your code on Github that you feel not great about
[Using erb with JS...Yuck](https://github.com/julsfelic/revenge_of_idea_box/blob/66467decb241e4d0a8dff5376050a56c3a6dc7b3/app/assets/javascripts/main.js.es6.erb#L4-L5)

* I had the hardest time using my image files with dynamically created ideas because
of the asset pipeline fingerprinting the images. The only work around was adding the
`.erb` extension to the JS file and using the `asset_path` helper to grab the image. Something
about the code just seems not clean to me and I really despise the asset pipeline
at the moment.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![testsuite](images/julian_test_suite.png)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

![edgecase](images/julian_edge_case.png)
-----

### Please feel free to ask any other questions or make any other statements below!

My main focus for this project was to try incorporating ES6 and a module loader,
browserify in this case, into a Rails project. I kept styling to a super minimum so
that I could focus all my energy towards the JS portion of the project. Unfortunately,
I could not get teaspoon to play nice with browserify and couldn't get the unit test
working. I left a unit test that is pending up for an example, but working with newer JS
features and the Asset Pipeline proved to be a big challenge.
