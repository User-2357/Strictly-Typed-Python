# Better Python*

\* In my opinion

### Overview

A strictly-typed version of python

This is exacly the same as python, just more strict.
Use colons to denote type.

This adds:
* Scope
* Switches & cases

### Access Modifiers

Modifier|Accessible From
--------|---------------
public  |anywhere
default | same folder
private | same file

### Examples

1.

    public void function(param: int):
  
        my_variable: int = 15
        
        my_variable += 1


2.

    switch my_variable:
        case 1:
            pass
        case* 2:
            pass
        default:
            pass
