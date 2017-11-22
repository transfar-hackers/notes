# how to handle a front-end project

## experience based on *b2b-online-shopping-mall* front-end project

# before start

## developping environment
1. choose an OS, Linux and MacOS preferred
2. choose a proper IDE, Sublime Text 3 and Visual Studio Code preferred
3. choose a version control tool, git + GitHub preferred
4. choose an HTTP forwarding / proxy tool, nginx preferred

## setup developing environment
5. it's better to have a **strict** restriction before-hand, this saves time and efforts
6. **restrictions** includes:
  *IDE used
  *IDE plugins used and settings
  *IDE configurations applied
  *Code styles(indents, tabs, wraps, blanks, functions, variables, statements...), ESLint
  recommended
7. HTTP forwarding / proxy tool --> for cros-domain-request and more
  * install and setup nginx
  * server blocks
  * server names
  * proxy_pass
  * /etc/hosts
8. make sure all team members have understood the setups, write down special settings 
when necessary

## based on the scenario and business requirements, setup developing framework
9. if we have to create our own framework, make sure **every team member understands the source codes**.
**IMPORTANT: outline coding styles and make sure every team member understands it and rely on it**
10. if we use existing frameworks, we should apply *best practise* of it, frameworks usually have a
*best practice* section

## last words
**It's better to have a STRIC restriction before-hand --> that saves a lot headaches**
*A strict restriction requires that the senior developer / team lead having much more experience*

# during development
10. senior developer / team lead should focus on:
  * coordinates with other parties(product manager, Prototype, UI/UX and other development teams if necessary)
  * the organization(structure) of the source codes
  * maintain a good development environment, solve the environment problems in advance
  * solve critical technical problems in advance
  * write out critical source codes(such as framework of the whole project, common components, common usages of 
  critical features of the framework)
  * should teach team member with new techniques used in this project, and hand out related tasks as soon as
  team members understands how to do it
  * should decide priorities, and always solve high priority problems first
11. framework --> components --> pages --> integrate with backend APIs
  **make sure every backend API has its own set of mock data**
  
# source code version control
12. always update local codes before writing new codes
13. check in codes as soon as you made some progress and tested
14. test and check in codes before EOD
15. add comments whenever commiting any codes

# for testing

# last words
**TEAM WORK, Compromise and Open mind**

  
@author: jack sparrow
@date: 2017-11-20 20:15 p.m.

