#Contents
* [Beginner's Delight](#beginners-delight)
* [Why Python?](#why-python)
* [Style Guide and Idioms](#style-guide-and-idioms)
* [Dictionary](#dictionary)
* [Decorators](#decorators)
* [Generators](#generators)
* [Iterators](#iterators)
* [Yield](#yield)
* [Context Managers](#context-managers)
* [Unicode](#unicode)
* [Networking](#networking)
* [Metaclasses](#metaclasses)
* [Documentation](#documentation)
    * [Sphinx](#sphinx)
* [Debugging](#debugging)
    * [Logging](#logging)
* [Testing](#testing)
* [Environments and Environment Management](#environments-and-environment-management)
* [Profiling](#profiling)
* [Packaging](#packaging)
* [Deployment](#deployment)
    * [Fabric](#fabric)
* [Warts and Gotchas](#warts-and-gotchas)
* [Web](#web)
    * [Frameworks](#frameworks)
        * [Flask](#flask)
        * [Web2Py](#web2py)
        * [Django](#django)
        * [Bottle](#bottle)
        * [Tornado](#tornado)
    * [Web Servers](#web-servers)
    * [API and Web Services](#api-and-web-services)
    * [Scraping](#scraping)
* [Mobile Development](#mobile-development)
    * [Kivy](#kivy)
* [Google Glass](#google-glass)
    * [Resources](#resources)
    * [Libraries](#libraries)
* [GUI Programming](#gui-programming)
* [Android](#Android)
    * [SL4A](#sl4a)
* [WSGI](#wsgi)
* [Databases](#databases)
    * [SQLAlchemy](#sqlalchemy)
* [Data Mining](#data-mining)
* [Data Analysis](#data-analysis)
    * [Pandas](#pandas)
* [IPython Notebooks](#ipython-notebooks)
* [Design Patterns](#design-patterns)
    * [Concurrency Patterns](#concurrency-patterns)
* [Concurrency and Distributed Systems](#concurrency-and-distributed-systems)
* [Functional Programming](#functional-programming)
* [Python 2 vs Python 3](#python-2-vs-3)
    * [Porting to Python 3](#porting-to-python-3)
* [Books](#books)
    * [Free](#free)
    * [Paid](#paid)
* [Online Courses and Challenges](#online-courses-and-challenges)
* [Discussions](#discussions)
* [Conferences and Events](#conferences-and-events)
* [Videos](#videos)
* [Editors and IDE's for Python programming](#editors-and-ides-for-python-programming)
* [Big Data](#bigdata)
* [Curated Python resources from other websites](#curated-python-resources-from-other-websites)
* [Newsletters](#newsletters)
* [Miscellaneous](#miscellaneous)


##Beginner's Delight
* [Beginner's guide to Python](http://wiki.python.org/moin/BeginnersGuide)
* [The Hitchhiker's guide to Python](http://docs.python-guide.org/en/latest/)
* [Learn Python the hard way](http://learnpythonthehardway.org/book/)
* [Learn Python](http://www.learnpython.org/)
* [Google's Python class](https://developers.google.com/edu/python/)
* [Python tracks at Codecademy](http://www.codecademy.com/tracks/python)
* [Python Monk](http://pythonmonk.com/)
* [Python for Beginners](http://www.pythonforbeginners.com/)
* [Best way to learn python](http://net.tutsplus.com/tutorials/the-best-way-to-learn-python/)
* [Python Tips, tools and resources](http://lurnq.com/lesson/Getting-started-with-Python-Tips-Tools-and-Resources)
* [Python Koans: Learn Python through TDD](https://github.com/gregmalcolm/python_koans)
* [LearnStreet Python course](http://www.learnstreet.com/lessons/study/python)
* [Beginner projects for a python newbie](http://newcoder.io/)
* [Learn X in Y minutes - Python](http://learnxinyminutes.com/docs/python/)
* [Python Practice book](http://anandology.com/python-practice-book/)
* [Facts and myths about Python names and values](http://nedbatchelder.com/text/names.html)
* [*args and **kwargs in python explained](http://freepythontips.wordpress.com/2013/08/04/args-and-kwargs-in-python-explained/)
* [Common newbie mistakes in Python- Part 1](http://blog.amir.rachum.com/post/54770419679/python-common-newbie-mistakes-part-1)
* [Common newbie mistakes in Python- Part 2](http://blog.amir.rachum.com/post/55024295793/python-common-newbie-mistakes-part-2)
* [PySchools](http://www.pyschools.com/)
* [Some cool Python Tricks](http://www.quora.com/Python-programming-language-1/What-are-some-cool-Python-tricks)
* [if x and if x is not None](http://blog.amir.rachum.com/post/30176371115/you-cant-handle-the-truth)
* [Better Python APIs](http://ozkatz.github.io/better-python-apis.html)
* [Declaring dependencies in Python](http://blog.ziade.org/2013/04/13/declaring-dependencies-in-python/)
* [Storing and Loading Data with JSON - Serialization/deserialization](http://freepythontips.wordpress.com/2013/08/08/storing-and-loading-data-with-json/)
* [A Guide to Python's Magic Methods](http://www.rafekettler.com/magicmethods.html)
* [Efficient String Concatenation in Python](http://www.skymind.com/~ocrow/python_string/)
* [Be Pythonic: __init__.py](http://mikegrouchy.com/blog/2012/05/be-pythonic-__init__py.html)
* [Building an open-source Python application the right way](http://kirang.in/2013/09/09/building-an-open-source-python-application-the-right-way/)
* [Python progression path - From apprentice to guru](http://stackoverflow.com/questions/2573135/python-progression-path-from-apprentice-to-guru)
* [Tutorialspoint python tutorial](http://www.tutorialspoint.com/python/)
* [Python Importing](http://blog.amir.rachum.com/post/63666832095/python-importing)
* [Python's super() considered super!](http://rhettinger.wordpress.com/2011/05/26/super-considered-super/)
* [No Naked Excepts](http://www.wilfred.me.uk/blog/2013/11/03/no-naked-excepts/)
* [Supercharge Your Python Developers](http://www.jeffknupp.com/blog/2013/11/15/supercharge-your-python-developers/)

##Why Python?
* [Python Success Stories](http://www.python.org/about/success/esr/)
* [Why Python - Slideshare](http://www.slideshare.net/arnav/python-presentation)
* [5 Reasons Why You Should Learn Python Programming](http://www.codercaste.com/2009/10/20/5-reasons-why-you-should-learn-python-programming/)
* [10 Reasons Python Rocks for Research (And a Few Reasons it Doesn’t)](http://www.stat.washington.edu/~hoytak/blog/whypython.html)
* [Why such popularity with Python?](https://programmers.stackexchange.com/questions/5427/why-such-popularity-with-python)
* [Why was Python's popularity so sudden?](https://programmers.stackexchange.com/questions/27207/why-was-pythons-popularity-so-sudden?rq=1)
* [Why Python?](http://www.reddit.com/r/Python/comments/1mb4y4/why_python/)
* [How Python became the language of choice for data science](http://blog.mikiobraun.de/2013/11/how-python-became-the-language-of-choice-for-data-science.html)

##Style Guide and Idioms
* [PEP 8 - Style Guide for Python Code](http://www.python.org/dev/peps/pep-0008/)
* [Code Like a Pythonista: Idiomatic Python](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)
* [Google Python Style Guide](http://google-styleguide.googlecode.com/svn/trunk/pyguide.html)
* [Python Idioms and Efficiency](https://www.memonic.com/user/pneff/folder/python/id/1bufp)
* [How not to write Python code](http://eikke.com/how-not-to-write-python-code/)
* [Docstring Conventions](http://www.python.org/dev/peps/pep-0257/)

##Dictionary
* [Python hash, id and dictionary order](http://blog.amir.rachum.com/post/54458435089/python-hash-id-and-dictionary-order)
* [Notes on dictionary implementation](http://bugs.python.org/file6941/dictnotes.txt)
* [Python: The Dictionary Playbook](http://blog.amir.rachum.com/post/39501813266/python-the-dictionary-playbook)

##Decorators
* [Understanding Python Decorators in 12 easy steps](http://simeonfranklin.com/blog/2012/jul/1/python-decorators-in-12-steps/)
* [Common uses of Python decorators - Quora](http://www.quora.com/Python-programming-language-1/What-are-common-uses-of-Python-decorators)
* [Common uses of Python decorators - Stack Overflow](http://stackoverflow.com/questions/489720/what-are-some-common-uses-for-python-decorators)
* [Python Decorators](http://pythonconquerstheuniverse.wordpress.com/2012/04/29/python-decorators/)
* [Decorators I: Introduction to Python Decorators](http://www.artima.com/weblogs/viewpost.jsp?thread=240808)
* [Decorators and annotations](http://blog.mattalcock.com/2013/1/5/decorates-and-annotations/)
* [The dark side of decorators](http://apiguy.github.io/blog/2013/06/03/the-dark-side-of-decorators/)
* [Thinking out aloud: Python decorators](http://curiosityhealsthecat.blogspot.in/2013/06/thinking-out-aloud-python-decorators_8528.html)
* [Using Python decorators for registering callbacks](http://curiosityhealsthecat.blogspot.in/2013/07/using-python-decorators-for-registering_8614.html)
* [Meta-matters: Using decorators for better Python programming](http://pydanny-event-notes.readthedocs.org/en/latest/PyconAU2011/decorators.html)
* [How can I make a chain of function decorators in Python?](http://stackoverflow.com/questions/739654/how-can-i-make-a-chain-of-function-decorators-in-python/1594484#1594484)
* [The Python Decorator Library](https://wiki.python.org/moin/PythonDecoratorLibrary)
* [Improve Your Python: Decorators Explained](http://www.jeffknupp.com/blog/2013/11/29/improve-your-python-decorators-explained/)
* [Painless Decorators](http://hackflow.com/blog/2013/11/03/painless-decorators/)

##Generators
* [Generator Tricks for Systems Programmers](http://www.dabeaz.com/generators-uk/)
* [Delegating to a Subgenerator in Python 3](http://docs.python.org/3/whatsnew/3.3.html#pep-380-syntax-for-delegating-to-a-subgenerator)

##Iterators
* [Understanding Iterators and Iterables](http://www.shutupandship.com/2012/01/understanding-python-iterables-and.html)

##Yield
* [Python yield keyword explained](http://stackoverflow.com/questions/231767/the-python-yield-keyword-explained)

##Context Managers
* [Understanding Python's with statement](http://effbot.org/zone/python-with-statement.htm)
* [The Python "with" Statement by Example](http://preshing.com/20110920/the-python-with-statement-by-example/)

##Unicode
* [Explain Unicode like I'm five years old](http://www.reddit.com/r/Python/comments/1g62eh/explain_it_like_im_five_python_and_unicode/)
* [Unicode Pain](http://nedbatchelder.com/text/unipain.html)
* [Python encodings and Unicode](http://eric.themoritzfamily.com/python-encodings-and-unicode.html)
* [The Updated Guide to Unicode on Python](http://lucumr.pocoo.org/2013/7/2/the-updated-guide-to-unicode/)
* [More About Unicode in Python 2 and 3](http://lucumr.pocoo.org/2014/1/5/unicode-in-2-and-3/)
* [Unicode in Python: Common Pitfalls](http://blogs.skicelab.com/maurizio/unicode-common-pitfalls.html)

##Networking
* [An intro to Python socket network programming](http://freepythontips.wordpress.com/2013/08/06/python-socket-network-programming/)

##Metaclasses
* [A primer on python metaclasses](http://jakevdp.github.io/blog/2012/12/01/a-primer-on-python-metaclasses/)
* [What is a metaclass in Python ?](http://stackoverflow.com/questions/100003/what-is-a-metaclass-in-python)
* [Yet Another Python Metaclass tutorial](http://blog.fruiapps.com/2013/03/Yet-another-Python-MetaClass-Tutorial)
* [Improve Your Python: Metaclasses and Dynamic Classes With Type](http://www.jeffknupp.com/blog/2013/12/28/improve-your-python-metaclasses-and-dynamic-classes-with-type/)
* [Metaprogramming in Python](http://pypix.com/python/metaprogramming-python/)

##Documentation
* [Documentation is King](http://kennethreitz.org/documentation-is-king/)
* [Make your open source project documentation suck less](http://kirang89.webfactional.com/2013/05/07/make-your-open-source-project-documentation-suck-less/)
* [Python Documentation Network](http://pydoc.net/)

###Sphinx
* [Quick Sphinx documentation for Python](http://scriptsonscripts.blogspot.in/2012/09/quick-sphinx-documentation-for-python.html)

## Environments and Environment Management
* [Virtualenv - The official documentation](http://www.virtualenv.org/en/latest/)
* [Virtual Environments — The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
* [Virtualenv Tutorial](http://simononsoftware.com/virtualenv-tutorial/)
* [A Primer on virtualenv](http://iamzed.com/2009/05/07/a-primer-on-virtualenv/)
* [How to use Python virtualenv](http://www.pythonforbeginners.com/basics/how-to-use-python-virtualenv)
* [Making Virtualenv play nice with Git](http://hmarr.com/2010/jan/19/making-virtualenv-play-nice-with-git/)
* [Extension to Virtualenv](https://bitbucket.org/dhellmann/virtualenvwrapper)
* [VirtualEnv Burrito = virtualenv + virtualenvwrapper](https://github.com/brainsik/virtualenv-burrito)

##Debugging
* [Debugging Tools in Python](http://blog.ionelmc.ro/2013/06/05/python-debugging-tools/)
* [Debugging Python Like a Boss](https://zapier.com/engineering/debugging-python-boss/)

###Logging
* [Sentry - realtime event logging and aggregation platform](https://sentry.readthedocs.org/en/latest/index.html)

##Testing
* [Nose Introduction](http://pythontesting.net/framework/nose/nose-introduction/)
* [Unittest Introduction](http://pythontesting.net/framework/unittest/unittest-introduction/)
* [How To Use Coverage.py With Unittest](https://github.com/audreyr/how-to/blob/master/python/use_coverage_with_unittest.rst)
* [An Extended Introduction to the nose Unit Testing Framework](http://ivory.idyll.org/articles/nose-intro.html)
* [Test strategies for your Python projects](http://blog.flaper87.com/post/522b9e560f06d32542ede77f/)
* [Improve Your Python: Understanding Unit Testing](http://jeffknupp.com/blog/2013/12/09/improve-your-python-understanding-unit-testing/)
* [An Introduction to Mocking in Python](http://www.toptal.com/python/an-introduction-to-mocking-in-python)

##Profiling
* [A guide to analyzing Python performance](http://www.huyng.com/posts/python-performance-analysis/)
* [Profiling Python Like a Boss](https://zapier.com/engineering/profiling-python-boss/)

##Packaging
* [The Hitchhiker’s Guide to Packaging](http://guide.python-distribute.org/)
* [Sharing Your Labor of Love: PyPI Quick And Dirty](http://hynek.me/articles/sharing-your-labor-of-love-pypi-quick-and-dirty/)
* [Open Sourcing a Python Project the Right Way](http://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/)
* [5 tips for packaging your Python projects](http://ziade.org/2011/08/19/5-tips-for-packaging-your-python-projects/)
* [AOSA: Python Packaging](http://www.aosabook.org/en/packaging.html)
* [The Package Dependency Blues](http://blog.miguelgrinberg.com/post/the-package-dependency-blues)
* [5 Simple Rules For Building Great Python Packages](http://axialcorps.com/2013/08/29/5-simple-rules-for-building-great-python-packages)
* [Unofficial Windows Binaries for Python Extension Packages](http://www.lfd.uci.edu/~gohlke/pythonlibs/)
* [Py2app: Standalone Mac OS X applications](http://pythonhosted.org/py2app/)
* [PyInstaller: Stand-alone executables, under Windows, Linux, Mac OS X, Solaris and AIX](http://www.pyinstaller.org/)

##Deployment
* [Solid Python Deployments for Everybody](http://hynek.me/talks/python-deployments)

###Fabric
* [Using Fabric in a development environment](http://www.pythonforbeginners.com/systems-programming/how-to-use-fabric-in-a-development-environment/)
* [Capture output from parallel execution with Fabric](http://dmsimard.com/2013/11/29/capture-output-from-parallel-execution-with-fabric/)

##Warts and Gotchas
* [Python 2.x gotcha's and landmines](http://stackoverflow.com/questions/530530/python-2-x-gotchas-and-landmines)
* [Python Warts](https://wiki.python.org/moin/PythonWarts)
* [Python Gotchas](http://blog.artlogic.com/2013/04/12/python-gotchas/)
* [Common Pitfalls in Python](http://stackoverflow.com/questions/1011431/common-pitfalls-in-python/1321075#1321075)

##Web
* [Python and Realtime Web](http://mrjoes.github.io/2013/06/21/python-realtime.html)

###Frameworks
####Flask
* [Flask Mega Tutorial Series](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
* [Designing a RESTful API with Python and Flask](http://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask)
* [Building websites in Python with Flask](http://maximebf.com/blog/2012/10/building-websites-in-python-with-flask)
* [How I structure my Flask apps](http://mattupstate.com/python/2013/06/26/how-i-structure-my-flask-applications.html)
* [Designing a RESTful API using Flask-RESTful](http://blog.miguelgrinberg.com/post/designing-a-restful-api-using-flask-restful)
* [Rapid Web Prototyping with Lightweight Tools](http://www.pixelmonkey.org/2013/03/13/rapid-web-prototyping-with-lightweight-tools)
* [Build a Simple, Static, Markdown-Powered Blog with Flask](http://www.jamesharding.ca/posts/simple-static-markdown-blog-in-flask/)
* [How to Build an API with Python and Flask](http://tech.pro/tutorial/1213/how-to-build-an-api-with-python-and-flask)
* [Create a Simple Music Streaming App with Flask](http://pypix.com/python/create-simple-music-streaming-app-flask/)

####Web2Py
* [Building a Twitter clone in Web2Py](http://fragile.org.uk/2013/06/twitter-clone-tutorial-in-web2py-part-1-getting-started/)

####Django
* [The official Django documentation](https://docs.djangoproject.com/en/1.5/)
* [Getting started with Django](http://gettingstartedwithdjango.com/)
* [Starting a Django 1.6 Project the Right Way](http://www.jeffknupp.com/blog/2013/12/18/starting-a-django-16-project-the-right-way/)
* [Building a hacker news clone in Django](http://arunrocks.com/building-a-hacker-news-clone-in-django-part-1/)
* [Djen of Django](http://agiliq.com/books/djenofdjango/)
* [Deploying Django](http://www.rdegges.com/deploying-django/)
* [Django by Example](http://www.lightbird.net/dbe/)
* [Django From the Ground Up (video tutorials)](http://showmedo.com/videotutorials/series?name=PPN7NA155)
* [Tango with Django](http://www.tangowithdjango.com/book/)
* [Django Screencasts](https://godjango.com/)
* [Let’s TDD a Simple App in Django](http://pypix.com/django/tdd-in-django/)
* [Django runserver and stunnel for testing HTTPS](http://mgile.com/post/4729505823/django-stunnel)
* [Scaling database with Django and HAProxy](http://engineering.hackerearth.com/2013/10/07/scaling-database-with-django-and-haproxy/)
* [Classy Class-Based Views](http://ccbv.co.uk/)

####Bottle
* [Developing with Bottle- Part 1](http://www.realpython.com/blog/python/developing-with-bottle-part-1/)

####Tornado
* [Tornado official documentation](http://www.tornadoweb.org/en/stable/documentation.html)
* [Fastest database for Tornado](http://www.peterbe.com/plog/fastestdb)

###Web Servers
* [A Comparison of Web Servers for Python Based Web Applications](https://www.digitalocean.com/community/articles/a-comparison-of-web-servers-for-python-based-web-applications)

###API and Web Services
* [How to access various web services in python](http://www.pythonforbeginners.com/python-on-the-web/how-to-access-various-web-services-in-python/)
* [Python API for various web services](http://www.pythonapi.com/)
* [Glassdoor API](https://github.com/hackerlist/glassdoor)

###Scraping
* [Web Scraping with BeautifulSoup](http://www.pythonforbeginners.com/python-on-the-web/web-scraping-with-beautifulsoup/)
* [Web Scraping 101 with Python](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/)
* [Web Scraping with Scrapy Framework](http://doc.scrapy.org/en/latest/intro/tutorial.html)
* [How to automatically search and download torrents with Python and Scrapy](http://fuzz-box.blogspot.in/2013/03/how-to-automatically-search-download-torrent-python-scrapy.html)

##Mobile Development
###Kivy
* [Creating an app in Kivy](http://archlinux.me/dusty/2013/06/13/creating-an-application-in-kivy-part-1/)

##Google Glass
###Resources
* [The official Python Quick Start for Google Glass](https://developers.google.com/glass/quickstart/python)

###Libraries
####glass.py
* [Create python web applications for Google Glass](https://github.com/SamyPesse/glass.py)

##Image Processing
* [Python Image Library - Examples](http://www.riisen.dk/dop/pil.html)

##GUI Programming
* [Python.org GUI Overview Page](https://wiki.python.org/moin/GuiProgramming)
* [PyQt Tutorial](http://zetcode.com/tutorials/pyqt4/)
* [Standalone executable for PyQt4 on Windows](http://www.py2exe.org/index.cgi/Py2exeAndPyQt)
* [Kivy GUI for cross-platform applications](http://kivy.org/)
* [EffBot.org Introduction to Tkinter](http://effbot.org/tkinterbook/tkinter-index.htm)
* [Pytkgen: JSON to Tkinter GUI Generator](https://github.com/tmetsch/pytkgen)
* [Intro to programming with Python and Tkinter](https://wiki.python.org/moin/Intro%20to%20programming%20with%20Python%20and%20Tkinter)

##Android
###SL4A
* [Making the Physics Gizmo app for Android using SL4A](http://www.brokenairplane.com/2011/08/im-not-texting-im-programming.html)

##WSGI
* [Getting started with WSGI](http://lucumr.pocoo.org/2007/5/21/getting-started-with-wsgi/)
* [WSGI Basics](http://agiliq.com/blog/2013/07/basics-wsgi/)

##Databases

###SQLAlchemy
* [SQLAlchemy](http://www.aosabook.org/en/sqlalchemy.html)
* [SQLAlchemy and you](http://lucumr.pocoo.org/2011/7/19/sqlachemy-and-you/)
* [Essential SQLAlchemy Tips and Techniques](http://pypix.com/tools-and-tips/essential-sqlalchemy/)
* [10 common stumbling blocks for SQLAlchemy newbies](http://alextechrants.blogspot.fr/2013/11/10-common-stumbling-blocks-for.html)

##Data Mining
* [Linux system mining using Python](http://architects.dzone.com/articles/linux-system-mining-python)

##Data Analysis
###Pandas
* [A 10 min intro to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* [Pandas and Python: Top 10](http://manishamde.github.io/blog/2013/03/07/pandas-and-python-top-10/)
* [Learn Pandas](https://bitbucket.org/hrojas/learn-pandas)

##IPython Notebooks
* [A Gallery of Interesting IPython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)
* [Statistical Natural Language Processing in Python | How To Do Things With Words. And Counters.](http://nbviewer.ipython.org/url/norvig.com/ipython/How%20to%20Do%20Things%20with%20Words.ipynb)
* [Analysis of World Bank Fertility Rate Data With Statsmodels PCA](http://nbviewer.ipython.org/urls/umich.box.com/shared/static/6m7f4lw9bdog241kqcmb.ipynb)
* [Modeling the Last Flight of MH370 with a Markov Chain Monte Carlo Method](http://nbviewer.ipython.org/github/myhrvold/MH370_MCMC/blob/master/MH370_MC_ConorMyhrvold.ipynb)
* [Differential Equations in Data Science](http://nbviewer.ipython.org/github/URXtech/techblog/blob/master/continuousTimeMarkovChain/markovChain.ipynb)
* [Stegotons: solitary waves arising in non-dispersive periodic media](http://nbviewer.ipython.org/gist/ketch/8554686)
* [The Traveling Salesperson Problem](http://nbviewer.ipython.org/url/norvig.com/ipython/TSPv3.ipynb)
* [Scientific Computing with Python](http://nbviewer.ipython.org/url/atwallab.cshl.edu/teaching/QBbootcamp3.ipynb)
* [Gaussian Blur](http://nbviewer.ipython.org/urls/raw.github.com/mroberts3000/GpuComputing/master/IPython/GaussianBlur.ipynb)
* [Understanding the FFT Algorithm](http://nbviewer.ipython.org/url/jakevdp.github.io/downloads/notebooks/UnderstandingTheFFT.ipynb)
* [lifelines: Survival Analysis in Python](http://nbviewer.ipython.org/urls/raw.github.com/CamDavidsonPilon/lifelines/master/Tutorial%20and%20Examples.ipynb)
* [Economics Simulation](http://nbviewer.ipython.org/url/norvig.com/ipython/Economics.ipynb)
* [An Introduction to Bayesian Methods for Multilevel Modeling](http://nbviewer.ipython.org/urls/raw.github.com/fonnesbeck/multilevel_modeling/master/multilevel_modeling.ipynb)
* [The Floods of the Nile](http://nbviewer.ipython.org/urls/raw.github.com/LCAV/SignalsOfTheDay/master/FloodsOfTheNile.ipynb)
* [Animal Foraging and the Evolution of Goal-Directed Cognition](http://nbviewer.ipython.org/urls/raw.github.com/rhiever/Intro-to-Evolutionary-Modeling/master/Animal%2520Foraging%2520and%2520the%2520Evolution%2520of%2520Goal-Directed%2520Cognition.ipynb)
* [Wikipedia data scraping functions](http://nbviewer.ipython.org/urls/raw.github.com/brianckeegan/Wikipedia/master/wikipedia_scraping.ipynb)
* [Python for Geosciences](https://github.com/koldunovn/python_for_geosciences)
* [Media Signal Processing](http://www.mat.ucsb.edu/201A/)
   * [Digital Filters](http://www.mat.ucsb.edu/201A/console/Digital_Filters-ipython.html)
   * [Image Filtering](http://www.mat.ucsb.edu/201A/console/Image_Filtering.html)
   * [Audio Features](http://www.mat.ucsb.edu/201A/console/Audio_Features.html)
   * [Feature Detection and Matching for Images](http://www.mat.ucsb.edu/201A/console/Feature_detection.html)
   * [Gestures](http://www.mat.ucsb.edu/201A/console/Gestures.html)

##Design Patterns
* [Python Best Practice Patterns by Vladimir Keleshev](http://www.youtube.com/watch?v=GZNUfkVIHAY)
* [28 Design Patterns in Python and Several Other Languages](https://github.com/oxnz/design-patterns)
* [Factory Pattern In Python](http://dailypython.wordpress.com/2013/08/04/factory-pattern-in-python/)

###Concurrency Patterns
* [Wasp's Nest: The Read-Copy-Update Pattern In Python](http://emptysqua.re/blog/wasps-nest-read-copy-update-python/)

##Concurrency and Distributed Systems
* [Gevent and ZeroMQ](http://architects.dzone.com/articles/gevent-zeromq)
* [Celery: Distributed Task Queue](https://celery.readthedocs.org/en/latest/getting-started/index.html)
* [Gevent for the working Python developer](http://sdiehl.github.io/gevent-tutorial/)

##Functional Programming
* [Recursion Explained with the Flood Fill Algorithm](http://inventwithpython.com/blog/2011/08/11/recursion-explained-with-the-flood-fill-algorithm-and-zombies-and-cats/)
* [Functional Programming in Python](http://pypix.com/python/functional-programming/)

##Python 2 vs 3
* [Python 2 or 3 ?](http://wiki.python.org/moin/Python2orPython3)
* [Python 3 Q & A](http://python-notes.curiousefficiency.org/en/latest/python3/questions_and_answers.html)
* [About Python 3](http://alexgaynor.net/2013/dec/30/about-python-3/)
* [Let’s talk about Python 3.0](http://www.b-list.org/weblog/2008/dec/05/python-3000/)
* [Pros and Cons about Python 3](http://lucumr.pocoo.org/2010/1/7/pros-and-cons-about-python-3/)

### Porting to Python 3
* [How to support both Python 2 and 3](http://ondrejcertik.blogspot.com/2013/08/how-to-support-both-python-2-and-3.html)
* [How CherryPy supports Python 2 and 3](http://pyvideo.org/video/689/how-cherrypy-supports-python-2-and-3)
* [Porting to Python 3 - The Book Site](http://python3porting.com/)

##Books
###Free
* [Free Programming Books - Python](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md#python)
* [Python Programming - Free Computer Books](http://freecomputerbooks.com/langPythonBooks.html)
* [Some free books on Python](http://pythonbooks.revolunet.com/)
* [Invent with Python](http://inventwithpython.com/chapters/)
* [Think Python](http://www.greenteapress.com/thinkpython/thinkpython.pdf)
* [Byte of Python](http://files.swaroopch.com/python/byte_of_python.pdf)
* [Snake Wrangling for Kids](http://www.briggs.net.nz/snake-wrangling-for-kids.html)
* [Data Structures and Algorithms with Object-Oriented Design Patterns in Python](http://www.brpreiss.com/books/opus7/html/book.html)
* [Python programming on wikibooks](http://en.wikibooks.org/wiki/Python_Programming)
* [Dive Into Python 3](http://getpython3.com/diveintopython3/)
* [Programming Computer Vision with Python](http://programmingcomputervision.com/)
* [Python for you and me](http://pymbook.readthedocs.org/en/latest/)
* [Program Arcade Games With Python And Pygame](http://programarcadegames.com/)

###Paid
* [Some list of paid books on python](http://wiki.python.org/moin/PythonBooks)
* [Porting to Python 3 - The Book Site](http://python3porting.com/)

##Online Courses and Challenges
* [A Gentle Introduction to Programming Using Python](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2011/index.htm)
* [Python Challenges](http://www.pythonchallenge.com/)
* [Project Euler](http://projecteuler.net)

##Discussions
* [What's your favorite programming language?](https://news.ycombinator.com/item?id=3746692)
* [What is your primary programming language?](https://news.ycombinator.com/item?id=5944863)
* [StackOverflow - Python beyond the basics](http://stackoverflow.com/questions/92230/python-beyond-the-basics)
* [StackOverflow - Python progression path from apprentice to guru](http://stackoverflow.com/questions/2573135/python-progression-path-from-apprentice-to-guru)
* [StackOverflow - Zen of Python](http://stackoverflow.com/questions/228181/zen-of-python)
* [StackOverflow - Hidden Features of Python](http://stackoverflow.com/questions/101268/hidden-features-of-python)

##Conferences and events
* [Official PyCon website](http://www.pycon.org/)
* [Lanyrd - Python Conference and Events](http://lanyrd.com/topics/python/)
* [Meetup.com - Python Meetup Groups](http://python.meetup.com/)

##Videos
* [Guido Van Rossum on the history of Python](http://www.youtube.com/watch?v=ugqu10JV7dk)
* [PyVideo](http://pyvideo.org/)
* [Khan Academy - Introduction to programming and computer science using Python](https://www.khanacademy.org/science/computer-science)
* [What are some "must-watch" Python videos ?](http://www.reddit.com/r/Python/comments/1rs7ub/what_are_some_mustwatch_python_videos/)
* [Lanyrd - Python Videos](http://lanyrd.com/topics/python/video/)
* [Python Videos, Tutorials and Screencasts at ShowMeDo](http://showmedo.com/videotutorials/python)
* [Talks by Brandon Rhodes](http://rhodesmill.org/brandon/talks/)
* [A Billion Rows per Second: Metaprogramming Python for Big Data](https://www.youtube.com/watch?v=rXj5nayS7Yg)
* [The newboston site tutorial](http://thenewboston.org/list.php?cat=36)
* [Python Programming Tutorials](https://www.youtube.com/playlist?list=PLEA1FEF17E1E5C0DA&feature=plcp)

##Editors and IDE's for Python programming
* [Setting up Sublime Text for Python Development](http://dbader.org/blog/setting-up-sublime-text-for-python-development)
* [Sublime Text 2 Love by Kenneth Reitz](http://kennethreitz.org/sublime-text-2-love/)
* [Sublime Text 2 tips for Python and web developers](http://opensourcehacker.com/2012/05/11/sublime-text-2-tips-for-python-and-web-developers/)
* [PyCharm](http://www.jetbrains.com/pycharm/)
* [Geany](http://geany.org/)
* [Geany with pylint](http://michaeljaylissner.com/blog/using-pylint-in-geany)
* [PyDev](http://pydev.org)
* [Ninja-IDE](http://ninja-ide.org/)
* [Emacs setup for python development environment](http://caisah.info/emacs-for-python/)
* [Emacs for python](https://github.com/gabrielelanaro/emacs-for-python)

##BigData
* [Mind map of Python for Big Data](http://www.xmind.net/m/WvfC/?goback=%2Emid_I2756675707*43_*1#%21)

##Curated Python resources from other websites
* [Python Resources (All) - Codesters.org](http://codesters.org/resource/topic/python/all/)

##Newsletters
* [Pycoder's](http://pycoders.com/)
* [Python Weekly](http://www.pythonweekly.com/)

##Miscellaneous
* [Good to great Python reads](http://jessenoller.com/good-to-great-python-reads/)
* [How to Create Barcodes in Your PDFs with Python](http://java.dzone.com/articles/how-create-barcodes-your-pdfs)
* [What are some good Python interview questions ?](http://www.quora.com/What-are-good-Python-interview-questions)
* [Python innards introduction](http://tech.blog.aknin.name/2010/04/02/pythons-innards-introduction/)
* [Projects - A list of practical projects](https://github.com/thekarangoel/Projects)
* [More Python Tutorials](http://awaretek.com/tutorials.html)
* [Developer Tools in Python](http://pypix.com/tools-and-tips/developer-tools/)
* [The Best of Python in 2013](http://pypix.com/roundups/best-python-2013/)
* [Top Projects of 2013](http://us4.campaign-archive2.com/?u=9735795484d2e4c204da82a29&id=384b699bca&e=1826c8bb55)
* [Advanced Regular Expression Tips and Techniques](http://pypix.com/tools-and-tips/advanced-regular-expression-tips-techniques/)
* [Advanced Data Structures in Python](http://pypix.com/python/advanced-data-structures-python/)
* [Simple Sudoku solver in python](http://freepythontips.wordpress.com/2013/09/01/sudoku-solver-in-python/)
* [Looking Inside Dropbox – Security whitepaper](http://freepythontips.wordpress.com/2013/08/30/looking-inside-dropbox-whitepaper/)
* [Why sorting an array makes a Python loop faster](http://rickystewart.wordpress.com/2013/09/03/why-sorting-an-array-makes-a-python-loop-faster/)
* [Python Integer object implementation](http://www.laurentluce.com/posts/python-integer-objects-implementation/)
* [The history of Python - Blog](http://python-history.blogspot.in/)
* [The ever useful and neat subprocess module](http://sharats.me/the-ever-useful-and-neat-subprocess-module.html)
* [Hidden Features in Python](http://stackoverflow.com/questions/101268/hidden-features-of-python/111176)
* [Python module of the week](http://pymotw.com/2/)
* [Become a programmer](http://programming-motherfucker.com/become.html#Python)
* [Python tutor](http://pythontutor.com/)
* [Best developer blogs about python - Quora](https://www.quora.com/Python-programming-language-1/What-are-the-best-developer-blogs-about-Python-development)
* [Python blogs -Stackoverflow](http://stackoverflow.com/questions/152480/python-blogs-that-you-regularly-follow)
* [Abstracting Control Flow](http://hackflow.com/blog/2013/10/08/abstracting-control-flow/)
* [Python Algorithm Visualizations done in Python running in the browser](http://pyalgoviz.appspot.com/)
* [Solving Every Sudoku Puzzle](http://norvig.com/sudoku.html)
* [IHeartPy!](http://www.iheartpy.com/)
