# Intelligent Route Recommendation Based on Historical AIS Data

## Project Overview

This project develops an adaptive vessel route recommendation framework based on historical Automatic Identification System (AIS) trajectories, vessel-specific characteristics, and environmental conditions.

Historical AIS data are used to reconstruct actual vessel trajectories, including vessel position, speed, course, and reported draught where available. Vessel-specific characteristics, including dimensions, maneuvering characteristics, and, where publicly available, stopping or braking characteristics, are incorporated into the analysis.

Environmental conditions corresponding to individual vessel passages are also considered, including wind, current, wave conditions, and reduced visibility where relevant.

Historical vessel trajectories are segmented according to operational and vessel characteristics, including inbound and outbound passages, berth or terminal, vessel type, vessel dimensions, and draught. Navigation patterns within each identified group are analyzed to develop representative recommended routes.

The resulting route is intended to be adaptive rather than universal. When applied to an individual vessel, the recommended route can be adjusted according to its specific characteristics, including dimensions, draught, maneuvering capabilities, and the prevailing environmental conditions. Navigational constraints such as available water depth, squat, and appropriate safety margins may also be incorporated into the route recommendation.

The current project focuses specifically on the development and evaluation of adaptive recommended routes. The integration of these routes with onboard navigation systems and the automated exchange of vessel and route information between vessels and pilots are considered as future research directions.

## Research Problem

Current vessel route planning and pilotage rely heavily on the integration of vessel-specific knowledge and local navigational expertise during the pilotage operation. The vessel's bridge team possesses detailed knowledge of the vessel's characteristics, while the pilot possesses detailed knowledge of the local navigational area. The safe execution of a passage therefore depends on the integration of these two sources of knowledge together with the prevailing environmental and navigational conditions.

However, a dynamically adapted, vessel-specific route is not necessarily generated and made available before the actual passage. In many operational contexts, the synchronization between vessel characteristics, local navigational knowledge, and environmental conditions takes place when the pilot is already involved in the operation.

The problem is therefore not the absence of navigational routes, but the lack of dynamically adapted, vessel-specific route recommendations generated in advance of the actual passage.

This project addresses this gap by investigating whether historical AIS trajectories, vessel-specific characteristics, and environmental conditions can be transformed into reliable and adaptable route recommendations for individual vessels.

## Objectives

### Main Objective

To develop an adaptive route recommendation framework capable of generating a vessel-specific recommended route based on historical AIS trajectories, vessel characteristics, and prevailing environmental conditions.

### Specific Objectives

1. Collect and preprocess historical AIS data, including vessel position, speed, course, and reported draught.

2. Collect vessel-specific characteristics, including dimensions, manoeuvring characteristics, and, where publicly available, stopping or braking characteristics.

3. Integrate environmental conditions associated with historical vessel passages, including wind, current, wave conditions, and visibility where relevant.

4. Segment historical vessel trajectories according to operational and vessel characteristics, including:
   - inbound and outbound movement;
   - berth or terminal;
   - vessel type;
   - vessel dimensions;
   - draught and other relevant characteristics.

5. Identify representative navigation patterns within each vessel and operational group.

6. Develop recommended routes based on historical navigation behavior and relevant navigational constraints.

7. Adapt the recommended route to the characteristics of an individual vessel and the prevailing environmental conditions.

8. Evaluate the proposed routes against historical vessel trajectories and relevant safety and navigational criteria.
