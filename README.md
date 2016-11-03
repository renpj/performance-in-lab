# performance-in-lab
A general framework for sharing and comparing the performance of frontier techniques in laboratory, such as catalyst activity, photocatalytic water splitting.

## HER (Hydrogen Evolution Reaction) as example
The most important parameters and criteria are
* electrolyte
* electrode material or catalyst
* current vs potential
* Tafel slope
* stability： loop + potential vs reserved performance

Each item has these attributes：
* name: string 
* type: choice, can be "choice", "string", "object", "number"
* decription: text
* source: string or foreignkey

Valid user can add new performance to certain technique or build a new evaluation. For the problematic items, user can submit a modification request or post a comment.

## About
The project use django website framework. 
