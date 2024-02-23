# <p align="center">MDP REPRESENTATION</p>

## AIM:
To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:

### Problem Description :
Plants are important due to its various beneficial factors. So it is necessary to take care of them. With reinforcement learning we can train a agent to ensure the growth of a saplings.</br>
![image](https://github.com/Jovita08/mdp-representation/assets/94174503/7dedc3d6-eeab-4985-b2f1-12256e9274b7)

### State Space :
{Dead, Sapling, Plant} -> {0,1,2}

### Sample State :
Sapling

### Action Space :
{Pouring water on regular interval, not pouring water} -> {0,1}

### Sample Action : 
Pouring water on regular interval

### Reward Function :
```
R={ +1 , on pouring water regularly
     0 , otherwise
  }
```
### Graphical Representation :
![image](https://github.com/Jovita08/mdp-representation/assets/94174503/a3defe66-146a-4833-ba5d-80158d97094d)

## PYTHON REPRESENTATION:
Developed By : **MOHAMED ASIL M**
</br>
Register No. : **212222230080**
```py
P={0: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 0, 0.0, True)]},
   1: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 2, 1.0, True)]},
   2: {0: [(1.0, 2, 0.0, True)],
       1: [(1.0, 2, 0.0, True)]}
  }
```
## OUTPUT:
![image](https://github.com/Jovita08/mdp-representation/assets/94174503/5df18586-d161-4d48-8479-68480b57ab1c)

## RESULT:
Thus, a real-world problem is represented in MDP form.
