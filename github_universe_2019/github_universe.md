# Github Universe 20191112-20191114

## 2019112 Workshops 

[Pre-requisite site](https://github.com/universeworkshops/general/blob/master/prereqs.md) 

### Code the foundation of DevOps pipelines 

#### Optimizin for Collaboration

wifi is shit, I can't even request pages 

lab.github.com learning lab for general github learning with a bot 

The main walk-through of this talk is [here](https://github.com/deg4uss3r/innersource)

#### Introduction to Github Actions

Here's the link to the lab bot for this part 
https://github.com/deg4uss3r/hello-github-actions 


### CI with Github Actions 

What is CI? 
    getting prompt feedback during the development process 

[learning lab link](https://github.com/deg4uss3r/github-actions-for-ci)

### CD with Github Actions 

What is CD? 
    ensures code is always deployable 
    push-button deployment 
    safely and rapidly get code into production with minimal interation 
    focuses on making software deployable over working on new features 

What CD is not
    does not mean any change gets pushed into production 
    does not mean it is a fully automated process
    not restricted to cloud providers 
    not limited to containers 

CI runs up to your testing phase...CD starts there and runs up to your release


### Navigating Regulated Environments with GitHub  

Places like Continental (automotive), Coinbase (financial), etc 

[learning lab](https://github.com/deg4uss3r/connect-the-dots-in-a-github-repository/)

[second learning lab](https://github.com/deg4uss3r/security-strategy-essentials)

security lab looks really good for everyone to take 


## 20191113 Conference Day 1 

### 0900; all stages; Opening Keynote 

Code to cloud, daily experience, and investments in the community 

#### Code to Cloud 

Github Packages and Actions 

No longer beta after today 

#### Actions

builds for unix (ubuntu, and MacOS) and windows 

built in secret store 

#### Packages

public and private looks like supports, docker, ruby, javascript 

Rust does use it, so does `brew`

*demo of actions* 

* Write an action that uses cargo outdated and puts in an issue if there's a new stable release to bump to 

Actions support self-hosted builds

#### Github Desktop 

GUI for pushing and commit code 

#### Github Site 

Better in browser code search matching 

slack support for PR reviews etc 

Enterprise 2.19 releases today 

#### Notifications updates 

Better organization of notifications, team and other subfolders 

can add 15 custom filters 

can save notifications for later 

#### Github for Mobile 

can use notifications, save them, complete them etc on mobile 

Some notifications can be pushed (mentioned in a issue, PR, or comment) 

still seems like too much that will get pushed 

all markdown and syntax highlighting is done natively, 

Dark mode for mobile app 

Also for iPadOS 

Beta for iOS today 

#### Github Sponsors 

@badger was mentioned 

teams and projects can be sponsored 
    must have a non-profit or cooperate bank account 

#### Artic Code Vault? 

lolz yup right in Svaldbard, next to the seed vault 

### 1030; Embarcadero Stage;  Shaping the contributor Experience 

government shutdown hit them hard 10% of the FY, and went from being on the engineering team, to being just an engineering team 

people really like CI badges 


### 1125; Embarcadero Stage; Communication with Github

All about the github app 

### 1315; Potrero; Panel: Women in open source 

Not bad talk, was standing and arrived late so hard to take notes

wish they formalized some Codes of Conducts to use like licenses (e.g. MIT, Apache2.0, etc.) so they were binding and trusted 

### 1410; Embarcadero;  The code behind cars: How GitHub turned Ford into a software company 

Just talked a lot about what Ford was and then the fact they moved to Github and it decreased build times

### 1520; Embarcadero;  Secure container development workflows with Anchore and GitHub Actions 

Really cool talk, need to look up and setup the Anchore Github Action for containers

## 20191114 Conference Day 2

### 0900; all stages; Opening Keynote

#### Security 

Talking about securing software development and trusting open source software 

New token detector partners so they can automatically revoke tokens (never really heard of any of them, they already have AWS, Google, Dropbox, etc.) 

*Security workflow demo* 

starts off as "view policy" hoping they release a private issue function... 

Can request a CVE right from the private team contribution page, Github is a CVE number distributor 

Github Advisory database is available for everyone for free, and can be accessed by API 

More about Semmle 

Semmle created a "codeQL" database from the source code 

Announced the Github Security Lab 

codeQL is free for open source and academic research, and a VS code extension 

#### More on Github Actions 

Just more showcasing actions (Twillio SMS seems interesting i.e. when a build fails/passes text you)

#### Container Management (Code to Cloud) workflow 

Amazon person talking about storing their containers with them 

myticalcreatures.com for AWS training/examples 

#### CI/CD for in the browser mabl 

More actions plugging 

mabl is a test suite for web development: screenshots, dom tests, and page load statistics 


### 1030; Potrero; The city guide to open source

Really cool talk comparing/contrasting city planning to open source and how we could learn/use lessons learned 

### 1315; Golden Gate; Machine learning operations with GitHub Actions and Kubernetes

[Code for this presentation](bit.ly/ml-ops) 

Using Kubeflow for the infra piece and using github actions for sending and receiving information to kubeflow 

So using Weights and Biases for some of the overall reports that each run of the model will take 

### 1520; Embarcadero;  What does it take to transform a federal agency to a lean, product-focused enterprise? 

US Dept of VA 

lots of horrible stats on how bad the site/experience was 

talker worked at the US digital service at the time, 
    now works at Boston Consulting Group 



### 1615; Potrero; Driving ethical change for AI across your organization 

They were also from Boston Consultant Group and talked about corporations losing money if not acted on.


