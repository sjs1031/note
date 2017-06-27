# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python frameworks, libraries, software and resources.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome Python](#awesome-python)
    - [Admin Panels](#admin-panels)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Anti-spam](#anti-spam)
    - [Asset Management](#asset-management)
    - [Audio](#audio)
    - [Authentication](#authentication)
    - [Build Tools](#build-tools)
    - [Caching](#caching)
    - [ChatOps Tools](#chatops-tools)
    - [CMS](#cms)
    - [Code Analysis and Linter](#code-analysis-and-linter)
    - [Command-line Tools](#command-line-tools)
    - [Compatibility](#compatibility)
    - [Computer Vision](#computer-vision)
    - [Concurrency and Parallelism](#concurrency-and-parallelism)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [Data Analysis](#data-analysis)
    - [Data Validation](#data-validation)
    - [Data Visualization](#data-visualization)
    - [Database Drivers](#database-drivers)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Debugging Tools](#debugging-tools)
    - [Deep Learning](#deep-learning)
    - [DevOps Tools](#devops-tools)
    - [Distribution](#distribution)
    - [Documentation](#documentation)
    - [Downloader](#downloader)
    - [E-commerce](#e-commerce)
    - [Editor Plugins and IDEs](#editor-plugins-and-ides)
    - [Email](#email)
    - [Environment Management](#environment-management)
    - [Files](#files)
    - [Foreign Function Interface](#foreign-function-interface)
    - [Forms](#forms)
    - [Functional Programming](#functional-programming)
    - [Game Development](#game-development)
    - [Geolocation](#geolocation)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [HTML Manipulation](#html-manipulation)
    - [HTTP](#http)
    - [Imagery](#imagery)
    - [Implementations](#implementations)
    - [Interactive Interpreter](#interactive-interpreter)
    - [Internationalization](#internationalization)
    - [Job Scheduler](#job-scheduler)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [MapReduce](#mapreduce)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Network Virtualization](#network-virtualization)
    - [Networking](#networking)
    - [News Feed](#news-feed)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Package Repositories](#package-repositories)
    - [Permissions](#permissions)
    - [Processes](#processes)
    - [Queue](#queue)
    - [Recommender Systems](#recommender-systems)
    - [RESTful API](#restful-api)
    - [RPC Servers](#rpc-servers)
    - [Science](#science)
    - [Search](#search)
    - [Serialization](#serialization)
    - [Serverless Frameworks](#serverless-frameworks)
    - [Specific Formats Processing](#specific-formats-processing)
    - [Static Site Generator](#static-site-generator)
    - [Tagging](#tagging)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [URL Manipulation](#url-manipulation)
    - [Video](#video)
    - [Web Content Extracting](#web-content-extracting)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
- [Services](#services)
    - [Code Quality](#code-quality)
    - [Continuous Integration](#continuous-integration)
- [Resources](#resources)
    - [Podcasts](#podcasts)
    - [Twitter](#twitter)
    - [Websites](#websites)
    - [Weekly](#weekly)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

- - -

## Admin Panels

*Libraries for administrative interfaces.*

* [Ajenti](https://github.com/ajenti/ajenti) - The admin panel your servers deserve.
* [django-suit](http://djangosuit.com/) - Alternative Django Admin-Interface (free only for Non-commercial use).
* [django-xadmin](https://github.com/sshwsfc/xadmin) - Drop-in replacement of Django admin comes with lots of goodies.
* [flask-admin](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask.
* [flower](https://github.com/mher/flower) - Real-time monitor and web admin for Celery.
* [Grappelli](http://grappelliproject.com) - A jazzy skin for the Django Admin-Interface.
* [Wooey](https://github.com/wooey/wooey) - A Django app which creates automatic web UIs for Python scripts.

## Algorithms and Design Patterns

*Python implementation of algorithms and design patterns.*

* [algorithms](https://github.com/nryoung/algorithms) - A module of algorithms for Python.
* [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - A simple yet effective library for implementing common design patterns.
* [python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns in Python.
* [sortedcontainers](http://www.grantjenks.com/docs/sortedcontainers/) - Fast, pure-Python implementation of SortedList, SortedDict, and SortedSet types.

## Anti-spam

*Libraries for fighting spam.*

* [django-simple-captcha](https://github.com/mbi/django-simple-captcha) - A simple and highly customizable Django app to add captcha images to any Django form.
* [django-simple-spam-blocker](https://github.com/moqada/django-simple-spam-blocker) - Simple spam blocker for Django.

## Asset Management

*Tools for managing, compressing and minifying website assets.*

* [django-compressor](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into a single cached file.
* [django-pipeline](https://github.com/jazzband/django-pipeline) - An asset packaging library for Django.
* [django-storages](https://github.com/jschneier/django-storages) - A collection of custom storage back ends for Django.
* [fanstatic](http://www.fanstatic.org/en/latest/) - Packages, optimizes, and serves static file dependencies as Python packages.
* [fileconveyor](http://fileconveyor.org/) - A daemon to detect and sync files to CDNs, S3 and FTP.
* [flask-assets](https://github.com/miracle2k/flask-assets) - Helps you integrate webassets into your Flask app.
* [jinja-assets-compressor](https://github.com/jaysonsantos/jinja-assets-compressor) - A Jinja extension to compile and compress your assets.
* [webassets](https://github.com/miracle2k/webassets) - Bundles, optimizes, and manages unique cache-busting URLs for static resources.

## Audio

*Libraries for manipulating audio.*

* [audiolazy](https://github.com/danilobellini/audiolazy) - Expressive Digital Signal Processing (DSP) package for Python.
* [audioread](https://github.com/beetbox/audioread) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
* [beets](http://beets.io/) - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
* [dejavu](https://github.com/worldveil/dejavu) - Audio fingerprinting and recognition.
* [django-elastic-transcoder](https://github.com/StreetVoice/django-elastic-transcoder) - Django + [Amazon Elastic Transcoder](http://aws.amazon.com/elastictranscoder/).
* [eyeD3](http://eyed3.nicfit.net/) - A tool for working with audio files, specifically MP3 files containing ID3 metadata.
* [id3reader](http://nedbatchelder.com/code/modules/id3reader.py) - A Python module for reading MP3 meta data.
* [m3u8](https://github.com/globocom/m3u8) - A module for parsing m3u8 file.
* [mingus](http://bspaans.github.io/python-mingus/) - An advanced music theory and notation package with MIDI file and playback support.
* [mutagen](https://github.com/quodlibet/mutagen) - A Python module to handle audio metadata.
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) - Python Audio Analysis Library: Feature Extraction, Classification, Segmentation and Applications
* [pydub](https://github.com/jiaaro/pydub) - Manipulate audio with a simple and easy high level interface.
* [pyechonest](https://github.com/echonest/pyechonest) - Python client for the [Echo Nest](http://developer.echonest.com/) API.
* [talkbox](http://scikits.appspot.com/talkbox) - A Python library for speech/signal processing.
* [TimeSide](https://github.com/Parisson/TimeSide) - Open web audio processing framework.
* [tinytag](https://github.com/devsnd/tinytag) - A library for reading music meta data of MP3, OGG, FLAC and Wave files.

## Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [Authomatic](http://peterhudec.github.io/authomatic/) - Simple but powerful framework agnostic authentication/authorization client.
    * [django-allauth](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works."
    * [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth 2 goodies for Django.
    * [Flask-OAuthlib](https://github.com/lepture/flask-oauthlib) - OAuth 1.0/a, 2.0 implementation of client and provider for Flask.
    * [OAuthLib](https://github.com/idan/oauthlib) - A generic and thorough implementation of the OAuth request-signing logic.
    * [python-oauth2](https://github.com/joestump/python-oauth2) - A fully tested, abstract interface to creating OAuth clients and servers.
    * [python-social-auth](https://github.com/omab/python-social-auth) - An easy-to-setup social authentication mechanism.
    * [rauth](https://github.com/litl/rauth) - A Python library for OAuth 1.0/a, 2.0, and Ofly.
    * [sanction](https://github.com/demianbrecht/sanction) - A dead simple OAuth2 client implementation.
* Others
    * [jose](https://github.com/demonware/jose) - JavaScript Object Signing and Encryption draft implementation.
    * [PyJWT](https://github.com/jpadilla/pyjwt) - Implementation of the JSON Web Token draft 01.
    * [python-jws](https://github.com/brianloveswords/python-jws) - Implementation of JSON Web Signatures draft 02.
    * [python-jwt](https://github.com/davedoesdev/python-jwt) - Module for generating and verifying JSON Web Tokens.

## Build Tools

*Compile software from source code.*

* [BitBake](http://www.yoctoproject.org/docs/1.6/bitbake-user-manual/bitbake-user-manual.html) - A make-like build tool for embedded Linux.
* [buildout](http://www.buildout.org/en/latest/) - A build system for creating, assembling and deploying applications from multiple parts.
* [PlatformIO](https://github.com/platformio/platformio) - A console tool to build code with different development platforms.
* [PyBuilder](https://github.com/pybuilder/pybuilder) - A continuous build tool written in pure Python.
* [SCons](http://www.scons.org/) - A software construction tool.

## CMS

*Content Management Systems.*

* [django-cms](http://www.django-cms.org/en/) - An Open source enterprise CMS based on the Django.
* [djedi-cms](http://djedi-cms.org/) - A lightweight but yet powerful Django CMS with plugins, inline editing and performance in mind.
* [FeinCMS](http://www.feincms.org/) - One of the most advanced Content Management Systems built on Django.
* [Kotti](http://kotti.pylonsproject.org/) - A high-level, Pythonic web application framework built on Pyramid.
* [Mezzanine](http://mezzanine.jupo.org/) - A powerful, consistent, and flexible content management platform.
* [Opps](http://opps.github.io/opps/) - A Django-based CMS for magazines, newspapers websites and portals with high-traffic.
* [Plone](https://plone.org/) - A CMS built on top of the open source application server Zope.
* [Quokka](http://quokkaproject.org/) - Flexible, extensible, small CMS powered by Flask and MongoDB.
* [Wagtail](https://wagtail.io/) - A Django content management system.
* [Widgy](https://wid.gy/) - Last CMS framework, based on Django.

## Caching

*Libraries for caching data.*

* [Beaker](https://github.com/bbangert/beaker) - A library for caching and sessions for use with web applications and stand-alone Python scripts and applications.
* [DiskCache](http://www.grantjenks.com/docs/diskcache/) - SQLite and file backed cache backend with faster lookups than memcached and redis.
* [django-cache-machine](https://github.com/django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models.
* [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.
* [django-viewlet](https://github.com/5monkeys/django-viewlet) - Render template parts with extended cache control.
* [dogpile.cache](http://dogpilecache.readthedocs.io/) - dogpile.cache is next generation replacement for Beaker made by same authors.
* [HermesCache](https://pypi.python.org/pypi/HermesCache) - Python caching library with tag-based invalidation and dogpile effect prevention.
* [johnny-cache](https://github.com/jmoiron/johnny-cache) - A caching framework for django applications.
* [pylibmc](https://github.com/lericson/pylibmc) - A Python wrapper around the [libmemcached](http://libmemcached.org/libMemcached.html) interface.

## ChatOps Tools

*Libraries for chatbot development.*

* [Errbot](http://errbot.io/) - The easiest and most popular chatbot to implement ChatOps.

## Code Analysis and Linter

*Libraries and tools for analysing, parsing and manipulation codebases.*

* Code Analysis
    * [coala](http://coala-analyzer.org/) - Language independent and easily extendable code analysis application.
    * [code2flow](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts.
    * [pycallgraph](https://github.com/gak/pycallgraph) - A library that visualises the flow (call graph) of your Python application.
    * [pysonar2](https://github.com/yinwang0/pysonar2) - A type inferencer and indexer for Python.
* Linter
    * [Flake8](https://pypi.python.org/pypi/flake8) - The modular source code checker: pep8, pyflakes and co.
    * [pylama](https://github.com/klen/pylama) - Code audit tool for Python and JavaScript.
    * [Pylint](https://www.pylint.org/) - A Fully customizable source code analyzer.

## Command-line Tools

*Libraries for building command-line application.*

* Command-line Application Development
    * [asciimatics](https://github.com/peterbrittain/asciimatics) - Cross-platform, full-screen terminal package (i.e.  mouse/keyboard input and coloured, positioned text output) complete with high-level API for complex animations and special effects.
    * [cement](http://builtoncement.com/) - CLI Application Framework for Python.
    * [click](http://click.pocoo.org/dev/) - A package for creating beautiful command line interfaces in a composable way.
    * [cliff](http://docs.openstack.org/developer/cliff/) - A framework for creating command-line programs with multi-level commands.
    * [clint](https://github.com/kennethreitz/clint) - Python Command-line Application Tools.
    * [colorama](https://pypi.python.org/pypi/colorama) - Cross-platform colored terminal text.
    * [docopt](http://docopt.org/) - Pythonic command line arguments parser.
    * [Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line
    * [Python-Fire](https://github.com/google/python-fire) - A library for creating command line interfaces (CLIs) from absolutely any Python object.
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - A Library for building powerful interactive command lines.
* Productivity Tools
    * [aws-cli](https://github.com/aws/aws-cli) - A universal command-line interface for Amazon Web Services.
    * [bashplotlib](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal.
    * [caniusepython3](https://github.com/brettcannon/caniusepython3) - Determine what projects are blocking you from porting to Python 3.
    * [cookiecutter](https://github.com/audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates).
    * [doitlive](https://github.com/sloria/doitlive) - A tool for live presentations in the terminal.
    * [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers via the command line.
    * [httpie](https://github.com/jkbrzt/httpie) - A command line HTTP client, a user-friendly cURL replacement.
    * [mycli](https://github.com/dbcli/mycli) - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting.
    * [PathPicker](https://github.com/facebook/PathPicker) - Select files out of bash output.
    * [percol](https://github.com/mooz/percol) - Adds flavor of interactive selection to the traditional pipe concept on UNIX.
    * [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting.
    * [SAWS](https://github.com/donnemartin/saws) - A Supercharged AWS CLI.
    * [thefuck](https://github.com/nvbn/thefuck) - Correcting your previous console command.
    * [try](https://github.com/timofurrer/try) - A dead simple CLI to try out python packages - It's never been easier.

## Compatibility

*Libraries for migrating from Python 2 to 3.*

* [Python-Future](http://python-future.org/index.html) - The missing compatibility layer between Python 2 and Python 3.
* [Python-Modernize](https://github.com/mitsuhiko/python-modernize) - Modernizes Python code for eventual Python 3 migration.
* [Six](https://pypi.python.org/pypi/six) - Python 2 and 3 compatibility utilities.

## Computer Vision

*Libraries for computer vision.*

* [OpenCV](http://opencv.org/) - Open Source Computer Vision Library.
* [pyocr](https://github.com/jflesch/pyocr) - A wrapper for Tesseract and Cuneiform.
* [pytesseract](https://github.com/madmaze/pytesseract) - Another wrapper for [Google Tesseract OCR](https://github.com/tesseract-ocr).
* [SimpleCV](http://simplecv.org/) - An open source framework for building computer vision applications.

## Concurrency and Parallelism

*Libraries for concurrent and parallel execution.*

* [eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).
* [multiprocessing](https://docs.python.org/2/library/multiprocessing.html) - (Python standard library) Process-based "threading" interface.
* [threading](https://docs.python.org/2/library/threading.html) - (Python standard library) Higher-level threading interface.
* [Tomorrow](https://github.com/madisonmay/Tomorrow) - Magic decorator syntax for asynchronous code.
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast implementation of asyncio event loop on top of libuv.

## Configuration

*Libraries for storing and parsing configuration options.*

* [config](https://www.red-dove.com/config-doc/) - Hierarchical config from the author of [logging](https://docs.python.org/2/library/logging.html).
* [ConfigObj](http://www.voidspace.org.uk/python/configobj.html) - INI file parser with validation.
* [ConfigParser](https://docs.python.org/2/library/configparser.html) - (Python standard library) INI file parser.
* [profig](http://profig.readthedocs.org/en/default/) - Config from multiple formats with value conversion.
* [python-decouple](https://github.com/henriquebastos/python-decouple) - Strict separation of settings from code.

## Cryptography

* [cryptography](https://cryptography.io/en/latest/) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [hashids](https://github.com/davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
* [Paramiko](http://www.paramiko.org/) - A Python (2.6+, 3.3+) implementation of the SSHv2 protocol, providing both client and server functionality.
* [Passlib](https://pythonhosted.org/passlib/) - Secure password storage/hashing library, very high level.
* [PyNacl](https://github.com/pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library.

## Data Analysis

*Libraries for data analyzing.*

* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data.
* [Open Mining](https://github.com/mining/mining) - Business Intelligence (BI) in Pandas interface.
* [Orange](http://orange.biolab.si/) - Data mining, data visualization, analysis and machine learning through visual programming or scripts.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [Cerberus](https://github.com/nicolaiarocci/cerberus/) - A lightweight and extensible data validation library.
* [colander](http://docs.pylonsproject.org/projects/colander/en/latest/) - Validating and deserializing data obtained via XML, JSON, an HTML form post.
* [jsonschema](https://github.com/Julian/jsonschema) - An implementation of [JSON Schema](http://json-schema.org/) for Python.
* [schema](https://github.com/keleshev/schema) - A library for validating Python data structures.
* [Schematics](https://github.com/schematics/schematics) - Data Structure Validation.
* [valideer](https://github.com/podio/valideer) - Lightweight extensible data validation and adaptation library.
* [voluptuous](https://github.com/alecthomas/voluptuous) - A Python data validation library.

## Data Visualization

*Libraries for visualizing data. See: [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Altair](https://github.com/altair-viz/altair) - Declarative statistical visualization library for Python.
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [ggplot](https://github.com/yhat/ggplot) - Same API as ggplot2 for R.
* [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [Pygal](http://www.pygal.org/en/latest/) - A Python SVG Charts Creator.
* [PyGraphviz](https://pypi.python.org/pypi/pygraphviz) - Python interface to [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.
* [VisPy](https://github.com/vispy/vispy) - High-performance scientific visualization based on OpenGL.

## Database

*Databases implemented in Python.*

* [pickleDB](https://pythonhosted.org/pickleDB/) - A simple and lightweight key-value store for Python.
* [PipelineDB](https://www.pipelinedb.com/) - The Streaming SQL Database.
* [TinyDB](https://github.com/msiemens/tinydb) - A tiny, document-oriented database.
* [ZODB](http://www.zodb.org/en/latest/) - A native object database for Python. A key-value and object graph database.


## Database Drivers

*Libraries for connecting and operating databases.*

* MySQL - [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysql-python](https://sourceforge.net/projects/mysql-python/) - The MySQL database connector for Python.
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - mysql-python fork supporting Python 3.
    * [oursql](https://pythonhosted.org/oursql/) - A better MySQL connector with support for native prepared statements and BLOBs.
    * [PyMySQL](https://github.com/PyMySQL/PyMySQL) - Pure Python MySQL driver compatible to mysql-python.
* PostgreSQL
    * [psycopg2](http://initd.org/psycopg/) - The most popular PostgreSQL adapter for Python.
    * [queries](https://github.com/gmr/queries) - A wrapper of the psycopg2 library for interacting with PostgreSQL.
    * [txpostgres](https://github.com/wulczer/txpostgres) - Twisted based asynchronous driver for PostgreSQL.
* Other Relational Databases
    * [apsw](http://rogerbinns.github.io/apsw/) - Another Python SQLite wrapper.
    * [dataset](https://github.com/pudo/dataset) - Store Python dicts in a database - works with SQLite, MySQL, and PostgreSQL.
    * [pymssql](http://www.pymssql.org/en/latest/) - A simple database interface to Microsoft SQL Server.
* NoSQL Databases
    * [cassandra-python-driver](https://github.com/datastax/python-driver) - Python driver for Cassandra.
    * [HappyBase](https://github.com/wbolster/happybase) - A developer-friendly library for Apache HBase.
    * [Plyvel](https://github.com/wbolster/plyvel) - A fast and feature-rich Python interface to LevelDB.
    * [py2neo](http://py2neo.org/2.0/) - Python wrapper client for Neo4j's restful interface.
    * [pycassa](https://github.com/pycassa/pycassa) - Python Thrift driver for Cassandra.
    * [PyMongo](https://docs.mongodb.org/ecosystem/drivers/python/) - The official Python client for MongoDB.
    * [redis-py](https://github.com/andymccurdy/redis-py) - The Redis Python Client.
    * [telephus](https://github.com/driftx/Telephus) - Twisted based client for Cassandra.
    * [txRedis](https://github.com/deldotdr/txRedis) - Twisted based client for Redis.

## Date and Time

*Libraries for working with dates and times.*

* [arrow](https://github.com/crsmithdev/arrow) - Better dates & times for Python.
* [Chronyk](https://github.com/KoffeinFlummi/Chronyk) - A Python 3 library for parsing human-written times and dates.
* [dateutil](https://github.com/dateutil/dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/2/library/datetime.html) module.
* [delorean](https://github.com/myusuf3/delorean/) - A library for clearing up the inconvenient truths that arise dealing with datetimes.
* [moment](https://github.com/zachwill/moment) - A Python library for dealing with dates/times. Inspired by [Moment.js](http://momentjs.com/).
* [Pendulum](https://github.com/sdispater/pendulum) - Python datetimes made easy.
* [PyTime](https://github.com/shinux/PyTime) - A easy-use Python module which aims to operate date/time/datetime by string.
* [pytz](https://launchpad.net/pytz) - World timezone definitions, modern and historical. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.
* [when.py](https://github.com/dirn/When.py) - Providing user-friendly functions to help perform common date and time actions.

## Debugging Tools

*Libraries for debugging code.*

* pdb-like Debugger
    * [ipdb](https://pypi.python.org/pypi/ipdb) - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
    * [pdb++](https://pypi.python.org/pypi/pdbpp/) - Another drop-in replacement for pdb.
    * [pudb](https://pypi.python.org/pypi/pudb) - A full-screen, console-based Python debugger.
    * [remote-pdb](https://github.com/ionelmc/python-remote-pdb) - Remote vanilla PDB (over TCP sockets).
    * [wdb](https://github.com/Kozea/wdb) - An improbable web debugger through WebSockets.
* Profiler
    * [line_profiler](https://github.com/rkern/line_profiler) - Line-by-line profiling.
    * [memory_profiler](https://github.com/fabianp/memory_profiler) - Monitor Memory usage of Python code.
    * [profiling](https://github.com/what-studio/profiling) - An interactive Python profiler.
    * [vprof](https://github.com/nvdv/vprof) - Visual Python profiler.
* Others
    * [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar) - Display various debug information for Django.
    * [django-devserver](https://github.com/dcramer/django-devserver) - A drop-in replacement for Django's runserver.
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django-debug-toolbar to flask.
    * [hunter](https://github.com/ionelmc/python-hunter) - Hunter is a flexible code tracing toolkit.
    * [lptrace](https://github.com/khamidou/lptrace) - [strace](http://man7.org/linux/man-pages/man1/strace.1.html) for Python programs.
    * [manhole](https://github.com/ionelmc/python-manhole) - Debug service that will accept unix domain socket connections and present the stacktraces for all threads and an interactive prompt.
    * [pyelftools](https://github.com/eliben/pyelftools) - Parsing and analyzing ELF files and DWARF debugging information.
    * [pyringe](https://github.com/google/pyringe) - Debugger capable of attaching to and injecting code into Python processes.

## Deep Learning

*Frameworks for Neural Networks and Deep Learning. See: [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [Caffe](https://github.com/BVLC/caffe) - A fast open framework for deep learning..
* [Keras](https://github.com/fchollet/keras) - A high-level neural networks library and capable of running on top of either TensorFlow or Theano.
* [MXNet](https://github.com/dmlc/mxnet) - A deep learning framework designed for both efficiency and flexibility.
* [Neupy](http://neupy.com/pages/home.html) - Running and testing different Artificial Neural Networks algorithms.
* [Pytorch](http://pytorch.org/) - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [TensorFlow](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google.
* [Theano](https://github.com/Theano/Theano) - A library for fast numerical computation.

## DevOps Tools

*Software and libraries for DevOps.*

* [Ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform.
* [Cloud-Init](http://cloudinit.readthedocs.io/) - A multi-distribution package that handles early initialization of a cloud instance.
* [cuisine](https://github.com/sebastien/cuisine) - Chef-like functionality for Fabric.
* [Docker Compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).
* [Fabric](http://www.fabfile.org/) - A simple, Pythonic tool for remote execution and deployment.
* [Fabtools](https://github.com/ronnix/fabtools) - Tools for writing awesome Fabric files.
* [honcho](https://github.com/nickstenning/honcho) - A Python clone of [Foreman](https://github.com/ddollar/foreman), for managing Procfile-based applications.
* [OpenStack](http://www.openstack.org/) - Open source software for building private and public clouds.
* [pexpect](https://github.com/pexpect/pexpect) - Controlling interactive programs in a pseudo-terminal like GNU expect.
* [psutil](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module.
* [SaltStack](https://github.com/saltstack/salt) - Infrastructure automation and management system.
* [supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX.

## Distribution

*Libraries to create packaged executables for release distribution.*

* [dh-virtualenv](https://github.com/spotify/dh-virtualenv) - Build and distribute a virtualenv as a Debian package.
* [Nuitka](http://nuitka.net/) - Compile scripts, modules, packages to an executable or extension module.
* [py2app](http://pythonhosted.org/py2app/) - Freezes Python scripts (Mac OS X).
* [py2exe](http://www.py2exe.org/) - Freezes Python scripts (Windows).
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - Converts Python programs into stand-alone executables (cross-platform).
* [pynsist](http://pynsist.readthedocs.io/) - A tool to build Windows installers, installers bundle Python itself.

## Documentation

*Libraries for generating project documentation.*

* [Sphinx](http://www.sphinx-doc.org/en/latest/) - Python Documentation generator.
    * [awesome-sphinxdoc](https://github.com/yoloseem/awesome-sphinxdoc)
* [MkDocs](http://www.mkdocs.org/) - Markdown friendly documentation generator.
* [pdoc](https://github.com/BurntSushi/pdoc) - Epydoc replacement to auto generate API documentation for Python libraries.
* [Pycco](https://github.com/pycco-docs/pycco) - The literate-programming-style documentation generator.

## Downloader

*Libraries for downloading.*

* [s3cmd](https://github.com/s3tools/s3cmd) - A command line tool for managing Amazon S3 and CloudFront.
* [s4cmd](https://github.com/bloomreach/s4cmd) - Super S3 command line tool, good for higher performance.
* [you-get](https://www.soimort.org/you-get/) - A YouTube/Youku/Niconico video downloader written in Python 3.
* [youtube-dl](http://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.

## E-commerce

*Frameworks and libraries for e-commerce and payments.*

* [alipay](https://github.com/lxneng/alipay) - Unofficial Alipay API for Python.
* [Cartridge](https://github.com/stephenmcd/cartridge) - A shopping cart app built using the Mezzanine.
* [django-oscar](http://oscarcommerce.com/) - An open-source e-commerce framework for Django.
* [django-shop](https://github.com/awesto/django-shop) - A Django based shop system.
* [merchant](https://github.com/agiliq/merchant) - A Django app to accept payments from various payment processors.
* [money](https://github.com/carlospalol/money) - Money class with optional CLDR-backed locale-aware formatting and an extensible currency exchange solution.
* [python-currencies](https://github.com/Alir3z4/python-currencies) - Display money format and its filthy currencies.
* [forex-python](https://github.com/MicroPyramid/forex-python) - Foreign exchange rates, Bitcoin price index and currency conversion.
* [shoop](https://www.shoop.io/en/) - An open source E-Commerce platform based on Django.

## Editor Plugins and IDEs

* Emacs
    * [Elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment.
* Sublime Text
    * [Anaconda](https://github.com/DamnWidget/anaconda) - Anaconda turns your Sublime Text 3 in a full featured Python development IDE.
    * [SublimeJEDI](https://github.com/srusskih/SublimeJEDI) - A Sublime Text plugin to the awesome auto-complete library Jedi.
* Vim
    * [Jedi-vim](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python.
    * [Python-mode](https://github.com/klen/python-mode) - An all in one plugin for turning Vim into a Python IDE.
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi](https://github.com/davidhalter/jedi)-based completion engine for Python.
* Visual Studio
    * [PTVS](https://github.com/Microsoft/PTVS) - Python Tools for Visual Studio.
* Visual Studio Code
    * [Python](https://github.com/DonJayamanne/pythonVSCode) - An extension with rich support for the Python language, with features including linting, IntelliSense, formatting, refactoring, debugging, unit tests, and jupyter support.
    * [Magic Python](https://github.com/MagicStack/MagicPython) - Cutting edge Python syntax highlighter for Sublime Text, Atom, and Visual Studio Code. Used by GitHub to highlight your Python code!
* IDE
    * [LiClipse](http://www.liclipse.com/) - Free polyglot IDE based on Eclipse. Uses PyDev for Python support.
    * [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
    * [Spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE.

## Email

*Libraries for sending and parsing email.*

* [envelopes](http://tomekwojcik.github.io/envelopes/) - Mailing for human beings.
* [flanker](https://github.com/mailgun/flanker) - A email address and Mime parsing library.
* [imbox](https://github.com/martinrusev/imbox) - Python IMAP for Humans.
* [inbox.py](https://github.com/kennethreitz/inbox.py) - Python SMTP Server for Humans.
* [lamson](https://github.com/zedshaw/lamson) - Pythonic SMTP Application Server.
* [Marrow Mailer](https://github.com/marrow/mailer) - High-performance extensible mail delivery framework.
* [modoboa](https://github.com/tonioo/modoboa) - A mail hosting and management platform including a modern and simplified Web UI.
* [Nylas Sync Engine](https://github.com/nylas/sync-engine) - Providing a RESTful API on top of a powerful email sync platform.
* [yagmail](https://github.com/kootenpv/yagmail) - Yet another Gmail/SMTP client.

## Environment Management

*Libraries for Python version and environment management.*

* [Pipenv](https://github.com/kennethreitz/pipenv) - Sacred Marriage of Pipfile, Pip, & Virtualenv.
* [p](https://github.com/qw3rtman/p) - Dead simple interactive Python version management.
* [pyenv](https://github.com/yyuu/pyenv) - Simple Python version management.
* [venv](https://docs.python.org/3/library/venv.html) - (Python standard library in Python 3.3+) Creating lightweight virtual environments.
* [virtualenv](https://pypi.python.org/pypi/virtualenv) - A tool to create isolated Python environments.
* [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) - A set of extensions to virtualenv.

## Files

*Libraries for file manipulation and MIME type detection.*

* [imghdr](https://docs.python.org/2/library/imghdr.html) - (Python standard library) Determine the type of an image.
* [mimetypes](https://docs.python.org/2/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/2/library/os.path.html).
* [pathlib](https://pathlib.readthedocs.org/en/pep428/) - (Python standard library in Python 3.4+) An cross-platform, object-oriented path library.
* [python-magic](https://github.com/ahupp/python-magic) - A Python interface to the libmagic file type identification library.
* [Unipath](https://github.com/mikeorr/Unipath) - An object-oriented approach to file/directory operations.
* [watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events.

## Foreign Function Interface

*Libraries for providing foreign function interface.*

* [cffi](https://pypi.python.org/pypi/cffi) - Foreign Function Interface for Python calling C code.
* [ctypes](https://docs.python.org/2/library/ctypes.html) - (Python standard library) Foreign Function Interface for Python calling C code.
* [PyCUDA](https://mathema.tician.de/software/pycuda/) - A Python wrapper for Nvidia's CUDA API.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - Simplified Wrapper and Interface Generator.

## Forms

*Libraries for working with forms.*

* [Deform](https://github.com/Pylons/deform) - Python HTML form generation library influenced by the formish form generation library.
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3) - Bootstrap 3 integration with Django.
* [django-crispy-forms](https://github.com/maraujop/django-crispy-forms) - A Django app which lets you create beautiful forms in a very elegant and DRY way.
* [django-remote-forms](https://github.com/WiserTogether/django-remote-forms) - A platform independent Django form serializer.
* [WTForms](https://github.com/wtforms/wtforms) - A flexible forms validation and rendering library.

## Functional Programming

*Functional Programming with Python.*

* [CyToolz](https://github.com/pytoolz/cytoolz/) - Cython implementation of Toolz: High performance functional utilities.
* [fn.py](https://github.com/kachayev/fn.py) - Functional programming in Python: implementation of missing features to enjoy FP.
* [funcy](https://github.com/Suor/funcy) - A fancy and practical functional tools.
* [Toolz](https://github.com/pytoolz/toolz) - A collection of functional utilities for iterators, functions, and dictionaries.

## GUI

*Libraries for working with graphical user interface applications.*

* [curses](https://docs.python.org/2/library/curses.html#module-curses) - Built-in wrapper for [ncurses](http://www.gnu.org/software/ncurses/) used to create terminal GUI applications.
* [enaml](https://github.com/nucleic/enaml) - Creating beautiful user-interfaces with Declaratic Syntax like QML.
* [Flexx](https://github.com/zoofIO/flexx) - Flexx is a pure Python toolkit for creating GUI's, that uses web technology for its rendering.
* [kivy](https://kivy.org/) - A library for creating NUI applications, running on Windows, Linux, Mac OS X, Android and iOS.
* [pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home) - A cross-platform windowing and multimedia library for Python.
* [PyGObject](https://wiki.gnome.org/Projects/PyGObject) - Python Bindings for GLib/GObject/GIO/GTK+ (GTK+3)
* [PyQt](https://riverbankcomputing.com/software/pyqt/intro) - Python bindings for the [Qt](http://www.qt.io/) cross-platform application and UI framework, with support for both Qt v4 and Qt v5 frameworks.
* [PySide](https://wiki.qt.io/PySide) - Python bindings for the [Qt](http://www.qt.io/) cross-platform application and UI framework, supporting the Qt v4 framework.
* [pywebview](https://github.com/r0x0r/pywebview/) - A lightweight cross-platform native wrapper around a webview component that allows to display HTML content in its own native dedicated window
* [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
* [Toga](https://github.com/pybee/toga) - A Python native, OS native GUI toolkit.
* [urwid](http://urwid.org/) - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.
* [wxPython](http://wxpython.org/) - A blending of the wxWidgets C++ class library with the Python.

## Game Development

*Awesome game development libraries.*

* [Cocos2d](http://cocos2d.org/) - cocos2d is a framework for building 2D games, demos, and other graphical/interactive applications. It is based on pyglet.
* [Panda3D](https://www.panda3d.org/) - 3D game engine developed by Disney and maintained by Carnegie Mellon's Entertainment Technology Center. Written in C++, completely wrapped in Python.
* [Pygame](http://www.pygame.org/news.html) - Pygame is a set of Python modules designed for writing games.
* [PyOgre](http://www.ogre3d.org/tikiwiki/PyOgre) - Python bindings for the Ogre 3D render engine, can be used for games, simulations, anything 3D.
* [PyOpenGL](http://pyopengl.sourceforge.net/) - Python ctypes bindings for OpenGL and it's related APIs.
* [PySDL2](http://pysdl2.readthedocs.io/) - A ctypes based wrapper for the SDL2 library.
* [RenPy](https://www.renpy.org/) - A Visual Novel engine.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [django-countries](https://github.com/SmileyChris/django-countries) - A Django app that provides country choices for use with forms, flag icons static files, and a country field for models.
* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.
* [GeoIP](https://github.com/maxmind/geoip-api-python) - Python API for MaxMind GeoIP Legacy Database.
* [geojson](https://github.com/frewsxcv/python-geojson) - Python bindings and utilities for GeoJSON.
* [geopy](https://github.com/geopy/geopy) - Python Geocoding Toolbox.
* [pygeoip](https://github.com/appliedsec/pygeoip) - Pure Python GeoIP API.

## HTML Manipulation

*Libraries for working with HTML and XML.*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
* [bleach](https://github.com/mozilla/bleach) - A whitelist-based HTML sanitization and text linkification library.
* [cssutils](https://pypi.python.org/pypi/cssutils/) - A CSS library for Python.
* [html5lib](https://github.com/html5lib/html5lib-python) - A standards-compliant library for parsing and serializing HTML documents and fragments.
* [lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [MarkupSafe](https://github.com/pallets/markupsafe) - Implements a XML/HTML/XHTML Markup safe string for Python.
* [pyquery](https://github.com/gawel/pyquery) - A jQuery-like library for parsing HTML.
* [untangle](https://github.com/stchris/untangle) - Converts XML documents to Python objects for easy access.
* [WeasyPrint](http://weasyprint.org) - A visual rendering engine for HTML and CSS that can export to PDF.
* [xmldataset](https://xmldataset.readthedocs.io) - Simple XML Parsing.
* [xmltodict](https://github.com/martinblech/xmltodict) - Working with XML feel like you are working with JSON.

## HTTP

*Libraries for working with HTTP.*

* [grequests](https://github.com/kennethreitz/grequests) - requests + gevent for asynchronous HTTP requests.
* [httplib2](https://github.com/httplib2/httplib2) - Comprehensive HTTP client library.
* [requests](http://docs.python-requests.org/en/latest/) - HTTP Requests for Humans™.
* [treq](https://github.com/twisted/treq) - Python requests like API built on top of Twisted's HTTP client.
* [urllib3](https://github.com/shazow/urllib3) - A HTTP library with thread-safe connection pooling, file post support, sanity friendly.

## Hardware

*Libraries for programming with hardware.*

* [ino](http://inotool.org/) - Command line toolkit for working with [Arduino](https://www.arduino.cc/).
* [Pingo](http://www.pingo.io/) - Pingo provides a uniform API to program devices like the Raspberry Pi, pcDuino, Intel Galileo, etc.
* [Pyro](http://pyrorobotics.com/) - Python Robotics.
* [PyUserInput](https://github.com/SavinaRoja/PyUserInput) - A module for cross-platform control of the mouse and keyboard.
* [scapy](https://github.com/secdev/scapy) - A brilliant packet manipulation library.
* [wifi](https://github.com/rockymeza/wifi) - A Python library and command line tool for working with WiFi on Linux.

## Imagery

*Libraries for manipulating images.*

* [hmap](https://github.com/rossgoodwin/hmap) - Image histogram remapping.
* [imgSeek](https://sourceforge.net/projects/imgseek/) - A project for searching a collection of images using visual similarity.
* [nude.py](https://github.com/hhatto/nude.py) - Nudity detection.
* [pagan](https://github.com/daboth/pagan) - Retro identicon (Avatar) generation based on input string and hash.
* [pillow](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.
* [pyBarcode](https://pythonhosted.org/pyBarcode/) - Create barcodes in Python without needing PIL.
* [pygram](https://github.com/ajkumar25/pygram) - Instagram-like image filters.
* [python-qrcode](https://github.com/lincolnloop/python-qrcode) - A pure Python QR Code generator.
* [Quads](https://github.com/fogleman/Quads) - Computer art based on quadtrees.
* [scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.
* [thumbor](https://github.com/thumbor/thumbor) - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.
* [wand](https://github.com/dahlia/wand) - Python bindings for [MagickWand](http://www.imagemagick.org/script/magick-wand.php), C API for ImageMagick.

## Implementations

*Implementations of Python.*

* [CLPython](https://github.com/metawilm/cl-python) - Implementation of the Python programming language written in Common Lisp.
* [CPython](https://github.com/python/cpython) - **Default, most widely used implementation of the Python programming language written in C.** Optimizing Static Compiler for Python. Uses type mixins to compile Python into C or C++ modules resulting in large performance gains.
* [Grumpy](http://grump.io) - More compiler than interpreter as more powerful CPython2.7 replacement (alpha).
* [IronPython](https://github.com/IronLanguages/ironpython3) - Implementation of the Python programming language written in C# targeting the .NET Framework and Mono.
* [Jython](https://hg.python.org/jython) - Implementation of Python programming language written in Java for the Java virtual machine (JVM).
* [MicroPython](https://github.com/micropython/micropython) - MicroPython - a lean and efficient Python programming language implementation for microcontrollers and constrained systems
* [Numba](http://numba.pydata.org/) - Python JIT complier to LLVM aimed at scientific Python.
* [PeachPy](https://github.com/Maratyszcza/PeachPy) - x86-64 assembler embedded in Python. Can be used as inline assembler for Python or as a stand-alone assembler for Windows, Linux, OS X, Native Client and Go.
* [Pyjion](https://github.com/Microsoft/Pyjion) - A JIT for Python based upon CoreCLR.
* [PyPy](https://bitbucket.org/pypy/pypy) - Implementation of the Python programming language written in RPython and translated into C. PyPy focuses on speed, efficiency and compatibility with the original CPython interpreter. The interpreter uses black magic to make Python very fast without having to add in additional type information.
* [PySec](https://github.com/ebranca/owasp-pysec) - Hardened version of python that makes it easier for security professionals and developers to write applications more resilient to attacks and manipulations.
* [Pyston](https://github.com/dropbox/pyston) - A Python implementation built using LLVM and modern JIT techniques with the goal of achieving good performance.
* [Stackless Python](https://bitbucket.org/stackless-dev/stackless/wiki/Home) - An enhanced version of the Python programming language which allows programmers to reap the benefits of thread-based programming without the performance and complexity problems associated with conventional threads.

## Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [bpython](https://github.com/bpython/bpython) - A fancy interface to the Python interpreter.
* [Jupyter Notebook (IPython)](https://jupyter.org) - A rich toolkit to help you make the most out of using Python interactively.
* [ptpython](https://github.com/jonathanslenders/ptpython) - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).

## Internationalization

*Libraries for working with i18n.*

* [Babel](http://babel.pocoo.org/en/latest/) - An internationalization library for Python.
* [PyICU](https://github.com/ovalhub/pyicu) - A wrapper of International Components for Unicode C++ library ([ICU](http://site.icu-project.org/)).

## Job Scheduler

*Libraries for scheduling jobs.*

* [APScheduler](http://apscheduler.readthedocs.io/) - A light but powerful in-process task scheduler that lets you schedule functions.
* [django-schedule](https://github.com/thauber/django-schedule) - A calendaring app for Django.
* [doit](http://pydoit.org/) - A task runner and build tool.
* [gunnery](https://github.com/gunnery/gunnery) - Multipurpose task execution tool for distributed systems with web-based interface.
* [Joblib](http://pythonhosted.org/joblib/index.html) - A set of tools to provide lightweight pipelining in Python.
* [Plan](https://github.com/fengsp/plan) - Writing crontab file in Python like a charm.
* [schedule](https://github.com/dbader/schedule) - Python job scheduling for humans.
* [Spiff](https://github.com/knipknap/SpiffWorkflow) - A powerful workflow engine implemented in pure Python.
* [TaskFlow](http://docs.openstack.org/developer/taskflow/) - A Python library that helps to make task execution easy, consistent and reliable.

## Logging

*Libraries for generating and working with logs.*

* [Eliot](https://github.com/ClusterHQ/eliot) - Logging for complex & distributed systems.
* [logbook](http://logbook.readthedocs.io/en/stable/) - Logging replacement for Python.
* [logging](https://docs.python.org/2/library/logging.html) - (Python standard library) Logging facility for Python.
* [Sentry](https://pypi.python.org/pypi/sentry) - A realtime logging and aggregation server.

## Machine Learning

*Libraries for Machine Learning. See: [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modelling for Humans.
* [Metrics](https://github.com/dmlc/xgboost) - Machine learning evaluation metrics.
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing.
* [scikit-learn](http://scikit-learn.org/) - The most popular Python library for Machine Learning.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/).
* [xgboost](https://github.com/dmlc/xgboost) - A scalable, portable, and distributed gradient boosting library.

## MapReduce

*Frameworks and libraries for MapReduce.*

* [dpark](https://github.com/douban/dpark) - Python clone of Spark, a MapReduce alike framework in Python.
* [dumbo](https://github.com/klbostee/dumbo) - Python module that allows one to easily write and run Hadoop programs.
* [luigi](https://github.com/spotify/luigi) - A module that helps you build complex pipelines of batch jobs.
* [mrjob](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or Amazon Web Services.
* [PySpark](http://spark.apache.org/docs/latest/programming-guide.html) - The Spark Python API.
* [streamparse](https://github.com/Parsely/streamparse) - Run Python code against real-time streams of data. Integrates with [Apache Storm](http://storm.apache.org/).

## Microsoft Windows

*Python programming on Microsoft Windows.*

* [Python(x,y)](http://python-xy.github.io/) - Scientific-applications-oriented Python Distribution based on Qt and Spyder.
* [pythonlibs](http://www.lfd.uci.edu/~gohlke/pythonlibs/) - Unofficial Windows binaries for Python extension packages.
* [PythonNet](https://github.com/pythonnet/pythonnet) - Python Integration with the .NET Common Language Runtime (CLR).
* [PyWin32](https://sourceforge.net/projects/pywin32/) - Python Extensions for Windows.
* [WinPython](https://winpython.github.io/) - Portable development environment for Windows 7/8.

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [blinker](https://github.com/jek/blinker) - A fast Python in-process signal/event dispatching system.
* [itsdangerous](https://github.com/pallets/itsdangerous) - Various helpers to pass trusted data to untrusted environments.
* [pluginbase](https://github.com/mitsuhiko/pluginbase) - A simple but flexible plugin system for Python.
* [Pychievements](https://github.com/PacketPerception/pychievements) - A framework for creating and tracking achievements.
* [Tryton](http://www.tryton.org/) - A general purpose business framework.

## Natural Language Processing

*Libraries for working with human languages.*

* [Jieba](https://github.com/fxsjy/jieba) - Chinese text segmentation.
* [langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system.
* [NLTK](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
* [Pattern](http://www.clips.ua.ac.be/pattern) - A web mining module for the Python.
* [SnowNLP](https://github.com/isnowfy/snownlp) - A library for processing Chinese text.
* [spaCy](https://spacy.io/) - A library for industrial-strength natural language processing in Python and Cython.
* [TextBlob](https://github.com/sloria/TextBlob) - Providing a consistent API for diving into common NLP tasks.
* [TextGrocery](https://github.com/2shou/TextGrocery) - A simple, efficient short-text classification tool based on LibLinear and Jieba.

## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [Mininet](http://mininet.org/) - A popular network emulator and API written in Python.
* [POX](https://github.com/noxrepo/pox) - An open source development platform for Python-based Software Defined Networking (SDN) control applications, such as OpenFlow SDN controllers.
* [Pyretic](http://frenetic-lang.org/pyretic/) - A member of the Frenetic family of SDN programming languages that provides powerful abstractions over network switches or emulators.
* [SDX Platform](https://github.com/sdn-ixp/internet2award) - SDN based IXP implementation that leverages Mininet, POX and Pyretic.

## Networking

*Libraries for networking programming.*

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
* [diesel](https://github.com/dieseldev/diesel) - Greenlet-based event I/O Framework for Python.
* [pulsar](https://github.com/quantmind/pulsar) - Event-driven concurrent framework for Python.
* [pyzmq](http://zeromq.github.io/pyzmq/) - A Python wrapper for the ZeroMQ message library.
* [Twisted](https://twistedmatrix.com/trac/) - An event-driven networking engine.
* [txZMQ](https://github.com/smira/txZMQ) - Twisted based wrapper for the ZeroMQ message library.

## News Feed

*Libraries for building user's activities.*

* [django-activity-stream](https://github.com/justquick/django-activity-stream) - Generating generic activity streams from the actions on your site.
* [Stream-Framework](https://github.com/tschellenbach/Stream-Framework) - Building newsfeed and notification systems using Cassandra and Redis.

## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - A part of Django.
    * [SQLAlchemy](http://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
    * [Orator](https://orator-orm.com) -  The Orator ORM provides a simple yet beautiful ActiveRecord implementation.
    * [Peewee](https://github.com/coleifer/peewee) - A small, expressive ORM.
    * [PonyORM](https://ponyorm.com/) - ORM that provides a generator-oriented interface to SQL.
    * [pyDAL](https://github.com/web2py/pydal/) - A pure Python Database Abstraction Layer.
    * [python-sql](https://pypi.python.org/pypi/python-sql) - Write SQL queries pythonically.
* NoSQL Databases
    * [django-mongodb-engine](https://github.com/django-nonrel/mongodb-engine) - Django MongoDB Backend.
    * [flywheel](https://github.com/mathcamp/flywheel) - Object mapper for Amazon DynamoDB.
    * [hot-redis](https://github.com/stephenmcd/hot-redis) - Rich Python data types for Redis.
    * [MongoEngine](http://mongoengine.org/) - A Python Object-Document-Mapper for working with MongoDB.
    * [PynamoDB](https://github.com/jlafon/PynamoDB) - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).
    * [redisco](https://github.com/kiddouk/redisco) - A Python Library for Simple Models and Containers Persisted in Redis.
* Others
    * [butterdb](https://github.com/Widdershin/butterdb) - A Python ORM for Google Drive Spreadsheets.
    * [dataset](https://github.com/pudo/dataset) - A JSON-based database.

## Package Management

*Libraries for package and dependency management.*

* [pip](https://pip.pypa.io/en/stable/) - The Python package and dependency manager.
    * [Python Package Index](https://pypi.python.org/pypi)
* [conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager.
* [Curdling](http://clarete.li/curdling/) - Curdling is a command line tool for managing Python packages.
* [pip-tools](https://github.com/nvie/pip-tools) - A set of tools to keep your pinned Python dependencies fresh.
* [wheel](http://pythonwheels.com/) - The new standard of Python distribution and are intended to replace eggs.

## Package Repositories

*Local PyPI repository server and proxies.*

* [warehouse](https://github.com/pypa/warehouse) - Next generation Python Package Repository (PyPI).
    * [Warehouse](https://pypi.org/)
* [bandersnatch](https://bitbucket.org/pypa/bandersnatch) - PyPI mirroring tool provided by Python Packaging Authority (PyPA).
* [devpi](http://doc.devpi.net/latest/) - PyPI server and packaging/testing/release tool.
* [localshop](https://github.com/mvantellingen/localshop) - Local PyPI server (custom packages and auto-mirroring of pypi).

## Permissions

*Libraries that allow or deny users access to data or functionality.*

* [Carteblanche](https://github.com/neuman/python-carteblanche/) - Module to align code with thoughts of users and designers. Also magically handles navigation and permissions.
* [django-guardian](https://github.com/django-guardian/django-guardian) - Implementation of per object permissions for Django 1.2+
* [django-rules](https://github.com/dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database.

## Processes

*Libraries for starting and communicating with OS processes.*

* [envoy](https://github.com/kennethreitz/envoy) - Python [subprocess](https://docs.python.org/2/library/subprocess.html) for Humans™.
* [sarge](http://sarge.readthedocs.io/) - Yet another wrapper for subprocess.
* [sh](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python.

## Queue

*Libraries for working with event and task queues.*

* [celery](http://www.celeryproject.org/) - An asynchronous task queue/job queue based on distributed message passing.
* [huey](https://github.com/coleifer/huey) - Little multi-threaded task queue.
* [mrq](https://github.com/pricingassistant/mrq) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent.
* [rq](http://python-rq.org/) - Simple job queues for Python.
* [simpleq](https://github.com/rdegges/simpleq) - A simple, infinitely scalable, Amazon SQS based queue.

## Recommender Systems

*Libraries for building recommender systems*

* [annoy](https://github.com/spotify/annoy) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.
* [fastFM](https://github.com/ibayer/fastFM) - A library for Factorization Machines.
* [implicit](https://github.com/benfred/implicit) - A fast Python implementation of collaborative filtering for implicit datasets.
* [LightFM](https://github.com/lyst/lightfm) - A Python implementation of a number of popular recommendation algorithms.
* [surprise](http://surpriselib.com) - A scikit for building and analyzing recommender systems.

## RESTful API

*Libraries for developing RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
    * [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* Flask
    * [eve](https://github.com/nicolaiarocci/eve) - REST API framework powered by Flask, MongoDB and good intentions.
    * [flask-api-utils](https://github.com/marselester/flask-api-utils) - Taking care of API representation and authentication for Flask.
    * [flask-api](http://www.flaskapi.org/) - Browsable Web APIs for Flask.
    * [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask.
    * [flask-restless](https://github.com/jfinkels/flask-restless) - Generating RESTful APIs for database models defined with SQLAlchemy.
* Pyramid
    * [cornice](https://github.com/mozilla-services/cornice) - A RESTful framework for Pyramid.
* Framework agnostic
    * [falcon](http://falconframework.org/) - A high-performance framework for building cloud APIs and web app backends.
    * [hug](https://github.com/timothycrosley/hug) - A Python3 framework for cleanly exposing APIs over HTTP and the Command Line with automatic documentation and validation.
    * [restless](https://github.com/toastdriven/restless) - Framework agnostic REST framework based on lessons learned from Tastypie.
    * [ripozo](https://github.com/vertical-knowledge/ripozo) - Quickly creating REST/HATEOAS/Hypermedia APIs.
    * [sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems.

## RPC Servers

*RPC-compatible servers.*

* [SimpleJSONRPCServer](https://github.com/joshmarshall/jsonrpclib/) - This library is an implementation of the JSON-RPC specification.
* [SimpleXMLRPCServer](https://docs.python.org/2/library/simplexmlrpcserver.html) - (Python standard library) Simple XML-RPC server implementation, single-threaded.
* [zeroRPC](https://github.com/0rpc/zerorpc-python) - zerorpc is a flexible RPC implementation based on [ZeroMQ](http://zeromq.org/) and [MessagePack](http://msgpack.org/).

## Science

*Libraries for scientific computing.*

* [astropy](http://www.astropy.org/) - A community Python library for Astronomy.
* [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen) - Providing best-practice pipelines for fully automated high throughput sequencing analysis.
* [bccb](https://github.com/chapmanb/bcbb) - Collection of useful code related to biological analysis.
* [Biopython](http://biopython.org/wiki/Main_Page) - Biopython is a set of freely available tools for biological computation.
* [cclib](http://cclib.github.io/) - A library for parsing and interpreting the results of computational chemistry packages.
* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [NIPY](http://nipy.org) - A collection of neuroimaging toolkits.
* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [Open Babel](http://openbabel.org/wiki/Main_Page) - A chemical toolbox designed to speak the many languages of chemical data.
* [ObsPy](http://obspy.org) - A Python toolbox for seismology.
* [PyDy](http://www.pydy.org/) - Short for Python Dynamics, used to assist with workflow in the modeling of dynamic motion.
* [PyMC](https://github.com/pymc-devs/pymc3) - Markov Chain Monte Carlo sampling toolkit.
* [RDKit](http://www.rdkit.org/) - Cheminformatics and Machine Learning Software.
* [SciPy](http://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.
* [SymPy](https://github.com/sympy/sympy) - A Python library for symbolic mathematics.
* [Zipline](https://github.com/quantopian/zipline) - A Pythonic algorithmic trading library.
* [SimPy](https://bitbucket.org/simpy/simpy) -  A process-based discrete-event simulation framework.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [django-haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django.
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch.
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [esengine](https://github.com/catholabs/esengine) - ElasticSearch ODM (Object Document Mapper) for Python.
* [pysolr](https://github.com/django-haystack/pysolr) - A lightweight Python wrapper for Apache Solr (incl. SolrCloud awareness).
* [solrpy](https://github.com/edsu/solrpy) - A Python client for [solr](http://lucene.apache.org/solr/).
* [Whoosh](http://whoosh.readthedocs.io/) - A fast, pure Python search engine library.

## Serialization

*Libraries for serializing complex data types*

* [marshmallow](https://github.com/marshmallow-code/marshmallow) - marshmallow is an ORM/ODM/framework-agnostic library for converting complex datatypes, such as objects, to and from native Python datatypes.

## Serverless Frameworks

*Frameworks for developing serverless Python code.*

* [apex](https://github.com/apex/apex) - Build, deploy, and manage [AWS Lambda](https://aws.amazon.com/lambda/) functions with ease.
* [python-lambda](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying Python code in AWS Lambda.
* [Zappa](https://github.com/Miserlou/Zappa) - A tool for deploying WSGI applications on AWS Lambda and API Gateway.

## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
    * [tablib](https://github.com/kennethreitz/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
* Office
    * [Marmir](https://github.com/brianray/mm) - Takes Python data structures and turns them into spreadsheets.
    * [openpyxl](https://openpyxl.readthedocs.io/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
    * [pyexcel](https://github.com/pyexcel/pyexcel) - Providing one API for reading, manipulating and writing csv, ods, xls, xlsx and xlsm files.
    * [python-docx](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files.
    * [relatorio](http://relatorio.tryton.org/) - Templating OpenDocument files.
    * [unoconv](https://github.com/dagwieers/unoconv) - Convert between any document format supported by LibreOffice/OpenOffice.
    * [XlsxWriter](https://xlsxwriter.readthedocs.io) - A Python module for creating Excel .xlsx files.
    * [xlwings](http://xlwings.org/) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files.
* PDF
    * [PDFMiner](https://github.com/euske/pdfminer) - A tool for extracting information from PDF documents.
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages.
    * [ReportLab](http://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Markdown
    * [Mistune](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown.
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown.
* YAML
    * [PyYAML](http://pyyaml.org/) - YAML implementations for Python.
* CSV
    * [csvkit](https://github.com/wireservice/csvkit) - Utilities for converting to and working with CSV.
* Archive
    * [unp](https://github.com/mitsuhiko/unp) - A command line tool that can unpack archives easily.

## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [Cactus](https://github.com/koenbok/Cactus/) - Static site generator for designers.
* [Hyde](http://hyde.github.io/) - Jinja2-based static web site generator.
* [Lektor](https://www.getlektor.com/) - An easy to use static CMS and blog engine.
* [Nikola](https://www.getnikola.com/) - A static website and blog generator.
* [Pelican](http://blog.getpelican.com/) - Uses Markdown or ReST for content and Jinja 2 for themes. Supports DVCS, Disqus. AGPL.
* [Tinkerer](http://tinkerer.me/) - Tinkerer is a blogging engine/.static website generator powered by Sphinx.

## Tagging

*Libraries for tagging items.*

* [django-taggit](https://github.com/alex/django-taggit) - Simple tagging for Django.

## Template Engine

*Libraries and tools for templating and lexing.*

* [Genshi](https://genshi.edgewall.org/) - Python templating toolkit for generation of web-aware output.
* [Jinja2](https://github.com/pallets/jinja) - A modern and designer friendly templating language.
* [Mako](http://www.makotemplates.org/) - Hyperfast and lightweight templating for the Python platform.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [hypothesis](https://github.com/HypothesisWorks/hypothesis-python) - Hypothesis is an advanced Quickcheck style property based testing library.
    * [mamba](http://nestorsalceda.github.io/mamba/) - The definitive testing tool for Python. Born under the banner of BDD.
    * [nose](https://github.com/nose-devs/nose) - A nicer unittest for Python.
    * [nose2](https://github.com/nose-devs/nose2) - The successor to nose, based on unittest2.
    * [pytest](http://pytest.org/latest/) - A mature full-featured Python testing tool.
    * [Robot Framework](https://github.com/robotframework/robotframework) - A generic test automation framework.
    * [unittest](https://docs.python.org/2/library/unittest.html) - (Python standard library) Unit testing framework.
* Test Runners
    * [green](https://github.com/CleanCut/green) - A clean, colorful test runner.
    * [tox](https://tox.readthedocs.io/) - Auto builds and tests distributions in multiple Python versions
* GUI / Web Testing
    * [locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
    * [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings.
    * [Selenium](https://pypi.python.org/pypi/selenium) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [sixpack](https://github.com/seatgeek/sixpack) - A language-agnostic A/B Testing framework.
    * [splinter](https://github.com/cobrateam/splinter) - Open source tool for testing web applications.
* Mock
    * [doublex](https://pypi.python.org/pypi/doublex) - Powerful test doubles framework for Python.
    * [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
    * [httmock](https://github.com/patrys/httmock) - A mocking library for requests for Python 2.6+ and 3.2+.
    * [httpretty](https://github.com/gabrielfalcao/HTTPretty) - HTTP request mock tool for Python.
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
    * [responses](https://github.com/getsentry/responses) - A utility library for mocking out the requests Python library.
    * [VCR.py](https://github.com/kevin1024/vcrpy) - Record and replay HTTP interactions on your tests.
* Object Factories
    * [factory_boy](https://github.com/rbarrois/factory_boy) - A test fixtures replacement for Python.
    * [mixer](https://github.com/klen/mixer) - Another fixtures replacement. Supported Django, Flask, SQLAlchemy, Peewee and etc.
    * [model_mommy](https://github.com/vandersonmota/model_mommy) - Creating random fixtures for testing in Django.
* Code Coverage
    * [coverage](https://pypi.python.org/pypi/coverage) - Code coverage measurement.
* Fake Data
    * [church](https://github.com/lk-geimfari/church) - is a Python library that help you generate fake data.
    * [fake2db](https://github.com/emirozer/fake2db) - Fake database generator.
    * [faker](https://github.com/joke2k/faker) - A Python package that generates fake data.
    * [radar](https://pypi.python.org/pypi/radar) - Generate random datetime / time.
* Error Handler
    * [FuckIt.py](https://github.com/ajalt/fuckitpy) - FuckIt.py uses state-of-the-art technology to make sure your Python code runs whether it has any right to or not.

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
    * [chardet](https://github.com/chardet/chardet) - Python 2/3 compatible character encoding detector.
    * [difflib](https://docs.python.org/2/library/difflib.html) - (Python standard library) Helpers for computing deltas.
    * [ftfy](https://github.com/LuminosoInsight/python-ftfy) - Makes Unicode text less broken and more consistent automagically.
    * [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) - Fuzzy String Matching.
    * [Levenshtein](https://github.com/ztane/python-Levenshtein/) - Fast computation of Levenshtein distance and string similarity.
    * [pangu.py](https://github.com/vinta/pangu.py) - Spacing texts for CJK and alphanumerics.
    * [pyfiglet](https://github.com/pwaller/pyfiglet) - An implementation of figlet written in Python.
    * [shortuuid](https://github.com/stochastic-technologies/shortuuid) - A generator library for concise, unambiguous and URL-safe UUIDs.
    * [unidecode](https://pypi.python.org/pypi/Unidecode) - ASCII transliterations of Unicode text.
    * [uniout](https://github.com/moskytw/uniout) - Print readable chars instead of the escaped string.
    * [xpinyin](https://github.com/lxneng/xpinyin) - A library to translate Chinese hanzi (漢字) to pinyin (拼音).
* Slugify
    * [awesome-slugify](https://github.com/dimka665/awesome-slugify) - A Python slugify library that can preserve unicode.
    * [python-slugify](https://github.com/un33k/python-slugify) - A Python slugify library that translates unicode to ASCII.
    * [unicode-slugify](https://github.com/mozilla/unicode-slugify) - A slugifier that generates unicode slugs with Django as a dependency.
* Parser
    * [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - Parsing, formatting, storing and validating international phone numbers.
    * [PLY](http://www.dabeaz.com/ply/) - Implementation of lex and yacc parsing tools for Python
    * [Pygments](http://pygments.org/) - A generic syntax highlighter.
    * [pyparsing](http://pyparsing.wikispaces.com/) - A general purpose framework for generating parsers.
    * [python-nameparser](https://github.com/derek73/python-nameparser) - Parsing human names into their individual components.
    * [python-user-agents](https://github.com/selwin/python-user-agents) - Browser user agent parser.
    * [sqlparse](https://github.com/andialbrecht/sqlparse) - A non-validating SQL parser.

## Third-party APIs

*Libraries for accessing third party services APIs. See: [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [apache-libcloud](https://libcloud.apache.org/) - One Python library for all clouds.
* [boto3](https://github.com/boto/boto3) - Python interface to Amazon Web Services.
* [django-wordpress](https://github.com/sunlightlabs/django-wordpress/) - WordPress models and views for Django.
* [facebook-sdk](https://github.com/mobolic/facebook-sdk) - Facebook Platform Python SDK.
* [facepy](https://github.com/jgorset/facepy) - Facepy makes it really easy to interact with Facebook's Graph API
* [gmail](https://github.com/charlierguo/gmail) - A Pythonic interface for Gmail.
* [google-api-python-client](https://github.com/google/google-api-python-client) - Google APIs Client Library for Python.
* [gspread](https://github.com/burnash/gspread) - Google Spreadsheets Python API.
* [twython](https://github.com/ryanmcgrath/twython) - A Python wrapper for the Twitter API.

## URL Manipulation

*Libraries for parsing URLs.*

* [furl](https://github.com/gruns/furl) - A small Python library that makes parsing and manipulating URLs easy.
* [purl](https://github.com/codeinthehole/purl) - A simple, immutable URL class with a clean API for interrogation and manipulation.
* [pyshorteners](https://github.com/ellisonleao/pyshorteners) - A pure Python URL shortening lib.
* [short_url](https://github.com/Alir3z4/python-short_url) - Python implementation for generating Tiny URL and bit.ly-like URLs.
* [webargs](https://github.com/sloria/webargs) - A friendly library for parsing HTTP request arguments, with built-in support for popular web frameworks, including Flask, Django, Bottle, Tornado, and Pyramid.

## Video

*Libraries for manipulating video and GIFs.*

* [moviepy](http://zulko.github.io/moviepy/) - A module for script-based movie editing with many formats, including animated GIFs.
* [scikit-video](https://github.com/aizvorski/scikit-video) - Video processing routines for SciPy.

## WSGI Servers

*WSGI-compatible web servers.*

* [bjoern](https://pypi.python.org/pypi/bjoern) - Asynchronous, very fast and written in C.
* [fapws3](http://www.fapws.org/) - Asynchronous (network side only), written in C.
* [gunicorn](https://pypi.python.org/pypi/gunicorn) - Pre-forked, partly written in C.
* [meinheld](https://pypi.python.org/pypi/meinheld) - Asynchronous, partly written in C.
* [netius](https://github.com/hivesolutions/netius) - Asynchronous, very fast.
* [paste](http://pythonpaste.org/) - Multi-threaded, stable, tried and tested.
* [rocket](https://pypi.python.org/pypi/rocket) - Multi-threaded.
* [uWSGI](https://uwsgi-docs.readthedocs.io/) - A project aims at developing a full stack for building hosting services, written in C.
* [waitress](https://waitress.readthedocs.io/) - Multi-threaded, powers Pyramid.
* [Werkzeug](http://werkzeug.pocoo.org/) - A WSGI utility library for Python that powers Flask and can easily be embedded into your own projects.

## Web Content Extracting

*Libraries for extracting web contents.*

* [Haul](https://github.com/vinta/Haul) - An Extensible Image Crawler.
* [html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text.
* [lassie](https://github.com/michaelhelmick/lassie) - Web Content Retrieval for Humans.
* [micawber](https://github.com/coleifer/micawber) - A small library for extracting rich content from URLs.
* [newspaper](https://github.com/codelucas/newspaper) - News extraction, article extraction and content curation in Python.
* [opengraph](https://github.com/erikriver/opengraph) - A Python module to parse the Open Graph Protocol
* [python-goose](https://github.com/grangier/python-goose) - HTML Content/Article Extractor.
* [python-readability](https://github.com/buriy/python-readability) - Fast Python port of arc90's readability tool.
* [sanitize](https://github.com/Alir3z4/python-sanitize) - Bringing sanity to world of messed-up data.
* [sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and HTML pages.
* [textract](https://github.com/deanmalmgren/textract) - Extract text from any document, Word, PowerPoint, PDFs, etc.

## Web Crawling

*Libraries for scraping websites.*

* [cola](https://github.com/chineking/cola) - A distributed crawling framework.
* [Demiurge](https://github.com/matiasb/demiurge) - PyQuery-based scraping micro-framework.
* [feedparser](http://pythonhosted.org/feedparser/) - Universal feed parser.
* [Grab](http://grablib.org/) - Site scraping framework.
* [MechanicalSoup](https://github.com/hickford/MechanicalSoup) - A Python library for automating interaction with websites.
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy.
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system.
* [RoboBrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser.
* [Scrapy](http://scrapy.org/) - A fast high-level screen scraping and web crawling framework.

## Web Frameworks

*Full stack web frameworks.*

* [Bottle](http://bottlepy.org/docs/dev/index.html) - A fast, simple and lightweight WSGI micro web-framework.
* [CherryPy](http://www.cherrypy.org/) - A minimalist Python web framework, HTTP/1.1-compliant and WSGI thread-pooled.
* [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
    * [awesome-django](https://github.com/rosarior/awesome-django)
* [Flask](http://flask.pocoo.org/) - A microframework for Python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
* [Pyramid](http://www.pylonsproject.org/) - A small, fast, down-to-earth, open source Python web framework.
    * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid)
* [Sanic](https://github.com/channelcat/sanic) - Web server that's written to go fast.
* [Tornado](http://www.tornadoweb.org/en/latest/) - A Web framework and asynchronous networking library.
* [TurboGears](http://www.turbogears.org/) - A microframework that can scale up to a full stack solution.
* [Web2py](http://www.web2py.com/) - Full-stack enterprise framework for secure database-driven web-based applications.
    * [GitHub Web2py](https://github.com/web2py)

## WebSocket

*Libraries for working with WebSocket.*

* [AutobahnPython](https://github.com/crossbario/autobahn-python) - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).
* [Crossbar](https://github.com/crossbario/crossbar/) - Open-source Unified Application Router (Websocket & WAMP for Python on Autobahn).
* [django-socketio](https://github.com/stephenmcd/django-socketio) - WebSockets for Django.
* [WebSocket-for-Python](https://github.com/Lawouach/WebSocket-for-Python) - WebSocket client and server library for Python 2 and 3 as well as PyPy.

# Services

Online tools and APIs to simplify development.

## Continuous Integration

*See: [awesome-CIandCD](https://github.com/ciandcd/awesome-ciandcd#online-build-system).*

* [CircleCI](https://circleci.com/) - A CI service that can run very fast parallel testing. (GitHub only)
* [Travis CI](https://travis-ci.org) - A popular CI service for your open source and [private](https://travis-ci.com) projects. (GitHub only)
* [Vexor CI](https://vexor.io) - A continuous integration tool for private apps with pay-per-minute billing model.
* [Wercker](http://wercker.com/) - A Docker-based platform for building and deploying applications and microservices.

## Code Quality

* [Codacy](https://www.codacy.com/) - Automated Code Review to ship better code, faster. Free for Open Source.
* [Codecov](https://codecov.io/) - Code coverage dashboard.
* [Landscape](https://landscape.io/) - Hosted continuous Python code metrics.
* [QuantifiedCode](https://www.quantifiedcode.com/) - A data-driven, automated, continuous code review tool.

# Resources

Where to discover new Python libraries.

## Podcasts

* [Podcast.init](http://podcastinit.com/)
* [Talk Python To Me](https://talkpython.fm/)
* [Python Bytes](https://pythonbytes.fm)

## Twitter

* [@codetengu](https://twitter.com/codetengu)
* [@getpy](https://twitter.com/getpy)
* [@importpython](https://twitter.com/importpython)
* [@planetpython](https://twitter.com/planetpython)
* [@pycoders](https://twitter.com/pycoders)
* [@pypi](https://twitter.com/pypi)
* [@pythontrending](https://twitter.com/pythontrending)
* [@PythonWeekly](https://twitter.com/PythonWeekly)
* [@TalkPython](https://twitter.com/talkpython)

## Websites

* [/r/CoolGithubProjects](https://www.reddit.com/r/coolgithubprojects/)
* [/r/Python](https://www.reddit.com/r/python)
* [Awesome Python @LibHunt](http://python.libhunt.com)
* [Django Packages](https://www.djangopackages.com/)
* [Full Stack Python](https://www.fullstackpython.com/)
* [PyPI Ranking](http://pypi-ranking.info/alltime)
* [Python 3 Wall of Superpowers](http://python3wos.appspot.com/)
* [Python Hackers](http://pythonhackers.com/open-source/)
* [Python ZEEF](https://python.zeef.com/alan.richmond)
* [Python 开发社区](http://python.ctolib.com)
* [Trending Python repositories on GitHub today](https://github.com/trending?l=python)

## Weekly

* [CodeTengu Weekly](http://weekly.codetengu.com/)
* [Import Python Newsletter](http://importpython.com/newsletter/)
* [Pycoder's Weekly](http://pycoders.com/)
* [Python Weekly](http://www.pythonweekly.com/)
* [Python Bytes](https://pythonbytes.fm)

# Other Awesome Lists

List of lists.

* Monty
    * [awesome](https://github.com/sindresorhus/awesome)
    * [lists](https://github.com/jnv/lists)
* Python
    * [pycrumbs](https://github.com/kirang89/pycrumbs)
    * [python-github-projects](https://github.com/checkcheckzz/python-github-projects)
    * [python_reference](https://github.com/rasbt/python_reference)
    * [pythonidae](https://github.com/svaksha/pythonidae)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/vinta/awesome-python/pulls) by adding :+1: to them. Pull requests will be merged when their votes reach **20**.






# Best-websites-a-programmer-should-visit
Some useful websites for programmers.

When learning CS there are some useful sites you must know to get always informed in order to do your technologies eve and learn new things. Here is a non exhaustive list of some sites you should visit, this list will get updated as soon as I can get another link, but you can also contribute by adding those you know :wink:

<h3>Index</h3>
<ul>
<li><a href="#when-you-get-stuck">When you get stuck</a></li>
<li><a href="#news">News</a></li>
<li><a href="#coding-practice-for-beginners">Coding practice for beginners</a></li>
<li><a href="#for-those-who-want-to-start-a-small-project-but-cant-find-the-ideas">For those who want to start a small project but cant find the ideas</a></li>
<li><a href="#general-coding-advice">General Coding advice</a></li>
<li><a href="#coding-style">Coding Style</a></li>
<li><a href="#general-tools">General Tools</a></li>
<li><a href="#interview-preparation">Interview Preparation</a></li>
<li><a href="#documentaries">Documentaries</a></li>
<li><a href="#moocs-for-learning-something-new">MOOCs for learning something new</a></li>
<li><a href="#sites-related-to-your-preferred-programming-language-for-me-java">Sites related to your preferred programming language (For me Java)</a></li>
<li><a href="#learn-ai">Learn AI</a></li>
<li><a href="#seminar--research-writing--talks-etc">Seminar , research writing , talks etc</a></li>
<li><a href="#everything-in-one-place">Everything in one place</a></li>
<li><a href="#youtube-channels">YouTube Channels</a></li>
<li><a href="#good-articles">Good Articles</a></li>
<li><a href="#building-a-simple-compilerinterpreter">Building a Simple Compiler/interpreter</a></li>
<li><a href="#watch-others-code">Watch others code</a></li>
<li><a href="#what-should-a-programmer-know">What should a programmer know</a></li>
<li><a href="#competitive-programming">Competitive programming</a></li>
<li><a href="#computer-books">Computer Books</a></li>
<li><a href="#video-tutorials">Video Tutorials</a></li>
<li><a href="#online-compiler-and-sharing-code-snippets">Online Compiler and Sharing Code snippets</a></li>
<li><a href="#blogs-of-developers">Blogs of Developers</a></li>
<li><a href="#for-improving-your-english">For improving your English</a></li>
<li><a href="#when-you-get-bored-from-cs-related-stuff">When you get bored from CS related stuff</a></li>
</ul>

# When you get stuck
   * [Stack Overflow](http://stackoverflow.com/) : subscribe to their weekly newsletter and any other topic which you find interesting
   * [Quora](https://www.quora.com/) : A place to share knowledge and better understand the world:
   * [Learn Anything](https://learn-anything.xyz/) : Community curated knowledge graph of best paths for learning anything

# News
   * [Hacker News](https://news.ycombinator.com/) : news aggregator for programmers where civility is king, try a newsletter to get top news to your inbox:
   * [Hacker Newsletter](http://www.hackernewsletter.com/) : curated by hand, delivered weekly 
   * [Hacker News Digest](https://hndigest.com/) : curated automatically, delivered as frequently as you want	
   * [Ars Technica](http://arstechnica.com/) : posts unique quality articles
   * [ACM TechNews](http://technews.acm.org/)
   * [Lobsters](https://lobste.rs/) : Lobsters is a technology-focused community centered around link aggregation and discussion.
   * [TechCrunch](http://techcrunch.com/) : another good website for tech news
   * [GSMArena.com](http://gsmarena.com/) : news related to latest mobile phones and android.
   * [product hunt ](https://www.producthunt.com/) : Discover your next favorite thing
   * [AlternativeTo](https://alternativeto.net) : Crowdsourced software recommendations
   * [Better Dev Links](https://betterdev.link) : Weekly links to help you become a better developer

# Coding practice for beginners
   * [freeCodeCamp](https://www.freecodecamp.com/) : Learn to code and build projects for nonprofits. Build your full stack web development portfolio today
   * [Reddit.com/r/dailyprogrammer](http://www.reddit.com/r/dailyprogrammer) : interesting programming challenges where you can learn from looking at other's code , even if you are not able to solve code you can look at how others solved.
   * [Programming by Doing](http://programmingbydoing.com/) : very good site for those who want to start with absolute basics
   * [CodeAbbey - a place where everyone can master programming](http://codeabbey.com/) : Best place to begin with problems that start at the easiest and gradually increase difficulty with each problem.
   * [Exercism.io](http://exercism.io/) : download and solve practice problems in over 30 different languages, and share your solution with others.
   * [Programming Tasks](http://rosettacode.org/wiki/Category:Programming_Tasks) : large collection of small programs
   * [karan/Projects-Solutions](https://github.com/karan/Projects-Solutions) Solutions to most of the problems in the link above
   * [Lod - Cloud](http://lod-cloud.net/) : The Linking Open Data cloud diagram
   * [Cave of programming](https://caveofprogramming.com/) : Learn to program, Upgrade your skills.
   * [Codeacademy](https://www.codecademy.com/) : Learn to code interactively, for free.

# For those who want to start a small project but can't find the ideas
   * [martyr2s-mega-project-ideas-list](http://www.dreamincode.net/forums/topic/78802-martyr2s-mega-project-ideas-list/) : contains about 125 project ideas from beginner to intermediate level.
   * [karan/Projects](https://github.com/karan/Projects) : a large collection of small projects for beginners with
   * [Wrong "big projects" for beginners](http://rodiongork.tumblr.com/post/108155476418/wrong-big-projects-for-beginners) : How to choose where to start
   * [vicky002/1000-Projects](https://github.com/vicky002/1000_Projects) : Mega List of practical projects that one can solve in any programming language! 

# General Coding advice
   * [Things I Wish Someone Had Told Me When I Was Learning How to Code — Free Code Camp](https://medium.freecodecamp.com/things-i-wish-someone-had-told-me-when-i-was-learning-how-to-code-565fc9dcb329#.y5wbd3pj6)
   * [Lessons From A Lifetime Of Being A Programmer](http://thecodist.com/article/lessons_from_a_lifetime_of_being_a_programmer)
   * [Principles of Good Programming](http://www.artima.com/weblogs/viewpost.jsp?thread=331531)
   * [What every computer science major should know](http://matt.might.net/articles/what-cs-majors-should-know/)
   * [How to become a programmer, or the art of Googling well](https://okepi.wordpress.com/2014/08/21/how-to-become-a-programmer-or-the-art-of-googling-well/)
   * [Code Review Best Practices](http://kevinlondon.com/2015/05/05/code-review-best-practices.html)
   * [Dieter Rams : 10 Principles of Good Product Design](https://stephenhaunts.com/2013/12/11/dieter-rams-10-principles-of-good-product-design/)
   * [10-ways-to-be-a-better-developer](https://stephenhaunts.files.wordpress.com/2014/04/10-ways-to-be-a-better-developer.png)
   * [Working as a Software Developer](https://henrikwarne.com/2012/12/12/working-as-a-software-developer/)
   * [Software design pattern](https://en.wikipedia.org/wiki/Software_design_pattern) : The entire collection of Design Patterns.
   * [Design Patterns](https://sourcemaking.com/design_patterns) : Design Patterns explained in detial with examples.

# Coding Style
   * [CS 106B Coding Style Guide](http://stanford.edu/class/archive/cs/cs106b/cs106b.1158/styleguide.shtml) : must see for those who create spaghetti
   * [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
   * [Airbnb JS Style Guide](https://github.com/airbnb/javascript) : A mostly reasonable approach to JavaScript
   * [What are some bad coding habits you would recommend a beginner avoid getting into?](https://www.reddit.com/r/learnprogramming/comments/1i4ds4/what_are_some_bad_coding_habits_you_would/)
   * [Good C programming habits. • /r/C_Programming](https://www.reddit.com/r/C_Programming/comments/1vuubw/good_c_programming_habits/)
   * [How to Report Bugs Effectively](http://www.chiark.greenend.org.uk/~sgtatham/bugs.html)
   * [Debugging Faqs](http://www.umich.edu/~eecs381/generalFAQ/Debugging.html)
   * [Stuff you need to Code Better!](http://codebetter.com/)
   * [Directory of Online CS Courses](https://github.com/open-source-society/computer-science)
   * [Directory of CS Courses (many with online lectures)](https://github.com/prakhar1989/awesome-courses)

# General Tools

# Interview Preparation
  * [GeeksforGeeks | A computer science portal for geeks](http://www.geeksforgeeks.org/) : also subscribe to their feeds to get links to their new articles.
  * [A site for technical interview questions, brain teasers, puzzles, quizzles](http://www.techinterview.org/) : whatever the heck those are) and other things that make you think!
  * [Problems | LeetCode OJ ](https://leetcode.com/problemset/algorithms/) : Coding practice for interviews
  * [Programmer And Software Interview Questions Answers](http://www.programmerinterview.com/)
  * [Reddit.com/user/ashish2199/m/puzzles](https://www.reddit.com/user/ashish2199/m/puzzles) : Logic Puzzles
  * [A Collection of Quant Riddles With Answers](http://puzzles.nigelcoldwell.co.uk/)
  * [Aptitude Questions and Answers](http://www.indiabix.com/) : Quant and aptitude preparation
  * [Interview Archives - Java Honk](http://javahonk.com/category/interview/)
  * [Top 10 Algorithms for Coding Interview](http://www.programcreek.com/2012/11/top-10-algorithms-for-coding-interview/)
  * [Algorithm design canvas](http://www.hiredintech.com/algorithm-design/))
  * [Big-O Algorithm Complexity Cheat Sheet](http://bigocheatsheet.com/#)
  * [Unix / Linux Cheat Sheet](http://cheatsheetworld.com/programming/unix-linux-cheat-sheet/)
  * [How to interview](http://kelukelu.me/interview/index.html)
  * [How to Ace an Algorithms Interview](http://www.palantir.com/2011/09/how-to-rock-an-algorithms-interview/)
  * [Delightful Puzzles ](http://gurmeet.net/puzzles/)
  * [visualising data structures and algorithms through animation](http://visualgo.net/)
  * [Here's How to Prepare for Tech Interviews • /r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/comments/1jov24/heres_how_to_prepare_for_tech_interviews/)
  * [Guide to Tech Interviews](http://www.kchodorow.com/blog/2013/02/28/guide-to-tech-interviews/)
  * [Why You Make Less Money • /r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/comments/1b8wa3/why_you_make_less_money/)
  * [IIT Delhi Placement Experience](http://placement-iit2013.blogspot.in/)
  * [what_are_your_goto_questions_for_the_do_you_have?](https://www.reddit.com/r/cscareerquestions/comments/209rkq/what_are_your_goto_questions_for_the_do_you_have/)
  * [/r/cscareerquestions](https://www.reddit.com/r/cscareerquestions/comments/20ahfq/heres_a_pretty_big_list_of_programming_interview/) : Here's a pretty big list of programming interview questions I compiled while studying for big 4 interviews. I think you guys will find it useful! •
  * [Interviewing At Jane Street](https://blogs.janestreet.com/interviewing-at-jane-street/)
  * [How to prepare for an interview - 1](http://se7so.blogspot.in/2014/01/how-to-prepare-for-interview-1.html)
  * [Summer Internship: The Ultimate Guide](eulercoder.me/blog/career/Summer-Internship-the-ultimate-guide)
  * [The 25 most difficult HR questions ](http://www.datsi.fi.upm.es/~frosal/docs/25mdq.html)
  * [Job interviews News, Videos, Reviews and Gossip - Lifehacker ](http://lifehacker.com/tag/job-interviews)
  * [How to Answer the Toughest 40 Job Interview Questions | ICS Job Portal ](http://www.icsjobportal.com/blog/job-interview-questions/)
  * [Job Interview Questions and Best Answers ](http://jobsearch.about.com/od/interviewquestionsanswers/a/interviewquest.htm)
  * [How to Answer "Tell Me a Little About Yourself" | The Art of Manliness ](http://www.artofmanliness.com/2016/01/05/tell-me-a-little-about-yourself/)
  * [Job Interview: How to Ace a Job Interview | The Art of Manliness ](http://www.artofmanliness.com/2012/08/06/how-to-ace-a-job-interview/)
  * [Give your résumé a face lift ](http://www.lifeclever.com/give-your-resume-a-face-lift/)
  * [BIG O Misconceptions ](http://ssp.impulsetrain.com/big-o.html)
  * [Bitwise tricks ](https://gist.github.com/dideler/2365607)
  * [Core Java Interview questions - Interview question on each topic ](http://javahonk.com/core-java-interview-questions/)
  * [Java Interview Questions and Answers ](http://adnjavainterview.blogspot.in)
  * [Big collection of interview preparation links • /r/cscareerquestions ](https://www.reddit.com/r/cscareerquestions/comments/2lzc4h/big_collection_of_interview_preparation_links/)
  * [Unsolicited_advice_for_job_seekers_and_employers ](https://www.reddit.com/r/india/comments/1clgdj/unsolicited_advice_for_job_seekers_and_employers/)
  * [five-essential-phone-screen-questions - steveyegge2 ](https://sites.google.com/site/steveyegge2/five-essential-phone-screen-questions)
  * [CS9: Problem-Solving for the CS Technical Interview ](http://web.stanford.edu/class/cs9/)
  * [Mission-peace/interview problems ](https://github.com/mission-peace/interview/wiki) : A large collection of coding interview problems
  * [SQL Joins explained using venn diagram ](http://stevestedman.com/wp-content/uploads/VennDiagram1.pdf)
  * [10 Frequently asked SQL Query Interview Questions ](http://java67.blogspot.in/2013/04/10-frequently-asked-sql-query-interview-questions-answers-database.html)
  * [Get Ready to Learn SQL: 8. Database Normalization Explained in Simple English - Essential SQL ](http://www.essentialsql.com/get-ready-to-learn-sql-database-normalization-explained-in-simple-english/)
  * [Programming Language Concepts: Lecture Notes ](http://www.cmi.ac.in/~madhavan/courses/pl2006/lecturenotes/lecture-notes/lecture-notes.html) : OOPs concepts and programming language concepts.
  * [We Help Coders Get Hired](http://www.hiredintech.com/app) : website offering courses on system design, interview strategies, soft skills etc
  * [checkcheckzz/system-design-interview](https://github.com/checkcheckzz/system-design-interview)
  * [How to Break Into the Tech Industry - a Guide to Job Hunting and Tech Interviews ](http://haseebq.com/how-to-break-into-tech-job-hunting-and-interviews/)
  * [Freshers Interviews](http://placementsindia.blogspot.in/)
  * [C PUZZLES, Some interesting C problems ](http://www.gowrikumar.com/c/index.php)
  * [A site for technical interview questions, brain teasers, puzzles, quizzles (whatever the heck those are) and other things that make you think! ](http://www.techinterview.org/)
  * [ wu :: riddles(hard) ](https://www.ocf.berkeley.edu/~wwu/riddles/hard.shtml) : logic puzzles and riddles
  * [https://github.com/odino/interviews](https://github.com/odino/interviews) : list of important questions for interview
  * [svozniuk/java-interviews](https://github.com/svozniuk/java-interviews) : Java interview questions
  * [kimberli/interviews](https://github.com/kimberli/interviews) : study sheet for Interview
  * [Determining the big-O runtimes of these different loops?](http://stackoverflow.com/questions/11094330/determining-the-big-o-runtimes-of-these-different-loops) : really good stackoverflow question that covers basics of calculating runtime complexity.
  * [ChiperSoft/InterviewThis](https://github.com/ChiperSoft/InterviewThis) : questions to ask during on a interview to know more about the company.
  * [SQL interview questions](https://www.jitbit.com/news/181-jitbits-sql-interview-questions/) : great SQL test

# Documentaries
  * Machine that Changed the World - a very good documentary about history of computers
      * [Part 1: Giant Brains ](http://www.youtube.com/watch?v=rcR74y61xZk)
      * [Part 2: Inventing the Future](http://www.youtube.com/watch?v=1APZ5-cjWfw)
      * [Part 3: The Paperback Computer](http://www.youtube.com/watch?v=zwC3gOudlAc)
      * [Part 4: The Thinking Machine](http://www.youtube.com/watch?v=4gzpd0irP58)
      * [Part 5: The World at Your Fingertips](http://www.youtube.com/watch?v=J_3A2jSnvHE)
  * [Triumph of the Nerds ](https://www.youtube.com/playlist?list=PLn-Y3vvQbmHO5WUcBdIWqiUfNawhC1cn3) : Play-list
  * [Project Code Rush - The Beginnings of Netscape / Mozilla Documentary ](https://www.youtube.com/watch?v=a-49a_CjH0M)
  * [The Code: Story of Linux documentary ](https://www.youtube.com/watch?v=XMm0HsmOTFI)
  * [Revolution OS Linux Documentary ](https://www.youtube.com/watch?v=fxjElWL8igo)
  * [Breaking the Code: Biography of Alan Turing ](https://www.youtube.com/watch?v=S23yie-779k)
  * [Mechanical Computer (All Parts) ](https://www.youtube.com/watch?v=s1i-dnAH9Y4) : a very good video from 1950s explaining how mechanical computers used to work without all the modern day electronics.
  * [Download: The True Story of the Internet ](https://www.youtube.com/playlist?list=PL_IlIlrxhtPMqW4b0-v8OgLvFZQes6SoZ) : Play-list of discovery channel documentary on browser wars , dot com bubble and more.
  * [Teach Yourself Computer Science ](https://teachyourselfcs.com/)
  * [How does CPU execute program (video)](https://www.youtube.com/watch?v=42KTvGYQYnA)
  * [Machine Code Instructions (video)](https://www.youtube.com/watch?v=Mv2XQgpbTNE)
  * [Harvard CS50 - Asymptotic Notation (video)](https://www.youtube.com/watch?v=iOq5kSKqeR4)
  * [Cracking The Code Interview](https://www.youtube.com/watch?v=4NIb9l3imAo)
  * [Cracking the Coding Interview - Fullstack Speaker Series](https://www.youtube.com/watch?v=Eg5-tdAwclo)
  * [Ask Me Anything: Gayle Laakmann McDowell (author of Cracking the Coding Interview)](https://www.youtube.com/watch?v=1fqxMuPmGak)


# MOOCs for learning something new
  * [Class Central](https://www.class-central.com) : a directory of 100,000+ student reviews of thousands of MOOCs.
  * [NPTEL Vidoes COMP_SCI_ENGG ](https://onlinecourses.nptel.ac.in/explorer/search?category=COMP_SCI_ENGG)
  * [Coursera.org](http://coursera.org/)
  * [edX](http://edx.org/)
  * [MOOC.fi](http://mooc.fi/english.html) : Free online courses from the University of Helsinki
  * [Udacity](http://udacity.com/)
  * [Kadenze | Creative Programming](https://www.kadenze.com/courses?subjects%5B%5D=7): Programming courses focused on art and creativity
  * [UCBerkeley](https://www.youtube.com/user/UCBerkeley/videos)
  * [MIT OCW Electrical Engineering and Computer Science](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/)
  * [CS50](https://www.youtube.com/user/cs50tv/videos)
  * [prakhar1989/awesome-CS-courses](https://github.com/prakhar1989/awesome-courses/blob/master/README.md) : List containing large amount of CS courses
  * [Computer Science Resources ](https://docs.google.com/spreadsheets/d/1BD8BJJUNaX63m2QmySWMGDp71nx4W4MyyiIBlfMoN3Q/htmlview?sle=true#) : list of MOOCs for autodidacts
  * [https://github.com/prakhar1989/awesome-courses/blob/master/README.md ](https://github.com/prakhar1989/awesome-courses/blob/master/README.md) : collection of CS courses on Internet

# Sites related to your preferred programming language (For me Java)
  * [Java Revisited ](http://javarevisited.blogspot.in/) : good for learning about Java Language and interview preparation.
  * [The Java™ Tutorials  ](https://docs.oracle.com/javase/tutorial/): The best tutorials for Java.
  * [Java Corner at Artima.com ](http://www.artima.com/java/index.html)
  * [Java Visualizer ](http://www.cs.princeton.edu/~cos126/java_visualize/) : helps visualize references , values of variables ect
  * [Java Lecture Notes ](http://www.cafeaulait.org/course/)
  * [Learning Java ](http://chimera.labs.oreilly.com/books/1234000001805/index.html) : a free online textbook for learning Java
  * [Free Online Chapters of Inside the Java Virtual Machine by Bill Venners ](http://www.artima.com/insidejvm/ed2/index.html)
  * [Understanding JVM Internals ](http://www.cubrid.org/blog/dev-platform/understanding-jvm-internals/)
  * [How Garbage Collection Works ](http://www.dynatrace.com/en/javabook/how-garbage-collection-works.html)
  * [Welcome to JavaWorld.com ](http://www.javaworld.com/)
  * [The Java Memory Model ](http://www.cs.umd.edu/~pugh/java/memoryModel/)
  * [Netbeans Keyboard Shortcuts ](https://netbeans.org/project_downloads/usersguide/shortcuts-80.pdf) : Keyboard shortcuts to enhance your productivity when working in Netbeans.
  * [XyzWs Java FAQs ](http://www.xyzws.com/javafaq/page/1) : large collection of java interview questions
  * [Search Open Source Java API ](http://www.docjar.com/) : view source of java library and learn how things are implemented.
  * [JournalDev - Java, Java EE, Android, Web Development Tutorials](http://www.journaldev.com/)
  * [Implementation of Algorithms and Data Structures, Interview Questions and Answers ](https://github.com/sherxon/AlgoDS)
  * [what-is-garbage-collection](https://plumbr.eu/handbook/what-is-garbage-collection) : Demystify the garbage collection
  * [Best books for learning java must read](https://javahungry.blogspot.com/2014/02/best-books-for-learning-java-must-read.html) : Get basics of Java
  * [Garbage collection (Java); Augmenting data str (video)](https://www.youtube.com/watch?v=StdfeXaKGEc&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&index=25)
  * [Compilers (video)](https://www.youtube.com/playlist?list=PLO9y7hOkmmSGTy5z6HZ-W4k2y8WXF7Bff)
  * [Deep Dive Java: Garbage Collection is Good!](https://www.infoq.com/presentations/garbage-collection-benefits)
  * [The C++ Programming Language](http://www.stroustrup.com/C++.html) : The C++ Programming Language.
  * [Bjarne Stroustrup's FAQ](http://www.stroustrup.com/bs_faq.html) : The C++ FAQ
  * [Bjarne Stroustrup's C++ Style and Technique FAQ](http://www.stroustrup.com/bs_faq2.html) : The C++ FAQ
  * [C++11 - the new ISO C++ standard](http://www.stroustrup.com/C++11FAQ.html) : The C++11 FAQ




# Learn AI
 * [Unsupervised Sentiment Neuron ](https://blog.openai.com/unsupervised-sentiment-neuron/)
 * [Robots that learn](https://blog.openai.com/robots-that-learn/)
 * [grakn.ai](https://grakn.ai/)

# Seminar , research writing , talks etc
  * [Advice on Research and Writing ](http://www.cs.cmu.edu/~mleone/how-to.html)
  * [Seminar and reports ](https://www.cse.iitb.ac.in/~ranade/communicationskills.html)
  * [PHD MS Articles ](http://www.cse.iitd.ac.in/~srsarangi/articles.html)
  * [Practical Tips for Talking at Usergroups and Conferences ](https://stephenhaunts.com/2015/10/02/practical-tips-for-talking-at-usergroups-and-conferences-part-1/)
  * [ Giving presentation on software project to non-programmers ](https://stephenhaunts.com/2015/10/02/practical-tips-for-talking-at-usergroups-and-conferences-part-1/)

# Everything in one place
  * [reddit.com/user/ashish2199/m/cs_student_subs](https://www.reddit.com/user/ashish2199/m/cs_student_subs) : a multisubreddit of all subreddits of topics related to computer science and programming.

# YouTube Channels
  * [Computerphile ](https://www.youtube.com/user/Computerphile/videos) : Must watch for every CS student
  * [ComputerHistory ](https://www.youtube.com/user/ComputerHistory/videos) : for those who like to know how we reached where we are.
  * [GoogleTechTalks ](https://www.youtube.com/user/GoogleTechTalks/videos) : videos on trending topics and cool stuff happening in the tech industry.
  * [Placement Grid ](https://www.youtube.com/user/PlacementGrid/videos) : Interview and campus placement experience
  * [Google Developers ](https://www.youtube.com/user/GoogleDevelopers/videos)
  * [Facebook Developers ](https://www.youtube.com/user/FacebookDevelopers/videos)
  * [O'Reilly ](https://www.youtube.com/user/OreillyMedia/videos) : interviews and talks of world's best technical writers.
  * [Java ](https://www.youtube.com/user/java/videos) : talks related to java
  * [JavaOne ](https://www.youtube.com/channel/UCdDhYMT2USoLdh4SZIsu_1g/videos) : Java Conference
  * [CppCon ](https://www.youtube.com/user/CppCon/videos?shelf_id=0&view=0&sort=dd) : C++ Conference
  * [Meeting C++ YT Kanalseite ](https://www.youtube.com/user/MeetingCPP/videos) : Talks on C++
  * [ThinMatrix ](https://www.youtube.com/user/ThinMatrix/videos) : blogs and tutorials developer making a 3d game in Java using opengl
  * [yegor256 ](https://www.youtube.com/user/technoparkcorp/videos)
  * [Scott Meyers: Past Talks ](http://www.aristeia.com/presentations.html)
  * [thoughtbot  ](https://www.youtube.com/user/ThoughtbotVideo/videos) : talks on various topics
  * [code::dive conference](https://www.youtube.com/channel/UCU0Rt8VHO5-YNQXwIjkf-1g) : code::dive conference organized by NOKIA Wrocław Technology Center
  * [HowToBecomeTV ](https://www.youtube.com/user/HowToBecomeTV/videos) : contains good interviews of developers and people related to tech industry.
  * [ITCuties ](https://www.youtube.com/user/itcuties/videos)
  * [CodeBabes](https://www.youtube.com/user/CodeBabes/videos) : For those who think CS lacks glamor :P
  * [Coding Blocks](https://www.youtube.com/CodingBlocks) : Tutorials, how to's, tips and tricks

# Good Articles
  * [Expectations of a Junior Developer ](http://blog.thefirehoseproject.com/posts/expectations-of-a-junior-developer/)
  * [The Key To Accelerating Your Coding Skills ](http://blog.thefirehoseproject.com/posts/learn-to-code-and-be-self-reliant/)
  * [A Software Developer’s Reading List ](https://stevewedig.com/2014/02/03/software-developers-reading-list/) : Some good books and links in there.
  * [how-to-break-into-tech-job-hunting-and-interviews/ ](http://haseebq.com/how-to-break-into-tech-job-hunting-and-interviews/)
  * [40 Keys Computer Science Concepts Explained In Layman’s Terms ](http://carlcheo.com/compsci)
  * [What every programmer should know about memory, Part ](https://lwn.net/Articles/250967/)
  * [We are reinventing the retail industry through innovative technology](http://multithreaded.stitchfix.com/)
  * [Unicode ](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
  * [What every programmer absolutely, positively needs to know about encodings and character sets to work with text](http://kunststube.net/encoding/)
  * [List of algorithms](https://www.wikiwand.com/en/List_of_algorithms)
  * [Dive into the byte code](https://www.wikiwand.com/en/Java_bytecode)
  * [What every computer science major should know ](http://matt.might.net/articles/what-cs-majors-should-know/)
  * [Teach Yourself Computer Science](https://teachyourselfcs.com/)
  * [Data Structure Map](https://fkcd.ca/b7d.svg)
  * [A Gentle Introduction To Graph Theory ](https://dev.to/vaidehijoshi/a-gentle-introduction-to-graph-theory)
  * [Linux Inside](https://0xax.gitbooks.io/linux-insides/content/Booting/linux-bootstrap-1.html)
  * [A programmer friendly language that compiles to Lua.](http://moonscript.org/)

# Podcasts
 * [Coding Blocks - Learning principles, patterns and better practices on the go](http://www.codingblocks.net/)
 * [MS Dev Show](http://msdevshow.com/)
 * [The Cynical Developer](http://cynicaldeveloper.com/)
 * [Herding Code](http://herdingcode.com/)
 * [Code Newbie](http://www.codenewbie.org/)
 * [Software Engineering Radio](http://www.se-radio.net/)
 * [JavaScript Jabber](https://devchat.tv/js-jabber)
 * [Developer Tea](https://spec.fm/podcasts/developer-tea) : A podcast for developers designed to fit inside your tea break.

# Building a Simple Compiler/interpreter
 * [Resources for Amateur Compiler Writers](http://c9x.me/compile/bib/)
 * [:snowman: Possibly the smallest compiler ever](https://github.com/thejameskyle/the-super-tiny-compiler)
 * [Writing My First Compiler ](https://dev.to/fcpauldiaz/writing-my-first-compiler)
 * [Structure and Interpretation of Computer Programs](https://sarabander.github.io/sicp/html/index.xhtml)
 *  [Let’s Build A Simple Interpreter. Part 1. ](https://ruslanspivak.com/lsbasi-part1/)
 *  [Growing a compiler](http://www.cs.dartmouth.edu/~mckeeman/cs48/mxcom/gem/html/GrowingCompiler.html)

# Tutorials
  * [Tutorialspoint ](http://www.tutorialspoint.com/)
  * [W3Schools Online Web Tutorials ](http://www.w3schools.com/)
  * [Open Data Structures ](http://opendatastructures.org/) : Excellent resource for learning about DS and algos , provides code in various languages C++ , Java , pseudocode
  * [Data Structures and Algorithms by John Morris ](http://oopweb.com/Algorithms/Documents/PLDS210/VolumeFrames.html) : another good source with code and its analysis
  * [CMSI 281: Data Structures ](http://cs.lmu.edu/~ray/classes/dsa/) : light weight introduction to DS
  * [How to Program in C++  ](http://cs.fit.edu/~mmahoney/cse2050/how2cpp.html) : Good resource for revising C++ topics and STL
  * [TopCoder Tutorials ](https://www.topcoder.com/community/data-science/data-science-tutorials/)
  * [A Hacker's Guide to Git ](http://wildlyinaccurate.com/a-hackers-guide-to-git/) : for those wanting to learn git with a solid foundation
  * [Git from the inside out ](http://maryrosecook.com/blog/post/git-from-the-inside-out)
  * [Learn UNIX in 10 minutes](http://freeengineer.org/learnUNIXin10minutes.html)
  * [The Bash Guide](http://guide.bash.academy/) : very good guide for learning the Bash Shell
  * [Linux Tutorial ](http://ryanstutorials.net/linuxtutorial/) : good resource for learning Linux
  * [UNIX Tutorial - Introduction ](http://www.ee.surrey.ac.uk/Teaching/Unix/unixintro.html)
  * [Linux Tutorial for Beginners ](http://www.ee.surrey.ac.uk/Teaching/Unix/)
  * [Learning the shell. ](http://linuxcommand.org/learning_the_shell.php)
  * [Dynamic programming - PrismoSkills](http://prismoskills.appspot.com/lessons/Dynamic_Programming/Chapter_01_-_Introduction.jsp) : very good resource if want to learn how to solve DP problems.
  * [Deep C  ](http://www.slideshare.net/olvemaudal/deep-c) : very good presentation on C language
  * [C programming language Frequently Asked Questions ](http://c-faq.com/index.html)
  * [OS Course Notes ](https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/) : Chapter wise course notes according to Galvin's book
  * [SQL (Structured Query Language) in one page : SQL.SU ](http://www.cheat-sheets.org/sites/sql.su/) : a very good SQL cheat sheet
  * [Introduction to C Programming ](http://www.le.ac.uk/users/rjm1/cotter/index.htm)
  * [MySQL Essentials ](http://www.techotopia.com/index.php/MySQL_Essentials)
  * [http://www.mysqltutorial.org/ ](http://www.mysqltutorial.org/)
  * [Best Of - Gustavo Duarte  ](http://duartes.org/gustavo/blog/best-of/) : contains articles on various topics
  * [Collecting all the cheat sheets ](http://overapi.com/) : cheat sheets for lots of programming languages
  * [The Descent to C  ](http://www.chiark.greenend.org.uk/~sgtatham/cdescent/) : for those moving to C from some higher programming language like java or python.
  * [VimTutor+ ](https://vimtutorplus.herokuapp.com/exercise/1) : learn VIM from browser itself
  * [HackerEarth Tutorials ](https://learn.hackerearth.com/tutorials/) : Good resource for DS and Algos tutorial
  * [Linux Journey ](https://linuxjourney.com/) : good site for learning linux
  * [C Programming ](http://www.cs.cf.ac.uk/Dave/C/CE.html)
  * [CS 2112/ENGRD 2112 Fall 2015 ](http://www.cs.cornell.edu/courses/cs2112/2015fa/lectures/index.html) : Good notes on data structures and algorithms.
  * [More about Github-flavored markdown](https://guides.github.com/features/mastering-markdown/)
  * [The Unix Programming Environment](http://product.half.ebay.com/The-UNIX-Programming-Environment-by-Brian-W-Kernighan-and-Rob-Pike-1983-Other/54385&tg=info)
  * [The Linux Command Line: A Complete Introduction](https://www.amazon.com/dp/1593273894/)
  * [TCP/IP Illustrated Series](https://en.wikipedia.org/wiki/TCP/IP_Illustrated)
  * [Head First Design Patterns](https://www.amazon.com/gp/product/0596007124/)
  * [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612) : aka the "Gang Of Four" book, or GOF
  * [UNIX and Linux System Administration Handbook, 4th Edition](https://www.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0131480057/)
  * [Programming, Web Development, and DevOps news, tutorials and tools for beginners to experts](https://dzone.com/)


# Watch others code
  * [LiveEdu.tv](https://www.liveedu.tv/) : screencast of people building application, websites, games, ect.

# What should a programmer know
  * [Programmer Competency Matrix  ](http://sijinjoseph.com/programmer-competency-matrix/) : article for knowing what our level as a programmer is.
  * [GitHub.com Build software better, together  ](https://github.com/) : Place to showcase your project and collaborate with others. (Must know Git in order to use it effectively)
  * [Gitlab offers free unlimited (private) repositories and unlimited collaborators](https://gitlab.com).

# Competitive programming
  * [HackerRank ](http://hackerrank.com/)
  * [Codeforces ](http://codeforces.com/)
  * [topcoder ](http://topcoder.com/)
  * [UVa Online Judge ](https://uva.onlinejudge.org) : hundreds of problems supporting multiple languages.
  * [HackerEarth - Programming challenges and Developer jobs ](http://hackerearth.com/)
  * [CodeChef ](http://codechef.com/)
  * [PKU ACM ICPC Practice problems ](http://poj.org/problemlist)
  * [Archived Problems - Project Euler ](https://projecteuler.net/archives)
  * [Google Code Jam Practice and ](https://code.google.com/codejam/contests.html) : past contest problems for practice
  * [Sphere Online Judge (SPOJ) ](http://www.spoj.com/)
  * [Art of Problem Solving](https://artofproblemsolving.com/)
  * [Riddles.io AI Games](https://www.riddles.io) : Compete with your bot and dominate the leaderboards!
  * [Codingame](https://www.codingame.com) : Learn coding through games and challenges!
  * [Codewars](https://www.codewars.com/) : Rank up by completing code kata

# Computer Books
  * [IT eBooks - Free Download - Big Library  ](http://it-ebooks.info/) : website for downloading ebooks without any advertisement and instant downloads.
  * [github.com/vhf/free-programming-books ](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md) : More than 500 free ebooks on almost any language you can think of
  * [Computer Science Books Online ](http://www.sciencebooksonline.info/computer-science.html) : about 150 computer free ebooks
  * [Best books for GATE CSE ](http://gatecse.in/wiki/Best_books_for_CSE#Best_Books_for_GATE_in_CSE)
  * [https://cses.fi/book.html](https://cses.fi/book.html)
  * [Library Genesis](gen.lib.rus.ec) : Almost any ebook you can think of, including countless CS texts and manuals. 

# Video Tutorials
  * [Tushar Roy ](https://www.youtube.com/user/tusharroy2525/videos) : Algorithm and Data structure tutorial by an Indian Youtuber.
  * [Derek Banas ](https://www.youtube.com/user/derekbanas/videos) : good quality tutorials
  * [thenewboston ](https://www.youtube.com/user/thenewboston/videos) : good but with too much talk as compared to actual content
  * [mycodeschool ](https://www.youtube.com/user/mycodeschool/videos) : Data structures and algorithms tutorials
  * [CodeGeek ](https://www.youtube.com/channel/UCJYhP1lceSUc1bg0LRBUvqA/videos)
  * [CodingMadeEasy  ](https://www.youtube.com/user/CodingMadeEasy/videos) : C++ tutorials
  * [XDA-University - Helping You Learn Android Development ](http://xda-university.com/)
  * [DevTips ](https://www.youtube.com/user/DevTipsForDesigners/videos) : web dev tutorials
  * [codedamn  ](https://www.youtube.com/channel/UCJUmE61LxhbhudzUugHL2wQ/videos) : front end web dev tutorials
  * [Design and Analysis of Algorithms ](http://openclassroom.stanford.edu/MainFolder/CoursePage.php?course=IntroToAlgorithms)
  * [Vim Tutorial Videos - Flarfnoogins ](http://derekwyatt.org/vim/tutorials/index.html) : good video tutorial for learning vim
  * [CS1: Higher Computing - Richard Buckland UNSW ](https://www.youtube.com/playlist?list=PL6B940F08B9773B9F) : a very good introductory CS course
  * [Kathryn Hodge ](https://www.youtube.com/channel/UC4DwZ2VXM2KWtzHjVk9M_xg/videos) : Has good videos for beginners

# Online Compiler and Sharing Code snippets
  * [CodePad](https://codepad.remoteinterview.io/) : Code editor to try, test and run 25+ languages
  * [JSFiddle](https://jsfiddle.net/) : Test your JavaScript, CSS, HTML or CoffeeScript with online code editor
  * [Ideone.com ](https://ideone.com/)
  * [Pastebin.com ](http://pastebin.com/)
  * [Godbolt.org ](https://godbolt.org/): Excellent tool for exploring the assembly output of different compilers with and without optimization.

# Blogs of Developers
  * [Coding Horror](http://blog.codinghorror.com/) : one the best coding blog
  * [WildMl](http://http://www.wildml.com/) : A blog for machine learning.
  * [Joel on Software](http://joelonsoftware.com/)
  * [ Stephen Haunts { Coding in the Trenches } ](https://stephenhaunts.com/)
  * [Programming in the 21st Century](http://prog21.dadgum.com/)
  * [Clean Coder Blog  ](http://blog.cleancoder.com/) : blog of author of book "Clean Code"
  * [Programming Blog  ](http://www.yegor256.com/) : programming blog of Yegor Bugayenko
  * [10K-LOC ](https://10kloc.wordpress.com/)
  * [http://stevehanov.ca/blog/ ](http://stevehanov.ca/blog/)
  * [Geek Land ](https://avidullu.wordpress.com/)
  * [Late Developer ](https://latedev.wordpress.com/)
  * [IT Enthusiast ](http://rodiongork.tumblr.com/)
  * [blog.might.net ](http://matt.might.net/articles/)
  * [CSE Blog - quant, math, computer science puzzles ](http://www.cseblog.com/)
  * [Small Programming Challenges and Puzzles](https://www.nayuki.io/category/programming)
  * [My Tech Interviews ](http://www.mytechinterviews.com/)
  * [HackerEarth Blog ](http://blog.hackerearth.com/)
  * [Algo-Geeks ](http://algo-geeks.blogspot.in/)
  * [CoderGears Blog Insights from ](http://www.codergears.com/Blog/) : the CoderGears Team
  * [blog.might.net ](http://matt.might.net/articles/)
  * [Runhe Tian Coding Practice ](https://tianrunhe.wordpress.com/)
  * [Paul Graham Essays ](http://www.paulgraham.com/articles.html)
  * [Dan Dreams of Coding ](http://dandreamsofcoding.com/)
  * [Antonio081014's Algorithms Codes ](http://code.antonio081014.com/)
  * [Math ∩ Programming](http://jeremykun.com/)
  * [Takipi Blog ](http://blog.takipi.com/) : mainly focuses on Java and JVM languages
  * [Coding Geek - A blog about IT, programming and Java ](http://coding-geek.com/)
  * [Daedtech.com ](http://www.daedtech.com/) : Stories about software
  * [Archives — Ask a Manager ](http://www.askamanager.org/archives) : HR related stuff

# For improving your English
  * [Quia - English ](https://www.quia.com/shared/english/)
  * [Punctuation and Capitalization Rules](http://www.grammarbook.com/english_rules.asp)
  * [Guide to Grammar and Writing](http://grammar.ccc.commnet.edu/grammar/)
  * [Purdue University Online Writing Lab (OWL) ](https://owl.english.purdue.edu/)
  * [Englishclub.com/learn-english](https://www.englishclub.com/learn-english.htm)

# When you get bored from CS related stuff

  * [r/ProgrammerHumor](https://www.reddit.com/r/ProgrammerHumor/) : Subreddit dedicated to exactly what it sounds like
  * [Guide to Grammar and Writing](http://grammar.ccc.commnet.edu/grammar/) for those who want to improve their english language skills
  * [Vsauce ](https://www.youtube.com/user/Vsauce/videos) : The best youtube channel
  * [TED ](https://www.youtube.com/user/TEDtalksDirector/videos) : Great talks about technology, entertainment, and design
  * [CrashCourse ](https://www.youtube.com/user/crashcourse/videos) : small courses on various subjects
  * [National Geographic ](https://www.youtube.com/user/NationalGeographic/videos) : High volume of high quality content from all over the world
  * [Barcroft TV](https://www.youtube.com/user/barcroftmedia/featured) : Daily short documentaries about the incredible variety of people that make up the world 
  * [ColdFusion ](https://www.youtube.com/user/coldfustion/videos) : Past, present, and future of technology
  * [SmarterEveryDay ](https://www.youtube.com/user/destinws2/videos) : Lots of amazing scientific information about the world around us, usually captured with a high-speed camera
  * [SciShow ](https://www.youtube.com/user/scishow/videos) : Answers to interesting questions that you've always wondered about
  * [Big Think](https://www.youtube.com/user/bigthink/videos) : Expert driven, actionable, educational content, featuring experts ranging from Bill Clinton to Bill Nye
  * [Every Frame a Painting ](https://www.youtube.com/user/everyframeapainting/videos) : High quality analysis of films and filmmaking
  * [TestTube News](https://www.youtube.com/user/TestTubeNetwork/videos) : Interesting information about news from around the world
  * [Reddit the front page of the internet](http://reddit.com/) : Where free time goes to die

  ___Maintained with :heart: by sdmg15 & al___


# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![](https://camo.githubusercontent.com/3d659054abd6ce21c0e47cf3b83a51bda69ca282/68747470733a2f2f64656d6f2e726f636b65742e636861742f696d616765732f6a6f696e2d636861742e737667)](https://chat.awesome-selfhosted.com)

Selfhosting is the process of locally hosting and managing applications instead of renting from SaaS providers.

This is a list of [Free](https://en.wikipedia.org/wiki/Free_software) Software [network services](https://en.wikipedia.org/wiki/Network_service) and [web applications](https://en.wikipedia.org/wiki/Web_application) which can be hosted locally. Non-Free software is listed on the [Non-Free](non-free.md) page.

See [Contributing](.github/CONTRIBUTING.md).

--------------------

  - [Analytics](#analytics)
  - [Automation](#automation)
  - [Blogging Platforms](#blogging-platforms)
  - [Bookmarks & Link Sharing](#bookmarks--link-sharing)
  - [Calendar and Address Books](#calendar-and-address-books)
  - [Communication systems](#communication-systems)
    - [Custom](#custom)
    - [Email](#email)
      - [Complete solutions](#complete-solutions)
      - [Mail Transfer Agents](#mail-transfer-agents)
      - [Mail Delivery Agents](#mail-delivery-agents)
      - [Mailing lists and newsletters](#mailing-lists-and-newsletters)
      - [Webmail clients](#webmail-clients)
    - [IRC](#irc)
    - [SIP](#sip)
    - [IPBX](#ipbx)
    - [Social Networks and Forums](#social-networks-and-forums)
    - [XMPP](#xmpp)
      - [XMPP Servers](#xmpp-servers)
      - [XMPP Web Clients](#xmpp-web-clients)
  - [Conference Management](#conference-management)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
    - [E-commerce](#e-commerce)
  - [DNS](#dns)
  - [Document Archiving](#document-archiving)
  - [Enterprise Resource Planning](#enterprise-resource-planning)
  - [Federated Identity/Authentication](#federated-identityauthentication)
  - [Feed Readers](#feed-readers)
  - [File Sharing and Synchronization](#file-sharing-and-synchronization)
      - [Distributed filesystems](#distributed-filesystems)
      - [File transfer/synchronization](#file-transfersynchronization)
      - [Peer-to-peer filesharing](#peer-to-peer-filesharing)
      - [Single-click/drag-n-drop upload](#single-clickdrag-n-drop-upload)
      - [Web based file managers](#web-based-file-managers)
  - [Games](#games)
  - [Gateways](#gateways)
  - [Groupware](#groupware)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Learning and Courses](#learning-and-courses)
  - [Maps & GPS](#maps--gps)
  - [Media Streaming](#media-streaming)
      - [Audio Streaming](#audio-streaming)
      - [Video Streaming](#video-streaming)
  - [Misc/Other](#miscother)
  - [Money, Budgeting and Management](#money-budgeting-and-management)
  - [Monitoring](#monitoring)
  - [Note-taking & Editors](#note-taking--editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo and Video Galleries](#photo-and-video-galleries)
  - [Polls and Events](#polls-and-events)
  - [Proxy](#proxy)
  - [Read it Later Lists](#read-it-later-lists)
  - [Search Engines](#search-engines)
  - [Software Development](#software-development)
    - [Project Management](#project-management)
    - [Bug Trackers](#bug-trackers)
    - [IDE/Tools](#idetools)
    - [Continuous Integration](#continuous-integration)
    - [API Management](#api-management)
    - [Documentation Generators](#documentation-generators)
    - [Localization](#localization)
  - [Static site generators](#static-site-generators)
  - [Task management/To-do lists](#task-managementto-do-lists)
  - [Ticketing](#ticketing)
  - [URL Shorteners](#url-shorteners)
  - [VPN](#vpn)
  - [Web servers](#web-servers)
  - [Wikis](#wikis)
  - [Self-hosting Solutions](#self-hosting-solutions)
  - [List of Licenses](#list-of-licenses)
  - [External links](#external-links)
  - [Contributing](#contributing)
  - [License](#license)


-----------------------------------------------------------------------------

<!-- BEGIN SOFTWARE LIST -->

## Analytics
For personal analytics/dashboards, see [Personal Dashboards](https://github.com/Kickball/awesome-selfhosted#personal-dashboards)

**[`^        back to top        ^`](#)**

_Web Analytics_

  * [AWStats](http://www.awstats.org/) - Generates web, streaming, ftp or mail server statistics graphically. ([Source Code](https://github.com/eldy/awstats)) `GPLv3` `Perl`
  * [Countly](https://count.ly) - Real time mobile & web analytics, crash reporting and push notifications platform. ([Source Code](https://github.com/countly)) `AGPLv3` `Javascript`
  * [Druid](http://druid.io/) - A distributed, column-oriented, real-time analytics data store. ([Source Code](https://github.com/druid-io/druid/)) `Apache` `Java`
  * [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal. ([Source Code](https://github.com/allinurl/goaccess)) `GPLv2` `C`
  * [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Piwik alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics/)) `GPLv2` `PHP`
  * [Piwik](https://piwik.org/) - Leading open-source analytics platform that gives you more than just powerful analytics. ([Source Code](https://github.com/piwik/)) `GPLv3` `PHP`
  * [Rakam](https://rakam.io/) - Custom analytics platform that allows you to create your own analytics services. Integrate with any data source (web, mobile, IoT etc.), analyze data with SQL and create dashboards. ([Source Code](https://github.com/rakam-io/rakam)) `Apache` `Java`
  * [Serposcope](https://serposcope.serphacker.com/) - Serposcope is a free and open-source rank tracker to monitor websites ranking in Google and improve your SEO performances. ([Source Code](https://github.com/serphacker/serposcope)) `MIT` `Java`
  * [Snowplow](http://snowplowanalytics.com/) - Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache` `Scala`
  * [ThinkUp](https://www.thinkup.com/) - Insights into your social networking activity on Twitter, Facebook, Instagram, and beyond. ([Source Code](https://github.com/ThinkUpLLC/ThinkUp)) `GPLv3` `PHP`

_Business Intelligence_

  * [Metabase](http://www.metabase.com/) - Simple Dashboarding and GUI Query tool, Nightly Emails and Slack Integration w/ PostgreSQL, MySQL, Redshift and other DBs. ([Source Code](https://github.com/metabase/metabase)) `AGPLv3` `Clojure`
  * [Redash](http://redash.io) - connect to over 18 types of databases (SQL and "NoSQL"), query your data, visualize it and create dashboards. Everything has a URL that can be shared. Slack and HipChat integration. ([Demo](https://demo.redash.io), [Source Code](https://github.com/getredash/redash)) `BSD` `Python`


## Automation

**[`^        back to top        ^`](#)**

  * [Alltube](http://www.alltubedownload.net) - A web interface for [youtube-dl](https://github.com/rg3/youtube-dl), a program to download videos and audio from [more than 100 websites](https://rg3.github.io/youtube-dl/supportedsites.html). ([Demo](http://www.alltubedownload.net), [Source Code](https://github.com/Rudloff/alltube)) `GPL` `PHP`
  * [AmIUnique](https://amiunique.org/) - Learn how identifiable you are on the Internet (browser fingerprinting tool). ([Source Code](https://github.com/DIVERSIFY-project/amiunique)) `MIT` `Java`
  * [bip.io](https://bip.io/) - Web Automation For People And Robots - Drag, Drop, and Connect The Services You Love. ([Source Code](https://github.com/bipio-server/bipio)) `GPLv3` `Nodejs`
  * [CouchPotato](https://couchpota.to/) - CouchPotato is an automatic Video Library Manager for Movies. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/CouchPotato/CouchPotatoServer/)) `GPLv3` `Python`
  * [Episodes](https://github.com/guptachetan1997/Episodes) - `⚠` Self Hosted TV show Episode tracker and recommender built using django, bootstrap4. `MIT` `Python`
  * [FHEM](https://fhem.de/fhem.html) - FHEM is used to automate common tasks in the household like switching lamps and heating. It can also be used to log events like temperature or power consumption. You can control it via web or smartphone frontends, telnet or TCP/IP directly. ([Source Code](https://svn.fhem.de/trac)) `GPLv3` `Perl`
  * [Headphones](https://github.com/rembo10/headphones) - An automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent, Deluge and Blackhole. `GPLv3` `Python`
  * [Healthchecks](https://healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD` `Python`
  * [Home Assistant](https://home-assistant.io/) - An open-source home automation platform. ([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/home-assistant)) `MIT` `Python`
  * [homebank-converter](https://github.com/Binnette/homebank-converter) - A web app to convert an export bank file to compatible Homebank csv. ([Demo](http://binnette.github.io/homebank-converter/)) `AGPLv3` `HTML5`
  * [Huginn](https://github.com/cantino/huginn) - Allows you to build agents that monitor and act on your behalf. `MIT` `Ruby`
  * [Http2pic](https://http2pic.haschek.at/) - Website screenshots/renderer. It uses the wkhtmltox to render websites with various options. ([Source Code](https://github.com/chrisiaut/http2pic)) `Apache 2.0` `PHP/Javascript`
  * [Kibitzr](https://kibitzr.github.io) - Lightweight personal web assistant with powerfull integrations. ([Source Code](https://github.com/kibitzr/kibitzr/)) `MIT` `Python`
  * [Medusa](https://github.com/pymedusa/SickRage) - Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. `GPLv3` `Python`
  * [Node RED](http://nodered.org/) - A browser-based flow editor that helps you wiring hardware devices, APIs and online services to create IoT solutions. ([Source Code](https://github.com/node-red/node-red)) `Apache` `Nodejs`
  * [openHAB](http://www.openhab.org) - Vendor and technology agnostic open source software for home automation. ([Source Code](https://github.com/openhab/openhab)) `EPLv1` `Java`
  * [Poffer](http://poffer.gabinaureche.com) `⚠` - A tool that makes it easier to share the content you like thanks to Pocket+Buffer. ([Source Code](https://github.com/Zhouzi/Poffer)) `MIT` `Nodejs`
  * [pyLoad](https://pyload.net/) - Lightweight, customizable and remotely manageable downloader for 1-click-hosting sites like rapidshare.com or uploaded.to. ([Source Code](https://github.com/pyload/pyload)) `GPLv3` `Python`
  * [Radarr](https://radarr.video/) - Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent, à la Couchpotato. ([Source Code](https://github.com/Radarr/Radarr)) `GPLv3` `C#`
  * [RSS-Bridge](https://github.com/sebsauvage/rss-bridge) - rss-bridge is a PHP project capable of generating ATOM feeds for websites which don't have one. `Public domain` `PHP`
  * [RSS Merger](https://github.com/taophp/rss-merger) - PHP script which will take multiple RSS / Atom feeds as input and merge them into a single RSS feed. `GPLv2` `PHP`
  * [SickRage](http://sickrage.github.io/) - SickRage is an automatic Video Library Manager for TV Shows. Automatic torrent/nzb searching, downloading, and processing at the qualities you want. ([Source Code](https://github.com/SickRage/SickRage/)) `GPLv3` `Python`
  * [Sonarr](https://sonarr.tv/) - An automatic TV Shows downloader and manager for Usenet and BitTorrent. It can grab, sort and rename new episodes and automatically upgrade the quality of files already downloaded when a better quality format becomes available. ([Source Code](https://github.com/Sonarr/Sonarr)) `GPLv3` `C#`
  * [TriggerHappy](http://trigger-happy.eu/) - An opensource clone of IFTTT, a bridge between your internet services. ([Source Code](https://github.com/foxmask/django-th)) `BSD` `Python`
  * [WebUI-aria2](https://github.com/ziahamza/webui-aria2) - Interface to interact with the aria2 downloader. Very simple to use, just download and open index.html in any web browser. ([Demo](http://ziahamza.github.io/webui-aria2/)) `MIT` `HTML5`
  * [WTFDYUM](https://github.com/jchampemont/WTFDYUM) `⚠` - Why The Fuck Did You Unfollow Me - Find out who stops following you on Twitter. ([Demo](https://www.wtfdyu.me/), [Source Code](https://github.com/jchampemont/WTFDYUM)) `Apache` `Java`
  * [Zenbot 3](https://s8f.org/zenbot.html) - Zenbot is a lightweight, extendable, artificially intelligent trading bot for Bitcoin, Ether, Litecoin, and more. ([Demo](https://zenbot.s8f.org/), [Source Code](https://github.com/carlos8f/zenbot)) `MIT` `Node.js`


## Blogging Platforms

**[`^        back to top        ^`](#)**

See also [Static Site Generators](#static-site-generators), [Content Management Systems](#content-management-systems-cms) and [WeblogMatrix](http://www.weblogmatrix.org/)

  * [Anchor CMS](https://anchorcms.com/) - Anchor is a free, lightweight, faster-than-a-bullet, simple blogging system, made for art–directed posts. ([Source Code](https://github.com/anchorcms/anchor-cms)) `GPLv3` `PHP`
  * [Antville](https://antville.org) - Antville is a free, open source project aimed at the development of a high performance, feature rich weblog hosting software. ([Source Code](https://github.com/antville/antville)) `Apache` `Javascript`
  * [Blogotext](http://lehollandaisvolant.net/blogotext/) - A free blog-engine written in PHP and using SQLite. This offers you both an unmatched simplicity during installation and great performances. ([Source Code](https://github.com/timovn/blogotext)) `MIT` `PHP`
  * [Bludit](https://www.bludit.com/) `⚠` - Simple application to build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. ([Demo](http://demo-bludit.rhcloud.com/), [Source Code](https://github.com/dignajar/bludit)) `MIT` `PHP`
  * [Chyrp](https://github.com/chyrp/chyrp) - An extra-awesome, extra-lightweight blog engine. `MIT` `PHP`
  * [Dotclear](http://dotclear.org/) - Take control over your blog. ([Source Code](https://hg.dotclear.org/dotclear)) `GPLv2` `PHP`
  * [Formtools](https://formtools.org/) - Powerful, flexible, free and open source PHP/MySQL script to manage your forms and data. ([Source Code](https://github.com/formtools)) `GPLv2` `PHP`
  * [Ghost](https://ghost.org/) - Just a blogging platform. ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
  * [Hexo](https://hexo.io/) - A fast, simple & powerful blog framework, powered by Node.js. ([Source Code](https://github.com/hexojs/hexo)) `MIT` `Nodejs`
  * [Hotglue](https://hotglue.me/) - HOTGLUE is a freehand CMS which allows to construct websites directly in a web-browser. It uses flat files for storage and provides an intuitive GUI. ([Demo](https://hotglue.me/demo/), [Source Code](https://github.com/k0a1a/hotglue2)) `GPLv3` `PHP`
  * [htmly](https://www.htmly.com/) - Databaseless Blogging Platform (Flat-File Blog). ([Demo](https://www.htmly.com/demo/), [Source Code](https://github.com/danpros/htmly)) `GPLv2` `PHP`
  * [Known](https://withknown.com/) - A single website for all your content. ([Source Code](https://github.com/idno/idno)) `Apache` `PHP`
  * [Noddity](http://noddity.com/) - It's a blog, it's a wiki, it's a fast CMS. ([Source Code](https://github.com/TehShrike/noddity)) `WTFPL` `Nodejs`
  * [PluXml](http://www.pluxml.org/) - XML-based blog/CMS platform. ([Source Code](https://github.com/pluxml/PluXml)) `GPL` `PHP`
  * [Postleaf](https://www.postleaf.org/) - An open source blogging platform with inline editing, handlebar templates, and a beautiful user interface. ([Source Code](https://github.com/Postleaf/postleaf)) `GPLv3` `PHP`
  * [Solo](http://b3log.org/) - A blogging system written in Java, feel free to create your or your team own blog. ([Demo](http://88250.b3log.org/), [Source Code](https://github.com/b3log/solo)) `Apache` `Java`
  * [Wagtail](https://wagtail.io/) - A Django content management system focused on flexibility and user experience. ([Source Code](https://github.com/torchbox/wagtail)) `BSD` `Python`
  * [WordPress](https://wordpress.org/) - Create a beautiful website or blog. ([Source Code](https://github.com/WordPress/WordPress)) `GPLv2` `PHP`


## Bookmarks & Link Sharing

**[`^        back to top        ^`](#)**

  * [Bookie](https://github.com/bookieio/Bookie) - Python based delicious.com replacement. `AGPLv3` `Python`
  * [dyu/bookmarks](https://github.com/dyu/bookmarks) - Single-threaded/process bookmark app powered by leveldb and uWebSockets. Supports importing from Delicious and Chrome. ([Demo](https://dyuproject.com/bookmarks/)) `Apache` `Java`
  * [Firefox Auth Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - This project implements the core server-side API for Firefox Accounts. ([Source Code](https://github.com/mozilla/fxa-auth-server/)) `MPLv2` `Nodejs`
   * [Firefox Content Server](https://docs.services.mozilla.com/howtos/run-fxa.html) - Static server that hosts Firefox Account sign up, sign in, email verification, etc. flows. ([Source Code](https://github.com/mozilla/fxa-content-server/)) `MPLv2` `Java`
   * [Firefox Sync Server](https://docs.services.mozilla.com/howtos/run-sync-1.5.html) - Sync Firefox bookmarks, passwords, history, tabs, preferences. ([Source Code](https://github.com/mozilla-services/syncserver)) `MPLv2` `Python`
  * [Lobsters](https://lobste.rs) - Run your own link aggregation site. ([Source Code](https://github.com/jcs/lobsters)) `BSD` `Ruby`
  * [No Fuss Bookmarks](http://nofussbm.herokuapp.com/signup.html) - Very simple software and service to store bookmarks especially designed for hackers (that don't need fancy interfaces, but nice API). ([Source Code](https://github.com/mapio/nofussbm)) `GPLv3` `Python`
  * [Pinry](http://getpinry.com/) - The tiling image board system for people who want to save, tag, and share images, videos, and webpages. ([Source Code](https://github.com/pinry/pinry)) `BSD` `Python`
  * [saveto](https://save.duyet.net/) - An open source, home for the best links on the web. ([Source Code](https://github.com/saveto-co/saveto)) `MIT` `Nodejs`
  * [SemanticScuttle](http://semanticscuttle.sourceforge.net/) - SemanticScuttle is a social bookmarking tool experimenting with features like structured tags and collaborative tag descriptions. ([Source Code](https://sourceforge.net/p/semanticscuttle/code/ci/master/tree/)) `GPLv2` `PHP`
  * [Shaarli](https://github.com/shaarli/Shaarli) - Personal, minimalist, super-fast, no-database bookmarking and link sharing plaform. ([Demo](https://demo.shaarli.org)) `Zlib` `PHP`
  * [unmark](https://unmark.it/) - An open source to do app for links. ([Source Code](https://github.com/plainmade/unmark)) `MIT` `PHP`

## Calendar and Address Books

**[`^        back to top        ^`](#)**

Some [Groupware](#groupware) solutions also feature calendar/address book editing and synchronization.

  * [AgenDAV](http://agendav.org/) - Multilanguage CalDAV web client with a rich AJAX interface and shared calendars support. ([Source Code](https://github.com/adobo/agendav)) `GPLv3` `PHP`
  * [Baïkal](http://baikal-server.com/) - Lightweight CalDAV+CardDAV server. ([Source Code](https://github.com/fruux/Baikal)) `GPLv3` `PHP`
  * [CalendarServer](http://trac.calendarserver.org/) - A standards-compliant server implementing the CalDAV and CardDAV protocols. `Apache` `Python`
  * [calypso](http://keithp.com/calypso/) - A python-based CalDAV/CardDAV server. ([Source Code](http://keithp.com/cgi-bin/gitweb.cgi?p=calypso.git;a=tree)) `GPLv3` `Python`
  * [DAViCal](http://www.davical.org/) - A server for calendar sharing (CalDAV). ([Source Code](https://gitlab.com/davical-project/davical)) `MIT` `PHP`
  * [ownCloud calendar](https://doc.owncloud.org/server/9.0/user_manual/pim/calendar.html) - The ownCloud Calendar app enables you to create and edit events, synchronize to other calendars you might use, and create new, personalized calendars. ([Source Code](https://github.com/owncloud/calendar-rework)) `AGPLv3` `PHP`
  * [Radicale](http://radicale.org/) - A Simple Calendar and Contact Server. ([Source Code](https://github.com/Kozea/Radicale)) `GPLv3` `Python`
  * [sabre/dav](http://sabre.io/) - A open source CardDAV, CalDAV and WebDAV server. ([Source Code](https://github.com/fruux/sabre-dav)) `MIT` `PHP`
  * [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/) - An open source CalDAV/CardDAV web client implementation. ([Demo](https://www.inf-it.com/infcloud/), [Source Code](https://www.inf-it.com/InfCloud_0.13.1.zip)) `AGPLv3` `Javascript`


## Communication systems

**[`^        back to top        ^`](#)**

### Custom

  * [Actor](https://actor.im/) - Actor is a fast, open source messaging platform with rich mobile and web clients. ([Demo](https://app.actor.im), [Source Code](https://github.com/actorapp/actor-platform)) `AGPLv3` `Scala`
  * [Centrifugo](https://github.com/centrifugal/centrifugo) - Language-agnostic real-time messaging (Websocket or SockJS) server. ([Demo](https://github.com/centrifugal/centrifugo#demo)) `MIT` `Go`
  * [Cherry](https://github.com/rafael-santiago/cherry) - A tiny webchat server. `GPLv2` `Go`
  * [Freenet](https://freenetproject.org/index.html) - Anonymously share files, browse and publish "freesites" (web sites accessible only through Freenet) and chat on forums. ([Source Code](https://github.com/freenet/fred)) `GPLv2` `Java`
  * [Friends](http://moose-team.github.io/friends/) - P2P chat powered by the web. ([Source Code](https://github.com/moose-team/friends)) `MIT` `Nodejs`
  * [GNUNet](https://gnunet.org/) - Free software framework for decentralized, peer-to-peer networking. ([Source Code](https://gnunet.org/svn/)) `GPLv3` `C`
  * [hack.chat](https://hack.chat/) - A minimal, distraction-free chat application. ([Source Code](https://github.com/AndrewBelt/hack.chat)) `GPLv3` `Nodejs`
  * [Hawkpost](https://hawkpost.co) - HawkPost is a web app that lets you create unique links that you can share with a person that desires to send you important information but doesn't know how to encrypt it. The message is encrypted in their browser and sent to your email address. ([Source Code](https://github.com/whitesmith/hawkpost)) `MIT` `Python`
  * [Hubl.in](https://hubl.in/) - WebRTC powered video conference, chat and collaborative editor. ([Source Code](https://github.com/linagora/hublin)) `AGPLv3` `Nodejs`
  * [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC Javascript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ([Source Code](https://github.com/jitsi/jitsi-meet)) `MIT` `Javascript`
  * [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache` `Java`
  * [Kandan](http://getkandan.com/) - Kandan is an Open Source Alternative to HipChat. ([Source Code](https://github.com/kandanapp/kandan)) `AGPLv3` `Ruby`
  * [Lets-Chat](http://sdelements.github.io/lets-chat/) - A self hosted chat suite written in Node. ([Source Code](https://github.com/sdelements/lets-chat)) `MIT` `Nodejs`
  * [Live Helper Chat](http://livehelperchat.com/) - Live Support chat for your website. ([Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache` `PHP`
  * [Mattermost](http://www.mattermost.org/) - Open-source, on-prem Slack-alternative. It can be integrated with [Gitlab](https://about.gitlab.com/). ([Source Code](https://github.com/mattermost/platform)) `AGPLv3/Apache` `Go`
  * [MiAOU](https://dystroy.org/miaou/login) - A multi-room persistent chat server. ([Source Code](https://github.com/Canop/miaou)) `MIT` `Nodejs`
  * [Mibew](https://mibew.org) - Mibew Messenger is an open-source live support application written in PHP and MySQL. It enables one-on-one chat assistance in real-time directly from your website. ([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache` `PHP`
  * [Mumble](http://wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. ([Source Code](https://github.com/mumble-voip/mumble)) `BSD` `C++`
    * [Mumblecop](https://bitbucket.org/Flandoo/mumblecop) - Stream audio from youtube and soundcloud, simulate dice rolls, or write your own commands with a simple plugin format. `MIT` `Ruby`
  * [Niltalk](http://niltalk.com/) - A simple, private, persistence-free web based multi-room chat server + client. ([Source Code](https://github.com/knadh/niltalk)) `AGPLv3` `Go`
  * [Node-Chat](https://github.com/IgorAntun/node-chat) - A not-so-basic open-source chat with admin features. `MIT` `Nodejs`
  * [Pushjet](https://pushjet.io/) - A self hosted push notification service built with a simple API making sending notifications easy. ([Source Code](https://github.com/Pushjet/Pushjet-Server-Api)) `BSD` `Python`
  * [Rallly](http://rallly.co) - Rallly is a free collaborative scheduling service. ([Source Code](https://github.com/lukevella/Rallly)) `CCBYSA` `Nodejs`
  * [RetroShare](http://retroshare.org) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. ([Source Code](https://github.com/RetroShare/RetroShare)) `GPLv2` `С++`
  * [Ring](https://ring.cx/) - Free software for universal communication which respects freedoms and privacy of its users. ([Source Code](https://github.com/savoirfairelinux/ring-project)) `GPLv3` `C++`
  * [Rocket.Chat](https://rocket.chat/) - Teamchat solution similar to Gitter.im or Slack. ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
  * [Scrollback](https://scrollback.io/) - Embeddable cross-platform chat for communities. ([Source Code](https://github.com/scrollback/scrollback)) `AGPLv3` `Nodejs`
  * [Spreed](https://www.spreed.me/) - WebRTC audio/video calls, conferencing server, and web client. ([Source Code](https://github.com/strukturag/spreed-webrtc)) `AGPLv3` `Go`
  * [Synapse](http://matrix.org/docs/projects/server/synapse.html) - A server for [Matrix](https://matrix.org/), an open standard for decentralized persistent communication. ([Source Code](https://github.com/matrix-org/synapse)) `Apache` `Python`
    * [Matrix Console Web](http://matrix.org/docs/projects/client/matrix-console.html) - A web client meant to be a showcase of Matrix capabilities, and reference implementation of the Matrix standard. ([Source Code](https://github.com/matrix-org/matrix-angular-sdk)) `Apache` `Javascript`
    * [RIOT](http://riot.im) - A glossy Matrix web client with an emphasis on performance and usability. ([Source Code](https://github.com/vector-im/riot-web)) `Apache` `Javascript`
  * [Syndie](https://www.syndie.de) - Syndie is a libre system for operating distributed forums. `CC0` `Java`
  * [TextBelt](https://github.com/typpo/textbelt) `⚠` - An outgoing SMS API that uses carrier-specific gateways to deliver your text messages for free, and without ads. `MIT` `Javascript`
  * [Tox](https://tox.chat/) - A distributed, secure messenger with audio and video chat capabilities. ([Source Code](https://github.com/irungentoo/toxcore)) `GPLv3` `C`
  * [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - Peer-to-peer video chat that works. ([Source Code](https://github.com/trailofbits/tubertc)) `MIT` `Javascript`
  * [Zulip](https://zulip.org) - Zulip is a powerful, open source group chat application. ([Source Code](https://github.com/zulip/zulip)) `Apache/Other` `Python`

### Email

**[`^        back to top        ^`](#)**

#### Complete solutions

_simple deployment of a mail server, e.g. for inexperienced or impatient admins._

  * [Citadel](http://www.citadel.org/) - Feature packed, easy, versatile, and powerful mail server, thanks to exclusive "rooms" based architecture. ([Source Code](http://code.citadel.org/?p=citadel.git;a=summary)) `GPLv3` `C`
  * [docker-mailserver](https://github.com/tomav/docker-mailserver) - A fullstack but simple mail server (smtp, imap, antispam, antivirus, etc.). Only configuration files, no SQL database. Keep it simple and versioned. Easy to deploy and upgrade. `MIT` `Docker`
  * [Inboxen](https://inboxen.org) - Inboxen is a service that provides you with an infinite number of unique inboxes. ([Source Code](https://github.com/Inboxen/Inboxen)) `GPLv3` `Python`
  * [iRedMail](http://www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. ([Source Code](https://bitbucket.org/zhb/iredmail/commits/)) `GPLv3` `Shell`
  * [Mailcow](https://mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. ([Source Code](https://github.com/andryyy/mailcow)) `GPLv2` `PHP`
  * [Mail-in-a-Box](https://mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. ([Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0` `Shell`
  * [Modoboa](http://modoboa.org/en/) - Modoboa is a mail hosting and management platform including a modern and simplified Web User Interface. ([Source Code](https://github.com/tonioo/modoboa)) `MIT` `Python`

#### Mail Transfer Agents

_MTAs / SMTP servers_

* [Courier MTA](http://www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services. ([Source Code](http://www.courier-mta.org/repo.html)) `GPLv3` `C`
* [Exim](https://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge. ([Source Code](http://git.exim.org/exim.git)) `GPLv3` `C`
* [Haraka](http://haraka.github.io/) - A high-performance, pluginable SMTP server written in Javascript. ([Source Code](https://github.com/haraka/Haraka)) `MIT` `Javascript`
* [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. ([Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
* [Maildrop](https://github.com/m242/maildrop) - Disposable email SMTP server, also useful for development. `MIT` `Scala`
* [MailHog](https://github.com/mailhog/MailHog) - Small Golang executable which runs an SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. `MIT` `Go`
* [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/smtpd/)) `ISC` `C`
* [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL` `C`
* [Qmail](http://www.qmail.org/top.html) - Secure Sendmail replacement. ([Source Code](https://sources.debian.net/src/netqmail/1.06-5/)) `CC0` `C`
* [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA). `SENDMAIL` `C`
* [Slimta](http://slimta.org) - Mail Transfer Library built on Python. ([Source Code](https://github.com/slimta/python-slimta)) `MIT` `Python`

#### Mail Delivery Agents

_MDAs - IMAP/POP3 software_

* [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in. ([Source Code](https://github.com/cyrusimap/cyrus-imapd )) `BSD` `C`
* [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. ([Source Code](https://github.com/dovecot/core)) `MIT/LGPLv2` `C`
* [Piler](http://www.mailpiler.org/wiki/start) - feature rich open source email archiving solution. ([Source Code](https://bitbucket.org/jsuto/piler)) `GPLv3` `C`

#### Mailing lists and Newsletters

_Mailing lists servers and mass mailing software - one message to many recipients._

  * [Dada Mail](http://dadamailproject.com/) - A web-based list management system that can be used for announcement lists and/or discussion lists. ([Source Code](https://github.com/justingit/dada-mail)) `GPLv2` `Perl`
  * [Mailman](https://www.gnu.org/software/mailman/) - The Gnu mailing list server. `GPL` `Python`
  * [Mailtrain](https://mailtrain.org/) - self hosted newsletter application built on Node.js (v5+) and MySQL (v5.5+ or MariaDB). ([Source Code](https://github.com/andris9/mailtrain)) `GPLv3` `Nodejs`
  * [MailyHerald](http://mailyherald.org/) - Self-hosted Mailchimp alternative that you can easily integrate with your site. Helps you send and manage your application mailings. It support email marketing and conducting the daily stream of notifications you send to your users. ([Source Code](https://github.com/Sology/maily_herald)) `LGPLv3` `Ruby`
  * [Mautic](https://www.mautic.org/) - Mautic is marketing automation software (email, social & more). ([Source Code](https://github.com/mautic/mautic)) `GPLv3` `PHP`
  * [phpList](https://phplist.org) - Newsletter and email marketing with advanced management of subscribers, bounces, and plugins. ([Source Code](https://github.com/phpList/)) `AGPLv3` `PHP`
  * [postal](https://github.com/atech/postal) - A fully featured open source mail delivery platform for incoming & outgoing e-mail. `MIT` `Ruby`
  * [Schleuder](https://schleuder.nadir.org/) - A GPG-enabled mailing list manager with resending-capabilities. ([Source Code](https://0xacab.org/schleuder/schleuder/tree/master)) `GPLv3` `Ruby`
  * [Sympa](https://www.sympa.org/) - A mailing list manager. `GPLv2` `Perl`


#### Webmail clients

  * [Cypht](http://cypht.org/index.html) - A feed reader for your email accounts. ([Source Code](https://github.com/jasonmunro/hm3)) `GPLv2` `PHP`
  * [Mailpile](https://www.mailpile.is/) - Webmail client with search, filtering, encryption features and more. ([Source Code](https://github.com/mailpile/Mailpile)) `AGPLv3` `Python`
  * [RainLoop](http://www.rainloop.net/) - Simple, modern & fast webmail with IMAP/SMTP Support and multi accounting. ([Demo](http://demo.rainloop.net/), [Source Code](https://github.com/RainLoop/rainloop-webmail)). `AGPLv3` `PHP`
  * [Roundcube](https://roundcube.net) - Browser-based IMAP client with an application-like user interface. ([Source Code](https://github.com/roundcube/roundcubemail/)) `GPLv3` `PHP`
  * [SquirrelMail](http://squirrelmail.org) - Another browser-based IMAP client. ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPLv2` `PHP`
  * [WebMail Lite](http://www.afterlogic.org/webmail-lite) - Web-based IMAP Mail client. ([Source Code](https://github.com/afterlogic/webmail-lite)) `GPLv3` `PHP`

### IRC

**[`^        back to top        ^`](#)**

_[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software_

  * [Convos](http://convos.by/) - Always online web IRC client. ([Demo](http://demo.convos.by), [Source Code](http://github.com/nordaaker/convos)) `ARTv2` `Perl`
  * [IRCAnywhere](http://ircanywhere.com/) - Open-source self-hosted alternative to IRCCloud. ([Source Code](https://github.com/ircanywhere/ircanywhere)) `GPLv2` `Nodejs`
  * [Quassel IRC](http://quassel-irc.org/) - distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. ([Source Code](https://github.com/quassel/quassel)) `GPLv2` `C++`
  * [Robust IRC](https://robustirc.net/) - RobustIRC is IRC without netsplits. Distributed IRC server, based on RobustSession protocol. ([Source Code](https://github.com/robustirc/robustirc)) `BSD` `Go`
  * [The Lounge](https://thelounge.github.io/) - The self-hosted web IRC client. ([Demo](https://avatar.playat.ch:1000/), [Source Code](https://github.com/thelounge/lounge)) `MIT` `Nodejs`
  * [Weechat](https://weechat.org/) - A fast, light and extensible chat client. `GPLv3` `C`
  * [ZNC](http://wiki.znc.in/ZNC) - An advanced IRC bouncer. ([Source Code](https://github.com/znc/znc)) `Apache` `C++`

### SIP


_[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol) telephony software_

  * [Asterisk](http://www.asterisk.org/) - An easy to use but advanced IP PBX system, VoIP gateway and conference server. `GPLv2` `C`
  * [FreeSWITCH](https://freeswitch.org/) - Scalable open source cross-platform telephony platform. ([Source Code](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPLv2` `C`
  * [Kamailio](http://www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc). ([Source Code](https://github.com/kamailio/kamailio)) `GPLv2` `C`
  * [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - Secure SIP telephony setup with ZRTP encryption. `GPLv3` `Ruby`

### IPBX

**[`^        back to top        ^`](#)**

_[IPBX](https://en.wikipedia.org/wiki/IP_PBX) telephony software_

  * [Freepbx](http://www.freepbx.org) - Web-based open source GUI that controls and manages Asterisk. ([Source Code](http://git.freepbx.org/projects/FREEPBX)) `GPLv2` `PHP`
  * [Kazoo](http://2600hz.org/) - KAZOO is an open-source, highly scalable software platform designed to provide carrier-grade VoIP switch functions and features. ([Source Code](https://github.com/2600hz/KAZOO)) `MPLv1.1` `Erlang`

### Social Networks and Forums

**[`^        back to top        ^`](#)**

  * [Abilian SBE](https://github.com/abilian/abilian-sbe) - Open Source Collaboration and Social Networking framework & platform. `LGPLv2` `Python`
  * [Anahita](https://www.getanahita.com/) - Open Source Social Networking Framework & Platform. ([Source Code](https://github.com/anahitasocial)) `GPLv3` `PHP`
  * [Bootcamp](http://trybootcamp.vitorfs.com) - An enterprise social network. ([Source Code](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
  * [Buddycloud](http://buddycloud.com/) - Tools, libraries, services and a community to build user-to-user, group and social messaging into your app. Saves time. Scales up. Supports you. ([Source Code](https://github.com/buddycloud)) `Apache` `Java`
  * [BuddyPress](https://buddypress.org/about/) - A powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. ([Source Code](https://buddypress.svn.wordpress.org/trunk/)) `GPLv2` `PHP`
  * [cartulary](https://github.com/daveajones/cartulary) - RSS reader, readability tool, article archiver, microblogger, social graph manager and reading list manager. `CDDL` `PHP`
  * [diaspora*](https://diasporafoundation.org/) - Distributed social networking server. ([Demo](https://podupti.me/go.php), [Source Code](https://github.com/diaspora/diaspora)) `AGPLv3` `Ruby`
  * [Discourse](http://www.discourse.org/) - Advanced forum / community solution based on Ruby and JS. ([Source Code](https://github.com/discourse/discourse)) `GPLv2` `Ruby`
  * [dyu/comments](https://github.com/dyu/comments/) - A markdown-enabled comment engine powered by leveldb. ([Demo](https://dyu.github.io/comments/)) `Apache` `Java`
  * [Elgg](https://elgg.org/) - A powerful open source social networking engine. ([Source Code](https://github.com/Elgg/Elgg)) `GPLv2` `PHP`
  * [Flarum](http://flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. ([Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
  * [flaskbb](https://flaskbb.org/) - FlaskBB is forum software written in Python using the microframework Flask. You can easily create new topics, posts and send other users private messages. It also includes basic administration and moderation tools. ([Source Code](https://github.com/sh4nks/flaskbb)) `BSD` `Python`
  * [FluxBB](http://fluxbb.org/) - Fast, light, user-friendly forum software for your website. ([Source Code](https://github.com/fluxbb/fluxbb)) `GPLv2` `PHP`
  * [Friendica](http://friendica.com/) - Social Communication Server. ([Source Code](https://github.com/friendica/friendica)) `AGPLv3` `PHP`
  * [GNU social](https://gnu.io/social/) - Social communication software for both public and private communications. ([Source Code](https://git.gnu.io/gnu/gnu-social)) `AGPLv3` `PHP`
  * [Hubzilla](https://hubzilla.org) - Decentralized identity, privacy, publishing, sharing, cloud storage, and communications/social platform. ([Source Code](https://github.com/redmatrix/hubzilla)) `MIT` `PHP`
  * [HumHub](https://www.humhub.org/) - A flexible kit for private social networks. ([Source Code](https://github.com/humhub/humhub)) `AGPLv3` `PHP`
  * [Isso](http://posativ.org/isso/) - A lightweight commenting server written in Python and Javascript. It aims to be a drop-in replacement for Disqus. ([Source Code](https://github.com/posativ/isso)) `MIT` `Python`
  * [Jappix](https://jappix.com/) - Jappix is an open social platform, that let's you easily get or keep in touch with everyone. ([Source Code](https://github.com/jappix/jappix)) `AGPLv3` `PHP`
  * [Loomio](https://www.loomio.org/) - Loomio is a collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them. ([Source Code](https://github.com/loomio/loomio)) `AGPLv3` `Ruby`
  * [Mastodon](https://mastodon.social) - Federated microblogging server, an alternative to GNU social. ([Source Code](https://github.com/tootsuite/mastodon)) `AGPLv3` `Ruby`
  * [Movim](https://movim.eu/) - A brand new social network, full of awesome features in a modern and smart interface. ([Source Code](https://github.com/movim/movim)) `AGPLv3` `PHP`
  * [MyBB](http://www.mybb.com/) - Free, extensible forum software package. ([Source Code](https://github.com/mybb/mybb)) `LGPLv3` `PHP`
  * [Newebe](http://newebe.org/) - A Distributed Social Network. ([Source Code](https://github.com/gelnior/newebe)) `AGPLv3` `Python`
  * [NodeBB](https://nodebb.org/) - Node.js based forum software built for the modern web. ([Source Code](https://github.com/NodeBB/NodeBB)) `GPLv3` `Nodejs`
  * [OSSN](https://www.opensource-socialnetwork.org/) - Open Source Social Network (OSSN) is a social networking software written in PHP. It allows you to make a social networking website and helps your members build social relationships, with people who share similar professional or personal interests. ([Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `GPLv2` `PHP`
  * [Oxwall](http://www.oxwall.org/) - Oxwall is used for a wide range of projects starting from family sites and custom social networks to collaboration tools and enterprise community solutions. ([Source Code](https://bitbucket.org/oxwall/public)) `CPALv1` `PHP`
  * [phpBB](https://www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. ([Source Code](https://github.com/phpbb/phpbb)) `GPLv2` `PHP`
  * [PPnet](https://github.com/pixelpark/ppnet) - Create and host your own social network. `MIT` `Javascript`
  * [Pump.io](http://pump.io/) - Stream server that does most of what people really want from a social network. ([Source Code](https://github.com/e14n/pump.io)) `Apache` `Nodejs`
  * [Reddit](https://www.reddit.com/) - Social networking and news website where registered community members can submit content. ([Demo](https://www.reddit.com/), [Source Code](https://github.com/reddit/reddit)) `CPALv1` `Python`
  * [Symphony](https://hacpai.com/) - A modern community (forum/SNS/blog) platform written in Java. ([Source Code](https://github.com/b3log/symphony)) `GPLv3` `Java`
  * [Telescope](http://www.telescopeapp.org/) - An open-source social news app built with Meteor. ([Demo](http://demo.telescopeapp.org/), [Source Code](https://github.com/TelescopeJS/Telescope)) `MIT` `Nodejs`
  * [Tokumei](https://tokumei.co/) - Anonymous microblogging platform. ([Demo](https://demo.tokumei.co/), [Source Code](https://kfarwell.org/projects/tokumei/git/)) `ISC` `rc`
  * [twister](http://twister.net.co/) - Fully decentralized P2P microblogging platform leveraging  the free software implementations of Bitcoin and BitTorrent protocols. ([Source Code](https://github.com/miguelfreitas/twister-core)) `BSD/MIT` `C++`
  * [Vanilla Forums](https://vanillaforums.org/) - Simple and flexible forum software. ([Source Code](https://github.com/vanilla/vanilla)) `GPLv2` `PHP`

### XMPP

**[`^        back to top        ^`](#)**

_[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) software_

#### XMPP Servers

  * [ejabberd](https://www.ejabberd.im/) - XMPP instant messaging server. ([Source Code](https://github.com/processone/ejabberd)) `GPL` `Erlang`
  * [Kontalk](http://kontalk.org/) - Kontalk is an Open Source Messenger, similar to WhatsApp (app for android only currently), including end-to-end encryption, server is based on Tigase XMPP Server. ([Source Code](https://github.com/kontalk)) `GPLv3` `Java`
  * [Metronome IM](https://lightwitch.org/metronome) - Fork of Prosody IM. ([Source Code](http://code.lightwitch.org/)) `MIT` `Lua`
  * [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - Mobile messaging platform with a focus on performance and scalability. ([Source Code](https://github.com/esl/MongooseIM)) `GPLv2` `Erlang`
  * [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. ([Source Code](https://github.com/igniterealtime/Openfire)) `Apache` `Java`
  * [Prosody IM](http://prosody.im/) - Feature-rich and easy to configure XMPP server. ([Source Code](http://hg.prosody.im/)) `MIT` `Lua`
  * [Tigase](http://www.tigase.net/content/tigase-xmpp-server) - XMPP server implementation in Java. `GPLv3` `Java`

#### XMPP Web Clients

  * [Candy](http://candy-chat.github.io/candy/) - Multi user XMPP client written in Javascript. ([Source Code](https://github.com/candy-chat/candy)) `MIT` `Javascript`
  * [Converse.js](https://conversejs.org/) - A free and open-source XMPP chat client in your browser. ([Source Code](https://github.com/jcbrand/converse.js)) `MPLv2` `Javascript`
  * [JSXC](https://jsxc.org) - A Real-time XMPP web chat application with video calls, file transfer and encrypted communication. There are also versions for Nextcloud/Owncloud and SOGo. ([Source Code](https://github.com/jsxc/jsxc)) `MIT` `Javascript`
  * [Kaiwa](http://getkaiwa.com/) - Web based chat client in the style of common paid alternatives. ([Source Code](https://github.com/digicoop/kaiwa)) `MIT` `NodeJS`
  * [Salut à Toi](http://www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralised communication tool. ([Source Code](http://repos.goffi.org/sat)) `AGPLv3` `Python`
    * [Libervia](http://wiki.goffi.org/wiki/Libervia/en) - Web frontend from Salut à Toi. ([Source Code](http://repos.goffi.org/libervia)) `AGPLv3` `Python`


## Conference Management

**[`^        back to top        ^`](#)**

  * [Conference Organizing Distribution (COD)](http://usecod.com/) - Create conference and event websites built on top of Drupal. ([Source Code](http://cgit.drupalcode.org/cod)) `GPL` `PHP`
  * [frab](https://frab.github.io/frab/) - web-based conference planning and management system. It helps to collect submissions, to manage talks and speakers and to create a schedule. ([Source Code](https://github.com/frab/frab)) `MIT` `Ruby`
  * [Open Conference Systems (OCS)](https://pkp.sfu.ca/ocs/) - is a free Web publishing tool that will create a complete Web presence for your scholarly conference. ([Demo](https://pkp.sfu.ca/ocs/ocs_demo/), [Source Code](https://github.com/pkp/ocs)) `GPL` `PHP`
  * [OpenConferenceWare](http://openconferenceware.org/) - An open source web application for supporting conference-like events. This customizable, general-purpose platform provides proposals, sessions, schedules, tracks, user profiles. ([Source Code](https://github.com/osbridge/openconferenceware)) `MIT` `Ruby`
  * [osem](http://osem.io/) - Event management tailored to free Software conferences. ([Demo](http://demo.osem.io/), [Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby`


## Content Management Systems (CMS)

**[`^        back to top        ^`](#)**

CMS are a practical way to setup a website with many features. CMS often come with third party plugins, themes and functionality that is easy to add and customize to your needs. See also [Blogging Platforms](#blogging-platforms) and [Static Site Generators](#static-site-generators)

  * [Apostrophe 2](http://apostrophenow.org/) - A node.js CMS with a focus on extensible in-context editing tools. ([Demo](http://demo.apostrophenow.com/), [Source Code](https://github.com/punkave/apostrophe)) `MIT` `Nodejs`
  * [Baun](https://bauncms.com/) - A modern, lightweight, extensible CMS for PHP. ([Source Code](https://github.com/BaunCMS/Baun)) `MIT` `PHP`
  * [BigTree CMS](https://www.bigtreecms.org/) - Straightforward, well documented, and capable written with PHP and MySQL. ([Source Code](https://github.com/bigtreecms/BigTree-CMS)) `LGPLv2` `PHP`
  * [CMS Made Simple](http://www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL` `PHP`
  * [Concrete 5 CMS](http://www.concrete5.org/) - An open source content management system. ([Source Code](https://github.com/concrete5/concrete5)) `MIT` `PHP`
  * [CouchCMS](http://www.couchcms.com/) - Simple Open-Source CMS for designers. ([Source Code](https://github.com/CouchCMS/CouchCMS)) `CPALv1` `PHP`
  * [Directus](http://getdirectus.com/) - Directus is a powerful and intuitive headless CMS for managing SQL databases with custom architectures. Built around a robust and extensible API, this decoupled content management framework is perfect for websites, apps, or multi-client projects. ([Source Code](https://github.com/directus/directus)) `GPL` `PHP`
  * [Drupal](https://www.drupal.org/) - Advanced open source content management platform. ([Source Code](http://cgit.drupalcode.org/drupal)) `GPL` `PHP`
  * [eLabFTW](http://www.elabftw.net) - An online lab notebook for research labs. Store experiments, use a database to find reagents or protocols, use trusted timestamping to legally timestamp an experiment, export as pdf or zip archive, share with collaborators…. ([Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)) `AGPLv3` `PHP`
  * [GetSimple CMS](http://get-simple.info/) - The Simplest Content Management System. Ever. ([Source Code](https://github.com/GetSimpleCMS/GetSimpleCMS)) `GPLv3` `PHP`
  * [ImpressPages CMS](https://www.impresspages.org/) - Easy code meets easy admin. ([Demo](https://www.impresspages.org/demo), [Source Code](https://github.com/impresspages/ImpressPages)) `GPLv3/MIT` `PHP`
  * [Joomla!](https://www.joomla.org/) - Advanced Content Management System (CMS). ([Source Code](http://joomlacode.org/gf/project/joomla/scmsvn/)) `GPL` `PHP`
  * [KeystoneJS](http://keystonejs.com/) - Node.js CMS & Web Application Platform. ([Demo](http://demo.keystonejs.com/), [Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
  * [MODX](http://modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. ([Source Code](https://github.com/modxcms/revolution)) `GPLv2` `PHP`
  * [Neos](https://www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS based on the Flow framework. ([Source Code](https://git.typo3.org/Packages/TYPO3.Neos.git)) `GPLv3` `PHP`
  * [Noosfero](http://noosfero.org/) - Noosfero is a web platform for social and solidarity economy networks with blog, e-Portfolios, CMS, RSS, thematic discussion, events agenda and collective inteligence for solidarity economy in the same system. ([Source Code](https://gitlab.com/noosfero/noosfero)) `AGPLv3` `Ruby`
  * [october](http://octobercms.com/) - Free, open-source, self-hosted CMS platform based on the Laravel PHP Framework. ([Source Code](https://github.com/octobercms/october)) `MIT` `PHP`
  * [Omeka](http://omeka.org) - Create complex narratives and share rich collections, adhering to Dublin Core standards with Omeka on your server, designed for scholars, museums, libraries, archives, and enthusiasts. ([Demo](http://omeka.org/showcase/), [Source Code](https://github.com/omeka/Omeka)) `GPLv3` `PHP`
  * [Pagekit](https://pagekit.com/) - A new modern CMS to create and share. ([Source Code](https://github.com/pagekit/pagekit)) `MIT` `PHP`
  * [Pico](http://picocms.org/) - A stupidly simple, blazing fast, flat file CMS. ([Source Code](https://github.com/picocms/Pico)) `MIT` `PHP`
  * [Pimcore](https://www.pimcore.org/) - Multi-Channel Experience and Engagement Management Platform. ([Source Code](https://github.com/pimcore/pimcore)) `BSD` `PHP`
  * [Plone](https://plone.org/) - Powerful open-source CMS system. ([Source Code](https://github.com/plone)) `Zope` `Python`
  * [ProcessWire](https://processwire.com/) - ProcessWire is an open source content management system (CMS) and web application framework aimed at the needs of designers, developers and their clients. ([Source Code](https://github.com/ryancramerdesign/ProcessWire)) `MPLv2` `PHP`
  * [PropertyWebBuilder](http://propertywebbuilder.com) - The ultimate Ruby on Rails engine for creating real estate websites. ([Demo](https://propertywebbuilder.herokuapp.com), [Source Code](https://github.com/etewiah/property_web_builder)) `MIT` `Ruby`
  * [Publify](http://publify.co/) - A simple but full featured web publishing software. ([Demo](http://demo.publify.co/), [Source Code](https://github.com/publify/publify)) `MIT` `Ruby`
  * [REDAXO](https://www.redaxo.org) - A simple, flexible and useful content management system (documentation only available in German). ([Source Code](https://github.com/redaxo/redaxo)) `MIT` `PHP`
  * [Redaxscript](https://redaxscript.com) - Ultra lightweight CMS for MySQL, SQLite and PostgreSQL. ([Demo](https://demo.redaxscript.com/demo/login), [Source Code](https://github.com/redaxmedia/redaxscript)) `GPLv3` `PHP`
  * [Roadiz](https://www.roadiz.io/) -  Modern CMS based on a node system which can handle many types of services. ([Source Code](https://github.com/roadiz/roadiz/)) `MIT` `PHP`
  * [SilverStripe](https://www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying. ([Demo](http://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD` `PHP`
  * [Sphido](http://www.sphido.org/) - A fast, lightweight, flat file CMS for PHP. ([Source Code](https://github.com/sphido/cms)) `MIT` `PHP`
  * [SPIP](http://www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors. ([Source Code](https://core.spip.net/projects/spip/repository)) `GPLv2` `PHP`
  * [Subrion](http://www.subrion.org) - Subrion is a free open source content management system that allows you to build websites for any purpose. Yes, from blog to corporate mega portal. ([Demo](http://demos.subrion.com), [Source Code](https://github.com/intelliants/subrion)) `GPLv3` `PHP`
  * [Textpattern](http://textpattern.com/) - A flexible, elegant and easy-to-use CMS. ([Demo](http://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPLv2` `PHP`
  * [TYPO3](https://typo3.org/) - A powerful and advanced CMS with a large community. ([Source Code](https://github.com/TYPO3/TYPO3.CMS)) `GPLv2` `PHP`
  * [Umbraco](https://umbraco.com/) - The friendly CMS. Free and open source with an amazing community. ([Source Code](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
  * [WordPress](https://wordpress.org/) - The worlds most-used blogging and CMS engine. ([Source Code](https://github.com/WordPress/WordPress)) `GPLv2` `PHP`

_Recipe management_

  * [OpenEats](http://www.openeats.org/) - A recipe management site that allows users to create, store, share and rate recipes, create grocery lists, and more. ([Source Code](https://github.com/RyanNoelk/OpenEats)) `BSD` `Python`

### E-commerce

  * [Attendize](https://www.attendize.com/) - Ticket selling and event management platform. ([Demo](https://www.attendize.com/documentation.php#demo), [Source Code](https://github.com/attendize/attendize)) `AAL` `PHP`
  * [CoreShop](https://www.coreshop.org) - CoreShop is a e-commerce plugin for Pimcore. ([Source Code](https://github.com/coreshop/CoreShop)) `GPLv3` `PHP`
  * [Magento](https://magento.com/) - Leading provider of open omnichannel innovation. ([Demo](https://magento.com/schedule-a-demo), [Source Code](https://github.com/magento/magento2)) `OSLv3` `PHP`
  * [Microweber](https://microweber.com/) - Drag and Drop CMS and online shop. ([Demo](http://demo.microweber.org/), [Source Code](https://github.com/microweber/microweber)) `Apache` `PHP`
  * [OpenCart](https://www.opencart.com) - Free open source shopping cart solution. ([Source Code](https://github.com/opencart/opencart)) `GPLv3` `PHP`
  * [Open Classifieds](http://open-classifieds.com/) - Free open-source, self-hosted CMS for classifieds sites. ([Source Code](https://github.com/open-classifieds/openclassifieds2)) `GPL` `PHP`
  * [Open eShop](https://open-eshop.com/) - Sell your digital goods with licenses and provide support. ([Source Code](https://github.com/open-classifieds/open-eshop)) `GPL` `PHP`
  * [Osclass](https://osclass.org/) - One-stop shop to building your own classifieds marketplace. ([Source Code](https://github.com/osclass/Osclass)) `Apache` `PHP`
  * [OXID eShop](http://oxidforge.org) - OXID eShop is a flexible open source e-commerce software with a wide range of functionalities. ([Demo](http://demoshop.oxid-esales.com/community-edition/), [Source Code](https://github.com/OXID-eSales/oxideshop_ce)) `GPLv3` `PHP`
  * [Open Food Network](https://openfoodnetwork.org/) - An online marketplace for local food. It enables a network of independent online food stores that connect farmers and food hubs with individuals and local businesses. ([Source Code](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPLv3` `Ruby`
  * [PrestaShop](https://www.prestashop.com/) - PrestaShop offers a free, open-source and fully scalable e-commerce solution. ([Demo](http://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSLv3` `PHP`
  * [Pretix](https://pretix.eu/) - Django based ticket sales platform for events. ([Source Code](https://github.com/pretix)) `Apache` `Python`
  * [Shuup](https://www.shuup.com/) - Django powered fully customizable open source e-commerce framework for small and large sites. ([Demo](https://www.shuup.com/en/demo/), [Source Code](https://github.com/shuup/shuup)) `AGPLv3` `Python`
  * [Sylius](http://sylius.org/) - Symfony2 powered open source full-stack platform for eCommerce. ([Demo](http://sylius.org/demo), [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
  * [Thelia](http://thelia.net/) - Thelia is an open source and flexible e-commerce solution. ([Demo](http://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)) `LGPL` `PHP`
  * [WooCommerce](https://www.woothemes.com/woocommerce/) - WordPress based e-commerce solution. ([Source Code](https://github.com/woothemes/woocommerce)) `GPL` `PHP`


## DNS

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#dns


## Document Archiving

**[`^        back to top        ^`](#)**

  * [CUPS](https://www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. ([Source Code](https://www.cups.org/software.php)) `GPLv2` `C`
  * [Paperless](https://github.com/danielquinn/paperless) - Scan, index, and archive all of your paper documents. `GPLv3` `Python`
  * [SANE Network Scanning](http://sane-project.org/) - allow remote clients to access image acquisition devices (scanners) available on the local host. ([Source Code](http://www.sane-project.org/cvs.html)) `GPLv2` `C`


## Enterprise Resource Planning

**[`^        back to top        ^`](#)**

* [ERPNext](https://erpnext.com) - Free open source ERP system. ([Demo](https://demo.erpnext.com), [Source Code](https://github.com/frappe/erpnext)) `GPLv3` `Python`
* [Odoo](http://odoo.com) - Free open source ERP system. ([Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)) `LGPLv3` `Python`
* [Tryton](http://www.tryton.org/) - Free open source business solution. ([Demo](http://www.tryton.org/download.html), [Source Code](https://hg.tryton.org/)) `GPLv3` `Python`


## Federated Identity/Authentication

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#identity-management


## Feed Readers

**[`^        back to top        ^`](#)**

  * [CommaFeed](https://www.commafeed.com/) - Google Reader inspired self-hosted RSS reader. ([Source Code](https://github.com/Athou/commafeed)) `Apache` `Java`
  * [Creaky Coot](http://bugs.derivoile.fr/Creaky-Coot/dashboard) - Minimalist and responsive RSS reader and links saver. ([Source Code](https://github.com/piero-la-lune/Creaky-Coot)) `MIT` `PHP`
  * [Feedbin](https://feedbin.com/) - A simple, fast and nice looking RSS reader. ([Source Code](https://github.com/feedbin/feedbin)) `MIT` `Ruby`
  * [FeedHQ](https://feedhq.org/) - FeedHQ is a web-based feed reader. ([Source Code](https://github.com/feedhq/feedhq)) `BSD` `Python`
  * [FreshRSS](http://freshrss.org/) - A self-hostable RSS feed aggregator. ([Demo](http://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Mobile app](https://github.com/Alkarex/EasyRSS)) `AGPLv3` `PHP`
  * [JARR](http://1pxsolidblack.pl/jarr-en.html) - JARR (Just Another RSS Reader) is a web-based news aggregator and reader. ([Demo](https://jarr.info/login?next=%2F), [Source Code](https://github.com/jaesivsm/JARR)) `AGPLv3` `Python`
  * [Kriss Feed](http://tontof.net/kriss/feed/) - A simple and smart (or stupid) feed reader. ([Demo](http://tontof.net/feed/), [Source Code](https://github.com/tontof/kriss_feed/)) `CC0` `PHP`
  * [Leed](http://leed.idleman.fr) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. ([Source Code](https://github.com/ldleman/Leed)) `AGPLv3` `PHP`
  * [Leselys](https://github.com/socketubs/leselys) - Your very elegant RSS reader. `AGPLv3` `Python`
  * [Lite-Reader](http://cubny.com/lite-reader/) - Read your feeds on your own machine with a simple and lite application. ([Source Code](https://github.com/cubny/lite-reader)) `BSD` `PHP`
  * [Moonmoon](http://moonmoon.org/) - simple feed agregator (planet like): it only aggregates feeds and spits them out in one single page. ([Source Code](https://github.com/mauricesvay/moonmoon)) `BSD` `PHP`
  * [Miniflux](https://miniflux.net/) - Miniflux is a minimalist and open source news reader. ([Source Code](https://github.com/miniflux/miniflux)) `AGPLv3` `PHP`
    * [RSSPBRRY](http://jasoncomely.com/rss-tastemaker/) - A fresh new RSS feed reader. ([Source Code](https://github.com/rsspbrry/rsspbrry)) `AGPLv3` `PHP`
  * [NewsBlur](http://www.newsblur.com/) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument. ([Source Code](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
  * [Nunux Reader](http://reader.nunux.org/) - A simple, fast and reactive RSS reader. ([Source Code](https://github.com/ncarlier/nunux-reader)) `GPLv3` `Nodejs`
  * [Reader-Self](http://readerself.com/) - Self-hosted rss reader (php / mysql or sqlite) - Google Reader alternative. ([Source Code](https://github.com/readerself/readerself)) `GPLv3` `PHP`
  * [RSS2EMail](http://www.allthingsrss.com/rss2email/) - Fetches RSS/Atom-feeds and pushes new Content to any email-reciever, supports OPML. ([Source Code](https://github.com/wking/rss2email)) `GPLv2` `Python`
  * [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster is an easy to use web-based RSS aggregator and reader compatible with the Fever API, created as an alternative for Google Reader. `MIT` `PHP`
  * [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder. `MIT` `PHP`
  * [Selfoss](http://selfoss.aditu.de/) - The new multipurpose rss reader, live stream, mashup, aggregation web application. ([Source Code](https://github.com/SSilence/selfoss)) `AGPLv3` `PHP`
  * [Stringer](https://github.com/swanson/stringer) - A work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
  * [Temboz](https://github.com/fazalmajid/temboz) - A two-column feed reader emphasizing filtering capabilities to manage information overload. `MIT` `Python`
  * [Tiny Tiny RSS](https://tt-rss.org/gitlab/fox/tt-rss) - Open source web-based news feed (RSS/Atom) reader and aggregator. ([Demo](http://framanews.org/)) `GPLv3` `PHP`
    * [gritttt-rss](http://gritttt-rss.nicolashoening.de/) - More features for Tiny Tiny RSS. ([Source Code](https://github.com/nhoening/gritttt-rss)) `BSD` `Python`
    * [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - A mobile webapp for Tiny Tiny RSS. `AGPLv3` `Javascript`
    * [ttrss-reader](https://github.com/kucrut/ttrss-reader) - Light and responsive client for TTRSS. `GPLv2` `Javascript`


## File Sharing and Synchronization

**[`^        back to top        ^`](#)**

Some [Groupware](#groupware) solutions also feature file sharing and synchronization.

#### Distributed filesystems

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#distributed-filesystems

#### File transfer/synchronization

  * [Git Annex](http://git-annex.branchable.com) - File synchronization between computers, servers, external drives. ([Source Code](https://github.com/joeyh/git-annex)) `GPLv3` `Haskell`
  * [Kinto](https://kinto.readthedocs.org) - Kinto is a minimalist JSON storage service with synchronisation and sharing abilities. ([Source Code](https://github.com/Kinto)) `Apache` `Python`
  * [Nextcloud](https://nextcloud.com/) - Access & share your files, calendars, contacts, mail & more from any device, on your terms. ([Source Code](https://github.com/nextcloud/server)) `AGPLv3` `PHP`
  * [OpenSSH/SFTP](http://www.openssh.com/) - Secure File Transfer Program. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD` `C`
  * [ownCloud](https://owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more. ([Source Code](https://github.com/owncloud/core)) `AGPLv3` `PHP`
  * [Pydio](https://pydio.com/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers. ([Source Code](https://github.com/pydio/pydio-core)) `AGPLv3` `PHP`
  * [Samba](https://www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol. ([Source Code](https://git.samba.org/samba.git/)) `GPLv3` `C`
  * [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([Demo](https://seacloud.cc/demo), [Source Code](https://github.com/haiwen/seafile)) `GPLv2` `C`
  * [SparkleShare](http://sparkleshare.org/) - Self hosted, instant, secure file sync. ([Source Code](https://github.com/hbons/SparkleShare)) `GPLv3` `C#`
  * [Syncany](https://www.syncany.org/) - Secure file sync software for arbitrary storage backends - An open-source cloud storage and filesharing application. Securely synchronize your files to any kind of storage. `GPLv3` `Java`
  * [Syncthing](https://syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. ([Source Code](https://github.com/syncthing/syncthing)) `MPLv2` `Go`
  * [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - Unison is a file-synchronization tool for OSX, Unix, and Windows. `GPLv3` `OCaml`
  * [Z-Push](http://z-push.org/) - An implementation of Microsoft’s [ActiveSync](https://en.wikipedia.org/wiki/ActiveSync) protocol. ([Source Code](https://stash.z-hub.io/projects/ZP/repos/z-push)) `AGPLv3` `PHP`

#### Peer-to-peer filesharing

  * [bittorrent-tracker](https://webtorrent.io/) - Simple, robust, BitTorrent tracker (client & server) implementation. ([Source Code](https://github.com/feross/bittorrent-tracker)) `MIT` `Nodejs`
  * [FilePizza](http://file.pizza/) - Peer-to-peer file transfers in your browser. ([Source Code](https://github.com/kern/filepizza)) `BSD` `Nodejs`
  * [instant.io](https://github.com/feross/instant.io) - Streaming file transfer over WebTorrent. ([Demo](https://instant.io)) `MIT` `Nodejs`
  * [Magnetico](https://github.com/boramalper/magnetico) - Magnetico is the first autonomous (self-hosted) BitTorrent DHT search engine suite that is designed for end-users. `APGLv3` `Python`
  * [Magnetissimo](https://github.com/sergiotapia/magnetissimo) - Search engine that indexes all popular torrent sites. `MIT` `Elixir`
  * [Opentracker](http://erdgeist.org/arts/software/opentracker/) - Open and free bittorrent tracker. It aims for minimal resource usage and is intended to run at your wlan router. ([Source Code](http://erdgeist.org/gitweb/opentracker/)) `Beerware` `C`
  * [peerflix-server](https://github.com/asapach/peerflix-server) - Downloads torrent files and provides a direct link download or a direct link stream. `MIT` `Nodejs`
  * [rartracker](https://github.com/swetorrentking/rartracker) - Complete private bittorrent tracker. `WTFPL` `PHP`
  * [Reep](https://reep.io) - In-browser peer-to-peer file transfer and streaming made easy. ([Source Code](https://github.com/KodeKraftwerk/reepio)) `GPLv2` `Nodejs`
  * [Transmission](https://transmissionbt.com/) - A fast, easy, Free Bittorrent client. ([Source Code](https://github.com/transmission/transmission)) `GPLv3` `C`

#### Single-click/drag-n-drop upload

  * [BoZoN](https://github.com/broncowdd/BoZoN) - Minimalist Drag & drop file sharing app. `AGPLv3` `PHP`
  * [Coquelicot](https://coquelicot.potager.org/) - Coquelicot is a “one-click” file sharing web application with a focus on protecting users’ privacy. ([Source Code](https://coquelicot.potager.org/gitweb/?p=coquelicot.git)) `AGPLv3` `Ruby`
  * [droppy](https://github.com/silverwind/droppy) - droppy is a self-hosted cloud server with an interface similar to desktop file managers and has capabilites to edit files on-the-fly as well as view and playback media directly in the browser. ([Demo](http://droppy.silverwind.io/)) `BSD` `Nodejs`
  * [FileShelter](https://github.com/epoupon/fileshelter) - FileShelter is a self-hosted software that allows you to easily share files over the Internet. ([Demo](http://fileshelter.suroot.com/)) `GPLv3` `C++`
  * [img.bi](https://github.com/imgbi/img.bi) - img.bi is a secure image hosting. Images are encrypted using AES-256 with random key in browser before upload. `GPLv3` `Nodejs`
  * [ipfs.pics](https://ipfs.pics/) - ipfs.pics is a o distributed image hosting website. ([Source Code](https://github.com/ipfspics/server)) `AGPLv3` `PHP`
  * [Jirafeau](https://gitlab.com/mojo42/Jirafeau) - Jirafeau is a web site permitting to upload a file in a simple way and give an unique link to it. ([Demo](http://jirafeau.net/)) `AGPLv3` `PHP`
  * [linx](https://github.com/andreimarcu/linx-server) - File sharing application and pastebin with API, auto-expiry, deletion keys, and web seed support. ([Demo](https://linx.li/)) `GPLv3` `Go`
  * [lufi](https://git.framasoft.org/luc/lufi) - Let's Upload that FIle, client-side encrypted. ([Demo](https://demo.lufi.io), [Source Code](https://git.framasoft.org/luc/lufi/tree/master)) `AGPLv3` `Perl`
  * [lutim](https://github.com/ldidry/lutim) - Let's Upload That Image. `AGPLv3` `Perl`
  * [Minio](https://minio.io/) - Store photos, videos, VMs, containers, log files, or any blob of data as objects. ([Source Code](https://github.com/minio/minio)) `Apache` `Go`
  * [Nimbus](https://github.com/ethanal/nimbus) - A drag-and-drop shortlink file sharer for OS X. `MIT` `Python`
  * [OnionShare](https://github.com/micahflee/onionshare) - Securely and anonymously share a file of any size. `GPLv2` `Python`
  * [PictShare](https://www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. ([Demo](https://www.pictshare.net/), [Source Code](https://github.com/chrisiaut/pictshare)) `Apache` `PHP`
  * [Plik](https://github.com/root-gg/plik) - Plik is a scalable & friendly temporary file upload system ( wetransfer like ). ([Demo](https://plik.root.gg/)) `MIT` `Go`
  * [Pomf](https://github.com/Pomf/Pomf) - Simple file uploading and sharing, source for the now shut down site Pomf.se. `MIT` `PHP`
  * [ProjectSend](http://www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. ([Source Code](https://github.com/ignacionelson/ProjectSend)) `GPLv2` `PHP`
  * [PsiTransfer](https://github.com/psi-4ward/psitransfer) - Simple open source self-hosted file sharing solution with robust up-/download-resume and password protection. ([Demo](https://transfer.psi.cx/)) `BSD` `Nodejs`
  * [Sharry](https://github.com/eikek/sharry) - Share files easily over the internet between authenticated and anonymous users (both ways) with resumable up- and downloads. ([Demo](https://sharrydemo.eknet.org)) `GPLv3` `Scala/Java`
  * [transfer.sh](https://transfer.sh) - Easy file sharing from the command line. ([Demo](https://transfer.sh), [Source Code](https://github.com/dutchcoders/transfer.sh)) `MIT` `Go`
  * [Uguu](https://uguu.se/) - Stores files and deletes after X amount of time. ([Source Code](https://github.com/nokonoko/uguu)) `MIT` `PHP`
  * [Up1](https://github.com/Upload/Up1) - A Client-side Encrypted Image Host. ([Demo](https://up1.ca/)) `MIT` `Nodejs`
  * [uPste](https://u.pste.pw) - A private file hosting application with an emphasis on serving technology communities. ([Source Code](https://github.com/TheReverend403/uPste)) `AGPLv3` `PHP`
  * [YouTransfer](http://www.youtransfer.io) - YouTransfer is a simple but elegant self-hosted file transfer & sharing solution. ([Demo](http://demo.youtransfer.io/), [Source Code](https://github.com/remie/YouTransfer)) `Apache` `Nodejs`

#### Web based file managers

  * [Apaxy](http://adamwhitcroft.com/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. ([Source Code](https://github.com/AdamWhitcroft/Apaxy)) `Unlicense` `HTML`
  * [DirectoryLister](http://www.directorylister.com/) - A simple PHP based directory lister that lists a directory and all it's sub-directories and allows you to navigate there within. ([Source Code](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP`
  * [Encode Explorer](http://encode-explorer.siineiolekala.net/) - Encode Explorer is a single page file browser, it is simple and functional. ([Demo](http://encode-explorer.siineiolekala.net/explorer/index.php), [Source Code](https://github.com/marekrei/encode-explorer)) `MIT` `PHP`
  * [explorer](https://github.com/soyuka/explorer) - Highly-configurable directory listing made with nodejs. ([Source Code](https://github.com/soyuka/explorer)) `MIT` `Nodejs`
  * [eXtplorer](https://extplorer.net/) - A PHP and Javascript based File Manager. ([Source Code](https://extplorer.net/projects/extplorer/repository)) `MPLv1.1/GPLv2` `PHP`
  * [goBrowser](https://github.com/xataz/gobrowser) - Simple http file browser. ([Source Code](https://github.com/xataz/gobrowser)) `GPLv3` `Go`
  * [h5ai](https://larsjung.de/h5ai/) - Modern file indexer for HTTP web servers with focus on your files. Directories are displayed in a appealing way and browsing them is enhanced by different views, a breadcrumb and a tree overview. ([Demo](https://larsjung.de/h5ai/demo/), [Source Code](https://github.com/lrsjng/h5ai)) `MIT` `PHP`
  * [Monsta FTP](http://www.monstaftp.com/) - Open source PHP/Ajax cloudware that puts FTP file management right in your browser, anywhere, any time. ([Demo](http://mftp.live/), [Source Code](https://github.com/MonstaApps/Monsta-FTP)) `GPLv3` `PHP`
  * [ResourceSpace](http://www.resourcespace.org) - ResourceSpace open source digital asset management software is the simple, fast, & free way to organise your digital assets. ([Demo](http://www.resourcespace.org/trial), [Source Code](http://www.resourcespace.org/svn)) `BSD/Other` `PHP`
  * [Sprut.io](https://sprut.io) - 2 panel file manager with drag and drop features, code editor, text search, hotkeys. ([Demo](https://demo.sprut.io:9443), [Source Code](https://github.com/LTD-Beget/sprutio)) `GPLv3` `Python`
  * [Surfer](https://github.com/nebulade/surfer) - Simple static file server with webui to manage files. `MIT` `Nodejs`


## Games

**[`^        back to top        ^`](#)**

  * [0hh1](https://github.com/Q42/0hh1) - A lovely little logic game by Q42. ([Demo](http://0hh1.com/)) `MIT` `HTML5`
  * [A Dark Room](https://github.com/doublespeakgames/adarkroom) - A minimalist text adventure game for your browser. ([Demo](http://adarkroom.doublespeakgames.com/)) `MPLv2` `HTML5`
  * [Agar.IO Clone](https://github.com/huytd/agar.io-clone) - Agar.io clone written with Socket.IO and HTML5 canvas. `MIT` `Nodejs`
  * [battlecraft](https://github.com/jbreindel/battlecraft) - A fully distributed multiplayer browser game. ([Demo](http://battlecraft.online)) `Apache` `Erlang`
  * [Clumsy Bird](https://github.com/ellisonleao/clumsy-bird) - A MelonJS port of the famous Flappy Bird Game. ([Demo](http://www.ellison.rocks/clumsy-bird/)) `MIT` `Nodejs`
  * [Hextris](https://github.com/Hextris/hextris) - Fast paced HTML5 puzzle game inspired by Tetris. ([Demo](http://hextris.io/)) `GPLv3` `HTML5`
  * [Posio](https://github.com/abrenaut/posio/) - A geography multiplayer game. ([Demo](https://posio.abrenaut.com/)) `MIT` `Python`
  * [TournamentMango](http://tournamentmango.com/) - TournamentMango is an open source tournament bracket and user management system. You can build an archive of players and keep track of all their scores over time as well as their regular characters, games, and aliases. ([Source Code](https://github.com/seiyria/tournamentmango)) `MIT` `Javascript`


## Gateways

**[`^        back to top        ^`](#)**

  * [GateOne](http://liftoffsoftware.com/Products/GateOne) - Gate One is an HTML5 web-based terminal emulator and SSH client. ([Source Code](https://github.com/liftoff/GateOne/)) `AGPLv3` `Python`
  * [Guacamole](http://guac-dev.org/) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. ([Source Code](https://github.com/glyptodon/)) `Apache` `Java/C`
  * [oneye](https://oneye-project.org/) - Cloud software to access your data from everywhere with any browser. ([Demo](https://wiki.oneye-project.org/0.9:demo), [Source Code](https://github.com/oneye/oneye)) `AGPLv3` `PHP`
  * [OS.js](https://os.js.org/) - A desktop implementation for your browser with a fully-fledged window manager, Application APIs, GUI toolkits and filesystem abstraction. ([Demo](https://osjsv2.0o.no/), [Source Code](https://github.com/os-js/OS.js)) `BSD` `Nodejs`


## Groupware

**[`^        back to top        ^`](#)**

  * [Citadel](http://www.citadel.org/doku.php) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more. ([Source Code](http://www.citadel.org/doku.php/installation:source)) `GPLv3` `C`
  * [Cozy Cloud](https://cozy.io) - A personal cloud where you can read your emails or manage and sync your contact, files or calendars, with an app store full of community contributions. ([Source Code](https://github.com/cozy)) `GPLv3` `Nodejs`
  * [egroupware](http://www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS. ([Source Code](https://github.com/EGroupware/egroupware)) `GPLv2` `PHP`
  * [Horde](http://www.horde.org/) - The Horde Project is about creating high quality Open Source applications and libraries, based on PHP and the Horde Framework. ([Demo](http://demo.horde.org/login.php), [Source Code](https://github.com/horde/horde)) `GPLv2` `PHP`
  * [Kolab](https://kolab.org/) - Kolab community is a unified communication and collaboration system. ([Source Code](https://git.kolab.org/)) `Multiple` `C++/Python/PHP`
  * [Kopano](https://kopano.com/) - Groupware suite including e-mail, calendars, tasks, todos and notes. Featuring a modern WebApp, DeskApp and mobile access over Z-Push/ActiveSync. ([Demo](http://demo.kopano.com), [Source Code](https://stash.kopano.io)) `AGPLv3` `C/Python/PHP`
  * [Mayan EDMS](http://www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features. ([Demo](http://demo.mayan-edms.com), [Source Code](https://gitlab.com/mayan-edms/mayan-edms)) `Apache` `Python`
  * [Openmeetings](https://openmeetings.apache.org/index.html) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming. ([Source Code](https://openmeetings.apache.org/source-repository.html)) `Apache` `Java`
  * [Sogo](http://www.sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and web interface. ([Demo](http://demo.sogo.nu/SOGo/), [Source Code](https://github.com/inverse-inc/sogo)) `GPLv1/LGPLv2` `Objective-C`
  * [Tine 2.0](https://www.tine20.org) - Contacts, Calendar, Tasks, WebDAV, ActiveSync, VOIP, Mail-Client, CRM, Sales, Projects, Timetracker. ([Demo](https://demo.tine20.net), [Source Code](https://packages.tine20.com/maintenance/source/)) `AGPLv3/Other` `PHP`
  * [Zimbra Collaboration](https://www.zimbra.com/downloads/) - Email, calendar, collaboration server with web interface and lots of integrations. ([Source Code](https://git.zimbra.com/repos/zimbra-foss/)) `GPLv2/CPALv1` `Java`


## Human Resources Management (HRM)

**[`^        back to top        ^`](#)**

  * [admidio](https://www.admidio.org/) - Admidio is a free open source user management system for websites of organizations and groups. The system has a flexible role model so that it’s possible to reflect the structure and permissions of your organization. ([Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)) `GPLv2` `PHP`
  * [IceHrm](https://icehrm.com/) - IceHrm employee management system allows companies to centralize confidential employee information. ([Demo](https://icehrm.com/demo.php), [Source Code](https://github.com/gamonoid/icehrm/)) `Apache` `PHP`
  * [OrangeHRM](https://www.orangehrm.com/) - OrangeHRM is a comprehensive HRM system that captures all the essential functionalities required for any enterprise. ([Source Code](https://sourceforge.net/projects/orangehrm/)) `GPLv2` `PHP`
  * [Sentrifugo](http://www.sentrifugo.com/) - Sentrifugo is a HRM system that can be easily configured to meet your organizational needs. ([Source Code](https://github.com/sapplica/sentrifugo)) `GPLv3` `PHP`


## Learning and Courses

**[`^        back to top        ^`](#)**

  * [Canvas LMS](https://www.canvaslms.com/) - Canvas is the trusted, open-source learning management system (LMS) that is revolutionizing the way we educate. ([Demo](https://canvas.instructure.com/register), [Source Code](https://github.com/instructure/canvas-lms)) `AGPLv3` `Ruby`
  * [Chamilo LMS](https://chamilo.org/chamilo-lms/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. ([Source Code](https://github.com/chamilo/chamilo-lms)) `GPLv3` `PHP`
  * [edX](https://www.edx.org/) - The Open edX platform is open-source code that powers [edX.org](https://www.edx.org/). ([Source Code](https://github.com/edx/)) `AGPLv3` `Python`
  * [ILIAS](http://www.ilias.de) - ILIAS is the Learning Management System that can cope with anything you throw at it. ([Demo](http://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPLv3` `PHP`
  * [lxHive](http://www.lxhive.com/) - Open Source ExperienceAPI compliant Learning Record Store (LRS) - previously code-named TinCanAPI. ([Source Code](https://github.com/Brightcookie/lxHive)) `GPLv3` `PHP`
  * [Mahara](https://mahara.org/) - Open Source fully featured web application to build students electronic portfolio. ([Source Code](https://github.com/MaharaProject/mahara)) `GPLv3` `PHP`
  * [Moodle](https://moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide. ([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL` `PHP`
  * [Open eClass](http://www.openeclass.org/) - Open eClass is an advanced e-learning solution that can enhance the teaching and learning process. ([Demo](http://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)) `GPL` `PHP`
  * [RELATE](https://documen.tician.de/relate/) - RELATE is a web-based courseware package, includes features such as: flexible rules, statistics, multi-course support, class calender. ([Source Code](https://github.com/inducer/relate/)) `MIT` `Python`
  * [Sakai](https://www.sakaiproject.org/) - The Sakai project provides a flexible and feature-rich environment for teaching, learning, research and other collaboration. ([Demo](https://www.sakaiproject.org/try-sakai), [Source Code](https://github.com/sakaiproject/sakai)) `ECLv2` `Java`
  * [SchoolTool](http://schooltool.org/) - SchoolTool is free administrative software for schools. It includes demographics, gradebook, attendance, calendaring, reporting and more for primary and secondary schools. ([Source Code](http://bazaar.launchpad.net/~schooltool-owners/schooltool/2.8/files)) `GPLv2` `Python`


## Maps & GPS

**[`^        back to top        ^`](#)**

  * [Graphhopper](https://graphhopper.com/) - Fast routing library and server using OpenStreetMap. ([Source Code](https://github.com/graphhopper/graphhopper)) `Apache` `Java`
  * [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - Tool for sharing custom OSM maps. Support for annotated markers, polygons, lines, multi-format import/export, multiple layers, shortlinks. ([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP`
  * [OpenGTS](http://www.opengts.org/) - Entry-level fleet tracking system. Supports variety of tracking devices and protocols. Comes with rich web-interface and reporting features. ([Demo](http://track.opengts.org/track/Track), [Source Code](https://sourceforge.net/projects/opengts/files/server-base/)) `Apache` `Java`
  * [Openstreetmap](http://www.openstreetmap.org/) - OpenStreetMap is a map of the world, created by people like you and free to use under an open license. ([Source Code](https://github.com/openstreetmap/openstreetmap-website)) `GPLv2` `Ruby`
  * [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - Store and access data published by [OwnTracks](http://owntracks.org/) location tracking apps. `GPLv2` `C`/`Lua`
  * [Traccar](https://www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips. ([Demo](http://demo.traccar.org/), [Source Code](https://github.com/tananaev?tab=repositories)) `Apache` `Java`
  * [uMap](https://umap.openstreetmap.fr/en/) - Create maps with OpenStreetMap layers in a minute and embed them in your site. ([Source Code](https://github.com/umap-project/umap)) `WTFPL` `Python`


## Media Streaming

**[`^        back to top        ^`](#)**

See also <https://en.wikipedia.org/wiki/List_of_streaming_media_systems>, <https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems>

### Audio Streaming

  * [Airtime](https://www.sourcefabric.org/en/airtime/) - Simple, open source platform that lets you broadcast streaming radio on the web. ([Source Code](https://github.com/sourcefabric/Airtime)) `AGPLv3` `PHP`
  * [Ampache](http://ampache.org/) - A web based audio/video streaming application. ([Demo](http://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPLv3` `PHP`
  * [CherryMusic](http://www.fomori.org/cherrymusic/) - Minimalistic Web-Mediaplayer. ([Source Code](https://github.com/devsnd/cherrymusic)) `GPLv3` `Python`
  * [cloudtunes](https://github.com/jkbrzt/cloudtunes) `⚠` - Web-based music player for the cloud. `MIT` `Python`
  * [GNU FM](https://gnu.io/fm/) - Running music community websites, alternative to last.fm. ([Source Code](http://git.savannah.gnu.org/cgit/librefm.git/)) `AGPLv3` `PHP`
  * [Groove Basin](http://groovebasin.com/) - A music player server with a web-based user interface inspired by Amarok 1.4. ([Source Code](https://github.com/andrewrk/groovebasin)) `MIT` `Nodejs`
  * [Icecast 2](http://www.icecast.org/) - streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between. ([Source Code](https://git.xiph.org/?p=icecast-server.git;a=summary)) `GPLv2` `C`
  * [koel](http://koel.phanan.net/) - A personal music streaming server that works. ([Source Code](https://github.com/phanan/koel)) `MIT` `PHP`
  * [Libresonic](http://libresonic.org/) - Open-source web-based media streamer and jukebox. A fork of Subsonic's last open-source release, before it switched licenses. `GPLv3` `Java`
  * [Mopidy](http://mopidy.readthedocs.org/) - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ([Source Code](https://github.com/mopidy/mopidy)) `Apache` `Python`
   * [Moped](https://github.com/martijnboland/moped) - Responisve HTML5 + Javascript client for the Mopidy music server. `MIT` `HTML5`
   * [Mopidy MusicBox](https://github.com/pimusicbox/mopidy-musicbox-webclient) - Web Client for Mopidy Music Server. `Apache` `HTML5`
   * [Mopidy-Party](https://github.com/Lesterpig/mopidy-party) - Mopidy web extension designed for party! Let your guests manage the sound. `Apache` `Python`
  * [mpd](http://www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. `GPLv2` `C++`
  * [mStream](http://mstream.io/) - Music streaming server with GUI management tools. Runs on Mac, Windows, and Linux. ([Demo](https://darncoyotes.mstream.io/), [Source Code](https://github.com/IrosTheBeggar/mStream)) `GPLv2` `Nodejs`
   * [ympd](http://www.ympd.org/) - Standalone MPD Web GUI written in C, utilizing Websockets and Bootstrap/JS. ([Source Code](https://github.com/notandy/ympd)) `GPLv2` `C`
  * [Sonerezh](https://www.sonerezh.bzh/) - A self-hosted, web-based application for stream your music, everywhere. ([Demo](https://www.sonerezh.bzh/demo/), [Source Code](https://github.com/sonerezh/sonerezh)) `GPLv3` `PHP`

### Video Streaming

  * [CyTube](https://github.com/calzoneman/sync) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels. ([Demo](http://cytu.be)) `MIT` `Nodejs`
  * [Emby](http://emby.media/) - A home media server built using other popular open source technologies. ([Source Code](https://github.com/MediaBrowser/Emby)) `GPLv2` `C#`
  * [Flumotion](http://flumotion.net/) - A streaming media server with intuitive graphical administration tools. ([Source Code](https://github.com/Flumotion/flumotion)) `LGPLv2` `Python`
  * [Hellowlol HTPC Manager fork](https://github.com/Hellowlol/HTPC-Manager) - A fully responsive interface to manage all your favorite media on your HTPC. ([Source Code](https://github.com/styxit/HTPC-Manager)) `MIT` `Python`
  * [Icecast 2](http://www.icecast.org/) - streaming audio/video server which can be used to create an Internet radio station or a privately running jukebox and many things in between. ([Source Code](https://git.xiph.org/?p=icecast-server.git;a=summary)) `GPLv2` `C`
  * [MistServer](http://mistserver.org/) - A streaming media server that works well in any streaming environment. ([Source Code](https://github.com/DDVTECH/mistserver)) `AGPLv3` `C++`
  * [Odd Networks](http://oddnetworks.com) - Open source video management system (VMS) and API for collections and videos with supporting SDKs for Roku, Apple iOS/tvOS, Google Android, and Amazon FireTV. ([Source Code](https://github.com/oddnetworks/oddworks)) `MIT` `Nodejs`
  * [ReadyMedia](http://sourceforge.net/projects/minidlna/) - A simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. `GPLv2` `C`
  * [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. ([Source Code](https://github.com/datarhei/restreamer)) `Apache` `Nodejs/Docker`
  * [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel is a UPnP AV MediaServer that allows you to easily share audio, video, and pictures. Media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller. `GPLv3` `C`
  * [Shinobi](https://moeiscool.github.io/Shinobi/) - Open Source CCTV software written in Node with both IP and local camera support. ([Source Code](https://github.com/moeiscool/Shinobi)) `GPLv2` `Nodejs`
  * [Streama](https://github.com/dularion/streama) - Self-hosted Netflix alternative. `MIT` `Java`
  * [Zoneminder](https://github.com/ZoneMinder/ZoneMinder) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. `GPLv2` `PHP`


## Misc/Other

**[`^        back to top        ^`](#)**

  * [411](https://demo.fouroneone.io/) - An Alert Management Web Application. ([Source Code](https://github.com/etsy/411)) `MIT` `PHP`
  * [Anchr](https://anchr.io) - Anchr is a toolbox for tiny tasks on the internet, including bookmark collections, URL shortening and (encrypted) image uploads. ([Source Code](https://github.com/n1try/anchr)) `GPLv3` `Nodejs`
  * [COPS](https://blog.slucas.fr/en/oss/calibre-opds-php-server) - A lightweight e-book server alternative to Calibre content server or Calibre2OPDS. ([Demo](http://cops-demo.slucas.fr/index.php), [Source Code](https://github.com/seblucas/cops)) `GPLv2` `PHP`
  * [CrushPaper](https://www.crushpaper.com/) - Research the web for relevant sources, save quotations from them to CrushPaper and then combine them with your own insights into a paper. ([Source Code](https://github.com/ZapBlasterson/crushpaper)) `AGPLv3` `Java`
  * [DomainMOD](https://domainmod.org) - An application to manage your domains and other internet assets in a central location. DomainMOD includes a Data Warehouse framework that allows you to import your WHM/cPanel web server data so that you can view, export, and report on your data. ([Demo](https://demo.domainmod.org), [Source Code](https://github.com/domainmod/domainmod)) `GPLv3` `PHP`
  * [EasyBook Project](http://easybook-project.org/) - Book publishing as easy as it should be. ([Source Code](https://github.com/javiereguiluz/easybook)) `MIT` `PHP`
  * [Flox](https://github.com/devfake/flox) `⚠` - Self hosted movie, TV series and anime watch list with a 3-point rating system. Uses The Movie Database backend for information. ([Demo](http://80.240.132.120/flox-demo/public/)) `MIT` `PHP`
  * [GeneWeb](https://geneweb.tuxfamily.org/wiki/GeneWeb) - GeneWeb is an open source genealogy software written in OCaml. It comes with a Web interface and can be used off-line or as a Web service. ([Demo](https://demo.geneweb.tuxfamily.org/gw7/), [Source Code](https://github.com/geneweb/geneweb)) `GPLv2` `OCAML`
  * [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - A Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets. ([Demo](https://google-webfonts-helper.herokuapp.com/)) `MIT` `Nodejs`
  * [King Phisher](https://github.com/securestate/king-phisher) - King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. `BSD` `Python`
  * [LicAPI](https://projects.miguelpiedrafita.com/LicAPI) - A PHP API to manage license info. ([Source Code](https://github.com/m1guelpf/LicAPI)) `MPLv2` `PHP`
  * [Mindmaps](https://github.com/drichard/mindmaps) - An open source, offline capable, mind mapping application. ([Demo](http://drichard.org/mindmaps/)) `AGPLv3` `HTML5`
  * [Musical Artifacts](https://musical-artifacts.com/) - Helping to catalog, preserve and free the artifacts you need to produce music. ([Source Code](https://github.com/lfzawacki/musical-artifacts)) `MIT` `Ruby`
  * [nnmm](https://nnmm.nl/) - A super tiny pastebin/url minifier "microservice". ([Source Code](https://github.com/Mechazawa/nnmm)) `Beerware` `PHP`
  * [Notica](https://notica.us) - Lets you send browser notifications from your terminal to your desktop or phone. No installation or registration is required. ([Source Code](https://github.com/tannercollin/Notica)) `MIT` `Nodejs`
  * [Skygear](https://skygear.io) - A complete backend server for web, mobile and iOT applcations. ([Demo](https://portal.skygear.io), [Source Code](https://github.com/SkygearIO/skygear-server)) `Apache` `Go`
  * [Trello Burndown](https://github.com/swordbeta/trello-burndown) `⚠` - An easy to use SCRUM burndown chart for Trello boards. `MIT` `Go/Docker`
  * [Ulterius](https://ulterius.io) - Ulterius is an open-source remote desktop software with lots of awesome functions. ([Demo](https://ulterius.io/signup/), [Source Code](https://github.com/Ulterius/server)) `MPLv2` `C#`
  * [ViMbAdmin](http://www.vimbadmin.net/) - Provides a web based virtual mailbox administration system to allow mail administrators to easily manage domains, mailboxes and aliases. ([Demo](http://www.vimbadmin.net/demo/auth/login), [Source Code](https://github.com/opensolutions/ViMbAdmin)) `GPLv3` `PHP`
  * [visualCaptcha](http://visualcaptcha.net/) - A configurable captcha solution, focusing on accessibility & simplicity whilst maintaining security. ([Demo](http://demo.visualcaptcha.net/), [Source Code](https://github.com/emotionLoop/visualCaptcha)) `MIT` `PHP/Nodejs/Ruby/Python`
  * [webtrees](https://www.webtrees.net) - webtrees is the web's leading on-line collaborative genealogy application. ([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)) `GPLv3` `PHP`

## Money, Budgeting and Management

**[`^        back to top        ^`](#)**

See also https://github.com/n1trux/awesome-sysadmin#it-asset-management

  * [Benedetto](https://github.com/arecker/bennedetto) - Bennedetto is a simple, turn-based budget management app. `GPLv3` `Python`
  * [Budget App](https://www.budgetapp.io/) - Budget App is an open source personal budgeting application. ([Demo](https://demo.budgetapp.io/), [Source Code](https://github.com/paukiatwee/budgetapp)) `Apache` `Java`
  * [Dot Ledger](https://www.dotledger.com/) - A web-based personal finance management tool. ([Demo](https://demo.dotledger.com/), [Source Code](https://github.com/dotledger/dotledger)) `Apache` `Ruby`
  * [Economizzer](http://www.economizzer.org/) - Economizzer is a simple and open source personal finance manager system, available in English, Portuguese (PT|BR) and Russian. ([Source Code](https://github.com/gugoan/economizzer)) `MIT` `PHP`
  * [ExMoney](https://github.com/gaynetdinov/ex_money) - A [work-in-progress] self-hosted personal finance app. `ISC` `Elixir`
  * [Firefly III](https://firefly-iii.github.io/) - Firefly III is a modern financial manager. It helps you to keep track of your money and make budget forecasts. It supports credit cards, shared household accounts, and savings accounts. It's powered by Laravel and requires PHP7. ([Demo](https://firefly-iii.nder.be/), [Source Code](https://github.com/firefly-iii/firefly-iii)) `CCBYSAv4` `PHP`
  * [Galette](http://galette.eu/dc/) - Galette is a membership management web application towards non profit organizations. ([Source Code](http://git.tuxfamily.org/galette/galette.git/)) `GPLv3` `PHP`
  * [GRR](http://grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. ([Source Code](https://github.com/JeromeDevome/GRR)) `GPLv2` `PHP`
  * [Hospital Run](http://hospitalrun.io/) - Hospital Run is offline enabled hospital management software. ([Source Code](https://github.com/HospitalRun/hospitalrun-server), [Demo](http://hospitalrun.io/demo/)) `GPLv3` `Nodejs`
  * [Inventaire](https://inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs. ([Source Code](https://github.com/inventaire/inventaire)) `AGPLv3` `Nodejs`
  * [Invoice Ninja](https://www.invoiceninja.org/) - A powerful tool to invoice clients online. ([Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
  * [InvoicePlane](https://invoiceplane.com/) - Manage quotes, invoices, payments and customers for your small business. ([Demo](https://demo.invoiceplane.com), [Source Code](https://github.com/InvoicePlane/InvoicePlane)) `MIT` `PHP`
  * [IHateMoney](http://ihatemoney.org/) - Manage your shared expenses, easily. ([Source Code](https://github.com/spiral-project/ihatemoney)) `BSD` `Python`
  * [Koha](https://koha-community.org/) - Fully featured, scalable library management system (integrated library system - ILS). ([Source Code](https://github.com/Koha-Community/Koha)) `GPLv3` `Perl`
  * [PartKeepr](https://www.partkeepr.org) - PartKeepr is an electronic part inventory management software. It helps you to keep track of your available parts and assist you with re-ordering parts. ([Demo](https://demo.partkeepr.org/), [Source Code](https://github.com/partkeepr/PartKeepr)) `GPLv3` `PHP`
  * [StockazNG](https://dev.sigpipe.me/dashie/StockazNG) - Asset Management System. `MIT` `Python`


## Monitoring

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#monitoring and https://github.com/n1trux/awesome-sysadmin#metric--metric-collection


## Note-taking & Editors

**[`^        back to top        ^`](#)**

*See also [Wikis](#wikis)*

  * [dillinger](http://dillinger.io/) - The last Markdown editor, ever. ([Source Code](https://github.com/joemccann/dillinger/)) `MIT` `Nodejs`
  * [Laverna](https://laverna.cc/) - Laverna is a Javascript note taking application with Markdown editor and encryption support. Consider it like open source alternative to Evernote. ([Demo](https://laverna.cc/index.html#notes), [Source Code](https://github.com/Laverna/laverna)) `MPLv2` `Nodejs`
  * [Leanote](http://leanote.org/) - Leanote, Not Just A Notepad! Open source cloud notepad. ([Demo](https://leanote.com/note), [Source Code](https://github.com/leanote/leanote)) `GPLv2` `Go`
  * [Markdown Edit](http://georgeosddev.github.com/markdown-edit/) - Online markdown editor/viewer. ([Source Code](https://github.com/georgeOsdDev/markdown-edit)) `MIT` `HTML5`
  * [Meemo](https://meemo.minimal-space.de/) - Personal notes stream with Markdown support. ([Source Code](https://github.com/nebulade/meemo)) `MIT` `Nodejs`
  * [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - A minimalist notepad.cc clone. `Apache` `PHP`
  * [notes](https://github.com/SSilence/notes) - Simple script for personal notes with a single page with a WYSIWYG Editor. `GPLv3` `PHP`
  * [OpenNote](https://github.com/FoxUSA/OpenNote) - OpenNote was built to be an open web-based alternative to Microsoft OneNote (T) and EverNote. ([Demo](https://foxusa.github.io/OpenNote/OpenNote/#/folder)) `MIT` `HTML5`
  * [Paperwork](http://paperwork.rocks) - OpenSource note-taking & archiving alternative to Evernote, Microsoft OneNote & Google Keep. ([Source Code](https://github.com/twostairs/paperwork)) `MIT` `PHP`
  * [savepad](https://github.com/novavex/textpad) - A minimalist notepad based on notepad.cc. `MIT` `PHP`
  * [ShareLaTex](https://www.sharelatex.com/) - A web-based collaborative LaTeX editor. ([Source Code](https://github.com/sharelatex/sharelatex)) `AGPLv3` `Ruby`
  * [to-markdown](https://domchristie.github.io/to-markdown/) - An HTML to Markdown converter written in JavaScript. ([Source Code](https://github.com/domchristie/to-markdown)) `MIT` `JavaScript`
  * [Turtl](https://turtl.it/) - A totally private personal database and note taking app. ([Source Code](https://github.com/turtl)) `GPLv3` `CommonLisp`


## Office Suites

**[`^        back to top        ^`](#)**

  * [EtherCalc](https://ethercalc.org/) - Web spreadsheet. ([Source Code](https://github.com/audreyt/ethercalc)) `CPALv1/Other` `Nodejs`
  * [EtherDraw](https://github.com/JohnMcLear/draw) - An intuitive collaborative drawing web based tool. ([Demo](http://draw.etherpad.org/)) `Apache` `Nodejs`
  * [Etherpad](http://etherpad.org/) - Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time. ([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad-lite)) `Apache` `Nodejs`
  * [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - A server for [Gobby](https://github.com/gobby/gobby/wiki), a multi-platform collaborative text editor. ([Source Code](https://github.com/gobby/gobby)) `MIT` `C++`
  * [ONLYOFFICE](http://onlyoffice.org/) - An office suite that enables you to manage documents, projects, team and customer relations in one place. ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPLv3` `Nodejs`
  * [ownCloud documents](https://doc.owncloud.org/server/8.2/user_manual/documents.html) - Collaborative editing and sharing of rich-text documents. ([Source Code](https://github.com/owncloud/documents)) `AGPLv3` `PHP`
  * [PHPOffice](http://phpoffice.github.io/) - PHPOffice contains libraries which permits to write and read files from most office suites. `LGPLv3` `PHP`
  * [WebODF](http://webodf.org/) - Tools and libraries to view and edit Open Document Format (ODF) files. ([Source Code](https://github.com/kogmbh/WebODF)) `AGPLv3` `HTML5`


## Password Managers

**[`^        back to top        ^`](#)**

 * [Bitwarden](https://bitwarden.com/) - Password manager with webapp, browser extension, and mobile app. ([Source Code](https://github.com/bitwarden/core)) `AGPLv3` `C#`
 * [keeweb](https://keeweb.info/) - This webapp is a browser and desktop password manager compatible with KeePass databases. ([Source Code](https://github.com/keeweb/keeweb)) `MIT` `HTML5`
 * [sysPass](http://www.syspass.org/) - Multiuser password management system. ([Demo](http://demo.syspass.org/), [Source Code](https://github.com/nuxsmin/sysPass)) `GPLv3` `PHP`
 * [Teampass](http://teampass.net/) - Password manager dedicated for managing passwords in a collaborative way on any server Apache, MySQL and PHP. ([Source Code](https://github.com/nilsteampassnet/TeamPass/)) `GPLv3` `PHP`


## Pastebins

**[`^        back to top        ^`](#)**

  * [0bin](https://github.com/sametmax/0bin) - Client side encrypted pastebin. `WTFPL` `Python`
  * [CoderVault](https://github.com/codervault) - An Open Source, Self-Hosted, Snippet Manager. ([Source Code](https://github.com/codervault/codervault)) `MIT` `Ruby`
  * [cryptonote](https://cryptonote.me/) - A simple open source web application that lets users encrypt and share messages that can only be read once. ([Source Code](https://github.com/alainmeier/cryptonote)) `BSD` `Ruby`
  * [CryptPad](https://cryptpad.fr/) - CryptPad is the zero knowledge realtime collaborative editor. ([Source Code](https://github.com/xwiki-labs/cryptpad)) `AGPLv3` `Nodejs`
  * [EdPaste](https://github.com/Edraens/EdPaste) - Self-hosted pastebin written in Laravel (PHP Framework). ([Demo](https://paste.edra.ovh/)) `MIT` `PHP`
  * [gist](https://gitnet.fr/deblan/gist) - GIST is an open-source application to share code. `GPLv3` `PHP`
  * [hastebin](http://hastebin.com/about.md) - Open source pastebin written in node.js. ([Demo](http://hastebin.com/), [Source Code](https://github.com/seejohnrun/haste-server)) `MIT` `Nodejs`
  * [localpaste](https://github.com/petermaloney/localpaste) - Simple python based pastebin you can run locally, with curl for input. Supports RAW text by default and binary data such as images (no extensions on returned url). `GPLv2` `Python`
  * [Modern Paste](https://www.modernpaste.com) - Modern pastebin with a contemporary, minimalistic user interface backed by a robust feature set. ([Demo](https://demo.modernpaste.com/), [Source Code](https://github.com/LINKIWI/modern-paste)) `MIT` `Python`
  * [mojopaste](http://search.cpan.org/dist/App-mojopaste/) - Perl based pastebin. ([Demo](http://p.thorsen.pm/), [Source Code](https://github.com/jhthorsen/app-mojopaste)) `ARTv2` `Perl`
  * [NoteHub](https://notehub.org) - Free and Hassle-free Pastebin for Markdown Pages. Simple, clean, password provided, generated-short link. ([Demo](https://notehub.org), [Source Code](https://github.com/chmllr/NoteHub)) `MIT` `Nodejs`
  * [Paste](http://phpaste.sourceforge.io/) - Paste is forked from the original source pastebin.com used before it was bought. ([Demo](http://phpaste.sourceforge.net/demo), [Source Code](https://github.com/jordansamuel/PASTE)) `GPLv3` `PHP`
  * [Pastebin](https://p.pantsu.cat) - Modern self-hosted pastebin service with a restful API. ([Demo](https://p.pantsu.cat), [Source Code](https://github.com/ewhal/Pastebin)) `MIT` `Go`
  * [pb](https://github.com/ptpb/pb) - Lightweight pastebin (and url shortener) built using flask. ([Demo](https://ptpb.pw/)) `GPLv3` `Python`
  * [pbnh](https://github.com/bhanderson/pbnh) - Pastebin inspired from project pb and hastebin, with an API and a SQL-based backend. `MIT` `Python`
  * [Phaste](https://pste.pw) - A Phalcon-based, MySQL pastebin application with privacy-respecting Piwik integration and syntax highlighting. ([Source Code](https://github.com/FoxDev/Phaste)) `AGPLv3` `PHP`
  * [PrivateBin](https://privatebin.info/) - PrivateBin is a minimalist, opensource online pastebin/discussion board where the server has zero knowledge of hosted data. ([Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
  * [SharpPaste](https://github.com/phonicmouse/SharpPaste) - A simple and modern open-source pastebin made with C# and NancyFX that just works. `MIT` `C#/ASP.NET`
  * [snipt](https://snipt.net/) - Long-term memory for coders. Share and store code snippets. ([Source Code](https://github.com/nicksergeant/snipt/)) `BSD` `Python`
  * [Sticky Notes](http://sayakb.github.io/sticky-notes/) - A powerful open-source pastebin application for effortless code sharing. ([Source Code](https://github.com/sayakb/sticky-notes)) `BSD` `PHP`
  * [Stikked](https://github.com/claudehohl/Stikked) - An advanced and beautiful pastebin. `GPLv3` `PHP`
  * [tastebin](https://github.com/andreineculau/tastebin) - Updated version of hastebin plus additional features. `Apache` `Nodejs`


## Personal Dashboards
See https://github.com/n1trux/awesome-sysadmin#metric--metric-collection

**[`^        back to top        ^`](#)**

  * [Dj Diabetes](https://github.com/foxmask/dj-diabetes) - My Glucose Manager - follow your daily health. `BSD` `Python`
  * [Habitica](http://habitica.com/) - A habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. ([Source Code](https://github.com/HabitRPG/habitrpg)) `GPLv3/Other` `Nodejs`
  * [Homepage](https://github.com/thetomester13/homepage) - A simple, standalone, self-hosted PHP page that is your window to your server and the web. `MIT` `PHP`
  * [iDashboard-PHP](https://github.com/causefx/iDashboard-PHP) - HTPC Dashboard to load website services. `MIT` `PHP`
  * [Phant](http://phant.io/) - Phant is a modular data logging tool for collecting data from the Internet of Things. ([Demo](https://data.sparkfun.com/), [Source Code](https://github.com/sparkfun/phant)) `GPLv3` `Nodejs`
  * [Thingspeak](https://thingspeak.com/) - An open source “Internet of Things” application and API to store and retrieve data from things using HTTP. ([Demo](https://thingspeak.com/channels/public), [Source Code](https://github.com/iobridge/thingspeak)) `GPL` `Ruby`
  * [Tipboard](http://allegro.tech/tipboard/) - In-house, tasty, local dashboarding system. ([Source Code](https://github.com/allegro/tipboard)) `Apache` `Python`
  * [wger](https://wger.de/) - A web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well. ([Demo](https://wger.de), [Source Code](https://github.com/rolandgeider/wger)) `AGPLv3` `Python`


## Photo and Video Galleries

**[`^        back to top        ^`](#)**

  * [Chevereto Free](https://chevereto.com/free) - A powerful and fast image hosting script that allows you to create your very own full featured image hosting website in just minutes. ([Source Code](https://github.com/Chevereto/Chevereto-Free)) `AGPLv3` `PHP`
  * [Coppermine](http://coppermine-gallery.net/) - Multilingual photo gallery that integrates with various bulletin boards. Includes upload approval and password protected albumns. ([Demo](http://coppermine-gallery.net/demo/cpg15x/), [Source Code](https://github.com/coppermine-gallery/cpg1.6.x)) `GPLv3` `PHP`
  * [CumulusClips](http://cumulusclips.org/) - Your own video sharing website with CumulusClips video sharing script. You can build a YouTube clone where users can upload, rate, comment on videos, and much more. ([Demo](https://tube.devosi.org/)) `GPLv2` `PHP`
  * [Gallery CSS](https://benschwarz.github.io/gallery-css/) - Gallery.css is all CSS. Think: Simple, maintainable and understandable galleries without the use of Javascript. ([Source Code](https://github.com/benschwarz/gallery-css)) `MIT` `CSS`
  * [Lychee](http://lychee.electerious.com/) - An open source grid and album based photo-management-system. ([Source Code](https://github.com/electerious/Lychee)) `MIT` `PHP`
  * [MediaDrop](http://mediadrop.net/) - A video, audio and podcast publication platform. ([Source Code](https://github.com/mediadrop/mediadrop)) `GPLv3` `Python`
  * [Mediagoblin](http://mediagoblin.org) - A Free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc. `AGPLv3` `Python`
  * [MinigalNano](https://github.com/sebsauvage/MinigalNano) - MinigalNano is a very simple image gallery. It adheres to the KISS principle and is very easy to install. MinigalNano does not have a web admin interface: You just upload your images in the photo folder on your server (using FTP, SFTP). `AGPLv3` `PHP`
  * [Photato](https://github.com/trebonius0/Photato) - A self-hosted photo gallery, accessible through a responsive WebUI. Directly uses and indexes a specific folder in the filesystem. `AGPLv3` `Java`
  * [Photofloat](http://blog.zx2c4.com/567) - A Web 2.0 Photo Gallery Done Right via Static JSON & Dynamic Javascript. ([Demo](http://photos.jasondonenfeld.com/)) `GPLv2` `Python`
  * [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - The easiest photo gallery there is. `GPLv3` `PHP`
  * [Photoshow](http://www.photoshow-gallery.com/) - Responsive Web Gallery. ([Source Code](https://github.com/thibaud-rohmer/PhotoShow)) `GPLv3` `PHP`
  * [Piwigo](http://piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. `GPLv2` `PHP`
  * [Plumi](http://blog.plumi.org/) - Create your own sophisticated video-sharing site. ([Source Code](https://github.com/plumi/plumi.app)) `GPLv2` `Python`
  * [sigal](https://github.com/saimn/sigal) - Yet another simple static gallery generator. `MIT` `Python`
  * [UberGallery](http://www.ubergallery.net) - UberGallery is an easy to use, simple to manage, web photo gallery. UberGallery does not require a database and supports JPEG, GIF and PNG file types. Simply upload your images and UberGallery will automatically generate thumbnails and output HTML. ([Source Code](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
  * [Videobin](http://videobin.org/code) - A simple video upload and sharing service with transcoding. ([Demo](http://videobin.org/), [Source Code](https://r-w-x.org/videobin.git)) `GPLv3` `Python`
  * [Zenphoto](http://www.zenphoto.org/) - Open-source gallery and CMS project. ([Source Code](https://github.com/zenphoto/zenphoto)) `GPLv2` `PHP`


## Polls and Events

**[`^        back to top        ^`](#)**

  * [Calagator](http://calagator.org/) - An event aggregator. ([Demo](http://calagator.org/), [Source code](https://github.com/calagator/calagator)) `MIT` `Ruby`
  * [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - An online scheduling application. ([Demo](https://dudle.inf.tu-dresden.de/)) `AGPLv3` `Ruby`
  * [Framadate](https://framadate.org/) - An online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision. ([Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://git.framasoft.org/framasoft/framadate)) `CeCILL-B` `PHP`
  * [Kyélà](http://kyela.net/) - Participation polls for group events. ([Demo](http://kyela.net/55232734237c8/), [Source Code](https://github.com/abienvenu/Kyela)) `AGPLv3` `PHP`
  * [LimeSurvey](https://www.limesurvey.org) - Feature-rich Open Source web based polling software. Supports extensive survey logic. ([Demo](https://demo.limesurvey.org)) `GPLv2` `PHP`
  * [MaterialPoll](https://github.com/nearbycoder/materialpoll) - An opensource strawpoll.me clone for creating random polls. ([Demo](http://materialpoll.tk), [Source Code](https://github.com/nearbycoder/materialpoll)) `MIT` `Nodejs`
  * [Nuages](https://nuages.domainepublic.net/) - Collaborative meeting poll system, similar to doodle or rdvz. ([Source Code](http://git.domainepublic.net/?p=nuages.git;a=tree)) `GPLv3` `Python`
  * [PHPBack](http://www.phpback.org) - The open source feedback system. ([Demo](http://www.phpback.org/demo/), [Source Code](https://github.com/ivandiazwm/phpback/)) `GPLv3` `PHP`
  * [TellForm](https://tellform.com) - A beautiful online form and survey creator. ([Demo](https://tellform.com/examples), [Source Code](https://github.com/whitef0x0/tellform)) `MIT` `Nodejs`


## Proxy

**[`^        back to top        ^`](#)**

  * [http2-serverpush-proxy](https://github.com/n1try/http2-serverpush-proxy) - A reverse proxy that helps to automatically utilize HTTP/2.0's server push mechanism for static websites. Available as middleware and standalone application. `MIT` `Nodejs`
  * [microproxy](https://github.com/thekvs/microproxy) - lightweight non-caching HTTP/HTTPS proxy server. ([Source Code](https://github.com/thekvs/microproxy)) `MIT` `Go`
  * [miniProxy](https://github.com/joshdick/miniProxy/) - Simple web proxy written in PHP that can allow you to bypass Internet content filters, or to browse the internet anonymously. Only one php file. ([Source Code](https://github.com/joshdick/miniProxy/)) `GPLv3` `PHP`
  * [Oranjeproxy](http://lehollandaisvolant.net/tout/oranjeproxy/) - Anonymizing web proxy. ([Source Code](https://github.com/AmauryCarrade/OranjeProxy)) `GPLv2` `PHP`
  * [PHP-Proxy](https://www.php-proxy.com/) - A web proxy script built specifically to be fast, easy to modify and to support video sites such as YouTube. ([Demo](https://unblockvideos.com/), [Source Code](https://github.com/Athlon1600/php-proxy-app)) `MIT` `PHP`
  * [Pound](http://www.apsis.ch/pound/) - Light-weight reverse proxy and load balancer for HTTP/HTTPS. ([Source Code](http://www.apsis.ch/pound/)) `GPLv2` `C`
  * [Privoxy](http://www.privoxy.org) - A non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPLv2` `C`
  * [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. ([Source Code](https://code.launchpad.net/squid)) `GPLv2` `C`
  * [Swiperproxy](https://swiperproxy.github.io/) - A lightning-fast, open source web proxy that is easy for you to run and customize. ([Demo](http://proxy.donttrustrobots.nl/), [Source Code](https://github.com/swiperproxy/swiperproxy)) `MIT` `Python`
  * [Tinyproxy](https://banu.com/tinyproxy/) - Light-weight HTTP/HTTPS proxy daemon. ([Source Code](https://github.com/tinyproxy/tinyproxy)) `GPLv2` `C`
  * [Traefik](https://traefik.io/) - Træfɪk is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease. It supports several backends (Docker, Swarm, Mesos/Marathon, …) to manage its configuration automatically and dynamically. ([Source Code](https://github.com/containous/traefik)) `MIT` `Go`


## Read it Later Lists

**[`^        back to top        ^`](#)**

  * [Nunux Keeper](http://keeper.nunux.org/) - Your personal content curation service. ([Source Code](https://github.com/ncarlier/nunux-keeper)) `GPLv3` `Nodejs`
  * [Wallabag](https://www.wallabag.org) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. ([Demo](http://demo.wallabag.org/), [Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`


## Search Engines

**[`^        back to top        ^`](#)**

  * [Gigablast](http://www.gigablast.com/) - open source search engine. ([Demo](http://www.gigablast.com/), [Source Code](https://github.com/gigablast/open-source-search-engine)) `Apache` `C++`
  * [Searx](https://github.com/asciimoo/searx) - A privacy-respecting, hackable metasearch engine. ([Demo](https://searx.me/)) `AGPLv3` `Python`
  * [Seeks](https://beniz.github.io/seeks/) - A websearch proxy and collaborative distributed tool for websearch. `AGPLv3` `C++`
  * [Yacy](http://yacy.net/en/index.html) - Peer based, decentralized search engine server. `GPL2` `Java`


## Software Development

**[`^        back to top        ^`](#)**

### Project Management

See also [Ticketing](#ticketing), [Task management/To-do lists](#task-managementto-do-lists)*

  * [Apache Bloodhound](https://bloodhound.apache.org/) - Manage software products, Keep track of features, tasks and bugs. `Apache` `Python`
  * [Bonobo Git Server](https://bonobogitserver.com/) - Set up your own self hosted git server on IIS for Windows. Manage users and have full control over your repositories with a nice user friendly graphical interface. ([Source Code](https://github.com/jakubgarfield/Bonobo-Git-Server)) `MIT` `C#`
  * [CaseBox](https://www.casebox.org) - Manage all your organisation's information in one system. ([Source Code](https://github.com/KETSE/casebox)) `AGPLv3` `PHP/Java`
  * [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - Distributed version control system featuring wiki and bug tracker. `BSD` `C`
  * [Gitblit](http://gitblit.com/) - A pure Java stack for managing, viewing, and serving Git repositories. ([Source Code](https://github.com/gitblit/gitblit)) `Apache` `Java`
  * [gitbucket](https://gitbucket.github.io/gitbucket-news/) - The easily installable GitHub clone powered by Scala. ([Source Code](https://github.com/gitbucket/gitbucket)) `Apache` `Scala/Java`
  * [Gitea](https://gitea.io) - A community managed fork of Gogs, lightweight code hosting solution. ([Demo](https://try.gitea.io), [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go`
  * [GitLab](http://gitlab.org/) - Self Hosted Git repository management, code reviews, issue tracking, activity feeds and wikis. ([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-ce)) `MIT` `Ruby`
  * [Gitlist](http://gitlist.org/) - A web-based git repository browser - GitList allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history and diffs. ([Source Code](https://github.com/klaussilveira/gitlist)) `BSD` `PHP`
  * [Gitprep](http://gitprep.yukikimoto.com/) - Portable Github clone. ([Source Code](https://github.com/yuki-kimoto/gitprep), [Demo](http://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi)) `GPL` `Perl`
  * [Git WebUI](https://github.com/alberthier/git-webui) - A standalone web based user interface for git repositories. `Apache` `Python`
  * [Gogs](https://github.com/gogits/gogs) - A painless self-hosted Git Service written in Go. ([Demo](https://try.gogs.io/)) `MIT` `Go`
  * [Kallithea](https://kallithea-scm.org/) - Source code management system that supports two leading version control systems, Mercurial and Git, with a web interface. ([Source Code](https://kallithea-scm.org/repos/kallithea)) `GPLv3` `Python`
  * [Klaus](https://github.com/jonashaag/klaus/) - A simple, easy-to-set-up Git web viewer that Just Works. ([Demo](http://klausdemo.lophus.org/)) `ISC` `Python`
  * [Lavagna](http://lavagna.io) - Lavagna is an open-source issue/project management tool designed for small teams. Lightweight, pure Java, easy to install, easy to use. ([Source Code](https://github.com/digitalfondue/lavagna)) `GPLv3` `Java`
  * [Octobox](https://octobox.io/) `⚠` - Take back control of your GitHub Notifications. ([Source Code](https://github.com/octobox/octobox)) `AGPLv3` `Ruby`
  * [OpenProject](https://www.openproject.org) - OpenProject is a web-based project management system. `GPLv3` `Ruby`
  * [Phabricator](http://phabricator.org/) - Collection of web applications that help build better software. ([Demo](https://secure.phabricator.com/), [Source Code](https://github.com/phacility/phabricator)) `Apache` `PHP`
  * [Redmine](http://www.redmine.org/) - Redmine is a flexible project management web application. ([Demo](http://demo.redmine.org/), [Source Code](https://svn.redmine.org/redmine/)) `GPLv2` `Ruby`
  * [RhodeCode](https://rhodecode.com/) - RhodeCode is an open source platform for software development teams. It unifies and simplifies repository management for Git, Subversion, and Mercurial. ([Demo](https://try.rhodecode.com/), [Source Code](https://code.rhodecode.com/)) `AGPLv3` `Python`
  * [SCM Manager](https://www.scm-manager.org/) - The easiest way to share and manage your Git, Mercurial and Subversion repositories over http. ([Source Code](https://bitbucket.org/sdorra/scm-manager/src)) `BSD` `Java`
  * [Taiga](https://taiga.io/) - Agile Project Management Tool based on the Kanban and Scrum methods. ([Source Code](https://github.com/taigaio)) `AGPLv3` `Python`
  * [The Bug Genie](http://www.thebuggenie.com/) - The Bug Genie is a friendly project management and issue tracking tool. ([Source Code](https://github.com/thebuggenie/thebuggenie)) `MPLv2` `PHP`
  * [Trac](http://trac.edgewall.org/) - Trac is an enhanced wiki and issue tracking system for software development projects. `BSD` `Python`
  * [Phproject](http://www.phproject.org/) - A high performance full-featured project management system. ([Demo](http://demo.phproject.org/), [Source Code](https://github.com/Alanaktion/phproject)) `GPLv3` `PHP`


### Bug Trackers

See **[Ticketing](#ticketing)**


### IDE/Tools

  * [Codiad](http://codiad.com/) - A web-based IDE framework with a small footprint and minimal requirements. ([Source Code](https://github.com/Codiad/Codiad)) `MIT` `PHP`
  * [Eclipse Che](http://www.eclipse.org/che/) - Open source workspace server and cloud IDE. ([Source Code](https://github.com/eclipse/che)) `EPLv1` `Docker/Java`
  * [ICEcoder](https://icecoder.net/) - ICEcoder is a web IDE / browser based code editor, which allows you to develop websites directly within the web browser. ([Demo](http://demo.icecoder.net/ICEcoder/), [Source Code](https://github.com/mattpass/ICEcoder)) `MIT` `PHP`
  * [JS Bin](http://jsbin.com/) - Open source collaborative web development debugging tool. ([Source Code](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
  * [Koding](http://www.koding.com/) - The simplest way to manage your entire Dev Infrastructure. ([Source Code](https://github.com/koding/koding)) `Apache` `Nodejs`
  * [Microglark](http://micro.glark.io) - A hacky minimalistic remote pair programming editor. ([Demo](http://micro.glark.io), [Source Code](https://github.com/Bluefinch/microglark)) `AGPLv3` `Nodejs`
  * [Regexr](http://regexr.com/) - RegExr is a HTML/JS based tool for creating, testing, and learning about Regular Expressions. ([Source Code](https://github.com/gskinner/regexr/)) `MIT` `Nodejs`
  * [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - Web browser based IDE for R. ([Source Code](https://github.com/rstudio/rstudio/)) `AGPLv3` `Java/C++`
  * [Wide](https://github.com/b3log/wide) - A Web-based IDE for Teams using Go programming language/Golang. ([Demo](http://wide.b3log.org/signup)) `Apache` `Go`


### Continuous Integration

  * [Buddy GO](https://buddy.works/) - The Git and Continous Integration / Delivery Platform. `Fair` `Nodejs/Java`
  * [Concourse](https://concourse.ci/) - Concourse is a CI tool that treats pipelines as first class objects and containerizes every step along the way. ([Demo](https://ci.concourse.ci/), [Source Code](https://github.com/concourse/concourse)) `Apache` `Go`
  * [drone](https://drone.io/) - Drone is a Continuous Delivery platform built on Docker, written in Go. ([Source Code](https://github.com/drone/drone)) `Apache` `Go`
  * [Factor](http://www.factor.io/) - It's like IFTTT (if-this-then-that) for Dev and DevOps. ([Source Code](https://github.com/factor-io/factor)) `MIT` `Ruby`
  * [Jenkins](https://jenkins-ci.org/) - Continuous Integration Server. ([Source Code](https://github.com/jenkinsci/jenkins/)) `MIT` `Java`
  * [PHPCI](https://www.phptesting.org/) - Free and open source continuous integration specifically designed for PHP. ([Source Code](https://github.com/block8/phpci)) `BSD` `PHP`
  * [Strider](http://strider-cd.github.io/) - Open Source Continuous Deployment / Continuous Integration platform. ([Source Code](https://github.com/Strider-CD/strider)) `BSD` `Nodejs`


### API Management

 * [DreamFactory](https://www.dreamfactory.com/) - Turns any SQL/NoSQL/Structured data into Restful API. ([Source Code](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache` `PHP`
 * [Endpoint](https://github.com/LINKIWI/endpoint/) - Super simple mock HTTP API endpoints that return static JSON data, for testing webhooks and client libraries in development. `MIT` `Nodejs`
 * [Fusio](http://www.fusio-project.org/) - Fusio is an open source API management platform which helps to build and manage REST APIs. ([Demo](http://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)) `AGPLv3` `PHP`
 * [Para](http://www.paraio.org) - Para is a flexible and modular backend framework/server for object persistence, API development and authentication. ([Source Code](https://github.com/erudika/para)) `Apache` `Java`


### Documentation Generators

See also [Static site generators](#static-site-generators)

  * [Docstore](http://haldean.org/) - Static document hosting without any server-side processing, does not require you to recompile every time you change an article. Clone the repository and add articles in the text/ directory to get started. ([Source Code](https://github.com/haldean/docstore)) `BSD` `Javascript`
  * [Flatdoc](http://ricostacruz.com/flatdoc/) - A small Javascript file that fetches Markdown files and renders them as full pages. `MIT` `Javascript`
  * [markdown-tree](https://github.com/mil/markdown-tree) - Serve a hierarchy / tree directory of markdown files. Use intended for small sites built in markdown. `MIT` `Ruby`
  * [Read the Docs](https://docs.readthedocs.org/en/latest/install.html) - Host documentation, making it fully searchable and easy to find; import your docs using any major version control system, including Mercurial, Git, Subversion, and Bazaar. ([Demo](https://readthedocs.org/projects/), [Source Code](https://github.com/rtfd/readthedocs.org)) `MIT` `Python`

### Localization

  * [Parrot](http://anthonynsimon.com/parrot.github.io/) - Self-hosted Localization Management Platform built with Go and Angular 2.. ([Source Code](https://github.com/anthonynsimon/parrot)) `MIT` `Go`
  * [Pootle](http://pootle.translatehouse.org) - Online translation and localization tool. ([Source Code](https://github.com/translate/pootle)) `GPLv3` `Python`
  * [Weblate](https://weblate.org) - Web-based translation tool with tight version control integration. ([Demo](https://demo.weblate.org), [Source Code](https://github.com/WeblateOrg/weblate)) `GPLv3` `Python`
  * [Zanata](http://zanata.org) - Web-based translation platform for translators, content creators and developers to manage localisation projects. ([Source Code](https://github.com/zanata/zanata-platform)) `GPLv2` `Java`

## Static site generators

**[`^        back to top        ^`](#)**

See https://staticsitegenerators.net and https://www.staticgen.com


## Task management/To-do lists

**[`^        back to top        ^`](#)**

*See also [Project Management](#project-management) and [Ticketing](#ticketing).*

  * [Crepido](https://github.com/arshad/crepido) - Create (kanban) boards to track users and projects from flat markdown files. `MIT` `Nodejs`
  * [Kanboard](http://kanboard.net/) - A simple and open source visual task board. ([Source Code](https://github.com/kanboard/kanboard)) `MIT` `PHP`
    * [Wheatbin](http://wheatbin.com/) - A project management software that combines Kanban methodology with the Law of the Harvest. ([Source Code](https://github.com/wheatbin/wheatbin)) `MIT` `PHP`
  * [myTinyTodo](http://www.mytinytodo.net/) - Simple way to manage your todo list in AJAX style. Uses PHP, jQuery, SQLite/MySQL. GTD compliant. `GPLv2` `PHP`
  * [omgnata](https://github.com/chr15m/omgnata) - Mobile friendly zero-feature TODO list web app. Unix philosophy. ([Demo](https://chr15m.github.io/omgnata/)) `GPLv3` `ClojureScript`
  * [PHP Task/Todo list](https://github.com/lgg/tasks.php) - A simple task/todo list that uses a JSON text file for the tasks. `MIT` `PHP`
  * [Restyaboard](http://restya.com/board/) - Open source Trello-like kanban board. ([Demo](http://restya.com/board/demo.html), [Source Code](https://github.com/RestyaPlatform/board)) `OSLv3` `PHP`
  * [scrumblr](http://scrumblr.ca/) - Collaborative Online Scrum Tool Using Websockets, Node.js, jQuery, and CSS3. ([Source Code](https://github.com/ocdtrekkie/scrumblr/tree/sandstorm)) `GPLv3` `Nodejs`
  * [TaskBoard](http://taskboard.matthewross.me/) - A Kanban-inspired app for keeping track of things that need to get done. ([Source Code](https://github.com/kiswa/TaskBoard)) `MIT` `PHP`
  * [Taskfreak](http://www.taskfreak.com/original) - A simple but efficient web based task manager written in PHP. ([Demo](http://demo.taskfreak.com/)) `GPLv3` `PHP`
  * [Tasks](https://projects.miguelpiedrafita.com/Tasks/) - Simple tasks & notes manager written in PHP, jQuery and Bootstrap using a custom flat file database. ([Demo](https://demo.miguelpiedrafita.com/tasks/), ([Source Code](https://github.com/m1guelpf/tasks)) `MPLv2` `PHP`
  * [Tasks](https://github.com/thewhitetulip/Tasks) - Kanban based to-do list manager written in Go. `MIT` `Go`
  * [tasks.php](https://github.com/RaymiiOrg/tasks.php) - A simple task/todo list manager. `MIT` `PHP`
  * [Taskwarrior](https://taskwarrior.org/) - Taskwarrior is Free and Open Source Software that manages your TODO list from your command line. It is flexible, fast, efficient, and unobtrusive. It does its job then gets out of your way. ([Source Code](https://taskwarrior.org/download/#git)) `MIT` `C++`
  * [Tinyissue](https://github.com/satrun77/tinyissue) - Simple Issue Tracking for Teams. `MIT` `PHP`
  * [Tracks](http://www.getontracks.org/) - A web-based application to help you implement David Allen’s [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) methodology. ([Source Code](https://github.com/TracksApp/tracks)) `GPLv2` `Ruby`
  * [Volition](https://www.usevolition.com) - Opinionated open-source task management. ([Source Code](https://github.com/garrettqmartin8/volition)) `MIT` `Ruby`
  * [Wekan](https://wekan.io/) - An open-source Trello-like kanban. ([Demo](https://oasis.sandstorm.io/appdemo/m86q05rdvj14yvn78ghaxynqz7u2svw6rnttptxx49g1785cdv1h), [Source Code](https://github.com/wekan/wekan)) `MIT` `Nodejs`


## Ticketing

**[`^        back to top        ^`](#)**

*See also [Task management/To-do lists](#task-managementto-do-lists) and [Project Management](#project-management)*

  * [Brimir](https://getbrimir.com/) - Simple and clean open-source ticket manager written in Ruby on Rails. ([Source Code](https://github.com/ivaldi/brimir)) `AGPLv3` `Ruby`
  * [Bugzilla](https://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. `MPLv2` `Perl`
  * [Bumpy Booby](http://bumpy-booby.derivoile.fr/) - A simple, responsive and highly customizable PHP bug tracking system. ([Source Code](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
  * [Cerb](http://www.cerberusweb.com/) - Group-based e-mail management project. ([Source Code](https://github.com/wgm/cerb)) `DPL` `PHP`
  * [Coordino](http://coordino.com/) - Open Source question & answer system on top of CakePHP. ([Source Code](https://github.com/Datawalke/Coordino)) `MIT` `PHP`
  * [Deskulu](https://github.com/Taskulu/deskulu) - Opensource helpdesk and ticketing system based on Drupal 7. ([Demo](https://help.taskulu.com)) `GPLv2` `PHP`
  * [DiamanteDesk](http://diamantedesk.com/) - DiamanteDesk is FREE Open Source easy-to-use help-desk solution. ([Demo](http://diamantedesk.com/demo/), [Source Code](https://github.com/eltrino/diamantedesk-application)) `OSLv3` `PHP`
  * [Flyspray](http://www.flyspray.org/) - Uncomplicated, web-based bug tracking system. ([Source Code](https://github.com/Flyspray/flyspray)) `GPLv2` `PHP`
  * [HuBoard](https://github.com/huboard/huboard) `⚠` - Instant project management for your GitHub issues (Connects directly GitHub API). `MIT` `Ruby`
  * [MantisBT](https://www.mantisbt.org/) - Self hosted bug tracker, fits best for software development. ([Demo](https://www.mantisbt.org/bugs/my_view_page.php)), ([Source Code](https://github.com/mantisbt/mantisbt)) `GPLv2` `PHP`
  * [osTicket](http://osticket.com/) -  Manage, organize and archive all your support requests and responses in one place. ([Source Code](https://github.com/osTicket/osTicket)) `GPLv2` `PHP`
  * [OTRS](http://www.otrs.com/) - Trouble ticket system for assigning tickets to incoming queries and tracking further communications. ([Source Code](https://github.com/OTRS/otrs)) `AGPLv3` `Perl`
  * [Request Tracker](https://www.bestpractical.com/rt/) -  An enterprise-grade issue tracking system. ([Source Code](https://github.com/bestpractical/rt)) `GPLv2` `Perl`
  * [TheBugGenie](http://www.thebuggenie.org) - Ticket system with extensive user rights system. ([Source Code](https://github.com/thebuggenie/thebuggenie)) `MPLv2` `PHP`
  * [Zammad](https://zammad.org/) - Easy to use but powerful open-source support & ticketing system. ([Source Code](https://github.com/zammad/zammad)) `AGPLv3` `Ruby`


## URL Shorteners

**[`^        back to top        ^`](#)**

  * [Linkr](https://linkrapp.com) - Beautiful, fast URL shortening. ([Demo](https://demo.linkrapp.com), [Source Code](https://github.com/LINKIWI/linkr)) `MIT` `Python/Nodejs`
  * [Lstu](https://github.com/ldidry/lstu) - _Let's SHorten That Url_ - Lightweight URL shortener. `WTFPL` `Perl`
  * [Nimbus](https://github.com/ethanal/nimbus) - A URL shortener and file sharer with a drag-and-drop OS X menu bar client and web interface. `MIT` `Python`
  * [Polr](https://project.polr.me/) - A modern, minimalist, modular, and lightweight URL shortener. ([Source Code](https://github.com/Cydrobolt/polr)) `GPLv2` `PHP`
  * [shuri](https://github.com/pips-/shuri) - SHort URI - Lighweight URL shortener. `MIT` `PHP`
  * [YOURLS](http://yourls.org/) - YOURLS is a set of PHP scripts that will allow you to run Your Own URL Shortener. Features include password protection, URL customization, bookmarklets, statistics, API, plugins, jsonp. ([Source Code](https://github.com/YOURLS/YOURLS/)) `MIT` `PHP`


## VPN

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#vpn


## Web servers

**[`^        back to top        ^`](#)**

See https://github.com/n1trux/awesome-sysadmin#web


## Wikis

**[`^        back to top        ^`](#)**

See also [Documentation Generators](#documentation-generators), [Wikimatrix](http://www.wikimatrix.org/), [Wiki Engines on WikiIndex](http://wikiindex.org/Category:Wiki_Engine), [List of wiki software on wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software on wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software).

  * [Blazekiss](http://projet.idleman.fr/blazekiss/) - BlazeKiss is a KISS-based wiki (Keep It Simple, Stupid) - simplicity and functionality comes before all. ([Source Code](https://github.com/ldleman/blazekiss)) `GPLv3` `PHP`
  * [BookStack](https://www.bookstackapp.com/) - BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information. It allows for documentation to be stored in a book like fashion. ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/ssddanbrown/BookStack)) `MIT` `PHP`
  * [django-wiki](https://github.com/django-wiki/django-wiki) - A wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models. ([Demo](https://demo.django.wiki/)) `GPLv3` `Python`
  * [Documize](https://documize.com) - Modern Docs + Wiki software with built-in workflow, single binary executable, just bring MySQL/Percona. ([Source Code](https://github.com/documize/community)) `AGPLv3` `Go`
  * [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - An easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain files, therefore no database is required. `GPL` `PHP`
  * [Gitit](https://github.com/jgm/gitit) - A wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. `GPLv2` `Haskell`
  * [Gollum](https://github.com/gollum/gollum) - A simple, Git-powered wiki with a sweet API and local frontend. `MIT` `Ruby`
  * [jingo](https://github.com/claudioc/jingo) - A git based wiki engine written for node.js, with a decent design, a search capability and a good typography. ([Demo](http://jingo.cica.li:6067/wiki/home), [Source Code](https://github.com/claudioc/jingo)) `MIT` `NodeJS`
  * [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - MediaWiki is a free and open-source wiki software package written in PHP. It serves as the platform for Wikipedia and the other Wikimedia projects, used by hundreds of millions of people each month. ([Source Code](https://phabricator.wikimedia.org/diffusion/MW/)) `GPLv2` `PHP`
  * [MoinMoin](https://moinmo.in/) - An advanced, easy to use and extensible WikiEngine with a large community of users. ([Source Code](http://hg.moinmo.in/moin)) `GPLv2` `Python`
  * [Olelo](https://github.com/minad/olelo) - Olelo is a wiki that stores pages in a Git repository, supports many markup styles and has an extensible, hackable architecture. ([Demo](http://gitwiki.org/)) `MIT` `Ruby`
  * [Pepperminty Wiki](https://github.com/sbrl/Pepperminty-Wiki/) - A complete markdown-powered wiki contained in a single PHP file. ([Demo](https://starbeamrainbowlabs.com/labs/peppermint/build/)) `MPLv2` `PHP`
  * [PmWiki](http://www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites. `GPLv3` `PHP`
  * [Raneto](http://raneto.com/) - Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. `MIT` `NodeJS`
  * [Realms](http://realms.io/) - A git-backed wiki inspired by Gollum. ([Source Code](https://github.com/scragg0x/realms-wiki)) `GPLv2` `Python`
  * [Redaxscript](http://redaxscript.com/) - Ultra lightweight website engine. ([Source Code](https://github.com/redaxmedia/redaxscript)) `GPLv3` `PHP`
  * [TiddlyWiki](http://tiddlywiki.com/) - A reusable non-linear personal web notebook. ([Source Code](https://github.com/Jermolene/TiddlyWiki5)) `BSD` `Nodejs`
  * [Tiki](https://tiki.org) - Wiki CMS Groupware with the most built-in features. ([Demo](https://tiki.org/Demo), [Source Code](https://sourceforge.net/p/tikiwiki/code/HEAD/tree/)) `LGPLv2` `PHP`
  * [TWiki](http://twiki.org/) - TWiki is a Perl-based structured wiki application, typically used to run a collaboration platform, knowledge or document management system, a knowledge base, or team portal. ([Demo](http://twiki.org/cgi-bin/view/Sandbox/WebHome), [Source Code](http://svn.twiki.org/svn/twiki/)) `GPL` `Perl`
  * [Wikifeat](https://www.wikifeat.org/app/wikis/wikifeat/pages/welcome) - Wikifeat is an open source collaboration platform built around the ever-popular Wiki concept. ([Source Code](https://github.com/rhinoman/wikifeat)) `BSD` `GO`
  * [WiKiss](http://wikiss.tuxfamily.org/) - A Wiki, simple to use and install. ([Source Code](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPLv2` `PHP`
  * [XWiki](http://www.xwiki.org) - A second generation wiki that allows the user to extend its functionalities with a powerful extension-based architecture. ([Demo](http://playground.xwiki.org), [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPLv2` `Java`


## Self-hosting Solutions

**[`^        back to top        ^`](#)**

  * [Cloudron](https://cloudron.io) - Effortlessly self-host web apps on your server. ([Source Code](https://git.cloudron.io/groups/cloudron)) `AGPLv3` `Nodejs/Docker`
  * [DPlatform](https://dfabric.github.io/DPlatform-ShellCore/) - Deploy self-hosted apps easily: simple, bloat-free, independent installation. ([Source Code](https://github.com/j8r/DPlatform)) `MIT` `Shell`
  * [FreedomBone](https://github.com/bashrc/freedombone) - Home server configuration based on Debian. `GPLv3` `Shell`
  * [FreedomBox](https://wiki.debian.org/FreedomBox) - A community project to develop, design and promote personal servers running free software for private, personal, communications. `GPLv3` `Python/Other`
  * [OpenMediaVault](http://www.openmediavault.org/) - OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more. ([Source Code](https://github.com/openmediavault/openmediavault)) `GPLv3` `PHP`
  * [Piratebox](https://piratebox.cc/start) - A DIY anonymous offline file-sharing and communications system built with free software and inexpensive off-the-shelf hardware. ([Source Code](https://github.com/PirateBox-Dev)). `GPLv3` `Python/Other`
  * [Puffin](http://puffin.rocks/) - Lightweight webapp catalog based on containers, with user interface à la mobile app store. ([Demo](http://puffin.rocks/), [Source Code](https://github.com/puffinrocks/puffin)) `AGPLv3` `Python/Docker`
  * [Sandstorm](https://sandstorm.io/) - Personal server for running self-hosted apps easily and securely. ([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache` `C++/Other`
  * [sovereign](https://github.com/sovereign/sovereign) - A set of Ansible playbooks to build and maintain your own private cloud: email, calendar, contacts, file sync, IRC bouncer, VPN, and more. `GPLv3` `YAML/Other`
  * [Syncloud](http://syncloud.org/) - Your own online file storage, social network or email server. ([Source Code](https://github.com/syncloud/platform)) `GPLv3/Other` `Python/Other`
  * [TagSpaces](https://www.tagspaces.org/) - TagSpaces is an offline, cross-platform file manager and organiser that also can function as a note taking app. The WebDAV version of the application can be installed on top of a WebDAV servers such as Nextcloud or ownCloud. ([Demo](http://demo.tagspaces.org), [Source Code](https://github.com/tagspaces/tagspaces)) `AGPLv3` `Javascript`    
  * [UBOS](http://ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, WordPress, etc., - and other [features](http://ubos.net/about/). `GPLv3` `Perl/Other`
  * [WikiSuite](http://WikiSuite.org) - The most comprehensive and integrated Free / Libre / Open Source software suite ever developed. ([Source Code](http://wikisuite.org/Source)) `Multiple` `ClearOS`
  * [yunohost](https://yunohost.org/) - A server operating system aiming to make self-hosting accessible to everyone. ([Source Code](https://github.com/YunoHost)) `AGPLv3` `Python/Other`


<!-- END SOFTWARE LIST -->

-------------------------------------------------------

## List of Licenses

**[`^        back to top        ^`](#)**

 * ` ⚠ ` - Depends on a third party network service
 * `AAL` - [Attribution Assurance License](https://opensource.org/licenses/AAL)
 * `AGPLv3` - [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0)
 * `Apache` - [Apache, Version 2.0](http://www.apache.org/licenses/)
 * `ARTv2` - [Artistic License Version 2.0](http://opensource.org/licenses/Artistic-2.0)
 * `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
 * `BSD` - [FreeBSD License](https://www.freebsd.org/copyright/license.html)
 * `BSD` - [BSD 2-Clause](https://opensource.org/licenses/BSD-3-Clause) or [BSD 3-Clause](https://opensource.org/licenses/BSD-3-Clause) license
 * `CCBYSA`  - [Creative Commons Attribution-ShareAlike International License](https://creativecommons.org/licenses/by-sa/4.0/)
 * `CC0` - [Public Domain](https://creativecommons.org/about/cc0/)
 * `CDDL` - [Common Development and Distribution License](https://opensource.org/licenses/CDDL-1.0)
 * `CeCILL-B` - [CEA CNRS INRIA Logiciel Libre](http://www.cecill.info/licences/Licence_CeCILL-B_V1-en.txt)
 * `CPALv1` - [Common Public Attribution License Version 1.0](http://opensource.org/licenses/CPAL-1.0)
 * `DPL` - [Devblocks Public License 1.0](http://www.cerberusweb.com/license)
 * `ECLv2` - [Educational Community License, Version 2.0 ](http://opensource.org/licenses/ECL-2.0)
 * `EPLv1` - [Eclipse Public License, Version 1.0](https://www.eclipse.org/legal/epl-v10.html)
 * `Fair` - [Fair License](http://fairlicense.org/)
 * `GPL` - [GNU General Public License](https://www.gnu.org/licenses/gpl-1.0)
 * `GPLv2` - [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
 * `GPLv3` - [GNU General Public License 3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)
 * `IPL` - [IBM Public License](https://opensource.org/licenses/IPL-1.0)
 * `ISC` - [Internet Software Consortium License](https://www.isc.org/downloads/software-support-policy/isc-license/)
 * `LGPLv2` - [Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)
 * `LGPLv3` - [Lesser General Public License 3.0](http://opensource.org/licenses/LGPL-3.0)
 * `MIT` - [MIT License](http://opensource.org/licenses/MIT)
 * `MPLv1.1` - [Mozilla Public License Version 1.1](https://www.mozilla.org/media/MPL/1.1/index.txt)
 * `MPLv2` - [Mozilla Public License](https://www.mozilla.org/MPL/2.0/index.txt)
 * `OSLv3` - [Open Software License 3.0](https://opensource.org/licenses/osl-3.0.php)
 * `SENDMAIL` - [Sendmail License](https://www.sendmail.com/pdfs/open_source/sendmail_license.pdf)
 * `Unlicense` - [The Unlicense](http://unlicense.org/)
 * `WTFPL` - [Do What the Fuck You Want to Public License](http://www.wtfpl.net/about/)
 * `Zlib` - [Zlib/libpng License](https://opensource.org/licenses/Zlib)
 * `Zope` - [Zope Public License 2.0](http://opensource.org/licenses/ZPL-2.0)


-------------------------------------------------------

## External links

**[`^        back to top        ^`](#)**

 * [Awesome Selfhosted Chat](https://chat.awesome-selfhosted.com) - A rocket.chat instance setup for the awesome selfhosted community.
 * [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) - A curated list of awesome big data frameworks, resources and other awesomeness.
 * [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of amazingly awesome open source sysadmin resources.
 * [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](http://libreprojects.net/) - Lists of software aimed at privacy and decentralization (in some form).
 * Dynamic Domain Name services: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
 * Communities/forums: [/r/selfhosted](https://www.reddit.com/r/selfhosted), [Auto-Hébergement (FR)](http://www.auto-hebergement.fr/)

-------------------------------------------------------

## Contributing

Contributing guidelines can be found [here](.github/CONTRIBUTING.md).

## Authors

The list of authors can be found [here](AUTHORS.md).

## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.
