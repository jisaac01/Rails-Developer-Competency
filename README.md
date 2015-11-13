<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Ruby](#ruby)
  - [General](#general)
  - [Metaprogramming		](#metaprogramming)
  - [Tools](#tools)
- [Patterns](#patterns)
- [Rails](#rails)
- [Rubymine](#rubymine)
- [PostGres](#postgres)
- [MySQL](#mysql)
- [JavaScript](#javascript)
- [Git](#git)
- [CSS](#css)
- [Networking](#networking)
- [Ops & *nix](#ops-&-nix)
- [Testing](#testing)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

Rails Developer Competency

What does it take to call yourself an expert in the Ruby on Rails stack? If you wanted to level up your game, is there a comprehensive list of **everything** that you could know? What dark corners of ignorance do you have? I'm trying to capture a list here of all of the things an expert might know.

**NOTE**  this is a list of possible knowledge. Expertise is not knowledge only. It requires experience and practice as well. Just as I wouldn't consider someone who memorized everything here an expert, I wouldn't consider someone who had 10 years of practice making Rails scaffolds an expert either.

[Shu Ha Ri](https://en.wikipedia.org/wiki/Shuhari)

#Ruby
##General
- program flow  
  - if/unless/while/do/case  
- variables
  - global/class/class instance/instance/local
- constants
  - namespacing  
- HEREDOC  
- true/false/nil  
- strings/symbols	 
  - interpolation  
  - %w  
- array		
- hash		
- ranges  
- regex
- splat (*)		
- block/proc/lambda		
  - scopes/closures	
  - yield	
  - return	
  - arity	
- exceptions		
  - custom	
  - rescue	
- Class		
- Module (included/self.inherited)	
- self  
- Include vs Extend vs Prepend vs Refinements
- Enumerable
  - map/each/inject/select/sort/loop  
  - break/redo/next/retry
- Inheritance
  - super
- public/private/protected
- built in classes
  - BasicObject/Object/Class/...
- StdLib
  - Net::HTTP/Open3/OpenSSL/REXML/Tracer
- C Extensions
- threads
- common idioms
  - Mimic Methods (methods disguised as keywords)
  - nil guards (a ||= b)
  - self yield
  - symbol#to_proc (&:whatever)

##Metaprogramming	
- around alias (alias, old_method)
- blank slate (using BasicObject as superclass, or removing unnused methods)
- class macro (using class methods in Class definitions; ie attr_attribute and validates)
- clean room (using an object with instance_eval to evaluate a block)
- method_missing
- define_method		
- Class.new & Module.new		
- instance_eval & instance_exec	
- class_eval & class_exec (& module_eval)  
- eval
- define_singleton_method
- singleton class (eigenclass, metaclass)
- methods & instance_methods		
- UnboundMethod	 
- binding
- BlockenSpiel/DSLs
- sandboxing (setting $SAFE levels within a proc)

##Tools
- Gems		
-- appraisals & gem testing		
-- create a new gem		
-- Symmantic Versioning		
- Bundler		
-- Gemfile/Gemfile.lock		
- ruby-toolbox  
- Debugging
  - pry

#Patterns
- OOP  
- Prototype Inheritance  
- Strategy  
- SOLID  
-- Single Responsibility  
-- Open/Closed  
-- Liskov Substitution  
-- Interface Segregation  
-- Dependency Inversion  
- Fat Models/Skinny Controllers/Dumb Views  
- Service Objects  
- Query Objects  
- Interactors  
- Presenters  
- Decorators  
- Duck Typing  
- Composition vs Inhertiance  

#Rails
* Controllers
  * respond_to: format.js, html, json
* Views
  * form_for, form_tag, remote, link_to, button_to
  * Turbolinks
* Autoload
* ActiveSupport::Concern
* ActiveModel
  * Dirty
  *

#Rubymine
* shortcuts
* running tests
  * editing configurations
  * working directory
  
#SQL
 - select
 - join
 - left join
 - autojoin
 - indexes & avoiding indexes (column + 0)
 - group by 
 - order
 - primary/foreign key
 - constraints
 
#PostGres
* \connect DBNAME
* \l
* \d
* \q

#MySQL
- INNODB vs MyISAM
- location of config file

#JavaScript
- prototypical inheritance
- scopes
- var/let/const
- declaring functions (multiple ways)
- ()();

#Git
- clone
- commit/add
- rebase
- rebase -i
- reset vs reset --HARD
- remotes
- ammend
- force pushing
- branching/merging

#CSS
*float
*flex-box
*Box model
*Conditional comments
*Email
  - TABLE vs DIV
  - Inline CSS
  - Float

#Networking

#Ops & *nix

#Testing
