# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/adriennedomingus/idea_box)

### Link to the Deployed Application
[Your Application](http://adriennedomingus-ideabox.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/adriennedomingus/idea_box/commits/master)

### Provide a Screenshot of your Application
![Screenshot](https://docs.google.com/drawings/d/1e7RBCSVU8W43j-t8b7ESBQQ7_UUMSm4_DVnGcHTilm4/pub?w=960&h=534)

## Completion

### Were you able to complete the base functionality?
* Yes

### Which extensions, if any, did you complete?
* Sorting, though I decided to do it before I saw that it was a defined extension, so did it a little differently - there are buttons for each quality type or all, and when clicked, only ideas of that type display

### Attach a .gif, or images of any extensions work being used on the site.
![sorting](http://g.recordit.co/wZk76xxfop.gif)
# Code Quality

### Link to a specific block of your code on Github that you are proud of
[This-ish](https://github.com/adriennedomingus/idea_box/blob/ed295bb055d9ceb149a5f1557347b3d0a75e5f29/app/assets/javascripts/ideas.js#L12-L23)
* Why were you proud of this piece of code?
  * I'm not entirely sure 'proud' is the right word. But until very recently this was a really ugly string of HTML with JS concatenated, so I feel significantly better about it than I did, and cool to use JavaScript to do something I'd always done with HTML before.  

### Link to a specific block of your code on Github that you feel not great about  
[Not proud of this](https://github.com/adriennedomingus/idea_box/blob/e1ebf049eb99fcf4edee065f4c8ea6d39f849222/app/assets/javascripts/edit.js#L1-L40)
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?  
 * I was able to pull the actual AJAX call out and reference it from both places, but the rest is redundant also. Trying to pull it out, I ran into issues with `that` and `this` and sending selectors as arguments.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![test suite](https://docs.google.com/drawings/d/1yAnAXGfRkcrknsWWICc19-HmQsAwDjQ2OEEFGz9LxUw/pub?w=960&h=720)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'
