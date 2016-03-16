# Routing Version 2
This is a slightly harder version of Routing V1 due to the implementation of one way path's.

In this problem you must build and transverse a network of nodes and report in the fastest route between nodes, (Or fastest routes if there is more than one.)

## Input
### Format
```
Node-Name-One Node-Name-2 Directions
... ... ...
Node-Name-OneHundred Node-Name-OneOhOne Directions
0 0 0
Start-Node End-Node
... ...
Start-Node End-Node
0 0 0
```

### Where:
Node Names is a string with no spaces.
Directions indicates if it is one way (First -> Seccond) or two way (First <-> Seccond)
Directions will be either '1' or '2'
Then you will receive the place you need to start from and end at.
Groups of input will be ended with '0 0 0'

## Output
Source: Start-Node
Dest: End-Node

When you find a single route output:
```
Route Found: Source -> Node -> ... -> Node -> Dest
```

When you find more than one routes:
```
Found # of routes for Source -> Dest:
Route 1: Source -> Node -> ... -> Node -> Dest
Route 2: Source -> Node -> ... -> Node -> Dest
...
Route 100: Source -> Node -> ... -> Node -> Dest
```

When you can not find ANY routes:
```
No routes found going from Source to Dest!
```
