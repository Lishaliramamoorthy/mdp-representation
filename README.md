# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP

## PROBLEM DESCRIPTION:
Imagine a smart city with multiple traffic intersections that need efficient traffic signal control to minimize congestion and reduce travel time for vehicles.

### State Space
state_space = {
    "Intersection1_Traffic": ("Low", "Moderate", "High"),  
    "Intersection2_Traffic": ("Low", "Moderate", "High"),
    # Additional intersections and relevant states
}



### Sample State
sample_state = {
    "Product1_Inventory": 8,
    "Product2_Inventory": 12,
    "Product3_Inventory": 5,
    "Demand_Forecast": 10
}


### Action Space
action_space = {
    "SignalChange_Red": 0,  
    "SignalChange_Yellow": 1,
    "SignalChange_Green": 2
}



### Sample Action
sample_action = {
    "OrderProduct1": 2,
    "OrderProduct2": 3,
    "OrderProduct3": 1,
    "NoOrder": 0
}


### Reward Function
reward_function = {
    "TrafficFlow": +1,  # Reward for smoother traffic flow
    "WaitTimePenalty": -0.5,  # Penalty for increased waiting time at intersections
}


### Graphical Representation
Write your answer here

## PYTHON REPRESENTATION:


## OUTPUT:


## RESULT:
Write your output here

