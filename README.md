# District-Medical-Handbook

Dataset:
1. Medical Information of all towns and villages of the state of West Bengal, India.
(For towns: https://censusindia.gov.in/2011census/dchb/DCHB_Town_Release_1900.xlsx)
(For villages: https://censusindia.gov.in/2011census/dchb/DCHB_Village_Release_1900.xlsx)
2. Latitude and Longitude of all towns and villages of the state of West Bengal, India.
(Attached in commit)

A Directed Graph is created where all the nodes represent a town or a village. The nodes has following attributes: Medical Score, Normalized Medical Score, Coordinates
U->V edge is present if a person residing in U would go to V for Medical treatment. This result takes into condition the parameters: Distance between U and V, willingness of a resident of U to travel, Relative Medical Facilities of U and V.

Given the name of a town/village, a sorted list of other towns/villages are to be given a resident would be willing to go.

