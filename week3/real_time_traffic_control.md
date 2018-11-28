#### Week 3: Introduction

If your train was the only one, life would be so much simpler. It could leave at the desired time and take you directly to your preferred destination. There would only have to be one track, one platform, no switches and (most likely) no delay. But, when millions start using the railway network, it becomes rather complex. Passengers expect to be able to travel at any time to any place, and unfortunately, both trains and the infrastructure have limited capacity.

We have local trains, intercity trains, high speed trains and freight trains, whose networks are all connected. Strategic and robust timetabling is essential to ensure comfort, reliability and safety. But that is only one piece of the operations-puzzle: if something unforeseen happens, people have to be able to adjust at the moment, in order to keep the inconvenience to a minimum. The challenge is not to make the perfect timetable on paper, but the one that is adaptable to the unexpected challenges that can happen at any moment: real-time traffic control.

---

#### Fun fact or good story?

Each week we have hidden a story related to the main topic discussed. Do you have any other fun facts affiliated to Real-Time Traffic Control? Share your knowledge on the forum below.

Trains, timetabling and time zones
Back in the 1840s, trains started to become a more common way of transportation in the United Kingdom, after the first passenger railway network was developed. Before the railways were built, communities across the UK set their clocks according to their own local time. Bristol, for example, was 10 minutes behind Greenwich Mean Time. This was fine for as long as the pace of life was governed by the natural speed of humans and horses, but the advent of a fast, structured form of transport through the railways, meant that a standardized system of time became imperative.

Various parts of the country working on slightly different, locally-agreed time posed a safety risk - not to mention, the difficulty in constructing understandable timetables. The Great Western Railway had already adopted standardized time, but it was the Railway Clearing House – a body set up to apportion financial receipts among the many private railway companies – that set the pace elsewhere. It decreed in 1847 that all railway companies should operate using GMT, and by 1855, the vast majority of towns and cities had complied. Clocks were set to a signal, set to GMT, which was sent along the newly-installed telegraph system.

---

#### Market vs Concession

While our focus during this MOOC is primarily on passenger transportation, we will sometimes look at freight transport, since it often uses the same infrastructure and is an important part of the railway network. When comparing both, the finances behind both of systems are particularly important. Where passenger transport is largely self-sufficient in dense area's (paying users), it has a wider range and also stops at remote places, which is often based on regulations from the government. This makes passenger transport supply-orientated.

Rail freight transport is in competition with the other modes of transport: truck and barge. Rail freight transport also contains several markets, for instance: automotive, chemicals, lubricants, steel, containers and dry bulk, which all have their own market dynamics and conjuncture constraints. The volumes, hinterland connections and frequencies differ between markets and regions. This means that there is a strong relationship between economic development and rail freight. As part of this economic relationship, the development of ports and logistic centers is a determining element in rail freight business. This is one of the main differences between freight transport and passenger transport. This makes freight transport demand-orientated.

For passenger transport, concessions are issued by governments and are based on regions. These concessions ensure a frequent supply of trains, even if there are no passengers. This makes the transport system user-friendly. For freight, this is not the case. If there is no demand, then there are no trains. This is a fundamental difference. Each train, track usage or container, costs money and someone has to pay for this.

While for passenger transport, railways are used for many different distances; for freight it usually is operating at a semi-long distance. The graphic below shows how money is the main factor in choosing a transport type, which is used for commercial purposes when transporting goods. Transport costs (Y-axis) are not zero for the different modes since it represents the terminal costs for loading and unloading. D1 is the break-even point of road and rail. Up until this point, transport by road is most cost efficient. D2 is the break-even point of rail and inland shipping. Beyond this point, shipping becomes cheapest. Between D1 and D2 is where rail transport gives the lowest transport costs per unit. The graph shows that for smaller distances, road transport remains the preferred mode of transport.

An exception is the new freight route from China to Europe, which has been briefly mentioned in the previous week. This new connection makes long rail transport possible. Where it might cost more than shipping, each transport has additional advantages. Where costs often are leading, time, reliability and safety are also taken into account as well as the environment. Railways are doing very well on these factors.

---

#### European Freight Network


Freight transport is an international operation. A free market requires a suitable railway network to be able to efficiently transport products. Rail infrastructure is generally developed separately in each country. Therefore, every country has its own kind of infrastructure facilities and materials. In Europe, to facilitate the free market, rail corridors are developed. These corridors are lines through multiple countries that use uniform structures and stock. This leads to a more suitable railway network for freight transport. The figure below shows these rail freight corridors.

The corridors can be strengthened in several ways. First of all, the structures and stock can be made uniform along the entire corridor. Another way is to improve the track to facilitate larger and heavier trains. This improves the capacity. The final way to strengthen the corridor is by removing bottlenecks. Bottlenecks are locations along the track, which largely limit the capacity. An example is the strengthening of the Rhine-Alpine corridor. This is done by removing the bottleneck in Switzerland: i.e. improving the Gotthard-Basis and Lötschberg tunnels. The figure below shows the pre and post situation for the Gotthard-Basis tunnel in blue and red respectively. The flat route in the new situation can accommodate longer and heavier freight trains.

