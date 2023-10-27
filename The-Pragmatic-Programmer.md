# The Pragmatic Programmer (20th Anniversary Edition) Notes
My thoughts and what I liked about each chapter or topic as I read them.

## Preface
Kaizen - A Japanese business philosophy of continuous improvement of working practices, personal efficiency, etc.
When asking someone what they do to make their lawn look so nice, they respond with "Every morning wipe the dew off, every other day mow the grass, and once a week roll it, and after 500 years of doing this, you too can have a nice lawn." This relates to our programming skills. If we continue to make small improvements, and continue learning new things and better ways to code, we will notice improvements much faster than a lawn. To have this "kaizen" mentality is important to getting better.

## Chapter 1. A Pragmatic Philosophy
Pragmatic Programmer - An attitude, style, or philosphy of how to approach problems and their solutions.
To be a pragmatic programmer, we need to take ownership of our projects. We should take full responsibility of it's problems, and not sit idly by knowing they exist.

### Topic 1. It's Your Life
Lots of people aren't happy in their jobs, location, or life in general. Programming is one of the easiest jobs to be able to make changes, we're paid well, and we work remotely. But programmers usually don't like change.
You have agency. Try to fix your problems but don't try forever. "You can change your organization, or you can change your organization." Investing in yourself off the clock is important. Do you want something from your current job? Have you asked? This career field provides a wide set of opportunities, be proactive and take them.

### Topic 2. The Cat Ate My Source Code
Take responsibility for your code and actions. Pragmatic programmers take charge of their own career, and aren't scared to admit to failure. Things happen. This means being honest and direct. Trusting your team is essential for creativity and collaboration. You have the right to not accept a responsibility due to possible unforseen uncontrolled events. However, if you do accept a responsibility, take ownership of what is going wrong. Provide options, don't make lame excuses. Run through the conversation in your mind before talking to your boss, how does it sound? Explain what can be done to salvage the situation. Don't be afraid to admit you need help. Flush out all lame excuses before saying them aloud. If you don't know, admit it but make sure you follow it up with "but i'll find out."

### Topic 3. Software Entropy
Entropy - Lack of order or predictability; gradual decline into disorder.
Debt and rot can spread uncontrollaby. The culture at work on a project can be a source of rot. Hopelessness can be contagious. Negative thoughts spreading through team members can be a viscious spiral. Don't leave broken windows. If you find broken code, fix it. If you can't fix the code, at least board it up. Neglect accelerates rot faster than any other factor. Don't let entropy win. Do no harm. Don't cause collateral damage because there's a crisis of some sort. One broken window is all it takes to begin the decline. A car will sit on the side of the road for weeks, but as soon as one window is broken, the car is stripped and turned upside down within hours. Don't be the first person to create broken windows in a project.

### Topic 4.
Coming soon...

### Topic 5.
Coming soon...

### Topic 6.
Coming soon...

### Topic 7.
Coming soon...

## Chapter 2. A Pragmatic Approach
There are topics that apply to all kinds of software. Those are the following:

### Topic 8. The Essence of Good Design
Good design is easier to change than bad design. It is well designed if it easily adapts by those who use it. ETC - easier to change. ETC is a value, not a rule. It will help you make decisions. Ask yourself, "Did the thing I just did make it easier or harder to change in the future?" To do this effectively, you need to develop instincts on how to write your code. You could easily fall into a practice of making code easier to change but never actually writing new code. Practicing is key. Documenting what you changed and why is a good way to track your progress and learn from your past mistakes.

### Topic 9. DRY - The Evils of Duplication
Most of our time is spent in maintenance mode. Our understanding changes every day. When duplicating code in our projects, we are creating a maintenance nightmare. DRY - don't repeat yourself. When there is a duplication and you need to change something in the code, it's not a matter of if you'll remember to change the others, it's a matter of when you'll forget. Dry is about the duplication of knowledge and intent. Acid test - when one single facet of the code has to change, do you find yourself changing things in multiple places and in multiple formats? If so, your code is not DRY. Someone may have written a function that validates if someone's age is greater than 0, and a seperate function that validates the order quantity ensuring that it also is greater than 0. Someone might see this and think it's a DRY violation, but it isn't. They are two separate pieces of knowledge. The validation being the same for both pieces of knowledge is just a coincidence. Some believe you need to comment logic on each function you build. This is not the case. Your naming and function logic should be as clear as a comment. Ask yourself, "What does this comment add to the clarity of the function?"

### Topic 10. Orthogonality
Orthogonality - borrowed from geometry, the term signifies an independence or decoupling. Two or more things are orthogonal if changes in one doesn't affect the others. Good orthogonality can be a backend and frontend. You should be able to change the database without changing the user interface, and vise versa. Non-orthogonal sytems are much harder to change and control. Orthogonality can be used by our design. Developers already put this into practice but use terms like "modular", "component-based", and "layered". Systems should be composed of a set of modules that you can easily change independently. Be careful about using libraries and toolkits, make sure they don't change any processes of current code. Write shy code. Avoid global data. Get in the habit of being constantly critical of your code and always be improving it - this process is called refactoring. If orthogonality and DRY principles are followed in tandem, you will find that the systems you develop are more flexible, more understandable, and more easier to test and maintain. If you find that when you change a single piece of code, and you notice other things start breaking as a result, remember the system is not orthogonal - it is time to refactor.
