https://powcoder.com
代写代考加微信 powcoder
Assignment Project Exam Help
Add WeChat powcoder
https://powcoder.com
代写代考加微信 powcoder
Assignment Project Exam Help
Add WeChat powcoder
Please fill out each TODO item in the header but change nothing else,
particularly nothing before the colon ":" on each line!

===================== HEADER ========================

Student #1, Name: TODO
Student #1, ugrad.cs.ubc.ca Login: TODO
Student #1, Student Number: TODO

Student #2, Name: TODO (or write "NONE")
Student #2, ugrad.cs.ubc.ca Login: TODO (or write "NONE")
Student #2, Student Number: TODO (or write "NONE")

Team name (for fun!): TODO

Acknowledgment that you understand and have followed the course's collaboration policy (READ IT at
http://www.ugrad.cs.ubc.ca/~cs311/current/_syllabus.php#Collaboration_Policy):

Signed: TODO (put your names here again as a signature)

===================== LOGISTICS =====================

Please fill in each of the following:

Approximate hours on the project: TODO (when you get there)

Acknowledgment of assistance (per the collab policy!): TODO

For teams, rough breakdown of work: TODO (no more than a paragraph needed!)

====================== THEORY =======================

1. In the description, we hinted that some features were similar to
existing features. In particular, "defquery" and "infer" share a
similarity with another pair of features, particularly in the way they
handle environments and delayed evaluation.  Explain which features
these are and what the similarity is.

2. Suppose instead of (interp), we had a function with the following signature:
;;interp-with-sampler: (SOMETHING) RSE? -> RSE-Value?
(define (interp-with-sampler sample-from-dist expr) ...)

That is, suppose we allowed someone calling this
function to interpret an expression, using
their own random number generator for "sample"
expressions.

What signature would we use in place of (SOMETHING)?
That is, what should the inputs and outputs of the
"sample-from-dist" function be?

3. In assignment 2, to add two distributions,
we looked at all combinations of values from the two.
This feature was removed in this assignment.
Given distributions D1 and D2, how could we
approximate {+ D1 D2} in our language,
using sample, defquery, and infer?

======================= BONUS =======================

If you attempted any bonuses, please note it here and describe how you approached them.

TODO
