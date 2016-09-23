From Zero To Iterators
===============================================================================

(This talk was presented at CppCon 2016.)

You've likely used the STL before, and you are probably comfortable
using std::vector some algorithms, but you may not be quite so
comfortable with STL iterators.  What even are "single pass writable
iterators"?  What does that mean to me as a user of the STL?

In this talk, we will motivate the iterator concept hierarchy as it
exists in the STL today by looking at useful algorithms and how they
traverse their input and output ranges.  will take these concrete
examples and slowly begin to abstract, building up the STL iterator
concepts, step-by-step.

After presenting the iterator concepts that exist in the STL today, we
will build up to two further iterator concepts by looking at useful
algorithms and then generalizing from them.  First, we will motivate
contiguous iterators, which have been voted into the C++17 working
draft.  Then, we will motivate a less-commonly known iterator concept,
segmented iterators, and show how they can help us write parallel and
cache-aware algorithms.

You should come away from this talk with an appreciation for generic
programming, experience with the syntax in the Concepts Lite Technical
Specification, and a better understanding of why iterators are
fundamental to the algorithms you write every day.

This work is licensed under a Creative Commons Attribution 4.0
International License.
