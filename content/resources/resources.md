+++
# Custom widget.
widget = "blank"  # Do not modify this line!
headless = true  # Homepage is headless, other widget pages are not.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.
date = 2020-01-01

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
# title = "Demos"
# subtitle = ""


[design]
# Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[advanced]
 # Custom CSS. 
 # css_style = "padding-top: 20px; padding-bottom: 20px;"
 
 # CSS class.
 # css_class = ""
+++

This page provides brief descriptions and links to various tools we produced or use for our research and teaching.

### Research Resources

In recent years, we made sure that for our publications, all code is supplied as supplementary material. In the past, this was not always possible. To allow as much access and reproducibility to our work as possible, we link here to a collection of programs, scripts and descriptions to produce results in various publications. 

You can get the publications from the publication section of this webpage. Some of the code is relatively well documented, some isn't. Feel free to use and modify the programs any way you want. If you need help understanding certain programs, I will try to help. But my time is limited, and for a lot of the old programs, I might not even remember anymore what exactly I did. That's especially true for anything Matlab or Fortran since I haven't used either in years.

[TB Cough duration analysis](/files/software/Supercougher_Supplements.zip) - A zip file containing various supplementary R scripts and codebooks for a superspreading/supercoughing study in TB patients. The manuscript describing this work is _Handel et al 2019 IJTLD_.

[TB-MAC UGA Model](/files/software/TB_MAC_UGA.zip) - A file containing the R code and description of the model that was used by us to produce the results described in a multi-model project on TB intervention analysis. The results are described in _Houben et al. (2016) Lancet Global Health_.

[TB Persistence](/files/software/TBpersistenceCode.zip) - A collection of R scripts to run the simulations described in our 2014 PLoS One publication _Modeling the potential impact of host population survival on the evolution of M. tuberculosis latency._

[Avian flu](/files/software/AIVstudy.zip) - a collection of R scripts and accompanying data to do the various analyses described in _Handel et al. (2013) PLoS Comp Bio_.

