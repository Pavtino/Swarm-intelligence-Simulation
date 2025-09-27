## <center>Swarm Intelligence for Decentralized Logistics</center>

## Project Description

This project is a web-based simulation of a decentralized logistics or resource-gathering system, inspired by the collective behavior of social insects like ants or bees. The simulation demonstrates how a swarm of simple, autonomous agents can cooperatively solve a complex problem resource collection and delivery without a central command or global knowledge.
The core principle is swarm intelligence, where each agent follows a set of simple, local rules. These local interactions, in aggregate, give rise to a highly efficient and robust global system.

## Core Components
<ul>
<li><bold>Agents (Foragers):</bold> Small, mobile circles that move around the environment. They have a state, such as 'searching' or 'carrying'.</li>
<li>Resources: Static circles representing items that need to be collected and delivered to a central hub.</li>
<li>Hub: A central point where agents deposit collected resources.</li>
<li>Local Rules: The agents' behavior is governed by simple rules. For example, when searching, an agent moves randomly. When it "sees" a resource, its rule changes to move directly towards it.</li>
</ul>
## Getting Started
To run the simulation, simply open the index.html file in any modern web browser.

## Key Features of the Baseline Code
<ul>
<li>Canvas-based Visualization: The entire simulation is rendered on an HTML <canvas> element.</li>
<li>Agent and Resource Classes: The code defines Agent and Resource objects to manage their state and behavior.</li>
<li>Simple Movement Logic: Agents use basic vector math to move and seek out resources.</li>
<li>State Transitions: Agents change their behavior based on their proximity to resources and the hub.</li>
Potential Next Steps
 </ul> 
  
This baseline code serves as a minimal working example. Here are some ideas for how to expand it:
<ul>
  <li>Pheromone System: Add a digital trail system where agents "drop" digital pheromones to guide other agents to resources or the hub.</li>
<li>Complex Obstacles: Introduce obstacles or a more complex map that agents must navigate around.</li>
<li>Adversarial Agents: Add a "rogue" agent that attempts to disrupt the system to test the swarm's robustness.</li>
<li>UI Controls: Add buttons or sliders to control the number of agents, resource density, or agent speed.</li>
