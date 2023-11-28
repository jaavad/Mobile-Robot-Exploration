# Autonomous Mobile Robot Exploration under Uncertainty Using Global and Local planning in Belief space

 In the autonomous mobile robot exploration problem, most of the time, it is assumed that the
environment is completely unknown. However, this is not always a correct assumption because
there are a lot of situation in which we could have some initial information such as rough 2D
plans and satellite images for exploration. In addition, most exploration algorithms, such as
frontier based exploration, are making decisions and planning locally. Although, recently, some
works have tried to leverage the initial information in planning, they have not considered
existing uncertainties in decision making. In this work, by leveraging existing initial information
and considering observation and motion uncertainties, we have proposed a novel approach in
which global plaining in belief space and local exploration planning have been combined to have
more effective exploration in more realistic condition. In order to have a reliable global planning
in continuous belief space, we need to have reliable initial information representing the
observation and motion uncertainties of the robot. For this purpose, we used a graph-based FIRM
(Feedback-based Information Road Map) approach in belief space. Indeed, FIRM is a new
framework inspiring PRM approach for approximating the solution of the intractable POMDP
problem in continuous belief space. After obtaining global planning, we combined it with a local
exploration algorithm (Histogram-based frontier exploration) to have local planning also.
Furthermore, leveraging FIRM graph features, we proposed another novel algorithm called
“Transfer algorithm” for navigating robot safely from the current region to the next planned
region, when robot needs to follow the global planning. More importantly, the transfer algorithm
causes robot’s uncertainty in each region to be independent from its’ uncertainty in other regions.
We have evaluated the novel approach algorithms by implementing it (them) in on a nonholonomic mobile robot with unicycle dynamic for several exploration problems in several
different environments. For these initials tests, we used OpenCv, RGB Camera and EKF for
Perception and Localization along with LIDAR and probabilistic Occupancy Grid Mapping
algorithm for Mapping.  
