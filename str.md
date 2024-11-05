Computer Networking > HTML >CSS >JS Basics > JS Advanced > JS Frameworks/Libraries(RNAV, Jquery) > React >tailwind > Version Control > VCS Hosting >Backend Framework(EN Springboot)
> Node JS > Typescript > Relational and Non Relational DB > API Protocol (REST SOAP GraphQL JSON-RPC Websockets) >Authentication(JWT OAUTH Token Auth SAML OPENID)
> API Security(HTTPS CORS SSL/TSL CSP >Containerization >Virtualization>Serverless Computing > CI/CD > Deployment Platform(AWS OCP Azure Firebase IBM Cloud)


MongoDB(Database)   ExpressJS(Web Framework)   ReactJS(Front-end Framework)    NodeJS(Application Server)

Structuring the web
Styling the web
Dynamic Client Side Scripting
Working with usee data
Making the web accessible by everyone
Acessibility- ARIA 
Performance
Server Side Website Programming
Static Side (Architecture)
Dynamic Side (Architecture)
in fact, writing your code by hand can be quicker and more efficient if you only need a small, simple website UI.In contrast, you would almost never consider 
writing the server-side component of a web app without a framework — implementing a vital feature like an HTTP server is really hard to do from scratch in say Python,
 but Python web frameworks like Django provide one out of the box, along with other very useful tools.


MDN is official

REACT
Overview- List Forms Keys Refs
Tic Tac Toe - CodeSandbox lets you write code in your browser and preview how your users will see the app you’ve created.(local development environment. To do this, 
you need to:Install Node.js  cd-->npm install  -->npm start
Creating and nesting components- JavaScript functions that return markup
Writing markup with JSX- JSX is stricter than HTML-  CSS rules for it in a separate CSS file
Adding styles-  string concatenation:
Displaying data
Conditional rendering- if or ?
Rendering lists- e for loop and the array map() function to render lists of components.
Responding to events
React DOM Events- 
onclickcapture Event
onMouseDown Event
onDoubleClick Event
onSubmit Event
onScroll Event
onBlur Event
PropTypes
Prop Drilling
React Lists
Context API
React Redux
Updating the screen
Using Hooks- useState Hook
useEffect Hook
useRef Hook
useMemo Hook
useContext Hook
React Connection and Deployment - serverless static on Netlify Surge Github Firebase heroku  
Sharing data between components- Functional Component and Class Component, Container and Presentation Pattern in components



EXPRESS JS
Methods
Express,json
Methods
Express.routing
Application- Properties Events Methods

Response- Properties Methods
Request- Properties Methods
Router- Methods
express.router()
express.urlencoded()
Basics- Express Generator Routing Writing and Using Middleware Error Handling Debugging Express behind proxies Database Integration Using template engines Overriding Express API
How to Structure my Application in Express JS 
Unique features of Express
How to send response from server to client using Node and Express ?
Why Express ‘app’ and ‘server’ files kept separately ?
How to implement JWT authentication in Express app
How to expire session after 1 min of inactivity in express-session of Express JS

Express Error Handling
Express Functions:
Express express():
Expresson() Function
express.raw() Function
express.Router() Function
express.static() Function
express.text() Function
express.urlencoded() Function
express() function Complete Reference
Express Applications Function:
app.locals Property
app.mountpath Property
Mount Event
app.all() Function
app.delete() Function
app.disable() Function
app.disabled() Function
app.enable() Function
app.enabled() Function
Application Complete Reference
Express Requests Function:
req.app Property
req.baseUrl Property
req.body Property
req.cookies Property
req.fresh Property
req.accepts() Function
req.acceptsCharsets() Function
req.acceptsEncodings() Function
req.acceptsLanguages() Function
Request Complete Reference
Express Response Function:
res.app Property
res.headersSent Property
res.locals Property
res.append() Function
res.attachment() Function
res.cookie() Function
res.clearCookie() Function
res.download() Function
res.end() Function
Response Complete Reference
Express Router Function:
router.all() Function
router.METHOD() Function
router.param() function
router.route() Function
router.use() Function
Router Complete Reference
Middleware- Third party middleware middleware chaining Express session middleware custom middleware app level route level middleware
Testing- Postman File Uploads POST GET DELETE API Endpoints 
Advanced Topics- Security Updates Security Best Practices Performance Updates Health Checks and ShutDowns Building Template Engines
Template Engines: Use template engines like EJS or Pug for dynamic content rendering.
Error Handling: Implement custom error handling middleware to gracefully handle exceptions.
Authentication: Integrate authentication middleware (e.g., Passport.js) for secure user sessions.
Node vs Express
Middlewares in Express
How to update record in Cassandra using Express 
What is the use of next() function in Express JS
How to create custom middleware in express
Why Express is used in Web Development
What is Express Generator
Express HTTP methods
How to create routes using Express and Postman?
Why Express Is Used For Enterprise App Development
REST API using the Express to perform CRUD
What is express-session middleware in Express


NODEJS
Blocking Architecture 
Node.js Introduction
Why Node.js?
Node.js NPM (Node.jsPackage Manager)
Installation of Node.js on Linux
Installation of Node.js on Windows
Node.js Basics
Node.js First Application
Node.js REPL
Node.js modules
Node.js Start and Run Server
Node.js Blocking and Non-Blocking
Node.js Callback Concept
Node.js Debugging
Node.js Set Console Font Color
Node.js Web Server
Node.js Create and Publish NPM packages
Node.js –save and –save-dev
Node.js Event Loop
Node.js Frameworks
Node.js Promise Chaining
Node.js This Binding
Node.js Global Objects
Node.js Automatic Restart Server with Nodemon
Node.js Child Process
Node.js Global Installation of Dependencies
Node.js Session Variable
Node.js Complete References
Node.js Assert
Node.js Buffer
Node.js Console
Node.js Crypto
Node.js DNS
Node.js File System
Node.js Globals
Node.js HTTP Module
Node.js HTTP2
Node.js OS
Node.js Path Module
Node.js Process
Node.js Query String
Node.js Stream
Node.js String Decoder
Node.js Timers
Node.js TLS/SSL
Node.js UDP/DataGram
Node.js URL
Node.js Utility
Node.js V8
Node.js VM
Node.js Zlib

REPL(Read Eval Print Loop)
NPM Global Objects Local Module
MODULE- Assert Console Buffer Crypto DNS File System HTTP HTTP2 OS Path Process Query String 

You have a couple of applications to deploy so, you can package it into a container and run it on a server containing a Docker engine or any other container engine. You package the application into a container using a Docker file and host it on a port for the external world to access it.

But there is a drawback is that it is only running on a single server so, if at that point any failure occurs it becomes an application failure, to handle the 
single point of failure google introduced Kubernetes to scale applications.
DOCKER
Docker Instructions
Run Commands Inside Containers
USER Instruction
Docker Images
A Docker Image contains everything a container needs to run, including the application code, libraries, dependencies, and the operating system it needs.

Docker Images
Working with Images
Publish Docker Images in Hub
Create a Customized Image
Use Image Tags
How to use Next.js Image
How to use Local Image with Minikube
Docker Compose
Managing multiple containers can get complex! Docker Compose simplifies this process. In this section we have listed down all the details about the Docker Compose like intro and Compose tools.

Introduction to Docker Compose
Compose tools to run Multi Container Apps
Docker Engine, Storage
Docker Engine, also known as Docker Daemon, is the core component of the Docker platform responsible for running and managing Docker containers. Explore this section to get all details about Docker Engine.

Docker Storage
Docker Data Storage
Backup Docker Container
Manage Volumes using CLI
Docker Networking
Docker Networking refers to the set of mechanisms and technologies Docker provides for communication between Docker containers, as well as between containers and the outside world. Go through this section to get more details about Docker Networking.

Docker Networking
Docker Ports
Creating a Network and connecting a Container
Connecting Two Docker Containers Over the Same Network
Default Bridge Networking
Create your own secure Home Network using Pi-hole and Docker
Docker Registry
After knowing the Docker Networking, in Docker tutorial, in this section we are going to discuss Docker Registry which is refer as central repository for storing the and managing Docker image.

Docker Registry
Docker – Public Repositories
Docker – Private Registries
Creating a Private Repository and Push an Image to That Private Repository
Using Public Repositories To Host Docker Images
Docker Containers and Managing Containers
Explores this section to get to know about the fundamental concepts and practical aspects of utilizing Docker technology to deploy and manage software applications efficiently in this section.

Containerization using Docker
Docker Container Virtualization
Docker Container for Node.js
Remove Containers
Push a Container Image to a Docker Repository
Docker Container Linking
Manage Containers using CLI
Mount Volume inside Container
Difference between Images and Container
Difference between Virtual Machines and Containers
How to Install Linux Package in Docker Container
Copying Files to and from Docker Containers
Run MongoDB as Container
Container for Node.js
Container for NGNIX
How to Provide the Static IP to a Docker Container?
Docker Swarm
Docker Swarm steps in as your reliable organizer, making sure all your containers are in the right place and working well together. Go through this section to get an all about Docker Swarm.

Introduction to Docker Swarm
Difference between Kubernetes and Docker Swarm

Introduction to Kubernetes
Kubernetes – Installation Methods
Installation of Kubernetes on Ubuntu
Kubernetes – Architecture
Kubernetes – Monolithic Architecture of Kubernetes
Kubernetes vs Docker
Kubernetes – Concept of Containers
Kubernetes – Introduction to Container Orchestration
Kubernetes – Images
Kubernetes – Jobs
Kubernetes – Labels & Selectors
Kubernetes – Namespace
Kubernetes – Node
Kubernetes – Node Port Service
Kubernetes – Cluster IP vs Node-Port
Kubernetes – Service
Kubernetes – Service DNS
Kubernetes – Pod
Kubernetes – Run a Command in Pod’s Containers
Kubernetes – Create Multiple Container in a Pod
Kubernetes – Replication Controller
Kubernetes – Difference Between Replicaset and Replication Controller
Kubernetes – Deployments
Kubernetes – Volumes
Kubernetes – Secrets
Kubernetes – Working with Secrets
How to set up a Kubernetes cluster on a local machine using minikube?
Kubernetes – Physical Servers vs Virtual Machines vs Containers

Kubernetes – API
Kubernetes – Taint and Toleration
Kubernetes – Kubectl
Kubernetes – Kubectl Commands
Kubernetes – Kubectl Delete
Kubernetes – Load Balancing Service
Kubernetes – Kubectl Create and Kubectl Apply
Kubernetes – ConfigMap
Kubernetes – Create Config Map From Files
Kubernetes – Create ConfigMap from YAML
Kubernetes – ConfigMap from Directories
Kubernetes – Injecting ConfigMap as Files
Kubernetes – Injecting ConfigMap in Pods
Kubernetes Resource Model (KRM) and How to Make Use of YAML?
Installing Private Git Server on K8s Cluster with Gitea and AKS
Enable Remote Debugging For Java Application Deployed in Kubernetes Environment
How to Enable JMX For Java Applications Running in the Kubernetes Cluster?


Introduction to AWS
AWS IAM – Identity and Access Management
Computing in AWS
Section 1 – AWS EC2 – Backbone of AWS
Section 2 – AWS EBS – Elastic Bean Stalk
Section 3 – AWS EBS – Elastic Block Store
Section 4- AWS AMI
Section 5 – AWS Load Balancer
Section 6 – AWS Lambda
Section 7 – AWS CloudWatch
Section 8 – AWS AutoScaling
Section 9 – Other Elastic Computes (ECS, EKS, ECR)
AWS Storage Services
AWS Application Services
AWS Database Services
AWS VPC – Virtual Private Cloud
AWS Billing and Management
Machine Learning and IoT
Advantages of AWS
Application of AWS

Section 1 – AWS EC2 – Backbone of AWS
What is EC2
How to create an Instance in EC2
Types of EC2
Price Model for EC2
Introduction to EC2 Spot Instances
Create a Windows EC2 Instance and Connect Using RDP
Create an EC2 Instance User Data Script
Flexibility in EC2 Spot Instances
Rules for Spot Instances
Installation of Python3 on AWS EC2?
Installation of GO on EC2?
Connecting EC2 using Bastion Host

Create EC2 instance -> Connect to terminal using SSH key --> AWS Resources using ansible --> Instance Types 

In terms of use cases, Kafka can be used for building distributed streaming applications that rely on message queues, such as event logging systems, monitoring and 
alerting services, etc. Spark can be used for building real-time streaming applications that process data in near real time, such as financial fraud detection and 
clickstream analysis. Hadoop can be used for batch processing of large datasets that are not suitable for real-time processing, such as log analysis or business 
intelligence.

Spark Core
Spark SQL Database
Spark Streaming
DOCX
Quick Start: -  Datasets can be created from Hadoop InputFormats (such as HDFS files) or by transforming other Datasets. --> transform this DataFrame -->chain together transformations and actions:  --> Maps and aliases 
Caching --> Self Contained Applications
RDD Programming Guide: overview of Spark basics - RDDs (core but old API), accumulators, and broadcast variables
Spark SQL, Datasets, and DataFrames: processing structured data with relational queries (newer API than RDDs) --Getting Started
Data Sources
Performance Tuning
Distributed SQL Engine
PySpark Usage Guide for Pandas with Apache Arrow
Migration Guide
SQL Reference
Error Conditions
Structured Streaming: processing structured data streams with relation queries (using Datasets and DataFrames, newer API than DStreams)- Overview
Quick Example
Programming Model
Basic Concepts
Handling Event-time and Late Data
Fault Tolerance Semantics
API using Datasets and DataFrames
Creating streaming DataFrames and streaming Datasets
Input Sources
Schema inference and partition of streaming DataFrames/Datasets
Operations on streaming DataFrames/Datasets
Basic Operations - Selection, Projection, Aggregation
Window Operations on Event Time
Handling Late Data and Watermarking
Types of time windows
Representation of the time for time window
Join Operations
Stream-static Joins
Stream-stream Joins
Inner Joins with optional Watermarking
Outer Joins with Watermarking
Semi Joins with Watermarking
Support matrix for joins in streaming queries
Streaming Deduplication
Policy for handling multiple watermarks
Arbitrary Stateful Operations
Unsupported Operations
State Store
HDFS state store provider
RocksDB state store implementation
RocksDB State Store Memory Management
RocksDB State Store Changelog Checkpointing
Performance-aspect considerations
State Store and task locality
Starting Streaming Queries
Output Modes
Output Sinks
Using Foreach and ForeachBatch
ForeachBatch
Foreach
Streaming Table APIs
Triggers
Managing Streaming Queries
Monitoring Streaming Queries
Reading Metrics Interactively
Reporting Metrics programmatically using Asynchronous APIs
Reporting Metrics using Dropwizard
Recovering from Failures with Checkpointing
Recovery Semantics after Changes in a Streaming Query
Asynchronous Progress Tracking
What is it?
How does it work?
How to use it?
Limitations
Switching the setting off
Continuous Processing
Additional Information
Migration Guide
Spark Streaming: processing data streams using DStreams (old API)- Note A Quick Example Basic Concepts Linking Initializing StreamingContext Discretized Streams (DStreams)
Input DStreams and Receivers Transformations on DStreams Output Operations on DStreams DataFrame and SQL Operations MLlib Operations
Caching / Persistence Checkpointing Accumulators, Broadcast Variables, and Checkpoints Deploying Applications Monitoring Applications
Performance Tuning Reducing the Batch Processing Times Setting the Right Batch Interval Memory Tuning
Fault-tolerance Semantics Where to Go from Here

MLlib: applying machine learning algorithms
GraphX: processing graphs
SparkR: processing data with Spark in R
PySpark: processing data with Spark in Python
Spark SQL CLI: processing data with SQL on the command line
API Docs:

Spark Scala API (Scaladoc)
Spark Java API (Javadoc)
Spark Python API (Sphinx)
Spark R API (Roxygen2)
Spark SQL, Built-in Functions (MkDocs)
Deployment Guides:

Cluster Overview: overview of concepts and components when running on a cluster
Submitting Applications: packaging and deploying applications
Deployment modes:
Amazon EC2: scripts that let you launch a cluster on EC2 in about 5 minutes
Standalone Deploy Mode: launch a standalone cluster quickly without a third-party cluster manager
Mesos: deploy a private cluster using Apache Mesos
YARN: deploy Spark on top of Hadoop NextGen (YARN)
Kubernetes: deploy Spark on top of Kubernetes
Other Documents:

Configuration: customize Spark via its configuration system
Monitoring: track the behavior of your applications
Tuning Guide: best practices to optimize performance and memory use
Job Scheduling: scheduling resources across and within Spark applications
Security: Spark security support
Hardware Provisioning: recommendations for cluster hardware
Integration with other storage systems:
Cloud Infrastructures
OpenStack Swift
Migration Guide: Migration guides for Spark components
Building Spark: build Spark using the Maven system
Contributing to Spark
Third Party Projects: related third party Spark projects

Tailwind CSS Layout
Tailwind CSS Layout utilities help you control the positioning and sizing of elements on your page. Use these classes to create responsive, flexible layouts that adapt to various screen sizes with ease.

Container
Box Sizing
Display
Float
Clear
Object Fit
Object Position
Overflow
Overscroll Behavior
Position
Top/Right/Bottom/Left
Visibility
Z-index
Tailwind CSS Flexbox
Tailwind CSS Flexbox utilities simplify building flexible and responsive layouts. They offer classes to manage the alignment, direction, and spacing of items within a flex container, making layout adjustments straightforward.

Flex Direction
Flex Wrap
Flex
Flex Grow
Flex Shrink
Order
Tailwind CSS Grid
Tailwind CSS Grid utilities allow you to create complex, responsive grid layouts effortlessly. With a range of classes, you can define columns, rows, and gaps, enabling you to design intricate grid systems quickly.

Grid Template Columns
Grid Column Start / End
Grid Template Rows
Grid Row Start / End
Grid Auto Flow
Grid Auto Columns
Grid Auto Rows
Grid Gap
Tailwind CSS Alignment
Tailwind CSS Alignment utilities enable precise control over the alignment of elements. Easily adjust vertical and horizontal alignment within containers, ensuring your content is positioned exactly where you want it.

Justify Content
Justify Items
Justify Self
Align Content
Align Items
Align Self
Place Content
Place Items
Place Self
Tailwind CSS Spacing
Tailwind CSS Spacing utilities manage the margins and padding of your elements. Use these classes to add consistent spacing between items, enhancing the overall layout and design of your website.

Padding
Margin
Space Between
Tailwind CSS Sizing
Tailwind CSS Sizing utilities help you define the width and height of your elements. Quickly adjust dimensions with classes that ensure your elements fit perfectly within your design.

Width
Min-Width
Max-Width
Height
Min-Height
Max-Height
Tailwind CSS Typography
Tailwind CSS Typography utilities control text appearance, including font size, weight, line height, and letter spacing. These classes ensure your text is styled consistently and legibly throughout your project.

Font Family
Font Size
Font Smoothing
Font Style
Font Weight
Font Variant Numeric
Letter Spacing
Line Height
List Style Type
Placeholder Color
Placeholder Opacity
Text Alignment
Text Color
Text Opacity
Text Decoration
Text Transform
Vertical Alignment
Whitespace
Word Break
Tailwind CSS Backgrounds
Tailwind CSS Backgrounds utilities manage background colors, images, and gradients. Apply these classes to set eye-catching backgrounds that enhance your site’s visual appeal.

Background Image
Background Clip
Background Color
Background Opacity
Background Position
Background Repeat
Background Size
Gradient Color Stops
Tailwind CSS Borders
Tailwind CSS Borders utilities allow you to style borders with different widths, colors, and styles. Use these classes to add borders to your elements and create visual separation or emphasis.

Border Radius
Border Width
Border Color
Border Opacity
Border Style
Divide Width
Divide Color
Divide Opacity
Divide Style
Ring Width
Ring Color
Ring Opacity
Ring Offset Width
Ring Offset Color
Tailwind CSS Effects
Tailwind CSS Effects utilities provide classes for adding visual effects like shadows and opacity. Enhance the look of your elements with effects that add depth and focus to your design.

Box Shadow
Opacity
Tailwind CSS Filters
Tailwind CSS Filters utilities let you apply image effects like blur, brightness, and contrast. Use these classes to adjust the visual presentation of images and other elements dynamically.

Filter
Blur
Brightness
Contrast
Drop Shadow
Grayscale
Hue Rotate
Invert
Saturate
Sepia
Backdrop Filter
Backdrop Blur
Backdrop Brightness
Backdrop Contrast
Backdrop Grayscale
Backdrop Hue Rotate
Backdrop Invert
Backdrop Opacity
Backdrop Saturate
Backdrop Sepia
Tailwind CSS Tables
Tailwind CSS Tables utilities style HTML tables with ease. Customize table elements, including borders, spacing, and alignment, to create clear and attractive data presentations.

Border Collapse
Table Layout
Tailwind CSS Transitions and Animation
Tailwind CSS Transitions and Animation utilities simplify adding animations and transitions to your elements. Use these classes to create smooth, dynamic effects that improve user interactions and engagement.

Transition Property
Transition Duration
Transition Timing Function
Transition Delay
Tailwind CSS Transforms
Tailwind CSS Transforms utilities enable you to rotate, scale, and translate elements. Apply these transformations to create engaging visual effects and enhance the user experience.

Transform
Transform Origin
Scale
Rotate
Translate
Tailwind CSS Interactivity
Tailwind CSS Interactivity utilities provide classes for adding interactive features like hover and focus states. These utilities help you create responsive and engaging UI elements that react to user actions.

Appearance
Cursor
Outline
Pointer Events
Resize
Select
Tailwind CSS SVG
Tailwind CSS SVG utilities simplify the styling of SVG graphics. Use these classes to control SVG attributes like size, color, and positioning directly within your HTML. Tailwind CSS makes it easy to integrate and style scalable vector graphics for a cleaner, more consistent design.

Fill
Stroke
Stroke Width
