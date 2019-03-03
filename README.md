# GSLIB: Geostatistical Library (Deutsch and Journel, 1998) Static Builds in Windows

* __What is this?__ 

Static builds of GSLIB for Windows to solve issues with missing DLL files. 

* __Why?__ 

GSLIB is a very powerful library of methods for constructing geostatistical modeling workflows.  Yet, the source code is in FORTRAN and with the modern use of dynamically linked libraries (DLLs) and the abscence of FORTRAN compilers on many Windows machines, people are now routinely getting 'missing DLL errors' when they try to use the available compiled code (e.g. [GSLIB.com](http://www.statios.com/software/gslib90.exe). By compiling the GSLIB source with static libraries instead of dynamically linked libraries we can overcome this issue and make GSLIB available to my students with Windows machines.

* __Why would I do this?__ 

When I teach I still find it useful to have access to GSLIB.  It provides the most simple, building block approach for geostatistical workflow construction.  I really appreciate the great contributions of Dr. Clayton Deutsch and Dr. Andre Journel to our modeling comunity.  My *GeostatsPy* Python package [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) is still under construction, in some cases I have simply just 'wrapped' the GSLIB executable.  i.e. the Python code writes the parameter and the input data files, runs the GSLIB executable and then reads the output back in.  I recognize that this is just a stop-gap, temporary solution.  I'm working on reimplimenting all of GSLIB along with other functionality in the Python package. 

### Michael Pyrcz, Associate Professor, University of Texas at Austin 
*Novel Data Analytics, Geostatistics and Machine Learning Subsurface Solutions*

With over 17 years of experience in subsurface consulting, research and development, Michael has returned to academia driven by his passion for teaching and enthusiasm for enhancing engineers' and geoscientists' impact in subsurface resource development. 

For more about Michael check out these links:

#### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

#### Want to Work Together?

I hope that this is helpful to those that want to learn more about subsurface modeling, data analytics and machine learning. Students and working professionals are welcome to participate.

* Want to invite me to visit your company for training, mentoring, project review, workflow design and consulting, I'd be happy to drop by and work with you! 

* Interested in partnering, supporting my graduate student research or my Subsurface Data Analytics and Machine Learning consortium (co-PIs including Profs. Foster, Torres-Verdin and van Oort)? My research combines data analytics, stochastic modeling and machine learning theory with practice to develop novel methods and workflows to add value. We are solving challenging subsurface problems!

* I can be reached at mpyrcz@austin.utexas.edu.

I'm always happy to discuss,

*Michael*

Michael Pyrcz, Ph.D., P.Eng. Associate Professor The Hildebrand Department of Petroleum and Geosystems Engineering, Bureau of Economic Geology, The Jackson School of Geosciences, The University of Texas at Austin

#### More Resources Available at: [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)
