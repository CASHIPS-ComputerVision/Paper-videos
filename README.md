# Paper-videos： Object-based Reliable Visual Navigation for Mobile Robot
## Authors: Fan Wang, Chaofan Zhang, Wen Zhang, Cuiyun Fang, Yingwei Xia and Yong Liu

### Abstract 
Visual navigation is of vital importance for autonomous mobile robots.
Most existing practical perception-aware based visual navigation methods generally require prior-constructed precise metric maps, and learning-based methods rely on large training to improve their generality. To improve the reliability of visual navigation, in this paper we propose a novel object-level topological visual navigation method.  
Firstly, a lightweight object-level topological semantic map is constructed to release the dependence on precise metric map, where the semantic associations between objects are stored via graph memory and topological organization is performed.  Then, we propose an object-based heuristic graph search method to select the global topological path with optimal and shortest characteristics. Furthermore, to reduce the global cumulative error, a global path segmentation strategy is proposed to divide global topological path, on basis of active visual perception and object guidance. Finally, to achieve adaptive smooth trajectory generation, a  Bernstein polynomial based smooth trajectory refinement method is proposed, by transforming trajectory generation into a nonlinear planning problem, achieving smooth multi-segment continuous navigation. Experimental results demonstrate the feasibility and efficiency of our method on both simulation and real-world scenarios. The proposed method also obtains better navigation success rate (SR) and success weighted by inverse path length (SPL) than the state-of-the-art methods.
![](https://github.com/CASHIPS-ComputerVision/Paper-videos/edit/main/Global segmented smooth trajectory generation.gif)
