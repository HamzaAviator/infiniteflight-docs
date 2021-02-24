---
id: inbounds
title: Inbounds
meta: Techniques to handle inbound traffic when operating a tower facility within Infinite Flight.
order: 1
---



# Inbounds



## Pattern Entry, Sequence and Clearance

In Infinite Flight the pattern altitude is 1000ft AAL (above aerodrome level) for prop aircraft, and 1500ft AAL for jet aircraft. It consists of multiple legs, each being joined by a 90 degree turn, and these are shown in the image below:



![The Traffic Pattern](_images/manual/graphics/atc-traffic-pattern.jpg)



The art of sequencing allows controllers to let pilots know who they are supposed to be following and is not just to be used with aircraft in the pattern. All inbounds need to be told who they are following, unless of course they aren't following anyone! For effective sequencing, it requires:



- both the controller and the pilot to have a knowledge of the different pattern legs
- the controller to issue sequencing in good time to keep the pilots informed
- the controller to update the sequencing when things change or don't go to plan
- the pilots to be courteous to each other by giving each pilot the space they need to maneuver
- the pilots to follow the issued sequence



![Image 3.3.1.1 - Tower Sequencing](_images/manual/graphics/atc-tower-sequencing.jpg)



Manual

: When there is no Radar Controller present, Tower **must**{.red} issue a pattern entry and clearance to **ALL**{.red} aircraft as a **MINIMUM**{.red}, regardless of what the aircraft uses to check in on the Tower frequency - the use of sequencing will be dependent on traffic. [More info?](/guide/atc-manual/3.-tower/3.3-inbounds#3.3.1)



+++ SCENARIO - Multiple Inbounds

::: scenario-heading
Scenario
:::

::: scenario
Multiple aircraft have just announced inbound but the Controller is unsure on what order to sequence them in.
::: 

![](_images/manual/screens/atcg-pw-inbound.png){.scenario}



| Technique 1                                                  |
| ------------------------------------------------------------ |
| Only send a pattern entry to the aircraft you are unsure about in terms of sequencing |
| Wait until the aircraft are closer, and once certain of their sequence, issue this along with their clearance |

{.technique}

| Technique 1       | Pro or Con?                                                  |
| ----------------- | ------------------------------------------------------------ |
| :fa-check-circle: | Offers flexibility                                           |
| :fa-check-circle: | Ensures aircraft know who they are following                 |
| :fa-times-circle: | May increase workload as you have to send two separate commands |

{.prosandcons}




| Technique 2                                                  |
| ------------------------------------------------------------ |
| Send a pattern entry and the most likely sequence to all aircraft |
| Monitor and if required, change the sequence as they get closer |

{.technique}

| Technique 2       | Pro or Con?                                                  |
| ----------------- | ------------------------------------------------------------ |
| :fa-check-circle: | Good for workload management                                 |
| :fa-times-circle: | Aircraft may be unsure who they are following if the sequence is given too early |

{.prosandcons}



Tip

: Work from the inside out by making sure that all aircraft closest to the airport have been given a pattern entry, sequence (unless they are number 1) and clearance. Then progressively work your way out to all the other aircraft!

+++



## Runway Changes

Once a runway assignment has been issued, it would be ideal if we did not need to change it. However by using all available runways, changing the assigned runway (if required) is a useful tool to help deal with a dynamic environment and promoting an efficient operation.



Manual

: If a runway change is issued, a new pattern entry and clearance **must**{.red} be given (the use of sequencing will be dependent on traffic). [More info?](/guide/atc-manual/3.-tower/3.3-inbounds#3.3.3)



+++ SCENARIO - Runway Changes

::: scenario-heading
Scenario
:::

::: scenario
*VP-MAX* is departing RWY32L and *I F A E Eleven* is departing RWY32R. Both departures happened simultaneously. *I F A E Eleven* then asks for a RWY change to RWY32L.
::: 

![](_images/manual/screens/atcg-pw-runway-change.png){.scenario}

| Technique 1                                                  |
| ------------------------------------------------------------ |
| Instruct *I F A E Eleven* to "enter right downwind RWY32L, number 2, traffic to follow is on left downwind” |
| If you are concerned about a conflict on the other end, then you can also tell *I F A E Eleven* to "extend downwind, I'll call your base" to alleviate this |
| When you clear *I F A E Eleven*, you can then give them left traffic if you wish to do so to move them onto that side for subsequent patterns |

{.technique}

| Technique 1       | Pro or Con?                                 |
| ----------------- | ------------------------------------------- |
| :fa-check-circle: | Offers flexibility                          |
| :fa-times-circle: | May cause confusion on who is following who |

{.prosandcons}




| Technique 2                                                  |
| ------------------------------------------------------------ |
| Instruct *VP-MAX* to "turn crosswind”                        |
| When you are happy with the separation, tell *I F A E Eleven* to "enter left downwind for RWY32L, number 2, traffic to follow is on left downwind” |
| If during this time, *I F A E Eleven* starts a right turn for RWY32R, then adopt Technique 1 instead |

{.technique}

| Technique 2       | Pro or Con?                                                  |
| ----------------- | ------------------------------------------------------------ |
| :fa-check-circle: | Ensures separation between both aircraft                     |
| :fa-times-circle: | *I F A E Eleven* may start the turn onto a right downwind before you have time to give the new pattern entry |

{.prosandcons}




| Technique 3                                                  |
| ------------------------------------------------------------ |
| Instruct *I F A E Eleven* "extend upwind, I'll call your crosswind” |
| Wait until separation between *VP-MAX* and *I F A E Eleven* is adequate (you can expedite this by telling *VP-MAX* to "turn crosswind"), and then tell *I F A E Eleven* to "enter left downwind for RWY32L, number 2, traffic to follow is on left downwind” |
| The new pattern entry supersedes the previous instruction    |

{.technique}

| Technique 3       | Pro or Con?                                                  |
| ----------------- | ------------------------------------------------------------ |
| :fa-check-circle: | Prevents *I F A E Eleven* from entering right downwind       |
| :fa-times-circle: | May add confusion when a pattern entry is used instead of "turn crosswind" |

{.prosandcons}



Tip

: Remember that other variables (such as terrain) might influence what is the best technique to use on the day, be flexible! 

+++


