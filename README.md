# Autonomous Mobile Robot Exploration under Uncertainty Using Global and Local planning in Belief space


In the autonomous mobile robot exploration problem, the prevailing assumption often involves an entirely unknown environment. However, this assumption does not always hold true, as there are scenarios where initial information, such as rough 2D plans and satellite images, may be available for exploration. Despite recent efforts to incorporate this initial information into planning, these approaches have generally overlooked the existing uncertainties inherent in decision-making processes.

### Novel Approach Overview

This work introduces a novel approach that leverages available initial information while accounting for observation and motion uncertainties. The proposed methodology combines global planning in belief space with local exploration planning, aiming to enhance exploration effectiveness under more realistic conditions. To achieve reliable global planning in continuous belief space, a graph-based Feedback-based Information Road Map (FIRM) approach is employed. FIRM, inspired by the Probabilistic Road Map (PRM) approach, addresses the intractable Partially Observable Markov Decision Process (POMDP) problem in continuous belief space.

### Integration of Global and Local Planning

Following the acquisition of global planning, it is integrated with a local exploration algorithm, specifically the Histogram-based Frontier Exploration method. Additionally, a novel algorithm termed the **"Transfer Algorithm"** is introduced, leveraging FIRM graph features to safely navigate the robot from the current region to the next planned region when adhering to the global plan. Notably, the transfer algorithm ensures that the robot's uncertainty in each region remains independent of its uncertainty in other regions.

### Experimental Evaluation

The proposed approach and algorithms are evaluated through implementation on a nonholonomic mobile robot with unicycle dynamics, addressing various exploration problems in diverse environments. The experimental setup involves **OpenCV**, **RGB camera**, and **Extended Kalman Filter (EKF)** for **Perception** and **Localization**, along with **LIDAR** and a probabilistic **Occupancy Grid Mapping algorithm** for **Mapping**.


 #### The code for this work will be shared soon, pending permission from the original author of a specific code segment used in the project

