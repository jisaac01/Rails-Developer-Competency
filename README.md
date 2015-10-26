<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Ruby](#ruby)
  - [General](#general)
  - [Metaprogramming		](#metaprogramming)
- [Tools](#tools)
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
- [Patterns](#patterns)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

Rails Developer Competency

What does it take to call yourself an expert in the Ruby on Rails stack? If you wanted to level up your game, is there a comprehensive list of *everything* that you could know? What dark corners of ignorance do you have? I'm trying to capture a list here of all of the things an expert might know.

*NOTE* this is a list of possible knowledge. Expertise is not knowledge only. It requires experience and practice as well. Just as I wouldn't consider someone who memorized everything here an expert, I wouldn't consider someone who had 10 years of practice making Rails scaffolds an expert either.

#Ruby
##General
- strings/symbols		
- Array		
- Hash		
- splat (*)		
- block/proc/lambda		
-- scopes/closures	
-- yield	
-- return	
-- arity	
- exceptions		
-- custom	
-- rescue	
- Class		
- Module		
- Include vs Extend vs Prepend		
- Constants (& namespacing)		
- Enumerable: map/each/inject/select/sort		

##Metaprogramming		
- method_missing		
- define_method		
- Class.new & Module.new		
- instance_eval & instance_exec		
- methods & instance_methods		
- UnboundMethod		

#Tools
- Gems		
-- appraisals & gem testing		
-- create a new gem		
-- Symmantic Versioning		
- Bundler		
-- Gemfile/Gemfile.lock		
- ruby-toolbox  

#Rails
* Controllers
  * respond_to: format.js, html, json
* Views
  * form_for, form_tag, remote, link_to, button_to
  * Turbolinks

#Rubymine
* shortcuts
* running tests
  * editing configurations
  * working directory
  
#PostGres
* \connect DBNAME
* \l
* \d
* 

#MySQL

#JavaScript

#Git

#CSS

#Networking

#Ops & *nix

#Testing

#Patterns
- Strategy
- SOLID
- Fat Models/Skinny Controllers/Dumb Views
- Service Objects
- Query Objects
- Interactors
- Presenters
- Decorators
