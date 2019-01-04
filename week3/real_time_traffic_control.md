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

**Design dilemma 1**
The first dilemma is the number of stops. This is a dilemma between speed and accessibility of the train system. When you add stops, more people have a train stop near their house or destination. The consequence is that the average speed of the train decreases.

The main considerations are:


| Many stops |  Few stops |
| ---------- | --------- | 
| High accessibility | Low accessibility| 
| Low speed | High speed| 

Travelers prefer high accessibility. But, for the train operating companies, new stations are often not profitable. The cost of longer driving times are higher than the revenue from the new passengers. At present, in the Netherlands, there are approximately 100 requests for new stations (mostly political wishes).

Another factor to consider is the optimal stop-distance depending on the travel distance. Five levels of scale can be defined as given in the table below.

| level of scale | average distance between stops | travel distances | means of transport | 
| -------------  | ------------------------------ | ---------------- | ------------------ | 
| international | 100 km | 300 – 1000 km | high speed train |
| national | 30 km | 80 – 300 km | intercity train |
| interregional | 10 km | 40 – 100 km | express train |
| regional | 3 km | 20 – 50 km | regional train |
| conurban | 1 km | 5 – 30 km | light train/metro |

**Design dilemma 2**
The next dilemma is: How many levels of scale should you offer on one line?

In this case the definition of a 'level' is the speed difference on one line (see figure below). With two different speed variations, there are 2 levels. Speed differentiation is very important for the capacity of a rail track (more about that later). The rule of thumb is that the capacity is dependant on the number of level of scale. As you can see, the more different levels exist on one track the lower the capacity.

The main considerations are:

| more levels of scale |  fewer levels of scale |
| -------------------- | ------------------- | 
| more stations in a higher system | greater total capacity | 
| lower travel time between main stations | greater robustness of the operations | 

A well-known system with one level of scale is the metro system. All trains have the same speed, size and number of stops. This results in a high capacity and a very robust system. The downside is a relatively longer travel time between main stations. For a national train system, this is unsuitable, as it would displease the traveler (especially commuters). Therefore, a second or even third level of scale is introduced on the same tracks. These trains stop at fewer stations, reducing the travel time between main stations, which better suits traveler-demand. But, the consequence is that the total capacity goes down.

---

#### 3. Real Time Traffic Control   3.2 Timetable design   Supply Design: Dilemmas 3 and 4

**Design dilemma 3**

A next dilemma is the coupling of lines through the main station. See figure below.

![dilemma3](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/b687213f4d0a7a3290dde002b2366cf4/asset-v1:DelftX+RAIL101x+3T2018+type@asset+block/supply_design_dilemma_3.png)


1. Radial: turning of trains in the main station. (Upper line)
2. Transversal: coupling of lines through the main station, no turning of trains. (Middle line)
3. Semi-transversal: the trains don’t turn at the main station, but one or some stations further on. (Lower line)

The main considerations are:

| coupling of lines |  turning of trains |
| ----------------- | ------------------ | 
| more direct connections without transfer | balanced train occupancy | 
| less turning trains | more robustness in operation | 
| less transferring travelers |  | 

Coupling of lines are often preferable because of the positive effect on track and station capacity. Less turning trains mean that the track capacity goes up. Less transferring travelers mean fewer people on the station, thus a decrease of transport flows. This is positive for the station capacity. In addition, travelers prefer fewer transfers. A downside of coupling is that the size of the train is based on the busiest section of track. This means that there will be sections where you will run trains that are bigger than necessary. By turning trains, the train occupancy is more balanced. Semi-transversal lines are used when turning on the main station is very difficult, because of track capacity. The main example is Schiphol. There the trains run through to Hoofddorp for turning there. 



**Design dilemma 4**

The last dilemma we discuss is the choice between direct train services (without transfer) or high frequencies. In professional terms: alternating or stretched. See figure below.

![dilemma4](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/76e5b245fe02913189b30f3bc1606459/asset-v1:DelftX+RAIL101x+3T2018+type@asset+block/supply_design_dilemma_4.png)

The main considerations are:

| alternating |  stretched |
| ----------------- | ------------------ | 
| fewer transferring travelers | higher frequency on essential connection |
|  | greater robustness in operation |

When the connections are all more or less equal, we usually choose alternating. This means that travelers have fewer transfers, which is preferable. When one connection is distinctly important, we usually choose stretched lines.

The red and blue lines in the figures go from one track to two tracks. This means a high frequency is possible for the busiest connections. Travelers going off the main line will have to transfer, but the number of travelers doing so is limited. Therefore, no direct line is necessary, which frees up the track for the main lines. 

---

#### Quiz: Timetable Design

You have seen what a supply design looks like and what kind of dilemmas arise when designing one. The second step in the design process is designing a timetable for the determined supply design. As explained previously, the software places your supply design in time. The result is a time-distance diagram of your supply design. This is the timetable. The following video explains what the time-distance diagram represents.

https://youtu.be/FS4UAPoFHeM


---

#### Governance

A very large determining factor in making supply designs and timetables is the governance: the juridical and financial relations in the rail system. Those relations differ per train type. The four main distinguishable train services are international, national, regional, and freight trains. | Different train services are run by different train operating companies. These train operating companies make their own supply designs. Some companies have to make concessions. Their supply design has to meet certain requirements. There are also differences in finances. Some companies get subsidies, while others have to pay concession fees. The table below gives a quick overview of these aspects for the four main train services. 


