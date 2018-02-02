---
layout: post
title: "Updated Milestones, 15-400"
description: "Altered due to new information on the scope of the task"
date: 2018-02-02
tags: [Forensics, PPP]
comments: true
share: true
---

Updated due to new information on the scope of the task:

Febuary 2:  Complete literature review for Computation Geometry Task and update cutThePolitics site to be in a format more ammendable to the project.  
Febuary 16:  Have attempted to find a generalizable way to extract election data from different state datasets.  Finding potential sources of consistently formatted data will be a challenge, but potential sources include David Bradlee’s gardlow.com or non-profits.  If no easy generalized approach exists, for 3+ states, one of which being Pennsylvania, gather and format a usable dataset such that population voting preferences is known to a reasonably granular level.
March 2:  Have experimented with a few different methods in order to identify a way to efficiently represent the districts.  Some initial approaches could include (1) adopting a cartogram method and overlying a grid on top or (2) finding some objective function that provides a rough heuristic to preserve geography for the mapping and then using ILP to minimize this objective function
March 16:  Use the method identified from task 2 to construct a very simple user interface that allows users to select districts within the constraints set forward by the protocol.   This does not involve the integration of the method, only the construction of the UI/UX interface.
March 30:  Integrate the method into the interface
April 13th: Trial the interface in practice and see what kind of districtings are produced.  Write up a brief report on whether the interface is of high quality.  If it is not, identify an alternative cartogram algorithm or complete an approach using an objective function.
April 27:   Modify the task as decided at the April 13th Milestone.
May 11:  Finalize a report of results from the semester


75 percent goal:  Implement a cartogram algorithm and a UX/UI
100 percent goal:  Completely implement the final cartogram algorithm and UX/UI that works well for this task
125 percent goal:  Complete the 100 percent goal and integrate a 2-player version of the protocol