Effect of corridors on infrastructure in a country
The introduction of the European rail freight corridors changed the focus of the rail network in countries from national to international. In the Netherlands, 85% of all freight transport is now international. Only 10% is national and 5 % transit. There are 3 European corridors that go to/from the Netherlands. The figure below indicates the distribution of this rail freight transport. You can see that most of the transport goes to/from the Rhine. Around 60% of the transport travels further than 300 km.

Rotterdam is the largest port of the Netherlands and the main rail freight routes are directed from there towards the hinterland. You can see this in the figure below. You clearly see a main “highway” for freight transport from the port towards the hinterland.

From this point onwards, we will again focus on passenger transport operations, looking at both time-tabling and real time traffic management.


---

#### Purpose of a Timetable

Why do we make a timetable?
There are four main reasons why we make timetables:

1. **Information to the passengers** Operational perspective for the traveler is a service provided by most public transport systems. The passengers use the timetable to plan their trip. Having a timetable allows them to do this.
2. **Allocation of resources** The timetable shows which train should be where throughout the day. This is used to determine when and where rolling stock and train crew should be ready. This cannot be scheduled without a timetable.
3. **Train traffic management** The timetable is the starting point for real-time traffic management. It is how the trains travel when everything is going according to plan. This published plan is the desired level of operation. When a disruption occurs this plan cannot be followed anymore. The traffic manager (train dispatcher) makes an alternative plan. After clearing a disruption the alternative plan is brought back to the level of the published plan.
4. **Capacity analysis** The test of the available rail capacity fits with the train traffic demand. Therefore, we use time-distance diagrams.

---

#### Design Process

Obtaining a workable timetable design isn't as simple as inputting everything into a single software package; it takes several steps and pieces of software.See figure below.

1. The first step is creating a supply design. A supply design defines how you want the trains to run throughout the available network. You decide which train you want to have at a place in the network, based on the passenger demands. The design outlines the route of the trains, where the trains stop and what the frequency of the trains is (given in the number of trains per hour). For passenger transport, making a supply design is a process of many choices.
2. Now that you have a supply design, it is time for the next step: creating a timetable design. The supply design gives the desired train frequency of trains on the network, but it does not tell you if this will actually fit. Timetabling is the placement of a supply design in time. Using timetabling software, a so-called time-distance diagram is generated showing what the supply design would look like when placed in time. If the results do not fit in time, the supply design is adjusted. The final result of this step is a workable timetable for a certain supply design.
3. The next step in the design process is to evaluate the obtained timetable. Two common evaluations are an evaluation based on passenger demand and an evaluation based on disruptions.
    1. The first evaluation matches the created timetable with the actual passenger demand. The timetable and a passenger prognosis are put in a program to determine how full the trains in the network will be. If trains are overfull or empty at places in the network, it means that the supply design needs to be adjusted.
    2. The second evaluation method evaluates the robustness of the design by randomly creating disruptions in a simulation, which is based on real-life cases. If the disruptions naturally dampen, then the design is sufficient. When the timetable passes all evaluation methods it is considered good enough to be executed.
4. Now that we have a definitive timetable, all sub-processes need to be scheduled. These are all the processes required to actually execute the timetable. Employees are needed, trains need to be coupled and decoupled at the right time, etc. This is called micro timetabling. Once this step is completed, the process is finished and we have obtained a workable and executable timetable for the network.

---

#### Supply Design: Introduction

The supply design defines how the trains will run throughout the network. Specifically, it outlines:

1. The route of the trains,
2. Where the train stops,
3. The frequency of the train (how many trains per hour).

It is not yet a timetable. That is the next step.

Below, you can see an example of a supply design.

This is based on the  Programme Train Transport with High Frequencies in the Netherlands, which will be discussed in more detail later this week. This is just to give you an idea of the complexity of a dense network.

You see high-speed lines (green), Interstate lines (blue) and Local lines (red).

For passenger transport, making a supply design is a process of many choices because there are many criteria to take into account.

Sometimes, these criteria conflict, and sometimes criteria are not fully rational, such as political wishes. Therefore, most supply designs are hand-crafted and supported by many tools for evaluation. There are some developments, using Artificial Intelligence, but they have not yet been particularly successful.

In the next units, we will discuss several design dilemmas related to timetabling.

---

#### Supply Design: Dilemmas 1 and 2

Design dilemma 1
The first dilemma is the number of stops. This is a dilemma between speed and accessibility of the train system. When you add stops, more people have a train stop near their house or destination. The consequence is that the average speed of the train decreases.

The main considerations are:


| Many stops |  Few stops |
| ---------- | --------- | 
| High accessibility | Low accessibility| 
| Low speed | High speed| 

