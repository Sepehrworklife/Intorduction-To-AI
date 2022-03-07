# Search
### Agent
Entity that perceives its environment and acts upon that environment 
e.g: car in google map
### State
A configuration of the agent and its environment.
### Intial state
The state in wich the agent begins.
### Action
Choices that can be made in state.
### Actions
Action(s) returns the set of actions that can be executed in state (s) 
e.g Slide tile up or down.
### Transition model
A description of what state results from performin any applicable action in any state.
RESULT(s, a) returns the state resulting from performing action (a) in state (s).
### State space
The set of all states reachable from the initial state by any sequence of actions.
e.g: Individuals states and arrows that connect states to each other.
### Goal test
Way to determine whether a given state is a goal state.
May have multiple goal states.
e.g: Arrived to the destination in map.
### Path cost
Numerical cost associated with a given path.
e.g: Traffic in map.
### Solution
A sequences of actions that leads from the intial state to a goal state.
### Optimal solution
A solution that has the lowest path cost among all solutions.
### Node
A data structure that keeps track of 
- A state
- A parent (node that genrated this node)
- An action (action applied to parent to get node)
- A path cost (from initial state to node)

