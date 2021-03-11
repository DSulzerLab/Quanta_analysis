# Quanta_analysis
Analysis of quantal release events in an Igor XOP
Analysis of quantal release events in an Igor XOP
(written by Eugene Mosharov: e-mail Eugene)

Requires Igor Pro version 4.07 or later.

This analysis program can be used to detect and characterize amperometric spikes recorded from chromaffin cells, PC12 cells, neurons, etc. The following parameters can be calculated:

Peak parameters:
Amplitude (Imax, pA)
Duration (t1/2, ms)
Charge (Q, pC or # molecules)
Interspike Interval (ms)

Peak rising phase parameters:
Slope (pA/s)
Time to Peak (tP, ms)

Peak falling phase parameters:
(Can be fit by linear, exponential or double-exponential regressions)
Duration (ms)
Decay time constants (tau1 and tau2, ms)

Peak foot parameters:
Amplitude (Ifoot, pA)
Duration (tfoot, ms)
Charge (Qfoot, pC)

Download the file Quanta_Analysis_8_26.ipf in "ipf" (Igor Pro) format. The current version of the program is 8.20.

This is an ipf file (Igor Procedure File) for Igor Pro (has to be version 4.07 or later). To install the routine, unzip the archive and put the file Quanta_Analysis_ver.ipf into the Igor Pro/Igor Procedures folder. After starting Igor, you should see a bookmark "Prepare for quanta analysis" under the Macros menu. Clicking it creates windows and controls for the program. (As the program was written on a PC, the sizes of panels and windows may look odd on a Mac.) Many tune-ups in the program (on the topmost Menu panel) change how the data are analyzed and presented.

If you have questions about the program, or can suggest improvements, please e-mail Eugene Mosharov (em706@columbia.edu).
