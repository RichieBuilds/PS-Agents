## Designing a Searching Agent

# PEAS Framework of self driving track
1. Performance Measure - Safety, fuel efficiency, time optimization, successful follow of the traffic laws, minimal damage to the goods it carries and delivery of cargo on time.

2. Environment - kenyan highways connecting Nairobi, Central , Rift valley and lake Victoria, wildlife, human drivers , changing road conditions, pedestrians, traffic lights, traffic signs and road surfaces.

3. Actuators(components the agent uses to take action) -  steering system, accelerator, break system, indicators, horn, light, gear control

4. Sensors(Components the agent uses to take information from the environment)- cameras, GPS system, speed sensor, weight and load system

## Defining the environmet
1. Fully observable vs Partially observable
- The environment for this agent is partially observable
- Because the agent cannot observe everything in its environment something like in a sharp may hide a pedestrian or a car also a road hazard maybe outside the sensors view

2. Deterministic vs Stochastic
- Classification - Stochastic
- Because the outcome is not always predictable even if the agent follows a specified route unexpected accident may make the journey longer or unexpected weather may halt the journey abit. So there are things that the agent can't control

3. Episodic vs Sequential
- classification - sequential
- Because the each decision by the agent affects future decisions like choosing one path decides the next town you will arrive at.

4. static vs dynamic
- Classification - Dynamic
- Because the environment changes while the truck is operating. Other vehicle move, obstacles may appear so the environment is dynamic

5. Single agent vs Multi agent
- Classification - Multi agent
- Because the agent is operating with other agents in the road like human drivers, pedesrtians and other self driving car. So the agent is not operating on its own hence its a multi agent
