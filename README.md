# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:
A customer is planning to buy a product online. They have three websites to choose from: Option A, Option B, and Option C. The customer wants to select the best website based on their preferences and the associated rewards.

### Problem Description
choosing the best website to buy

### State Space
The state space consists of the different options available for the customer to choose from:
```
State 0: Website A
State 1: Website B
State 2: Website C
```

### Sample State
A sample state could be the customer currently considering website B.

### Action Space
The action space consists of the decisions the customer can make:
```
Action 0: Stay with the current option
Action 1: Switch to the next option
```

### Sample Action
A sample action could be the customer deciding to switch from Website A to Website B.

### Reward Function
```
The customer receives a reward of 0 for staying with the current option.
If the customer switches to the last option (Website C), they receive a reward of 1.
There are no intermediate rewards for other actions or states.
```

### Graphical Representation
![REINFORCEMENT LEARNING 1](https://github.com/Asilsathik/mdp-representation/assets/119476247/b89cba12-e89c-4bcb-8675-9aea92d998c4)



## PYTHON REPRESENTATION:
``` 
#Name: Mohamed asil
#Reg No: 212222230080

T = {
    0:{
        0: [(0.8, 0, 0.0, True), (0.2, 1, 1.0, True)],
        1: [(0.8, 1, 1.0, True), (0.2, 0, 0.0, True)]
    },
    1:{
        0: [(0.8, 0, 0.0, True), (0.2, 2, 1.0, True)],
        1: [(0.8, 2, 1.0, True), (0.2, 0, 0.0, True)],
    },
    2: {
        0: [(0.8, 1, 0.0, True), (0.2, 2, 0.0, True)],
        1: [(0.8, 2, 0.0, True), (0.2, 1, 0.0, True)],
    }
}
T
```


## OUTPUT:

![Screenshot 2024-02-23 100417](https://github.com/Anas536/mdp-representation/assets/139841834/0adaf3eb-2353-4121-a694-125a7a1d8c66)


## RESULT:

Thus the given real world problem is successfully represented in a MDP form .

