# CSC221-skolvitz-GroupProject

Group Project for CSC221 2020FA

**Owner:** Shannon Kolvitz - smkolvitz@my.waketech.edu

**Project Description:** Create a state web scraping program and share GitHub Repository.

**Web scraped URL:** [Oklahoma](https://en.wikipedia.org/wiki/Oklahoma)

**Collaborators:**

- Susan Rizzo           srizzo@waketech.edu
- Lee Lewis             lelewis1@my.waketech.edu - Accepted
- Rick Longoria         rlongoria@my.waketech.edu- Accepted
- Patrick Gabriel Luy   paluy@my.waketech.edu - Accepted
- Anna Malmberg         amalmberg@my.waketech.edu  - Accepted
<br/>
Suggestions from Anna:<br/>
1. You are importing some libraries that you are not using, I would leave them out if you're not using them.<br/>
2. I'm not sure about this, but your data looks very linear, are you sure that it's reading it correctly? I had to convert my datatype to int to get it to read properly.<br/>
<br/>

Suggestions from Lee:<br/>
Everything looks good besides what Anna brought up in her second point -- you need to convert the list of population counts into an int to make them plot properly. Due to the fact that they're still strings, they plot on the graph linearly. While they may be the correct numbers, they've still got the data type of 'str' so matplotlib can't make a difference between any of them. Once you convert the list of strings to a list of ints, everything should plot properly!

**Instructor:**
- Ms. Rizzo             srizzo@waketech.edu
