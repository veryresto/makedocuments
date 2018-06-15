# Core Network Simulation System

## Cellular Core Network
Core networks are implemented similarly from one another. Generally, core network comprises S-GW and P-GW.

TWAMP based measurement is conducted between NEs to acquire network metrics. Those are collected in measurement server and processed in simulation server.

## Simulation Server
Receiving input from measurement server. It maps network metrics to user level performance metric. The mapping process is mainly conducted by using simulation.

Kriging is implemented to ease the burden of simulation process. It only use sinulation results.

## Simulation Model
