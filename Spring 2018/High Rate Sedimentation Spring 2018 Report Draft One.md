# High Rate Sedimentation, Spring 2018
#### Mike Zarecor, Sneha Sharma, Justin Conneely
#### March 9th, 2018

## Abstract
Past High Rate Sedimentation (HRS) teams have hypothesized that floc blankets thin as experiments progress due to coagulant sticking to the walls of the flocculator, reducing the overall coagulant dosage. The Spring 2018 team conducted experiments that found increasing coagulant dosage did not prevent floc blanket thinning. The team also found that increasing tube settler length and reducing flocculator shear had minimal effects on floc blanket thinning.

<div class="alert alert-block alert-danger">
Consider using "Spring 2018 team."

Instead of "The team has conducted" use "The team conducted" for conciseness and clarity.

Consider "conducted an experiment to test whether" instead of "conducted an experiment to test if."

Instead of saying "this problem," use that space to reiterate what the problem is i.e. "increasing the caug dosage replenishes the overall coag dosage and leads to stable floc blankets."

What is the point of the last sentence? If not significant, consider removing.
</div>

## Introduction
Sedimentation is a critical process for water treatment plants. It is the process by which coagulated minerals, dirt, clay, and other particles are removed from the water via gravitational settling. In a sedimentation tank, water flows upward as flocs settle downward. The particles settle into a "floc blanket" - a fluidized bed of suspended solids colliding in a bottom zone of the sedimentation tank. The particles are initially light and small, but as coagulant dosage persists and particles continue to collide,  the particles clump together into heavier floc that will settle into the basin of the recirculator. This process permits clearer water to continue up the plate settler, resulting in a lower effluent NTU (Nephelometric Turbidity Unit, a measure of clarity).

<div class="alert alert-block alert-danger">
Check definition of floc in the third sentence. Aren't you describing a floc blanket there?

Clarify that it is the sedimentation tank not just a tank.

In the last sentence, you mention "water to continue up the plate settler." Students not exposed to sedimentation would not know that the flow is upwards in a sed tank. Consider mentioning that the water is flowing upwards as flocs settle downward to explain this phenomena.
</div>

AguaClara's sedimentation tank design includes inclined parallel plates called plate settlers. The purpose of these plates is to provide a settling surface for small particles and return them to the floc blanket developing in the base of the tank. Plate settlers work by changing the direction of flow from vertical to an angle. This change reduces the y direction velocity, allowing for more particles to settle before leaving the sedimentation tank. The defining paramater of a plate settler is capture velocity. Capture velocity is the minimum velocity a particle must be settling at in order to be captured by the plate settler.

In the AguaClara lab, a sedimentation tank and its respective plate settlers are simulated by plastic piping, and is called a tube settler. The tube that simulates a pathway of fluid in the tank is referred to as the "recirculator" by the HRS team. See figure 1 for a visual representation of these designs.

<div class="alert alert-block alert-danger">
When you say "the purpose of these plates is to catch small particles and return them to the floc blanket," the purpose of plate settlers may be misrepresented to people not exposed to sed tanks. The theory behind plate settlers (fluids etc) is also really difficult to understand without 4540. So maybe try to explain how plate settlers work in different terms. I take most objection to the word catch because it evokes an idea of intercepting particles against a surface, when my understanding is that the flow near the plat settlers slows down and that decrease allows the particles in the flow to approach their settling velocity and settle out the water. This is may be something to look further into (correct me if I am wrong).

Are the plate settlers simulated by tubing or by clear pvc pipes?

Consider defining the acronym HRS in the abstract and then using it throughout.
</div>



<div class="alert alert-block alert-danger">
A better representation of how plate settlers work here!!!

Why include the word aggregate if you are only going to define the term. Cut out unnecessary words.

Also the name definitions "Recirculators" and "tube settlers" are hard to visualize without a diagram. Maybe label these things on the diagram below?
</div>

![SedimentationTank](https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Figure%201.JPG)
Figure 1: Comparison of sedimentation tank in an AguaClara plant vs. in an AguaClara lab.

