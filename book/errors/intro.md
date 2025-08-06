(errors)=
# Errors

<!-- ## Contents
- [Introduction](#Introduction)
- [Why are we doing testing](#Why-are-we-doing-testing)
- [What is debugging](#What-is-debugging)
- [Types of errors](#Types-of-errors)
- [Raising errors](#Raising-errors)
- [Handling errors](#try_except)
- [Assertions](#Assertions)
- [Logging](#Logging)
- [Exercises](#Exercises)
- [References and used resources](#References-and-used-resources) -->

This chapter focuses on a number of different topics to help you identify and fix _errors,_ which are an essential component of _software testing._ Incorporating the concepts in this chapter into your own coding practice will help you fix problems in the future, especially as you work on larger projects with multiple people.

**Why should we learn about software testing?**

Testing our code is necessary, because we as humans all make mistakes. Some of our mistakes may not be that important, but some can be dangeours and harmful. There are numerous examples of the latter such as the explosion of the Ariane 5 rocket or the problem with NASA’s Mars Climate Orbiter. You can read more on these examples [here](https://medium.com/swlh/some-of-the-most-famous-bugs-in-software-history-bb16a2ee3f8e). Testing our code for hidden flaws is the first step towards ensuring that the programs we write are robust.

```{figure} https://static.wixstatic.com/media/cfc1ef_55f398d6fbdb418ea4970567251efe6a.png/v1/fill/w_680,h_476,al_c,q_95/cfc1ef_55f398d6fbdb418ea4970567251efe6a.webp
---
name: nasa
---
A depiction of the NASA's Mars Climate Orbiter disaster. The incongruence in the units used by scientists at NASA (metric unit) and Lockheed Martin (US customary units) led the space probe too close to the planet. It was either destroyed in the atmosphere or escaped the planet's vicinity and entered an orbit around the Sun. (Source: Unleesh.com)
```


**What is debugging?**

Debugging is the process of identifying code-related problems (bugs) by analysing the behaviour of the program we have written. Testing and debugging are complementary to one another. Testing is used to identify a bug, while debugging is used to fix a bug.

In the sections that follow, we will start to learn about errors as a practical way of identifying issues with our code. Then we will learn how to improve our code with testing to make it easier to debug in the future.


<!-- **Additional Resources**

New sections will be added to this chapter progressively throughout the semester. -->

<!-- If you are interested in the topic, you can check out the references below, some of which were also used in the creation of this chapter:

- https://carpentries-lab.github.io/python-aos-lesson/08-defensive/index.html
- https://swcarpentry.github.io/python-novice-inflammation/09-errors.html
- https://python-textbok.readthedocs.io/en/1.0/Errors_and_Exceptions.html
- https://docs.python.org/3/tutorial/errors.html
- https://coderefinery.github.io/testing/ -->
