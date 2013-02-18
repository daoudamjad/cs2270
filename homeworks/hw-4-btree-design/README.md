B-Trees
========

This assignment is on designing your implementation for B-Trees.

The purpose is to take on a very complicated data structure, and
proceed purposefully and systematically according to a design that you
create.

You will find this useful:

[B-Tree Chapter](http://zgking.com:8080/home/donghui/publications/books/dshandbook_BTree.pdf)
by D. Zhang. In Handbook of Data Structures and Applications,
D. P. Mehta, S. Sahni (editors), Chapman & Hall/CRC, ISBN
1-5848-8435-5, 2004.

This week's homework is NOT graded by RetroGrade. You will write
something and send it according to the instructions below.

Write a __plain text__ document that outlines how you are going to go
about implementing the B-Tree. It does not need to be long, but it
does need to be thoughtful.

For all the various functions, consider:

* What does it take on input?
* What could be malformed about the input?
* What precautions should the function take to deal with 'bad' input?
* What B-Tree invariants could the function break? Under which
  circumstances?
* How will you check to make sure your function has not broken any
  B-Tree invariants?
* What does the function return if it completed normally?
* What does the function return if something went wrong?

It is also helpful to make diagrams that illustrate how various
functions call each other. This isn't necessary or required, but it
might help. I strongly recommend making whiteboard or pencil-on-napkin
diagrams. If you do, document your work in pictures. The diagrams can
help you figure out how low-level nodes work, and how the high-level
B-Tree works.

B-Tree Head File Soon
--------

I will put up the header file early this week. Don't design yourself
into a box. You can get started without knowing the exact signature
for each function.

What You Turn In
-----------

Here's a checklist:

* Email your __plain text__ document directly to your TA. If you don't
  know your TA, this will be a problem. Don't ask Gabe, because this
  will be embarrassing to you.
* Be sure to make the subject line include the string [b-tree]
  including the square brackets so we can filter them.
* CC gabe.johnson@gmail.com
* If you make diagrams or take pictures, zip them up (tarballs are
  OK), but be sure to use PDF, PNG, or JPEG format.
* Any photos should be less than 100k or so.
* Did I mention that the document has to be __plain text__? If you
  send a Word document, I will personally install a 50 point minus for
  your score in the database.

How we grade this
---------

We will spot check all of these, and if it looks like you have engaged
in the process we'll give you 15. If you made a vague attempt, you'll
get 7. If you're late (received after 6pm Friday) we'll cap it at 5
points.

This is really an exercise for you to get into the very good habit of
designing complicated things before you dive in and start hacking.