The recirculator and tube settler simulate the sedimentation tank basin and plate settlers respectively. Since the behavior of a section of fluid is characteristic of the entire tank, tubing can be used to simulate a simple pathway in the reactor. This allows for a practical form of experimentation that is small scale, easy to manipulate, and representative of the respective tank design.

<div class="alert alert-block alert-danger">
I am having mixed feelings about this figure caption. It provides excellent insight into the assumptions of the experimental Apparatus (like crazy and important insight). Why is it in a figure caption and not in the body of the text?
</div>

AguaClara designed a vertical sedimentation tank, which has the water flow from the bottom of the tank to the top. The flow velocity that maintains the floc blanket is known as overflow rate or upflow velocity. Flow rate (Q), upflow velocity (V), and tank surface area (A) are related to the continuity equation:

$$ Q = V * A $$

The HRS team hopes to design a tank that will yield an effluent of 0.3 NTU or lower with maintaining high upflow velocity. While the World Health Organization has a standard of at most 1 NTU for drinking water, the EPA standard is 0.3 NTU. AguaClara currently achieves this with an upflow velocity of 1 mm/s, but not at upflows of 3 mm/s or greater. A larger upflow velocity would allow for a reduction in treatment plant size, which would reduce construction costs.

<div class="alert alert-block alert-danger">
Delete the "AguaClara" from "AguaClara HRS team"

This last paragraph really shows the importance of HRS. Major key

**Only thing missing is your specific research focus (like what are you doing with the sedimentation to get it to be high rate i.e. changing the geometry/angle of plate settlers)**
</div>
Response to comment: "high rate sedimentation" refers to the rate at which water flows in the plant (upflow velocity), not the rate of the sedimentation process itself.

## Literature Review and Previous Work
Past researchers have studied sedimentation and floc blankets. Their research provides valuable information for the Spring 2018. Culp et al. (1968) used tubes to figure out the optimal slope of the tube settlers. Under laboratory conditions, a 60 degree angle with respect to the horizontal provided continuous sludge removal while showing effective sedimentation performance. This information was used by the Fall 2017 team when designing the tube settler currently being used by the Spring 2018 team.

<div class="alert alert-block alert-danger">
Is there a better transition into this section than the current first sentence?
</div>

Hurst (2010) stated that the presence of the floc blanket would enhance the removal of particles. These experiments found that upflow velocities of 1.0 to 1.3 m/s produced the best performance. Past high rate teams have been successful in establishing floc blankets at higher upflow velocities than Hurst’s optimal range, but unable to create stable floc blankets.

<div class="alert alert-block alert-danger">
Are all particles "turbidity causing particles"? Watch out for redundant phrases

In regard to previous teams' attempts at reproducing findings at higher flow rates, does this mean that Hurst was able to develop a stable floc blanket or that the past teams were trying to develop a stable flc blanket using Hurst's findings for lower velocities as a starting point?
</div>

Swetland (2014) Found that as flocs formed, they would settle due to their higher density compared to water. In order for particle removal to occur flocs must settle faster than the capture velocity. As the flocs concentrated and fell down to the bottom of the tank, a floc blanket formed. These findings defined the High Rate Sedimentation teams's understanding of a floc formation, which is a critical step of the AguaClara sedimentation process.

<div class="alert alert-block alert-danger">
What does "sediment" mean as a verb in the first sentence?

Why must flocs settle faster than the upflow velocity?
</div>

Balwan (2016) explored the effect of the length of tube settler on effluent turbidity. As indicated in his report, increasing the length of tube settlers increased the percentage of turbidity removed (defined as percentage change between influent and effluent turbidity). With tube settlers in 45 degrees inclination angle and 60 cm length, turbidity removal was measured to be 80 percent. However, his experiments only had three length variables (40cm, 50cm, 60cm) and the effluent of longer tube settlers were unknown.

The Fall 2017 High Rate Sedimentation team experimented with varied sedimentation tank geometries in an attempt to find a configuration that allowed for stable floc blankets. They were unsuccessful; however, they found that they could not reestablish floc blankets mid experiment, and that headloss increased as the experiment progressed. This led to their floc accumulation hypothesis. This hypothesis suggests that coagulant and flocs sticks to the inside of the flocculator tubing, reducing the effective dosage of coagulant and reducing the effective diameter of the tubing. The Spring 2018  team began by testing this idea.

 <div class="alert alert-block alert-danger">
