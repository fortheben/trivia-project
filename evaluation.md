# Project Feedback + Evaluation

## Project Workflow

>Did you complete the user stories, wireframes, task tracking, and/or ERDs, as specified above? Did you use source control as expected for the phase of the program you’re in (detailed above)?

**Meets expectations**: I think that thinking through your code (without overthinking it) is going to be your thing for this course. One place to start is with your commit messages. These should give a hint about what was changed from the previous commit. So "first draft" and "second draft" isn't particularly helpful. Thinking about what you changed before you make a commit message is a great way to code more intentionally.

Also, as much as I love having 600 Nic Cage MP3s on my computer, it might be a good idea next time to upload those to SoundCloud or something so that the folks forking your repo don't have to download an extra 4 megabytes. :)

## Technical Requirements

>Did you deliver a project that met all the technical requirements? Given what the class has covered so far, did you build something that was reasonably complex?

**Does not meet expectations**: There are some funky inconsistencies in your code. For instance, you use `<script>` tags to include jQuery, but then never actually do anything with it -- there isn't a single `$` in your code. It's fine to not use it, but make it look intentional!

Additionally, all of your Javascript is right in with your HTML. It should really be split out into a separate file. I get the impression that you tried that, but then the file wasn't working for some reason, so you went back.

I would really have liked to have seen you use event listeners instead of `onclick` attributes in your HTML. 

## Code Quality

>Did you follow code style guidance and best practices covered in class, such as spacing, modularity, and semantic naming? Did you comment your code as your instructors have in class?

**Does not meet expectations**: The CSS validates, and the HTML *almost* validates! I left a comment about keeping your semantics and style separate, and generally separating your concerns. This, along with indentation, is something that doesn't have a whole lot of impact on the performance of your code, but makes a **huge** difference when it comes to your marketability as a programmer.

The biggest change you could make is with the DRYness of your code, as you mentioned. Remember that when you see the same words repeated a bunch in your code it's a great indicator that something could be DRYed up. For example, you basically copied and pasted the same `askQuestion` function nine times, one for each question, when you really only need to define that function once. 

This project is totally something you could and *should* show to prospective employers (tech people love Nic Cage -- who doesn't?). But before you do, I'd encourage you to go through and refactor this code.

## Problem Solving

>Are you able to defend why you implemented your solution in a certain way? Can you demonstrate that you thought through alternative implementations?

**Meets expectations**: You get major kudos for having made something that works and that is fun to use! I think refactoring this would be great practice for you, and when you're done I'd **strongly** encourage you to share it on reddit.com/r/internetisbeautiful or something! 
