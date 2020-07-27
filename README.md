# Basic_software_tools
# Notes
# Linux
Just like Windows and macOS, Linux is an operating system. It has come into existence in
the mid-90s. An operating system manages all hard resources of a laptop or desktop. Linux
is one of the most secure, reliable, and worry-free operating system available on the planet.
Linux comprises of following pieces:
1. Bootloader: It is a software for managing the boot process of your computer.
2. Kernel: This piece is actually called Linux. It is the core thing that manages CPU,
memory, and peripheral devices.
3. Init system: A sub-system that bootstraps the user space and charged with controlling
daemons. It is the first process to start after the kernel starts. systemd is one of the most
popular init system.
4. Daemons: Background services like printing, sound, scheduling, etc. are called daemons.
They either start during reboot or when you log in to the computer.
5. Graphical Server: Subsystem that displays graphics on the monitor and is also called the
X server.
6. Desktop Environment: The piece with which the user actually interacts. Some of the
desktop environments are GNOME, Cinnamon, Mate, Pantheon, Enlightenment, KDE, Xfce,
etc.
7. Applications: High-quality software designed for specific tasks. Just like other operating
systems, Linux has its own app store from where applications can be downloaded and
installed.

# Bash
A kernel (whether it's Linux, BSD, Mach, or NT) maintains all the physical hardware and
enables each component to talk with one another and be orchestrated by some basic
software. So, how to give instructions to computer to do something. A shell outside kernel or
around kernel serves this task. Bash is one of the most popular, the most powerful, and the
most friendly. When you start terminal running Bash shell, a prompt symbol usually dollar sign( $ ) waits for
your input and command. Bash is just an application, and its primary job is to run other
applications (in the form of commands) that are installed on the same system.

# VSCode
Visual Studio Code is a free source-code editor. It was developed and launched by Microsoft
in 2015 for Windows, Linux, and macOS.It supports a variety of programming languages which include Java, JavaScript, Go, Node.js,
and C++. With free extensions, python, R, Ruby, etc. can also be edited. It has built-in
debugging support, embedded Git control, syntax highlighting, code completion, integrated
terminal, code refactoring, and snippets. It is based on an electron framework which is used
to develop Node.js and web apps that run on the Blink layout engine.
Visual Studio Code includes multiple extensions for FTP, thus can be used as a free
alternative for web development. Code can be synced between the editor and the server,
without downloading any extra software.

# MySQL
It is an open-source relational database management system. ‘My’ name is derived from the
daughter of MySQL founder and SQL stands for Structured Query Language. It is
open-source under GNU General Public License. It is written in C and C++.

Features of MySQL:

❖ Being a relational database management system, it is based on SQL queries to access
and manage records of the table.

❖ It is easy to use as you just have to have basic knowledge of SQL queries

❖ It is secure as it has a solid data security layer that projects sensitive data from
crackers

❖ Follows the working of client/server architecture

❖ It is free to download

❖ It is scalable as it can store a large amount of data up to 50 million rows or more

❖ Considered to be one of the very fast database languages

❖ It is highly flexible as it supports a large no. of embedded applications
❖ Runs on many operating systems

❖ Allows transactions to roll-back, commit and recovery

❖ Highly efficient as very low memory leakage problemFeatures of MySQL

# MongoDB
It is a cross-platform document-oriented database program. It is a NoSQL database program
that uses JSON-like documents with optional schemas.

Features of MongoDB:

❖ Supports ad hoc queries such as range query, field query, and regular expression
searches

❖ Any field can be indexed in document

❖ Supports master save replication

❖ Can run over multiple servers. Data duplication is done to retrieve data in case of
hardware failure

❖ Has automatic load balancing configuration

❖ Map-reduce and aggregation tools are supported

❖ Provides high performance and stores files of any size easily without complicating your
stack

# Elasticsearch
Elasticsearch is a distributed, open-source search and analytics engine for all types of data,
including textual, numerical, geospatial, structured, and unstructured.

Where we use Elasticsearch:

❖ Application search

❖ Website search

❖ Enterprise search

❖ Logging and log analytics

❖ Infrastructure metrics and container monitoring

❖ Application performance monitoring

❖ Geospatial data analysis and visualization

❖ Security analytics

❖ Business analytics

Working of Elasticsearch:

❖ Raw data flows from a variety of sources which include web applications, logs and
system metrics

❖ Raw data is parsed, normalized and enriched through the process of data ingestion
before data is indexed

❖ Once data is indexed, the user can run complex queries on data

❖ From Kibana, powerful visualization of data can be created

# Redis
Redis stands for Remote Dictionary Server is an in-memory data structure store , used as a
database, cache and message broker. It supports data structures such as strings, hashes,
lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes with
radius queries and streams.

Features of Redis:

❖ Stores data as key and value pair and up to 1GB data can be stored per entry

❖ Uses its own hashing mechanism called Redis Hashing

❖ Supports data replication

❖ Can withstand failures and provide uninterrupted service

❖ Has APIs in all popular programming languages

❖ The high-performance messaging system can be developed with Redis

❖ Allows insertion of large amount of data into its cache very easily

❖ Having a very small memory requirement, Redis can be installed in Raspberry Pi and
ARM devices

❖ Simple protocols

❖ Support transactions

# SQL
SQL stands for Structured Query Language is a query language for relational databases. It is
data manipulation language i.e. can access and manipulate stored data, declarative
language i.e. you need to specifies what to do but not how to do, and data definition
language i.e. defines databases relations and schemas

Advantages of SQL:

❖ Easy to manage the database systems without writing substantial code

❖ Well defined standards

❖ Highly portable, can be used in the program in PCs, servers, laptops, and even some
of the mobile phones

❖ It is an interactive language

❖ With the help of SQL language, the users can make different views of database
structure and databases for the different users

Disadvantages of SQL:

❖ It has a complex interface so some users find difficulty

❖ Programmers don’t have full control over the database because of hidden business
rules

❖ Operating cost of some SQL versions are very high

# Pandas
It is a python library written for data manipulation and analysis. Particularly, it offers data
structures and operations for manipulating numerical tables and time series.
Features of Pandas

❖ DataFrame object for data manipulation with integrated indexing

❖ Tools for reading and writing data between in-memory data structures and different file
formats

❖ Data alignment and integrated handling of missing data

❖ Reshaping and pivoting of data sets

❖ Label-based slicing, fancy indexing, and subsetting of large data sets

❖ Data structure column insertion and deletion

❖ Group by engine allowing split-apply-combine operations on data sets
❖ Data set merging and joining

❖ Hierarchical axis indexing to work with high-dimensional data in a lower-dimensional
data structure

❖ Time series-functionality: Date range generation and frequency conversion, moving
window statistics, moving window linear regressions, date shifting, and lagging.

❖ Provides data filtration.

# Flask
It is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions. However, Flask supports extensions that can add application features as if they were implemented in Flask itself.

# Tornado
Tornado is a Python web framework and asynchronous networking library, originally developed at FriendFeed. By using non-blocking network I/O, Tornado can scale to tens of thousands of open connections, making it ideal for long polling, WebSockets, and other applications that require a long-lived connection to each user.

# GCP
Google Cloud Platform (GCP), offered by Google, is a suite of cloud computing services that runs on the same infrastructure that Google uses internally for its end-user products, such as Google Search, Gmail and YouTube. Alongside a set of management tools, it provides a series of modular cloud services including computing, data storage, data analytics and machine learning.

# Git & Github
Simply put, Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

# References
❖ https://www.linux.com/what-is-linux/

❖ https://fedoramagazine.org/what-is-an-init-system/

❖ https://www.hostinger.in/tutorials/linux-commands

❖ https://opensource.com/resources/what-bash

❖ https://www.howtoinstall.me/ubuntu/18-04/bash/

❖ https://en.wikipedia.org/wiki/Visual_Studio_Code

❖ https://www.youtube.com/watch?v=VqCgcpAypFQ

❖ https://en.wikipedia.org/wiki/MySQL

❖ https://www.javatpoint.com/mysql-features

❖ https://www.careerride.com/MySQL-disadvantages.aspx

❖ https://en.wikipedia.org/wiki/MongoDB

❖ https://www.javatpoint.com/mongodb-features

❖ https://acodez.in/mongodb-nosql-database/#Disadvantages_of_MongoDB

❖ https://www.quora.com/What-are-the-disadvantages-of-MongoDB

❖ https://www.elastic.co/what-is/elasticsearch

❖ https://en.wikipedia.org/wiki/Redis

❖ https://redis.io/topics/introduction

❖ https://dzone.com/articles/10-traits-of-redis

❖ https://www.quora.com/What-are-the-disadvantages-of-Redis

❖ Lecture Notes by Prof. Arnab Bhattacharya, IIT Kanpur

❖ https://whatisdbms.com/what-is-sql-applications-advantages-and-disadvantages/

❖ https://en.wikipedia.org/wiki/Pandas_(software)

❖ https://www.dataquest.io/blog/pandas-cheat-sheet/

❖ https://en.wikipedia.org/wiki/Flask_(web_framework)

❖ https://www.tornadoweb.org/en/stable/

❖ https://en.wikipedia.org/wiki/Google_Cloud_Platform

❖ https://blog.devmountain.com/git-vs-github-whats-the-difference/#:~:text=Simply%20put%2C%20Git%20is%20a,help%20you%20better%20manage%20them.