The term "floc accumulation hypothesis" makes it seem like the coagulant is sticking to the flocs/particles rather than the tubing?

Again you see a switch from "Semester Year Team" format to "2018 spring team." Use "Spring 2018 team."
 </div>

## Methods
### Experimental Apparatus
The overall lab bench set up of the HRS team is composed of several parts (Figure 2). These parts include the pumps, the stocks, the flocculator, and the turbidimeters.

<div class="alert alert-block alert-danger">
Check Figure Number
</div>

<img src="https://raw.githubusercontent.com/JustinConneely/Personal/master/Images/Lab%20Bench%20Setup.png" height250 width=400>

Figure 2: The HRS lab bench setup is composed of the turbidimeters, stocks, pumps, and a flocculator.

This system allows the team to simulate non-potable water and its treatment through high rate sedimentation while keeping track of performance via NTU. The influent and effluent turbidimeters record system performance at any given time. In order to run experiments, tap water is contaminated with clay from the clay stock. This contaminated water is called the influent. It is kept at a constant turbidity of 100 NTU through ProCoDA's PID control. For more on clay dosing, see the Manual.

<div class="alert alert-block alert-danger">
Consider "The influent and effluent turbidimeters record system performance at any given time."

Read through report in the future and edit out unnecessary words.

Please watch capitalization "contaminated from the Clay stock"

Cut unnecessary words out of "This contaminated water is known as the influent and is kept at a constant NTU of 100 through ProCoDA by utilizing PID control."

