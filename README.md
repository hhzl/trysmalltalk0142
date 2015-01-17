# TrySmalltalk

Tutorial to learn Smalltalk

Repository contains version created from scratch with 

    amber init

with the correct parameters (see below).

The parameters were chosen so that the existing code file
https://github.com/amber-smalltalk/trysmalltalk/blob/master/src/TrySmalltalk.st
fits. That file was added to the generated ``amber init`` generated TrySmalltalk.st 
file and in the #augmentpage method 

    TrySmalltalkWidget new appendToJQuery: 'body' asJQuery.


was added.


    grunt

recompiled everything successfully.
 

## Getting Started

To bring project alive (for example after `git clone`):

```sh
npm install
bower install
grunt devel
```

Developing the project (after brought alive):
 
Start server with `amber serve` and go to `http://localhost:4000/` in your browser and follow the instructions


amber init
----------

    Welcome to Amber version 0.14.0-0 (NodeJS 0.10.25).
    Running "init:/usr/local/lib/node_modules/amber-cli/node_modules/grunt-init-amber" (init) task
    This task will create one or more files in the current directory, based on the
    environment and the answers to a few questions. Note that answering "?" to any
    question will show question-specific help and answering "none" to most questions
    will leave its value blank.
    
    "grunt-init-amber" template notes:
     Project title should be a human-readable title.
    
    Please answer the following:
    [?] Project title (Application or Library Title) TrySmalltalk
    [?] Main class and package of Amber application.
    Project name is derived by lowercasing this. (Trysmalltalk) TrySmalltalk
    [?] Description (The Application or The Library doing The Thing.) Tutorial to learn Smalltalk
    [?] Author name (hhzl) 
    [?] Author email (hannes.hirzel@gmail.com) 
    [?] Namespace of the new Amber package. (amber-trysmalltalk) 
    [?] Version (0.1.0) 
    [?] Project git repository (git://github.com/hhzl/trysmalltalk0142.git) 
    [?] Project homepage (https://github.com/hhzl/trysmalltalk0142) 
    [?] Project issues tracker (https://github.com/hhzl/trysmalltalk0142/issues) 
    [?] Author url (none) 
    [?] Licenses (MIT) 
    [?] Do you need to make any changes to the above before continuing? (y/N)