[resimmcode.m](/files/software/resimmcode.zip) - A short Matlab program that simulates the dynamics of bacteria and drugs during emergence of resistance. A version of this code was used in our paper [_Exploring the role of the immune response in preventing antibiotic resistance_](https://doi.org/10.1016/j.jtbi.2008.10.025).

[Gapjunction ABM](/files/software/gapjunction.zip) - An agent-based simulation, written for the freely available [Netlogo platform](http://ccl.northwestern.edu/netlogo/). The code simulates gap junction mediated antigen transport during the local spread of virus and clearance by CTL. The simulation is described and used in 
_Handel et al. 2009 JRSI_.

[Bacteria evolution simulation](/files/software/populationmodel.zip) - A Matlab program that simulates the evolution of a bacterial population in repeated exponential growth and serial dilution cycles. A version of this code was used in _Handel and Rozen 2009 BMC Evo Bio_. Note that this uses the [lightspeed collection of Matlab functions](https://github.com/tminka/lightspeed).

[Compensatory Mutations](/files/software/compensatorymutation.zip) - (sparsely documented) Matlab and Fortran programs to simulate the evolution and spread of drug resistance through compensatory mutations. Details about the mathematical model can be found in _Handel et al (2006) PLoS Comp Bio_.


### Teaching Resources

I use the materials in this section for several of the classes and workshops I teach. You are of course free to use 
them independently from any of my courses.

#### Software

[__DSAIDE__](https://ahgroup.github.io/DSAIDE/) - Dynamical Systems Approaches to Infectious Disease Epidemiology. This is an R package containing multiple Infectious Disease Epidemiology models that the user/student can run through a graphical user interface. 

[__DSAIRM__](https://ahgroup.github.io/DSAIRM/) - Dynamical Systems Approach to Immune Response Modeling. This R package consists of a set of simulations (refered to here as apps) that teach within-host infection dynamics and immune response modeling from a dynamical system perspective. By manipulating the models through a graphical (Shiny) user interface and working through the provided instructions, you can learn about some important concepts of within-host and immmune response modeling.

[__modelbuilder__](https://ahgroup.github.io/modelbuilder/) - Our latest R package, still in development, that allows users to build their own compartmental simulation models and analyze them without having to write any code.

[__flowdiagramr__](https://andreashandel.github.io/flowdiagramr/) - Is an - under development - R package that allows users to use R code to make hopefully nice flow diagrams.

[__quizgrader__](https://andreashandel.github.io/quizgrader/) - Is an R package that can be used to deploy a grading app to a Shiny server and auto-grade student quizzes. I use it in my teaching since I don't like our university's LMS.



#### Online Course Materials

[__Modern Applied Data Analysis (MADA)__](https://andreashandel.github.io/MADAcourse/) is a course I regularly teach online. All course materials are available online and can be used by anyone for self-learning. 

[__Simulation Modeling in Immunology (SMI)__](https://andreashandel.github.io/SMIcourse/) is a website with course materials covering within-host modeling and immunology. It is, among other things, used as part of an an annual workshop that I co-teach with my colleague Paul Thomas. 

[__Infectious Disease Epidemiology - A model based approach (IDEMA)__](https://andreashandel.github.io/IDEMAcourse/) is a graduate level course I regularly teach online. All materials from this course are avaiable on the website. 


#### Online Books and other materials

[__Infectious Disease Epidemiology - A model based approach (IDEMA) - an online textbook__](https://andreashandel.github.io/IDEMAbook/) this book goes with the course of the same mentioned in the previous section. The book will likely be under perpetual development, with some chapters being more complete than others. Most chapters are fairly readable and complete enough that I use it when I teach a course on that topic. It is however not thoroughly fact-checked, error-corrected, properly referenced, etc. While I have been considering the idea of turning this into a full/real book, in my current thinking the cost-benefit analysis doesn't pan out. I thus plan to leave it online for free as is, with occasional updates and fixes, but without an attempt to make it polished and complete enough for a printed book.

[Lists with further resources, pertaining to learning R, Data Analysis, and other topics.](https://andreashandel.github.io/research-and-teaching-resources/) - I maintain a compilation of links and bits of information related to my research and teaching on Github. Mainly as a quick look-up and reminder for myself, though others might find it useful too.


### Group Tools

This section is mainly intended for potential group members so they know what they might be getting themselves into. If others profit from some of the information, even better.

Our current programming environment of choice is the free and Open Source software [R](https://www.r-project.org/). We use it for almost all of our projects. While not required, using R through [R Studio](https://www.rstudio.com/) makes working in R more user/beginner friendly. R Studio is also free. Almost all of our current writing is also done in the R ecosystem using Rmarkdown/bookdown/blogdown, etc.

In the past, we have used [Netlogo](http://ccl.northwestern.edu/netlogo/), a free agent based simulation platform, for both teaching and research. It is fairly easy to program, has lots of examples and is quite flexible. The main disadvantage is that it's not that fast.

Sometimes we need to do a bit of analytics. While [Mathematica](http://www.wolfram.com/products/mathematica/index.html) and [Maple](http://www.maplesoft.com/) are the two main programs for analytical calculations, they are expensive. We have found that for our purpose, the freely available [Maxima](http://maxima.sourceforge.net/) suffices.

We do all our reference management using the BibTeX format with either [JabRef](http://jabref.sourceforge.net/) or [Zotero](http://www.zotero.org/) as front end reference manager. Both are free.


If you need to regularly synchronzie files between different machines, [Dropbox](https://www.dropbox.com/), is very useful. Dropbox even works nicely with large files, such as encrypted [VeraCrypt](https://www.veracrypt.fr/) containers. For more structured work and syncing between computers and users, [Github](https://github.com) is our preferred mode of work.

If you can get people to send you their data, great! But often, that fails, even if the data is already published. A great tool to extract data from figures is the free program [Engauge Digitizer](http://digitizer.sourceforge.net/). The program [Data Thief](http://www.datathief.org/) provides similar functionality.
