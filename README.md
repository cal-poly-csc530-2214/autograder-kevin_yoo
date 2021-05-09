# autograder-kevin_yoo
autograder-kevin_yoo created by GitHub Classroom

## Update 1
Read through the paper twice to get enough of an understanding of how the pipeline works. Also read through [this lecture](https://people.csail.mit.edu/asolar/SynthesisCourse/Lecture7.htm) as well as [this paper](https://people.csail.mit.edu/asolar/papers/Solar-Lezama09.pdf). A couple things I need to consider/big ideas that I am understanding the most:

* The search space increases exponentially with every correction rule. So this implementation can be really helpful for introductory level programs that don't have as much room for errors as other more complex programs.
* Having a short list of common mistakes (i.e. {a0, a0+1, a0-1} from the paper) is what I think is at the heart of this problem. Again, with each rule the search space increases exponentially. Programs that work well for this implementation will be those with easily identifiable common mistakes in a common syntactic form.

With this in mind, I am attempting to choose a common introductory CS problem which I will translate manually into something acceptable by SKETCH. 