Capitalization issue on "Clay dosing" (Clay is not typically a proper noun unless you're talking about American Idol alum Clay Aiken)
</div>

Once the influent passes through the turbidimeter, it moves through the flocculator. Upon entering the flocculator, the untreated water is dosed with the coagulant Poly-Aluminum-Chloride (PACl). The coagulant pump is manually set up to control how much of the Coagulant stock enters the system. When a dose is chosen, the team uses a python markdown file to determine the stock concentration. Additionally, the markdown file is used to determine number of rotations per minute (RPM) required for the pump to achieve the desired concentration of coagulant inside of the system. For more on coagulant dosing, see the Manual. The treated water then passes through the coiled tube that is the flocculator, which allows for the formation of flocs. After passing through the flocculator, the flow then enters the bottom of the recirculator where upflow begins. The effluent that exits through the top of the tube settler then flows through the effluent turbidimeter. This is where the turbidity of the effluent is determined; the goal is to reach an NTU of 0.3 or lower. After flowing through the effluent turbidimeter, the wastewater flows out of the system and is discarded.

<div class="alert alert-block alert-danger">
Is "Poly-Aluminum-Chloride (PAC)" the conventional name? (Hint: the acronym has a hidden l to denoate chloride)

The second sentence has more unnecessary words. Consider "Upon entering the flocculator, the untreated water is dosed with the coagulant PACl."

Watch capitals "Coagulant"

Avoid the word "is"

"doc" is too informal, it can be more accurately referred to as a markdown file

Is the history of MathCAD important enough for this report?

Define RPM (and how that relates to dosing, not evident for people not associated intimately with the experimental setup)

Does the end of the flocculator enter the bottom of the recirculator or does the flow?

The last to sentences paint a murky picture. Where is this waste you speak of? Where did it come from? Where is it located?
</div>

Most particle removal teams are currently utilizing the HRS standard apparatus design and a flocculator designed by the High G Flocculation Fall 2017 team. The flocculator’s purpose is to mimic the flocculation process in an actual AguaClara plant with a sufficient collision potential (G). The High G flocculation team has provided information, listen in  the following table, on the flocculator’s dimensions that allow the team to reach an upflow velocity of 3 mm/s.

<div class="alert alert-block alert-danger">
Are all particle removal teams using this apparatus design? Would be a false claim if even a single particle removal team was not using it.

Last sentence is unclear. What are you trying to say?
</div>

| Parameter | Meaning | Value |
| ----- | ------------------------ | ----- |
| V.Sed | Sed Tank Upflow Velocity | 3 mm/s |
| D.Sed | Sed Tank Inner Diameter  | 1 in  |
|Q.Sed, Q.Reactor| Flow rate (from V.Sed) |1.52 mL/s|
|D.Floctube|Floctube Inner Diameter| 0.17 in |
|R.c|Radius of Curvature of Floc Coils|5 gm|
| Gtheta | G*theta | 20,000 |
|  G  |  Shear   |  175.5 Hz  |
|Theta |Residence Time | 1.899 min or 113.9 s|
| L.Flocc| Length of Flocculator Tubing|11.821 m|
|Epsilon.Flocc |Energy Dissipation Rate| 30.814 mW/kg|

Table 1: The HRS lab bench setup consists of a flocculator developed by the High G Flocculation Fall 2017 team. The above are the parameters and resulting values of the current flocculator design.

### The Standard Design

This section contains the theories, steps, and progress the Fall 2017 team followed in order to fabricate the five reactors that all particle removal teams are to use for their experiments (flouride removal, high G flocculation, etc.). For more information on the work that these teams are involved in, see AguaClara’s Github page.

Design: The geometry of the apparatus is based on the concept of ”capture velocity.” Capture velocity is the slowest moving particle that an area can capture and is a property of the sedimentation tank. In other words, the greater a particle’s terminal settling velocity, the less distance it must travel and the more likely it is to be captured. Terminal settling velocity is reached when the frictional force (viscous shear) of the fluid, combined with the buoyant force, balances with the gravity. The larger the diameter of a particle, the greater its terminal velocity. This relationship may be shown through Stoke’s Theorem as seen in the following formula:

$$ V_t = \frac{d^2g}{18v} ∗ \frac{ρ_{floc} − ρ_{H_2O}}{ρ_{H_2O}} ... (2)$$

Where d is the diameter of the pipe, g the gravity force, v is viscosity and ρ represents the different densities of the water and the floc.

On the other hand, capture velocity depends on the dimensions of the apparatus being used, as one can see in the following formula:

$$ V_c = \frac{SV_αsinα}{Lsinαcosα+S} ... (3)$$

Where α is the angle of the tube settler, V<sub>α</sub> is the upflow velocity, L is the length of the tube settler (after the floc weir), and S is the diameter of the tubing. If a floc has a terminal settling velocity that is too low, it will not be captured and instead will escape with the effluent.

<div class="alert alert-block alert-danger">
Weird separation above (maybe pressed enter accidentally?)

Need to proofread.
</div>

A floc blanket has the potential to climb up to the weir, so the distance after the floc weir is used as the active length of the tube settler in the capture velocity calculation. In the case of the standard design, with an effective length of 27.08 cm, the resulting capture velocity is .462 mm/s. In order to be consistent with previous research teams, the tube settler is at a 60<sup>o</sup> bend in relation to the x-axis in the Fall 2017 model. Also, the inner diameter is set to 1 inch rather than 3/4 inches.

<div class="alert alert-block alert-danger">
Why did you decide to use a 1" diameter pipe rather than 3/4"?
</div>

<img src="https://raw.githubusercontent.com/JustinConneely/Personal/master/Images/Screen%20Shot%202018-03-08%20at%2011.53.45%20PM.png" height250 width=400>

Figure 3: A diagram of the active tube settler length L, the inner diameter of the apparatus S, and the angle α.

###Materials

In the Fall 2017 model, the floc weir—a floc drainage pipe that keeps the floc blanket at a stable height—is welded onto the tube settler rather than the recirculator and the apparatus is enclosed by compression fittings. The reason for an intermittent floc weir on the tube settler is due to the findings of the Summer 2017 team. If a floc blanket could be established with a low bend, then further investigation is required on whether multiple bends characteristic of the trapezoidal apparatus are necessary for performance, or just keep essential  flocs low and recirculating.

<div class="alert alert-block alert-danger">
Maybe make "Materials" a heading?

What is the floc weir? Is it defined earlier? Define it at first reference.
</div>

<img src="https://raw.githubusercontent.com/JustinConneely/Personal/master/Images/Screen%20Shot%202018-03-08%20at%2011.53.29%20PM.png" height250 width=400>

Figure 4: The standard design includes a 50 cm recirculation zone, a 36.47 cm tube settler, an a 40 cm long floc weir. The inner diameter of the PVC tubing is 1 inch rather than 3/4 inches like previous
semesters.

Compared to previous semesters, the size of the apparatus has been reduced a considerable amount.
It is important to note that the team’s goal is not necessarily to reduce turbidity more than what the trapezoidal design with multiple in-line tube settlers was able to achieve, but rather to investigate possible alternatives to sedimentation tank design in order to avoid the complex geometry that the trapezoidal design implicates. Since the tubing size increased from 3/4 inch to 1 inch, the flow rate of influent water had to be altered in order to achieve the 3 mm/s upflow velocity that is unique to high rate sedimentation. The following equation is used in order to help the team determine these values:

<div class="alert alert-block alert-danger">
You mention a "trapezoidal", what does that mean? Who did that and why?

Explain why it simplifying geometry is important (save $$)
</div>

$$ V_{floc} = \frac{Q_{floc}}{\frac{D^2_{pipe}}{4} ∗ π} ... (4) $$

Where Q<sub>floc</sub> is the volumetric flow of water through the system and D<sub>pipe</sub> is the inner diameter of the PVC pipe.

### Procedure
####Experiment 1
Using the aforementioned set-up, the HRS team tests the effect of increasing coagulant dose on floc blanket degradation and effluent turbidity. This is tested by first flushing the system to assure it was clean of coagulant and clay particles, then stabilizing the influent turbidity at 100 NTU by dosing clay using the PID control in ProCoDA. Then the team tests varying doses of coagulant with a constant upflow velocity in the sedimentation tank of 3 mm/s (experimentally extrapolated from an RPM of 28.3); this value was chosen as the team's experimental parameter. The first experiment is conducted at a coagulant dosage of 1.4 mg/L, as that was the minimum effective dose of coagulant in treatment plants. The corresponding coagulant pump RPM is 20. That initial coagulant dose was then increased incrementally, then tested under the same conditions as above.

<div class="alert alert-block alert-danger">
Where did you get the coagulant dosing from? How do you make 100 NTU water? Need to justify all values in experimental set-up.
</div>

####Experiment 2
Using the same general experimental set-up as the first experiment, the team designed a 930 mm tube settler to decrease the capture velocity of the sedimentation tank from 0.36 mm/s to 0.15 mm/s. After running a test with this set-up, the team also changed the flocculator to a 3/16 inch design provided by High G Flocculation to replace 1/8 inch tubing flocculator.
<img src="https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/long%20tube%20settler.png" height250 width=400>

Figure 5: Sedimentation tank with the 930 mm tube settler.

## Results and Analysis
###Experiment 1
The floc blanket serves as a filter, decreasing the effluent turbidity of water flowing through the sedimentation tank. Therefore, a decrease in effluent turbidity is directly correlated to the presence of a floc blanket.

Prior to experimentation, the Spring 2018 HRS Team hypothesized that the floc blanket degrades as a result of the coagulant adhering to the walls of the flocculator tubing. Thus, it was predicted that increasing the concentration of the coagulant would compensate for the amount of coagulant  sticking to the tubing's walls, resulting in a sustainable floc blanket and a consistently low effluent turbidity. The hypothesis was tested by varying the coagulant dose with respect to time over a period of 24 hours.

Increasing the PAC dose led to a lower effluent turbidity, but only until a dose of 4.2 mg/L was reached. This can be seen in figure 5. Floc blanket decay can be correlated to changes in effluent turbidity readings. Once the minimum effluent turbidity is reached the only changes occurring in the sedimentation tank will be the density of the floc blanket. Since particles are only removed in the sedimentation tank, changes to removal must be a function of changes to the floc blanket. Thus, the increase in effluent turbidity that began approximately 5 hours after experiment began indicated that all coagulant doses still resulted in floc blanket decay and the hypothesis was not supported by the data.

<div class="alert alert-block alert-danger">
Are there any other variables that could explain why the effluent turbidity may decrease with increased coagulant dosing? How can you accurately relate reduced effluent to greater longevity of the floc blanket? Also what does the word "longevity" imply? Is it the right word in this situation?
</div>

![Figure5](/Images/HRSupdatedgraph.png)

Figure 6: The effluent turbidity over 24 hours at varied coagulant doses.

###Experiment 2
After collecting and analyzing the data from Experiment 1, it was hypothesized that the degradation of the floc blanket was a result of smaller flocs escaping, rather than a result of flocs accumulating on the tubing walls. Therefore, the tube settler was lengthened and a flocculator with a larger diameter was used to decrease the capture velocity and ensure that the smaller flocs were settled out.

As is shown in Figure 6, the results illustrated that increasing the length of the tube settler and the diameter of the flocculator did decrease the effluent turbidity. However, this decrease was not significant and the floc blanket still degraded.

![Figure6](/Images/Experiment2Graph.png)
Figure 7: The effluent turbidity recorded using tube settlers of varying lengths and flocculators of varying diameters.

Thus, the hypothesis for the second experiment was not supported by the results.

###Experiment 3

A third experiment was conducted to determine if the flocculator is the cause of floc blanket decay. The experiment was run at 3 mm/s upflow velocity, 4.2 mg/L PACL, using a 3/16 inch diameter flocculator and a 930 mm tube settler. The flocculator was flushed using a syringe approximately 5 hours after dosing coagulant.

[Figure needed, analysis of results needed]

###Experiment 4

In a failed trial of Experiment 3, the coagulant was dosed approximately 5 hours after initially dosing clay; when the data was plotted, the HRS team found that the stability of the floc blanket had increased. The objective of Experiment 4 was to test the effects of dosing coagulant 5 hours after dosing clay.

[Figure needed, analysis of results needed]

Further studies must be conducted to determine the cause of floc blanket decay.

## Conclusions
Based on the above data, the HRS team was able to conclude that increasing coagulant dose mitigated floc blanket degradation up until a coagulant dose of 4.2 mg/L. After this dose there is no effect on effluent turbidity, and all doses still resulted in floc blanket decay.

Experiment two demonstrated that decreased particle size due to floc accumulation in the flocculator is not fully responsible for floc blanket decay. The bigger flocculator should have resulted in larger particles, while the longer tube settler allows for the capture of smaller particles. Neither of these changes resulted in a stable floc blanket, but the duration of effective particle removal was slightly increased. This may be a partial solution to the floc blanket decay problem, but more research will need to be done to verify these results.

<div class="alert alert-block alert-danger">
Too many unnecessary words

Watch change in tenses from third to first person. Have to pick one or the other, until now you picked third.

Also does this data confirm that you are right or just that you are not wrong? I am not convinced by what you have written here that you have proven that a decrease in the effective coagulant concentration is linked with floc blanket duration because other options are not ruled out.
</div>

## Future Work
Currently the Spring 2018 team does not have a solution for floc blanket degradation. Future work should focus on discovering what mechanisms cause the degradation, as well as methods to prevent or minimize it. There are currently three specific causes that the team intends to test. They are: 1. experimental apparatus becoming dirty and inaccurate, 2. particle interactions within the floc blanket being unstable, and 3. the floc weir draining too many particles.

<div class="alert alert-block alert-danger">
Very superficial. What other questions do you have about this? What are possible areas of error to investigate. What willyou be doing with the rest of your semester?
</div>

## Bibliography

Balwan, K. (2016). Study of the effect of length and inclination of tube settler on the effluent quality. Journal (International Journal of Innovative Research and Advanced Engineering).

Culp, G., Hansen, S., & Richardson, G. (1968). High-rate sedimentation in water treatment works. Journal (High-Rate Sedimentaion in Water Treatment Works).

Galantino, C., Oritz, A., & Zarecor, M. (2017). High Rate Sedimentation Fall 2017 Report.

Hurst, M. (2010). Evaluation Of Parameters Affecting Steady-State Floc Blanket Performance. Thesis (Cornell University).

Swetland, K., Weber-Shirk, M., Lion, L. (2014).  Flocculation-sedimentation performance model for laminar flow hydraulic flocculation with polyaluminum chloride and aluminum sulfate coagulants. Journal (Journal of Environmental Engineering).

<div class="alert alert-block alert-danger">
Organize alphabetically
</div>

# Manual

## Experimental Methods
### Set-up
1. Make sure the set up is throughly cleaned out and the stocks are replenished. Open the valves for the water supply as well as the wastewater tube. Fill the recirculator and tube settler with water by turning on the water pump, but keep the effluent turbidimeter closed. To speed up the process of filling up the apparatus with water, increase the RPM of the water pump.
2. Once the apparatus is filled, pause the water pump, close the valve to the wastewater, and use a push pin to replace the influent turbidimeter outflow tube on the connection between the flocculator and influent turbidimeter.
3. Turn on the water pump to the respective RPM for your experiment. Be sure to put the outflow tube of the influent turbidimeter in a container to collect the water that will be flowing through the influent turbidimeter.
4. Turn on ProCoDA by going to process operations and select ON, make sure the clay pump stabilizes and does not constantly stay at 100 RPM. The clay pump must be set on EXT and going clockwise. Also, make sure that the ”1 rpm pump” and ”on off switch” are both OFF. See ProCoDA section below on how to turn those off.
5. Wait until the the influent turbidimeter stabilizes to 100 NTU.
6. Start experiment (be sure to start recording data).

### Cleaning Procedure
1. Clean turbidimeters by removing the top, detaching the glass vial, emptying to the sink, then refilling with water.

2. Clean flocculator and sedimentation tank by attaching the long cleaning tube to the push to connect at the start of the flocculator and the sink. Then detach the tube at the bottom of the sedimentation tank and attach it to the top of the tank. Then turn the sink on slowly and run for 30 seconds. A picture of the cleaning tube is shown in figure 8.

<img src="https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/20180420_171602.jpg" width=600>
Figure 8: Cleaning tube.

3. Rinse coagulent reservoir with DI water.

<div class="alert alert-block alert-danger">
Good place for a photo because I don't know what the long cleaning tube looks like.
</div>

## ProCoDA Method File

The following is taken directly from the Calibrating PID Control on the AguaClara Confluence website:

To establish constants for PID control in ProCoDA, follow the procedure shown at this [link](https://confluence.cornell.edu/display/AGUACLARA/Calibrating+PID+Control). The steps will be summarized below

<div class="alert alert-block alert-danger">
What is this link you speak of?
</div>

1. After you have loaded the proper PID control function and have created the appropriate set points in your method file, set the P, I, and D set points to zero.
2. Set P to a small value and change the target value to provoke a response from the PID control
3. Observe the graph of the variable being controlled for this value of P. If the result is an oscillation that becomes damped (decreasing amplitude), increase the value of P incrementally and repeat the process. If the result is an oscillation that becomes amplified (increasing amplitude), lower the value of P and repeat the process.
4. The objective is to find a value of P for which there is a periodic oscillation of the value with a constant amplitude. Once the correct P value (Ku) has been found, write it down and also record the period of the wave (time between two consecutive crests of the oscillation - Pu - in minutes).
5. AguaClara researchers typically use PI control (the value of D is set to zero). To find the value of P required, use the equation: P = Ku/2.2. To find the value of I required, use the equation: I = Pu/1.2. This should result in a value in minutes, which is the correct unit for I.
6. Change your set points (P and I) to the new values. Ensure that there is less than 10 percent variation in your variable, and fine tune if necessary.

This calibration method may result in oscillatory behavior. To reduce variability in the output, consider reducing P to damp the oscillations. This will reduce the responsiveness of the algorithm and will increase the stability.

### States
In order to properly begin an experiment, the ProCoDA method file must be turned ON. When an experiments in not in progress, ProCoDA is turned off.
* ON - The active state of ProCoDa. The 1 rpm pump drain is turned on (for draining the floc hopper) and the the clay pump is control (with PID) is turned on.

* OFF – Resting state of ProCoDA. All sensors, relays, and pumps are turned off.


<img src="https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/On%20State.png" width=600>

Figure 9: The ON state of the HRS ProCoDA method file. The floc hopper drain and clay pump are the active items controlled by the pump.

<div class="alert alert-block alert-danger">
**None of the figures in the manual section are visible.**
</div>

### Set Points
Here, you should list the set points used in your method file and explain their use as well as how each was calculated.

The following is a list of all the Set Points in the method file and their values. Exact location of these points in the method file can be seen in the figure below.

<img src="https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Set%20Points.png" width=600>

Figure 10: This is the overall order of the Set Points for the HRS method file.


* OFF - no units, value of 0, constant
* ON - no units, value of 1, constant
* Turb Target - NTU, value of 100, constant. Value determined as the influent turbidity desired by the pump control
* P - no units, value of 300m, constant. Value determined through method mentioned in "PID Control" section of report and trial and error.
* i - no units, value of 2.3, constant. Value determined through method mentioned in "PID Control" section of report and trial and error.
* D - no units, value of 0, constant

<img src="https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Output%20Settings.png" width=600>

Figure 11: This is the output settings for the PID state. This process runs in the background and only needs to be set up at the beginning of a semester's work. Note that PID controls the clay pump and whether it is turned on or not at any given time.

* Influent Turbidimeter ID - no units, value of 1, constant. Value is due to the step in which the turbidimeter is installed and acknowledged in the data recording process. Effluent Turbidimeter ID is 2 since it takes in data later down the line.
* Influent Turbidity - no units, value of 0, variable. See Figure below

<img src="https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Influent%20Set%20Point.png" width=600>

Figure 12: This displays the influent turbidity Set Point and the selected sensors to establish the relationship.

* Effluent Turbidimeter ID - no units, value of 1, constant.
* Effluent Turbidity - no units, value of 2
* PumpControl(Clay) - no units, value of 0, variable

<img src="https://raw.githubusercontent.com/AguaClara/high_rate_sedimentation/master/Images/Pump%20Control.png" width=600>

Figure 13: This shows the relationship between the PumpControl(Clay) variable and other predefined set points.

## Python Code
### Variables

$C_{sys}$: Concentration of coagulant in system

$C_{labstock}$: Concentration of coagulant in lab stock

$Q_{sys}$: Flowrate of system

$K_{dilution}$: Dilution factor in reservoir

$V_{reservoir}$: Volume of reservoir

$Frac_{resivor}$: Fraction of usable reservoir

$Q_{per rpm}$: Flow rate per pump rpm

$M_{flowcoag}$: Mass flowrate of coagulant

$C_{reservoir}$: Concentration of coagulant in reservoir

$Q_{reservoir}$: Flow rate out of reservoir

$RPM$: number of pump RPMs for desired flowrate

$RunTime$: Amount of time the experiment can run without refilling the coagulant reservoir

### Python Code

```python
from aide_design.play import*

#inputs
C_sys = 1.4*(u.mg/u.L)
C_labstock = 70.9*(u.g/u.L)
Q_sys = 1.48*(u.mL/u.s)
K_dilution = .8*(u.mL/u.L)
V_reservoir = 5*(u.L)
Frac_reservoir = .76
Q_per_rpm = .001828 *(u.mL/u.s)

#Calculations
M_flow_coag = (Q_sys * C_sys).to(u.mg/u.s)
C_reservoir = (C_labstock * K_dilution).to(u.gram/u.L)
Q_reservoir = (M_flow_coag / C_reservoir).to(u.mL/u.s)

#Outputs
RPM = Q_reservoir / Q_per_rpm
RunTime = ((V_reservoir * Frac_reservoir) / Q_reservoir).to(u.hour)

print('The RPM needed for this coagulent dosage is' ,RPM)

print('The run time is ', RunTime)
```

```python
# To convert the document from markdown to pdf
pandoc Name_of_this_file.md -o TeamName_Research_Report.pdf
```

<div class="alert alert-block alert-danger">
Code is well organized but I don't know what the run time is for. Explain in your report or in the manual!
</div>

Comment response: I think this variable was explained fairly clearly in the variables section. - Mike