| Kind of train service | Train operating companies | Concession | Costs train operating companies | Subsidy to train operating companies | 
| --------------------- | ------------------------- | ---------- | ------------------------------- | ------------------------------------ | 
| International | National train operating companies, in cooperation with companies from other countries | None, free market | None | None | 
| National | National train operating companies | HRN-concession - (Head Rail Network) with the Department of Transport, requirements for the main features | Concession fee (to the Department of Transport), | dividend (to the Department of Finance) | Limited, only for additional train services by regional authorities |
| Regional | Regional train operating companies | Regional concessions with regional authorities, | detailed requirements | none | Quite large subsidies from the regional authorities |
| Freight | Freight carriers | None, free market | None | None |


Notice the differences in concessions:

1. National train operating companies can make their own supply design with only some restrictions. They get requirements for the main features on the Head Rail Network (NS).
1. The supply design of regional networks is highly prescribed by the regional authorities. There are detailed requirements in the regional concessions.
1. There are no concessions for international trains and freight trains.

And notice the differences in finance:

1. National train operating companies have to pay for the concession of the Head Rail Network.
1. Regional train operating companies get subsidies from the government.
1. International trains and freight trains are free markets.


#### Core Rail vs Regional

When we look at the previous table we see that there is a large difference between national and regional trains. This is because of the distinction in the Core Rail Network and regional networks.

Look at the map below. Every train operating company must have an admittance agreement with the rail infrastructure manager and they have to pay user fees to the rail infrastructure manager for the use of the railway network. The rail infrastructure manager has a management concession with the Department of Transport and gets a management fee. Most of the smaller train operating companies are in regional areas. In this case, the Core Rail Network is run by only one company (blue) and covers the densely populated area and main connections inland.


Core Rail Network is run by companies that create supply designs according to the travel market. Most trains travel where most travelers are. This creates the most profitable operation. The government gets concession fees and dividend from the train operating companies but is not in the position to give strict requirements for the supply design.

The regional networks are often not run by the same companies as the Core Rail Network. These companies want to have a profitable operation and that is rarely possible in regional areas due to the small number of travelers. The companies are more likely to lose money in these areas. So regional networks are only profitable when subsidized. The government pays the train operating companies to make sure trains travel through these more remote areas with a regular frequency in order to accommodate the travelers. Since the government invests in these companies they also give detailed requirements for the supply design.

This division between the two networks is a logical construction and occurs in most countries. This becomes clear when considering what happens when the complete network is managed by one system.

If the regional networks are also run by the same companies that take care of the Core Rail Network, then the supply design in these areas would be created according to the travel market. This means that trains will travel at much lower frequencies or not at all. There will also be fewer stations. This is the only way that the operation remains profitable. The government does not have to subsidize anymore but the network will become very inconvenient for travelers living outside of the main urban areas.

If the Core Rail Network is given detailed requirements by the government, then the main focus would not be profit but traveler satisfaction. This means higher frequencies of trains and more stations. The result is that operations become less profitable. Therefore, the government will receive fewer concession fees and dividend from the train operating companies or would even have to pay a subsidy to the train operating company. Doing this for an entire country would make the train network far too expensive for the government.

---

#### Disruptions

Disruptions occur with varying degrees of impact, demanding an adjustable timetable. This is real-time traffic management. The main goal of real-time traffic management is to always have an executable and safe plan and to have an operational perspective for the traveler. In the next section, we will have a look how to take care of these situations using the bathtub model and predefined solutions.

Who are actively involved when handling a disruption, depends on the type of the situation. The classification of these situations is based on the scale of the impact and how much the alternative plan will deviate from the published plan. There are minor, moderate, severe and catastrophic situations. The following video will give an idea of what these types of disruptions mean and who are involved when they occur. 

https://youtu.be/S4H1wDYBkik

---

#### Adjustment Model

When a disruption occurs, the published plan can no longer be carried out. This means that an alternative plan needs to be created. This alternative plan will perform at a lower level than the published plan but is executable and safe. The alternative plan is executed, as long as the disruption is present. Once the disruption is cleared, the published plan can be reverted to again. A startup plan is created, which determines how the alternative plan is brought back to the level of the published plan.

For minor and moderate disruptions, this is done in one step. For severe and catastrophic disruptions, the difference between the two plans is too large. Therefore, a second alternative plan, performing on a level between the alternative and published plan, is executed to ease the transition.

The figure below shows the steps in a model. The blue line indicates the level of the plan. The published plan is the desired level of operation. After the disruption, the blue line goes down to the alternative plan. Once the disruption is cleared the plan is brought back to the originally published plan. The green line illustrates the execution. When a disruption occurs, emergency measures are taken to keep the execution safe. Once the alternative plan is created, the execution is performed according to this plan. After the disruption changes in execution are made to fit the new plan. The red line illustrates the measures taken during the disruption. First, the disruption is reported and alarmed. The calamity is isolated and safety measures are taken. While the disruption is being cleared, the alternative plan is executed.

---

#### Pre-defined Solutions















