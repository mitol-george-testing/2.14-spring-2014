---
content_type: page
title: Design Project
uid: 98593a12-d5fa-7ba8-30c7-0831dc32f0f0
---

This problem considers the control of a fast tool servo (FTS), and is based upon the work done by [Xiaodong Lu in his Ph.D. thesis (PDF - 11.2MB)](/ans7870/2/2.14/s14/MIT2_14S14_XDLU_PhD_Thesis.pdf). The design problem focuses on:

*   High-bandwidth current controller for driving the actuator.
*   Identification of the electromechanical plant dynamics from a measured Bode plot.
*   Design of a controller to minimize following error for a sinusoidal reference trajectory, in the presence of sensor noise.
*   Graduate students only: Design of an add-on Adaptive Feedforward Cancellation (AFC) control block at the reference trajectory frequency in order to eliminate following error at that frequency.

We do not give you exact specifications for the servo performance. Rather, you are to apply your best effort to get good performance. The measure of performance in this problem is reduction of the following error due to the reference trajectory and to sensor noise.

The problem starts with designing the controller for the current loop, and then moves on to design of the FTS position controller.

Read the entire ![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[Final Design Project (PDF)]({{< baseurl >}}/resources/mit2_14s14_fin_desgn_prob).

Additional files

*   [Plant measured Bode plot (ZIP)]({{< baseurl >}}/resources/gpplantfrequencydata) (This zip folder contains: 1 .pdf file and 2 .mat files)
*   [MATLAB Template (M)]({{< baseurl >}}/resources/template)