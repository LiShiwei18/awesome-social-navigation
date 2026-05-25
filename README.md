# Awesome Social Navigation 
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
![# of Papers](https://img.shields.io/badge/Num%20of%20Papers-147-AD8EA7.svg) <!-- Note: increment number "Papers-###-AD8EA7" after adding a paper -->
![GitHub contributors](https://img.shields.io/github/contributors/rashid1844/awesome-social-navigation.svg?style=flat&color=AD8EA7)
![Last Commit](https://img.shields.io/github/last-commit/rashid1844/awesome-social-navigation?color=AD8EA7)
![GitHub stars](https://img.shields.io/github/stars/rashid1844/awesome-social-navigation.svg?style=flat&color=AD8EA7)


> 📚 A curated collection of resources on social navigation, including papers, code, and tools.

👤Created and maintained by Rashid Alyassi ([ralyassi@ethz.ch](mailto:ralyassi@ethz.ch)), ETH Zurich.

📩 If you notice any missing papers or resources, feel free to email me or submit a [request](#contributing).

📖 Resources are based on findings from our survey paper: ["Social Robot Navigation: A Review and Benchmarking of Learning-Based Methods"](https://socialnavigation.github.io/).



## Table of Contents

* [Social Navigation Methods](#methods)
	* [End-to-End Social Navigation](#rawdata)
	* [Human-Position Social Navigation](#human_pose)
	* [Human-Attention Social Navigation](#human_attention)
	* [Human-Prediction Social Navigation](#human_prediction)
	* [Safety-aware Social Navigation](#safety)
	
* [Human Tracking](#tracking)
* [Human Prediction](#prediction)
* [Datasets](#datasets)
* [Simulators](#simulators)
* [Crowd Behavior](#crowd_sim)
* [Contributing](#contributing)


<!-- ![Social Navigation Algorithms](/figs/socialnav_algos.png) -->

<p align="center">
	<img src="/figs/socialnav_algos.png" alt="Social Navigation Algorithms" title="Social Navigation Algorithms" style="width:70%;" />
</p>



## <a name="methods"></a> Social Navigation Methods

### <a name="rawdata"></a> End-to-End Social Navigation

* **Learning to navigate through complex dynamic environment with modular deep reinforcement learning** <br>
*Wang, Y., He, H. and Sun, C.* <br>
IEEE Transactions on Games, 2018. [[Paper]](https://ieeexplore.ieee.org/abstract/document/8395072/)


* **Learning a State Representation and Navigation in Cluttered and Dynamic Environments** <br>
*Hoeller, D., Wellhausen, L., Farshidian, F. and Hutter, M.* <br>
IEEE RAL, 2021. [[Paper]](https://arxiv.org/pdf/2103.04351) [[Video]](https://youtu.be/CICWcLJ3aPs?si=HVTC1N96FmDNS-b0)


* **Towards Optimally Decentralized Multi-Robot Collision Avoidance via Deep Reinforcement Learning** <br>
*Long, P., Fan, T., Liao, X., Liu, W., Zhang, H. and Pan, J.* <br>
ICRA, 2018. [[Paper]](https://www.google.com/url?q=https%3A%2F%2Farxiv.org%2Fpdf%2F1709.10082.pdf&sa=D&sntz=1&usg=AOvVaw29j-587Uu0EeMGxUiRaBFc) [[Website]](https://sites.google.com/view/drlmaca)


* **CrowdMove: Autonomous Mapless Navigation in Crowded Scenarios** <br>
*Fan, T., Cheng, X., Pan, J., Manocha, D. and Yang, R.* <br>
arXiv, 2018. [[Paper]](https://arxiv.org/pdf/1807.07870) [[Website]](https://sites.google.com/view/crowdmove) [[Video]](https://youtu.be/iOE6rm8dfBA?si=Hb2heIcVn3-6n_Y8)


* **Crowd-Steer: Realtime Smooth and Collision-Free Robot Navigation in Densely Crowded Scenarios Trained using High-Fidelity Simulation** <br>
*Liang, J., Patel, U., Sathyamoorthy, A.J. and Manocha, D.* <br>
IJCAI, 2020. [[Paper]](https://dl.acm.org/doi/pdf/10.5555/3491440.3492023) [[Video]](https://www.youtube.com/watch?v=3NrhuQDsAoc)


* **Mapless Navigation among Dynamics with Social-safety-awareness: a reinforcement learning approach from 2D laser scans** <br>
*Jin, J., Nguyen, N.M., Sakib, N., Graves, D., Yao, H. and Jagersand, M.* <br>
ICRA, 2020. [[Paper]](https://arxiv.org/pdf/1911.03074) [[Website]](https://sites.google.com/view/ssw-batman)


* **NavRep: Unsupervised Representations for Reinforcement Learning of Robot Navigation in Dynamic Human Environments** <br>
*Dugas, D., Nieto, J., Siegwart, R. and Chung, J.J.* <br>
ICRA, 2021. [[Paper]](https://arxiv.org/pdf/2012.04406) [[Code]](https://github.com/ethz-asl/navrep) ⭐104 [[Video]](https://www.youtube.com/watch?v=bg4j9I4p0-I&t=1046s&pp=ygUMbmF2cmVwIGNyb3dk)


* **Learning World Transition Model for Socially Aware Robot Navigation** <br>
*Cui, Y., Zhang, H., Wang, Y. and Xiong, R.* <br>
ICRA, 2021. [[Paper]](https://arxiv.org/pdf/2011.03922) [[Code]](https://github.com/ZJU-Robotics-Lab/model-based-social-navigation) ⭐66 [[Video]](https://www.bilibili.com/video/BV1W64y1o7Ru/)


* **Deep Reinforcement Learning for Robot Collision Avoidance With Self-State-Attention and Sensor Fusion** <br>
*Han, Y., Zhan, I.H., Zhao, W., Pan, J., Zhang, Z., Wang, Y. and Liu, Y.J.* <br>
IEEE RAL, 2022. [[Paper]](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/2022-Deep-Reinforcement-Learning-for-Robot-Collision-Avoidance-With-Self-State-Attention-and-Sensor-Fusion.pdf)


* **Deep Reinforcement Learning of Navigation in a Complex and Crowded Environment with a Limited Field of View** <br>
*Choi, J., Park, K., Kim, M. and Seok, S.* <br>
ICRA, 2019. [[Paper]](https://ieeexplore.ieee.org/abstract/document/8793979) [[Video]](https://youtu.be/432jivlvx-o?si=LnvIyhI0yPG2_G5I)


* **Fast Adaptation of Deep Reinforcement Learning-Based Navigation Skills to Human Preference** <br>
*Choi, J., Dance, C., Kim, J.E., Park, K.S., Han, J., Seo, J. and Kim, M.* <br>
ICRA, 2020. [[Paper]](https://europe.naverlabs.com/wp-content/uploads/2020/02/Fast-Adaptation-of-Deep-Reinforcement-Learning-Based-Navigation-Skills-to-Human-Preference.pdf) [[Website]](https://europe.naverlabs.com/blog/fast-adaptation-of-reinforcement-learned-robot-navigation-skills-to-human-preferences/) [[Video]](https://www.youtube.com/watch?v=B8Js2cEFNF0&t=10s&ab_channel=NAVERLABS)


* **Multi-objective deep reinforcement learning for crowd-aware robot navigation with dynamic human preference** <br>
*Cheng, G., Wang, Y., Dong, L., Cai, W. and Sun, C.* <br>
 Neural Computing and Applications, 2023. [[Paper]](https://link.springer.com/article/10.1007/s00521-023-08385-4)


* **Adaptive and Explainable Deployment of Navigation Skills via Hierarchical Deep Reinforcement Learning** <br>
*Lee, K., Kim, S. and Choi, J.* <br>
ICRA, 2023. [[Paper]](https://arxiv.org/pdf/2305.19746) [[Code]](https://github.com/leekwoon/hrl-nav) ⭐137


* **A Hierarchical Deep Reinforcement Learning Framework With High Efficiency and Generalization for Fast and Safe Navigation** <br>
*Zhu, W. and Hayashibe, M.* <br>
IEEE Transactions on industrial Electronics, 2022. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9834298/) [[Code]](https://github.com/zw199502/RL_navigation) ⭐54 [[Video]](https://youtu.be/S95BQDEiTE0)


* **Resilient Navigation Among Dynamic Agents with Hierarchical Reinforcement Learning** <br>
*Wang, S., Jiang, H. and Wang, Z.* <br>
Advances in Computer Graphics, 2021. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-89029-2_39) [[Video]](https://youtu.be/UqUzS2v0vpU?si=CuFj5TE5dMBZWntg)


* **Learning Navigation Behaviors End-to-End With AutoRL** <br>
*Chiang, H.T.L., Faust, A., Fiser, M. and Francis, A.* <br>
IEEE RAL, 2019. [[Paper]](https://ieeexplore.ieee.org/abstract/document/8643443/) [[Video]](https://youtu.be/0UwkjpUEcbI?si=2Y8BalJE26Z_9deH)


* **PRM-RL: Long-range Robotic Navigation Tasks by Combining Reinforcement Learning and Sampling-Based Planning** <br>
*Faust, A., Oslund, K., Ramirez, O., Francis, A., Tapia, L., Fiser, M. and Davidson, J.* <br>
ICRA, 2018. [[Paper]](https://arxiv.org/pdf/1710.03937) [[Short Video]](https://youtu.be/_XiaL5W-5Lg?si=e2K4RW1q7OkldN4K) [[Video]](https://youtu.be/wHrxpLfcLdo?si=drXUQPnC_X8BCadu)


* **Deep Reinforcement Learning with Successor Features for Navigation across Similar Environments** <br>
*Zhang, J., Springenberg, J.T., Boedecker, J. and Burgard, W.* <br>
IROS, 2017. [[Paper]](https://arxiv.org/pdf/1612.05533) [[Video]](https://youtu.be/WcCcdkhgjdY)


* **Deep reinforcement learning for indoor mobile robot path planning** <br>
*Gao, J., Ye, W., Guo, J. and Li, Z.* <br>
Sensors, 2020. [[Paper]](https://www.mdpi.com/1424-8220/20/19/5493/pdf)


* **DeepMNavigate: Deep Reinforced Multi-Robot Navigation Unifying Local & Global Collision Avoidance** <br>
*Tan, Q., Fan, T., Pan, J. and Manocha, D.* <br>
IROS, 2020. [[Paper]](https://arxiv.org/pdf/1910.09441) [[Video]](https://youtu.be/LWLBxWuwPeU?si=rXVBYshhgsmbQ2C8)


* **Mapless Collaborative Navigation for a Multi-Robot System Based on the Deep Reinforcement Learning** <br>
*Chen, W., Zhou, S., Pan, Z., Zheng, H. and Liu, Y.* <br>
Applied Sciences, 2019. [[Paper]](https://www.mdpi.com/2076-3417/9/20/4198/pdf)

* **iPlanner: Imperative Path Planning** <br>
*Yang, F., Wang, C., Cadena, C. and Hutter, M.* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2302.11434) [[Code]](https://github.com/leggedrobotics/iPlanner) ⭐364 [[Video]](https://youtu.be/-IfjSW0wPBI?si=2T5lWoWgBUwiOBQ_)




* **Exploiting Proximity-Aware Tasks for Embodied Social Navigation** <br>
*Cancelli, E., Campari, T., Serafini, L., Chang, A.X. and Ballan, L.* <br>
IEEE/CVF, 2023. [[Paper]](http://openaccess.thecvf.com/content/ICCV2023/papers/Cancelli_Exploiting_Proximity-Aware_Tasks_for_Embodied_Social_Navigation_ICCV_2023_paper.pdf) [[Code]](https://github.com/EnricoCancelli/ProximitySocialNav) ⭐11 [[Video]](https://youtu.be/havP4HyYKtI?si=i2Ug384kCf-ghhaE)


* **From Cognition to Precognition: A Future-Aware Framework for Social Navigation** <br>
*Gong, Z., Hu, T., Qiu, R. and Liang, J.* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.13244) [[Code]](https://github.com/Zeying-Gong/Falcon) ⭐107 [[Website]](https://zeying-gong.github.io/projects/falcon/) [[Video]](https://youtu.be/elNI7XlRyvU?si=jHz_LnPMXnlo1Ehz)




* **Socially Adaptive Path Planning in Human Environments Using Inverse Reinforcement Learning** <br>
*Kim, B. and Pineau, J.* <br>
Journal of Social Robotics, 2016. [[Paper]](http://people.csail.mit.edu/beomjoon/publications/kim-SORO15.pdf)


* **Learning How Pedestrians Navigate: A Deep Inverse Reinforcement Learning Approach** <br>
*Fahad, M., Chen, Z. and Guo, Y.* <br>
IROS, 2018. [[Paper]](https://par.nsf.gov/servlets/purl/10111828)


* **From Perception to Decision: A Data-driven Approach to End-to-end Motion Planning for Autonomous Ground Robots** <br>
*Pfeiffer, M., Schaeuble, M., Nieto, J., Siegwart, R. and Cadena, C.* <br>
ICRA, 2017. [[Paper]](https://arxiv.org/pdf/1609.07910) [[Video]](https://youtu.be/ZedKmXzwdgI?si=hYAM6KzqeYhuOLKw)


* **Deep-Learned Collision Avoidance Policy for Distributed Multi-Agent Navigation** <br>
*Long, P., Liu, W. and Pan, J.* <br>
IEEE RAL, 2017. [[Paper]](https://arxiv.org/pdf/1609.06838) [[Video]](https://youtu.be/-kwnxS83DVo?si=j0ZjvJIuX850Gjc5)


* **Map-based Deep Imitation Learning for Obstacle Avoidance** <br>
*Liu, Y., Xu, A. and Chen, Z.* <br>
IROS, 2018. [[Paper]](https://ieeexplore.ieee.org/abstract/document/8593683/)


* **Socially Compliant Navigation through Raw Depth Inputs with Generative Adversarial Imitation Learning** <br>
*Tai, L., Zhang, J., Liu, M. and Burgard, W.* <br>
ICRA, 2018. [[Paper]](https://arxiv.org/pdf/1710.02543) [[Code]](https://github.com/onlytailei/gym_ped_sim) ⭐122 [[Video]](https://youtu.be/0hw0GD3lkA8?si=p7WeLEisUuoUELUM)


* **DeepMoTIon: Learning to Navigate Like Humans** <br>
*Hamandi, M., D’Arcy, M. and Fazli, P.* <br>
IEEE RO-MAN, 2019. [[Paper]](https://arxiv.org/pdf/1803.03719) [[Video]](https://youtu.be/YTz1brqQKEw?si=gkTFbmqf-bQg64Bs)


* **Toward Human-Like Social Robot Navigation: A Large-Scale, Multi-Modal, Social Human Navigation Dataset** <br>
*Nguyen, D.M., Nazeri, M., Payandeh, A., Datar, A. and Xiao, X.* <br>
IROS, 2023. [[Paper]](https://arxiv.org/pdf/2303.14880) [[Code]](https://github.com/RobotiXX/MuSoHu-data-collection) ⭐32 [[Website]](https://cs.gmu.edu/~xiao/Research/MuSoHu/)













### <a name="human_pose"></a> Human-Position Social Navigation

* **Decentralized Non-communicating Multiagent Collision Avoidance with Deep Reinforcement Learning** <br>
*Chen, Y.F., Liu, M., Everett, M. and How, J.P.* <br>
ICRA, 2017. [[Paper]](https://ieeexplore.ieee.org/iel7/7960754/7988677/07989037.pdf) [[Code]](https://github.com/ChanganVR/CADRL) ⭐95 [[Video]](https://youtu.be/BryJ9jeBkbU?si=riqBOrH3Zo0v-D34)


* **Socially Aware Motion Planning with Deep Reinforcement Learning** <br>
*Chen, Y.F., Everett, M., Liu, M. and How, J.P.* <br>
IROS, 2017. [[Paper]](https://ieeexplore.ieee.org/iel7/8119304/8202121/08202312.pdf) [[Code]](https://github.com/mit-acl/gym-collision-avoidance) ⭐320 [[Video]](https://youtu.be/CK1szio7PyA?si=71FX3u0GIuwkT7uS)


* **Motion Planning Among Dynamic, Decision-Making Agents with Deep Reinforcement Learning** <br>
*Everett, M., Chen, Y.F. and How, J.P.* <br>
IROS, 2018. [[Paper]](https://ieeexplore.ieee.org/iel7/8574473/8593358/08593871.pdf) [[Code]](https://github.com/mit-acl/gym-collision-avoidance) ⭐320 [[Video]](https://youtu.be/XHoXkWLhwYQ?si=Qzlw1QLc-r0CPkB6)


* **Collision Avoidance in Pedestrian-Rich Environments With Deep Reinforcement Learning** <br>
*Everett, M., Chen, Y.F. and How, J.P.* <br>
IEEE Access, 2021. [[Paper]](https://ieeexplore.ieee.org/iel7/6287639/6514899/09317723.pdf) [[Code]](https://github.com/mit-acl/gym-collision-avoidance) ⭐320 [[Video]](https://youtu.be/Bjx4ZEov0yE?si=OfacA3ukOhf2HgXt)


* **DenseCAvoid: Real-time Navigation in Dense Crowds using Anticipatory Behaviors** <br>
*Sathyamoorthy, A.J., Liang, J., Patel, U., Guan, T., Chandra, R. and Manocha, D.* <br>
ICRA, 2020. [[Paper]](https://ieeexplore.ieee.org/iel7/9187508/9196508/09197379.pdf) [[Video]](https://youtu.be/AsUbng-E8gg?si=lW8FhU9CZsjQgGw-)


* **Deep Imitation Learning for Autonomous Navigation in Dynamic Pedestrian Environments** <br>
*Qin, L., Huang, Z., Zhang, C., Guo, H., Ang, M. and Rus, D.* <br>
ICRA, 2021. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9561220/)


* **Reinforcement Learned Distributed Multi-Robot Navigation With Reciprocal Velocity Obstacle Shaped Rewards** <br>
*Han, R., Chen, S., Wang, S., Zhang, Z., Gao, R., Hao, Q. and Pan, J.* <br>
IEEE RAL, 2022. [[Paper]](https://ieeexplore.ieee.org/iel7/7083369/7339444/09740403.pdf) [[Code]](https://github.com/hanruihua/rl_rvo_nav) ⭐291 [[Video]](https://youtu.be/-8a8Vqm6epM?si=IjXp_V3kcmNJSF19)


* **DRL-VO: Learning to Navigate Through Crowded Dynamic Scenes Using Velocity Obstacles** <br>
*Xie, Z. and Dames, P.* <br>
IEEE Transactions on Robotics, 2023. [[Paper]](https://ieeexplore.ieee.org/iel7/8860/10214173/10089196.pdf) [[Code]](https://github.com/TempleRAIL/drl_vo_nav) ⭐293 [[Video]](https://youtu.be/KneELRT8GzU?si=xrL5dbeWu48Y6I3o)


* **Aligning Human Preferences with Baseline Objectives in Reinforcement Learning** <br>
*Marta, D., Holk, S., Pek, C., Tumova, J. and Leite, I.* <br>
ICRA, 2023. [[Paper]](https://ieeexplore.ieee.org/iel7/10160211/10160212/10161261.pdf)


* **Learning Adaptive Multi-Objective Robot Navigation Incorporating Demonstrations** <br>
*de Heuvel, J., Sethuraman, T. and Bennewitz, M.* <br>
arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2404.04857)


* **Learning Personalized Human-Aware Robot Navigation Using Virtual Reality Demonstrations from a User Study** <br>
*de Heuvel, J., Corral, N., Bruckschen, L. and Bennewitz, M.* <br>
IEEE RO-MAN, 2022. [[Paper]](https://ieeexplore.ieee.org/iel7/9900506/9900507/09900554.pdf) [[Video]](https://www.hrl.uni-bonn.de/publications/deheuvel22roman_presentation.mp4)


* **Learning Depth Vision-Based Personalized Robot Navigation From Dynamic Demonstrations in Virtual Reality** <br>
*de Heuvel, J., Corral, N., Kreis, B., Conradi, J., Driemel, A. and Bennewitz, M.* <br>
IROS, 2023. [[Paper]](https://ieeexplore.ieee.org/iel7/10341341/10341342/10341370.pdf) [[Video]](https://youtu.be/IbYpfUuwzjM?si=7w21fUUP9ZsKiFz0)







### <a name="human_attention"></a> Human-Attention Social Navigation

* **Crowd-Robot Interaction: Crowd-aware Robot Navigation with Attention-based Deep Reinforcement Learning** <br>
*Chen, C., Liu, Y., Kreiss, S. and Alahi, A.* <br>
ICRA, 2019. [[Paper]](https://ieeexplore.ieee.org/iel7/8780387/8793254/08794134.pdf) [[Code]](https://github.com/vita-epfl/CrowdNav) ⭐716 [[Website]](https://www.epfl.ch/labs/vita/research/planning/crowd-robot-interaction/) [[Video]](https://youtu.be/0sNVtQ9eqjA?si=KWwaCPWSmRXGVN_V)


* **Robot Navigation in Crowded Environments Using Deep Reinforcement Learning** <br>
*Liu, L., Dugas, D., Cesari, G., Siegwart, R. and Dubé, R.* <br>
IROS, 2020. [[Paper]](https://ieeexplore.ieee.org/iel7/9340668/9340635/09341540.pdf) [[Video]](https://youtu.be/Sccs1y16S3g)


* **Robot Navigation in Crowds by Graph Convolutional Networks With Attention Learned From Human Gaze** <br>
*Chen, Y., Liu, C., Shi, B.E. and Liu, M.* <br>
IEEE RAL, 2020. [[Paper]](https://ieeexplore.ieee.org/iel7/7083369/7339444/08990034.pdf) [[Website]](https://sites.google.com/view/gazenav) [[Video]](https://youtu.be/Z_UcyGEeznA?si=JTzn5ZwJzHEJwtb4)


* **A Generative Approach for Socially Compliant Navigation** <br>
*Tsai, C.E. and Oh, J.* <br>
ICRA, 2020. [[Paper]](http://www.cs.cmu.edu/~./jeanoh/papers/TO-ICRA2020.pdf) [[Video]](https://youtu.be/61blDymjCpw?si=noVU7-mrPaLqoEdt)


* **Decentralized Structural-RNN for Robot Crowd Navigation with Deep Reinforcement Learning** <br>
*Liu, S., Chang, P., Liang, W., Chakraborty, N. and Driggs-Campbell, K.* <br>
ICRA, 2021. [[Paper]](https://ieeexplore.ieee.org/iel7/9560720/9560666/09561595.pdf) [[Code]](https://github.com/Shuijing725/CrowdNav_DSRNN) ⭐122 [[Website]](https://sites.google.com/illinois.edu/crowdnav-dsrnn/home) [[Video]](https://www.youtube.com/watch?v=FRWxJroI-vg)


* **NaviSTAR: Socially Aware Robot Navigation with Hybrid Spatio-Temporal Graph Transformer and Preference Learning** <br>
*Wang, W., Wang, R., Mao, L. and Min, B.C.* <br>
IROS, 2023. [[Paper]](https://ieeexplore.ieee.org/iel7/10341341/10341342/10341395.pdf) [[Code]](https://github.com/SMARTlab-Purdue/SAN-NaviSTAR) ⭐61 [[Website]](https://sites.google.com/view/san-navistar) [[Video]](https://www.youtube.com/watch?v=iPDF3jZZ-4M&t=222s&ab_channel=PurdueSMARTLab)


* **Graph Relational Reinforcement Learning for Mobile Robot Navigation in Large-Scale Crowded Environments** <br>
*Liu, Z., Zhai, Y., Li, J., Wang, G., Miao, Y. and Wang, H.* <br>
IEEE T-ITS, 2023. [[Paper]](https://ieeexplore.ieee.org/iel7/6979/10202228/10115223.pdf)







### <a name="human_prediction"></a> Human-Prediction Social Navigation


* **Where to go Next: Learning a Subgoal Recommendation Policy for Navigation in Dynamic Environments** <br>
*Brito, B., Everett, M., How, J.P. and Alonso-Mora, J.* <br>
IEEE RAL, 2021. [[Paper]](https://autonomousrobots.nl/assets/files/publications/21-brito-ral.pdf) [[Code]](https://github.com/tud-amr/go-mpc) ⭐76 [[Video]](https://youtu.be/sZBbWMnwle8?si=iWcVoE8V6YpGNmOS)


* **Path Planning in Dynamic Environments using Generative RNNs and Monte Carlo Tree Search** <br>
*Eiffert, S., Kong, H., Pirmarzdashti, N. and Sukkarieh, S.* <br>
ICRA, 2020. [[Paper]](https://arxiv.org/pdf/2001.11597) [[Code]](https://github.com/stuarteiffert/MCTS-GRNN) ⭐29 [[Video]](https://youtu.be/vBPKiqtCYRU)


* **Relational Graph Learning for Crowd Navigation** <br>
*Chen, C., Hu, S., Nikdel, P., Mori, G. and Savva, M.* <br>
IROS, 2020. [[Paper]](https://arxiv.org/pdf/1909.13165) [[Code]](https://github.com/ChanganVR/RelationalGraphLearning) ⭐147 [[Video]](https://youtu.be/_L-Ih3cE3l0?si=s0wolpMhRUMpglIq) [[Short Video]](https://youtu.be/U3quW30Eu3A?si=kOIxrxm8so5DA5uU)


* **From Crowd Motion Prediction to Robot Navigation in Crowds** <br>
*Poddar, S., Mavrogiannis, C. and Srinivasa, S.S.* <br>
IROS, 2023. [[Paper]](https://arxiv.org/pdf/2303.01424) [[Code]](https://github.com/sriyash421/Pred2Nav) ⭐12 [[Video]](https://youtu.be/mzFiXg8KsZ0?si=9AgWqTaO8HEBjrix)


* **Socially Aware Crowd Navigation with Multimodal Pedestrian Trajectory Prediction for Autonomous Vehicles** <br>
*Li, K., Shan, M., Narula, K., Worrall, S. and Nebot, E.* <br>
IEEE ITSC, 2020. [[Paper]](https://arxiv.org/pdf/2011.11191)


* **Intention Aware Robot Crowd Navigation with Attention-Based Interaction Graph** <br>
*Liu, S., Chang, P., Huang, Z., Chakraborty, N., Hong, K., Liang, W., McPherson, D.L., Geng, J. and Driggs-Campbell, K.* <br>
ICRA, 2023. [[Paper]](https://arxiv.org/pdf/2203.01821) [[Code]](https://github.com/Shuijing725/CrowdNav_Prediction_AttnGraph) ⭐253 [[Website]](https://sites.google.com/view/intention-aware-crowdnav/home) [[Video]](https://youtu.be/boDDQvZ1yV0?si=SdBnmCfjFbZ1xFro)







### <a name="safety"></a> Safety-aware Social Navigation

* **Reinforced Imitation: Sample Efficient Deep Reinforcement Learning for Mapless Navigation by Leveraging Prior Demonstrations** <br>
*Pfeiffer, M., Shukla, S., Turchetta, M., Cadena, C., Krause, A., Siegwart, R. and Nieto, J.* <br>
IEEE RAL, 2018. [[Paper]](https://arxiv.org/pdf/1805.07095) [[Code]](https://github.com/ethz-asl/rl-navigation) ⭐65


* **Distributed multi-robot collision avoidance via deep reinforcement learning for navigation in complex scenarios** <br>
*Fan, T., Long, P., Liu, W. and Pan, J.* <br>
Journal of Robotics Research, 2020. [[Paper]](https://journals.sagepub.com/doi/abs/10.1177/0278364920916531) [[Website]](https://sites.google.com/view/hybridmrca)


* **Autonomous Mobile Robot Navigation for Complicated Environments by Switching Multiple Control Policies** <br>
*Amano, K. and Kato, Y.* <br>
IECON, 2022. [[Paper]](https://ieeexplore.ieee.org/abstract/document/9968759/) 


* **All-in-One: A DRL-based Control Switch Combining State-of-the-art Navigation Planners** <br>
*Linh, K.U., Cox, J., Buiyan, T. and Lambrecht, J.* <br>
ICRA, 2022. [[Paper]](https://arxiv.org/pdf/2109.11636) [[Code]](https://github.com/ignc-research/all-in-one-DRL-planner) ⭐49


* **Intent-Aware Pedestrian Prediction for Adaptive Crowd Navigation** <br>
*Katyal, K.D., Hager, G.D. and Huang, C.M.* <br>
ICRA, 2020. [[Paper]](https://intuitivecomputing.github.io/publications/2020-icra-katyal.pdf)


* **Crowd Navigation in an Unknown and Dynamic Environment Based on Deep Reinforcement Learning** <br>
*Sun, L., Zhai, J. and Qin, W.* <br>
IEEE Access, 2019. [[Paper]](https://ieeexplore.ieee.org/iel7/6287639/8600701/08789446.pdf)


* **Safe Reinforcement Learning with Model Uncertainty Estimates** <br>
*Lütjens, B., Everett, M. and How, J.P.* <br>
ICRA, 2019. [[Paper]](https://arxiv.org/pdf/1810.08700) [[Video]](https://youtu.be/7vwQkSS0D-g?si=E8s5YugiFFRcjR8p)


* **Frozone: Freezing-Free, Pedestrian-Friendly Navigation in Human Crowds** <br>
*Sathyamoorthy, A.J., Patel, U., Guan, T. and Manocha, D.* <br>
IEEE RAL, 2020. [[Paper]](https://arxiv.org/pdf/2003.05395) [[Video]](https://youtu.be/bejfMfpUyXA?si=I623OQI2ulUji20Q)


* **XAI-N: Sensor-based Robot Navigation using Expert Policies and Decision Trees** <br>
*Roth, A.M., Liang, J. and Manocha, D.* <br>
IROS, 2021. [[Paper]](https://arxiv.org/pdf/2104.10818) [[Code]](https://github.com/AMR-/JackalCrowdEnv) ⭐6 [[Website]](https://gamma.umd.edu/researchdirections/xrl/navviper)


* **L2B: Learning to Balance the Safety-Efficiency Trade-off in Interactive Crowd-aware Robot Navigation** <br>
*Nishimura, M. and Yonetani, R.* <br>
IROS, 2020. [[Paper]](https://arxiv.org/pdf/2003.09207) [[Code]](https://github.com/denkiwakame/Python-ERVO) ⭐23 [[Website]](https://denkiwakame.github.io/l2b/)


* **IAN: Multi-Behavior Navigation Planning for Robots in Real, Crowded Environments** <br>
*Dugas, D., Nieto, J., Siegwart, R. and Chung, J.J.* <br>
IROS, 2020. [[Paper]](http://ras.papercept.net/images/temp/IROS/files/1703.pdf) [[Code]](https://github.com/ethz-asl/interaction_actions_for_navigation) ⭐32 [[Video]](https://youtu.be/qbzbXufX6V4?si=WbbHv73-D7hjDFNp)


* **SoNIC: Safe Social Navigation with Adaptive Conformal Inference and Constrained Reinforcement Learning** <br>
*Yao, J., Zhang, X., Xia, Y., Wang, Z., Roy-Chowdhury, A.K. and Li, J.* <br>
Conference, Year. [[Paper]](https://arxiv.org/pdf/2407.17460) [[Code]](https://github.com/tasl-lab/SoNIC-Social-Nav) ⭐23 [[Video]](https://www.youtube.com/watch?v=TyyrCHwMD18&t=180s) [[Website]](https://sonic-social-nav.github.io/)


* **Confidence-Aware Robust Dynamical Distance Constrained Reinforcement Learning for Social Robot Navigation** <br>
*Zhu, K., Xue, T. and Zhang, T.* <br>
Conference, Year. [[Paper]](https://ieeexplore.ieee.org/abstract/document/11029302/)


* **Social Zone as a Barrier Function for Socially-Compliant Robot Navigation** <br>
*Jang, J. and Ghaffari, M.* <br>
Conference, Year. [[Paper]](https://arxiv.org/pdf/2405.15101)


* **A safe reinforcement learning approach for autonomous navigation of mobile robots in dynamic environments** <br>
*Zhou, Z., Ren, J., Zeng, Z., Xiao, J., Zhang, X., Guo, X., Zhou, Z. and Lu, H.* <br>
Conference, Year. [[Paper]](https://ietresearch.onlinelibrary.wiley.com/doi/pdfdirect/10.1049/cit2.12269)















## <a name="tracking"></a> Human Detection/Tracking

* **You Only Look Once: Unified, Real-Time Object Detection** <br>
*Redmon, J., Divvala, S., Girshick, R., and Farhadi, A.* <br>
CVPR, 2016. [[Paper]](https://www.academis.eu/machine_learning/_downloads/51a67e9194f116abefff5192f683e3d8/yolo.pdf) [[Code]](https://github.com/WongKinYiu/yolov7) ⭐14096

* **SSD: Single Shot MultiBox Detector** <br>
*Liu, W., Anguelov, D., Erhan, D., Szegedy, C., Reed, S., Fu, C.Y. and Berg, A.C.* <br>
Springer International, 2016. [[Paper]](http://www.cs.utoronto.ca/~bonner/courses/2020s/csc2547/papers/discriminative/object-detection/ssd,-liu,-eccv-2016.pdf) [[Code]](https://github.com/weiliu89/caffe/tree/ssd)

* **End-to-End Object Detection with Transformers** <br>
*Carion, N., Massa, F., Synnaeve, G., Usunier, N., Kirillov, A. and Zagoruyko, S.* <br>
Springer International Publishing, 2020. [[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460205.pdf) [[Code]](https://github.com/facebookresearch/detr) ⭐15277

* **DR-SPAAM: A Spatial-Attention and Auto-regressive Model for Person Detection in 2D Range Data** <br>
*Jia, D., Hermans, A. and Leibe, B.* <br>
IROS, 2020. [[Paper]](https://arxiv.org/pdf/2004.14079) [[Code]](https://github.com/VisualComputingInstitute/DR-SPAAM-Detector) ⭐89

* **Multiple Hypothesis Tracking Algorithm for Multi-target Multi-camera Tracking with Disjoint Views** <br>
*Yoon, K., Song, Y.M. and Jeon, M.* <br>
IET Image Processing, 2018. [[Paper]](https://ietresearch.onlinelibrary.wiley.com/doi/pdfdirect/10.1049/iet-ipr.2017.1244) [[Code]](https://github.com/yoon28/SCT4DukeMTMC) ⭐36

* **Simple Online and Realtime Tracking with a Deep Association Metric** <br>
*Wojke, N., Bewley, A. and Paulus, D.* <br>
IEEE ICIP, 2017. [[Paper]](https://arxiv.org/pdf/1703.07402) [[Code]](https://github.com/nwojke/deep_sort) ⭐6138

* **ByteTrack: Multi-Object Tracking by Associating Every Detection Box** <br>
*Zhang, Y., Sun, P., Jiang, Y., Yu, D., Weng, F., Yuan, Z., Luo, P., Liu, W. and Wang, X.* <br>
ECCV, 2022. [[Paper]](https://arxiv.org/pdf/2303.15334) [[Code]](https://github.com/ifzhang/ByteTrack) ⭐6386










## <a name="prediction"></a> Human Prediction

* **Social LSTM: Human Trajectory Prediction in Crowded Spaces** <br>
*Alahi, A., Goel, K., Ramanathan, V., Robicquet, A., Fei-Fei, L. and Savarese, S.* <br>
CVPR, 2016. [[Paper]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Alahi_Social_LSTM_Human_CVPR_2016_paper.pdf) [[Code]](https://github.com/quancore/social-lstm) ⭐495

* **Social GAN: Socially Acceptable Trajectories with Generative Adversarial Networks** <br>
*Gupta, A., Johnson, J., Fei-Fei, L., Savarese, S. and Alahi, A.* <br>
CVPR, 2018. [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf) [[Code]](https://github.com/agrimgupta92/sgan) ⭐914

* **SoPhie: An Attentive GAN for Predicting Paths Compliant to Social and Physical Constraints** <br>
*Sadeghian, A., Kosaraju, V., Sadeghian, A., Hirose, N., Rezatofighi, H. and Savarese, S.* <br>
CVPR, 2019. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Sadeghian_SoPhie_An_Attentive_GAN_for_Predicting_Paths_Compliant_to_Social_CVPR_2019_paper.pdf) [[Code]](https://github.com/coolsunxu/sophie) ⭐65

* **Probabilistic Crowd GAN: Multimodal Pedestrian Trajectory Prediction Using a Graph Vehicle-Pedestrian Attention Network** <br>
*Eiffert, S., Li, K., Shan, M., Worrall, S., Sukkarieh, S. and Nebot, E.* <br>
IEEE RAL, 2020. [[Paper]](https://arxiv.org/pdf/2006.12906)

* **Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion** <br>
*Gu, T., Chen, G., Li, J., Lin, C., Rao, Y., Zhou, J. and Lu, J.* <br>
CVPR, 2022. [[Paper]](http://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Stochastic_Trajectory_Prediction_via_Motion_Indeterminacy_Diffusion_CVPR_2022_paper.pdf) [[Code]](https://github.com/gutianpei/MID) ⭐228

* **Social Ways: Learning Multi-Modal Distributions of Pedestrian Trajectories with GANs** <br>
*Amirian, J., Hayet, J.B. and Pettré, J.* <br>
CVPR, 2019. [[Paper]](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Precognition/Amirian_Social_Ways_Learning_Multi-Modal_Distributions_of_Pedestrian_Trajectories_With_GANs_CVPRW_2019_paper.pdf) [[Code]](https://github.com/crowdbotp/socialways) ⭐129

* **Social-STGCNN: A Social Spatio-Temporal Graph Convolutional Neural Network for Human Trajectory Prediction** <br>
*Mohamed, A., Qian, K., Elhoseiny, M. and Claudel, C.* <br>
CVPR, 2020. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mohamed_Social-STGCNN_A_Social_Spatio-Temporal_Graph_Convolutional_Neural_Network_for_Human_CVPR_2020_paper.pdf) [[Code]](https://github.com/abduallahmohamed/Social-STGCNN) ⭐576










## <a name="datasets"></a> Datasets

* **ETH Dataset** <br>
*Pellegrini, S., Ess, A., Schindler, K. and Van Gool, L.* <br>
ICCV, 2009. [[Paper]](http://europa.informatik.uni-freiburg.de/files/iccv09stefano.pdf) [[Dataset]](https://github.com/StanfordASL/Trajectron-plus-plus/tree/master/experiments/pedestrians/raw/raw/all_data) 


* **UCY Dataset** <br>
*Lerner, A., Chrysanthou, Y. and Lischinski, D.* <br>
Computer graphics forum, 2007. [[Paper]](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=3921f459a9ee26827963abc4abf013b4cc9cbd32) [[Dataset]](https://github.com/StanfordASL/Trajectron-plus-plus/tree/master/experiments/pedestrians/raw/raw/all_data)


* **Central Train Station Dataset** <br>
*Zhou, B., Wang, X. and Tang, X.* <br>
CVPR, 2012. [[Paper]](https://people.csail.mit.edu/bzhou/project/cvpr2012/zhoucvpr2012.pdf) [[Dataset]](https://www.ee.cuhk.edu.hk/~xgwang/grandcentral.html)


* **Edinburgh Form Dataset** <br>
*Majecka, B.* <br>
Thesis, 2009. [[Paper]](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=6505d259758fc2fd4e60da018c35d687a2ddc250) [[Dataset]](https://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/)


* **Stanford Drone Dataset** <br>
*Robicquet, A., Sadeghian, A., Alahi, A. and Savarese, S.* <br>
ECCV, 2019. [[Paper]](https://infoscience.epfl.ch/record/230262/files/ECCV16social.pdf) [[Dataset]](https://cvgl.stanford.edu/projects/uav_data/)


* **VIRAT Dataset** <br>
*Oh, S., Hoogs, A., Perera, A., Cuntoor, N., Chen, C.C., Lee, J.T., Mukherjee, S., Aggarwal, J.K., Lee, H., Davis, L. and Swears, E.* <br>
CVPR, 2011. [[Paper]](https://apps.dtic.mil/sti/pdfs/ADA554181.pdf) [[Dataset]](https://viratdata.org) 


* **Oxford Town-Center Dataset** <br>
*Benfold, B. and Reid, I.* <br>
CVPR, 2011. [[Paper]](https://web.archive.org/web/20161020120026id_/http://www.robots.ox.ac.uk:80/~lav/Papers/benfold_reid_cvpr2011/benfold_reid_cvpr2011.pdf) [[Dataset]](https://www.kaggle.com/datasets/ashayajbani/oxford-town-centre) 


* **ATC Dataset** <br>
*Brščić, D., Kanda, T., Ikeda, T. and Miyashita, T.* <br>
IEEE THMS, 2013. [[Paper]](https://www.researchgate.net/profile/Drazen-Brscic-2/publication/264580888_Person_Tracking_in_Large_Public_Spaces_Using_3-D_Range_Sensors/links/55b5de3608ae092e96559c0f/Person-Tracking-in-Large-Public-Spaces-Using-3-D-Range-Sensors.pdf) [[Dataset]](https://dil.atr.jp/crest2010_HRI/ATC_dataset/) 


* **Ko-PER Dataset** <br>
*Strigel, E., Meissner, D., Seeliger, F., Wilking, B. and Dietmayer, K.* <br>
ITSC, 2014. [[Paper]](http://www.uni-ulm.de/fileadmin/website_uni_ulm/iui.inst.110/Bilder/Forschung/Datensaetze/20141010_DatasetDocumentation.pdf) [[Dataset]](https://www.uni-ulm.de/in/mrm/forschung/datensaetze.html)


* **inD Dataset** <br>
*Bock, J., Krajewski, R., Moers, T., Runde, S., Vater, L. and Eckstein, L.* <br>
IEEE IV, 2020. [[Paper]](https://arxiv.org/pdf/1911.07602) [[Dataset]](https://levelxdata.com/ind-dataset/)


* **CITR and DUT Dataset** <br>
*Yang, D., Li, L., Redmill, K. and Özgüner, Ü.* <br>
IEEE IV, 2019. [[Paper]](https://arxiv.org/pdf/1902.00487) [[CITR Dataset]](https://github.com/dongfang-steven-yang/vci-dataset-citr) ⭐38 [[DUT Dataset]](https://github.com/dongfang-steven-yang/vci-dataset-dut) ⭐63 


* **WILDTRACK Dataset** <br>
*Chavdarova, T., Baqué, P., Bouquet, S., Maksai, A., Jose, C., Bagautdinov, T., Lettry, L., Fua, P., Van Gool, L. and Fleuret, F.* <br>
CVPR, 2018. [[Paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chavdarova_WILDTRACK_A_Multi-Camera_CVPR_2018_paper.pdf) [[Dataset]](https://www.epfl.ch/labs/cvlab/data/data-wildtrack/) 


* **STCrowd Dataset** <br>
*Cong, P., Zhu, X., Qiao, F., Ren, Y., Peng, X., Hou, Y., Xu, L., Yang, R., Manocha, D. and Ma, Y.* <br>
CVPR, 2022. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Cong_STCrowd_A_Multimodal_Dataset_for_Pedestrian_Perception_in_Crowded_Scenes_CVPR_2022_paper.pdf) [[Dataset]](https://github.com/4DVLab/STCrowd) ⭐53 [[Website]](https://4dvlab.github.io/STCrowd/)


* **Thor Dataset** <br>
*Rudenko, A., Kucner, T.P., Swaminathan, C.S., Chadalavada, R.T., Arras, K.O. and Lilienthal, A.J.* <br>
IEEE RAL, 2020. [[Paper]](https://arxiv.org/pdf/1909.04403) [[Dataset]](http://thor.oru.se/thor.html) 


* **L-CAS Dataset** <br>
*Yan, Z., Duckett, T. and Bellotto, N.* <br>
IROS, 2017. [[Paper]](https://www.researchgate.net/profile/Zhi-Yan-7/publication/321815265_Online_learning_for_human_classification_in_3D_LiDAR-based_tracking/links/5da973b092851c577eb81c06/Online-learning-for-human-classification-in-3D-LiDAR-based-tracking.pdf) [[Dataset]](https://lcas.lincoln.ac.uk/wp/research/data-sets-software/l-cas-3d-point-cloud-people-dataset/) 


* **SCAND Dataset** <br>
*Karnan, H., Nair, A., Xiao, X., Warnell, G., Pirk, S., Toshev, A., Hart, J., Biswas, J. and Stone, P.* <br>
IEEE RAL, 2022. [[Paper]](https://arxiv.org/pdf/2203.15041) [[Dataset]](https://www.cs.utexas.edu/~xiao/SCAND/SCAND.html) 


* **JRDB Dataset** <br>
*Martin-Martin, R., Patel, M., Rezatofighi, H., Shenoi, A., Gwak, J., Frankel, E., Sadeghian, A. and Savarese, S.* <br>
IEEE TPAMI, 2021. [[Paper]](https://arxiv.org/pdf/1910.11792.pdf?trk=public_post_comment-text) [[Dataset]](https://jrdb.erc.monash.edu/) 


* **FLOBOT Dataset** <br>
*Yan, Z., Schreiberhuber, S., Halmetschlager, G., Duckett, T., Vincze, M. and Bellotto, N.* <br>
ISR, 2020. [[Paper]](https://arxiv.org/pdf/2002.10158) [[Dataset]](https://lcas.github.io/FLOBOT) 


* **NCLT Dataset** <br>
*Carlevaris-Bianco, N., Ushani, A.K. and Eustice, R.M.* <br>
IJRR, 2016. [[Paper]](http://nickcarlevaris.com/pdfs/ncarlevaris-2016a.pdf) [[Dataset]](https://robots.engin.umich.edu/nclt/) 


* **MuSoHu Dataset** <br>
*Nguyen, D.M., Nazeri, M., Payandeh, A., Datar, A. and Xiao, X.* <br>
IROS, 2023. [[Paper]](https://arxiv.org/pdf/2303.14880) [[Dataset]](https://cs.gmu.edu/~xiao/Research/MuSoHu/) 


* **CrowdBot Dataset** <br>
*Paez-Granados, D., He, Y., Gonon, D., Huber, L., Billard, A.* <br>
ICCV, 2019. [[Paper]](https://motion-planning-workshop.kavrakilab.org/papers/crowdbot-dataset.pdf) [[Dataset]](https://www.epfl.ch/labs/lasa/crowdbot-dataset/) 


* **HuRoN Dataset** <br>
*Hirose, N., Shah, D., Sridhar, A. and Levine, S.* <br>
IEEE RAL, 2023. [[Paper]](https://arxiv.org/pdf/2306.01874) [[Dataset]](https://sites.google.com/view/sacson-review/home) 


* **SiT Dataset** <br>
*Bae, J.W., Kim, J., Yun, J., Kang, C., Choi, J., Kim, C., Lee, J., Choi, J. and Choi, J.W.* <br>
NeurIPS, 2024. [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/4d6a000c216974f59e597bc878cd6325-Paper-Datasets_and_Benchmarks.pdf) [[Dataset]](https://github.com/SPALaboratory/SiT-Dataset) ⭐81 [[Website]](https://spalaboratory.github.io/SiT/)


* **KITTI Dataset** <br>
*Geiger, A., Lenz, P. and Urtasun, R.* <br>
CVPR, 2012. [[Paper]](https://projet.liris.cnrs.fr/imagine/pub/proceedings/CVPR2012/data/papers/424_O3C-04.pdf) [[Dataset]](https://www.cvlibs.net/datasets/kitti/) 


* **nuScences Dataset** <br>
*Caesar, H., Bankiti, V., Lang, A.H., Vora, S., Liong, V.E., Xu, Q., Krishnan, A., Pan, Y., Baldan, G. and Beijbom, O.* <br>
CVPR, 2020. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf) [[Dataset]](https://www.nuscenes.org/nuscenes) 


* **Waymo Dataset** <br>
*Ettinger, S., Cheng, S., Caine, B., Liu, C., Zhao, H., Pradhan, S., Chai, Y., Sapp, B., Qi, C.R., Zhou, Y. and Yang, Z.* <br>
ICCV, 2021. [[Paper]](http://openaccess.thecvf.com/content/ICCV2021/papers/Ettinger_Large_Scale_Interactive_Motion_Forecasting_for_Autonomous_Driving_The_Waymo_ICCV_2021_paper.pdf) [[Dataset]](https://waymo.com/open/) 


* **BDD100K Dataset** <br>
*Yu, F., Chen, H., Wang, X., Xian, W., Chen, Y., Liu, F., Madhavan, V. and Darrell, T.* <br>
CVPR, 2020. [[Paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yu_BDD100K_A_Diverse_Driving_Dataset_for_Heterogeneous_Multitask_Learning_CVPR_2020_paper.pdf) [[Dataset]](https://www.vis.xyz/bdd100k/) 


* **A2D2 Dataset** <br>
*Geyer, J., Kassahun, Y., Mahmudi, M., Ricou, X., Durgesh, R., Chung, A.S., Hauswald, L., Pham, V.H., Mühlegg, M., Dorn, S. and Fernandez, T.* <br>
arXiv, 2020. [[Paper]](https://arxiv.org/pdf/2004.06320) [[Dataset]](https://www.a2d2.audi/a2d2/en/dataset.html) 













## <a name="simulators"></a> Simulators

* **Menge** <br>
*Curtis, S., Best, A. and Manocha, D.* <br>
Collective Dynamics, 2016. [[Paper]](https://collective-dynamics.eu/index.php/cod/article/download/A1/3) [[Code]](https://github.com/MengeCrowdSim/Menge) ⭐152


* **SEAN** <br>
*Tsoi, N., Xiang, A., Yu, P., Sohn, S.S., Schwartz, G., Ramesh, S., Hussein, M., Gupta, A.W., Kapadia, M. and Vázquez, M.* <br>
IEEE RAL, 2022. [[Paper]](https://www.nathantsoi.com/papers/SEAN_2.0_Formalizing_and_Generating_Social_Situations_for_Robot_Navigation.pdf) [[Code]](https://sean.interactive-machines.com/)


* **SEAN-EP** <br>
*Tsoi, N., Hussein, M., Fugikawa, O., Zhao, J.D. and Vázquez, M.* <br>
IROS, 2021. [[Paper]](https://arxiv.org/pdf/2012.12336) [[Code]](https://sean.interactive-machines.com/)


* **UnrealCV** <br>
*Qiu, W., Zhong, F., Zhang, Y., Qiao, S., Xiao, Z., Kim, T.S. and Wang, Y.* <br>
ACM-ICM, 2017. [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3123266.3129396) [[Code]](https://github.com/unrealcv/unrealcv) ⭐2182


* **MORSE** <br>
*Echeverria, G., Lassabe, N., Degroote, A. and Lemaignan, S.* <br>
ICRA, 2011. [[Paper]](https://www.openrobots.org/morse/material/media/pdf/paper-icra.pdf) [[Code]](https://morse-simulator.github.io/)


* **Gazebo** <br>
*Koenig, N. and Howard, A.* <br>
IROS, 2004. [[Paper]](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=79f91c1c95271a075b91e9fdca43d6c31e4cbe17) [[Code]](https://gazebosim.org/home)


* **Isaac Sim** <br>
*Mittal, M., Yu, C., Yu, Q., Liu, J., Rudin, N., Hoeller, D., Yuan, J.L., Singh, R., Guo, Y., Mazhar, H. and Mandlekar, A.* <br>
IEEE RAL, 2023. [[Paper]](https://arxiv.org/pdf/2301.04195) [[Code]](https://github.com/isaac-sim/IsaacLab) ⭐7232


* **Webots Sim** <br>
*Michel, O.* <br>
IJARS, 2004. [[Paper]](https://journals.sagepub.com/doi/pdf/10.5772/5618) [[Code]](https://cyberbotics.com/)


* **AI2-THOR** <br>
*Kolve, E., Mottaghi, R., Han, W., VanderBilt, E., Weihs, L., Herrasti, A., Deitke, M., Ehsani, K., Gordon, D., Zhu, Y. and Kembhavi, A.* <br>
arXiv, 2017. [[Paper]](https://arxiv.org/pdf/1712.05474) [[Code]](https://github.com/allenai/ai2thor) ⭐1728


* **Habitat 2.0** <br>
*Szot, A., Clegg, A., Undersander, E., Wijmans, E., Zhao, Y., Turner, J., Maestre, N., Mukadam, M., Chaplot, D.S., Maksymets, O. and Gokaslan, A.* <br>
NeurIPS, 2021. [[Paper]](https://proceedings.neurips.cc/paper/2021/file/021bbc7ee20b71134d53e20206bd6feb-Paper.pdf) [[Code]](https://aihabitat.org/docs/habitat2/)


* **Habitat 3.0** <br>
*Puig, X., Undersander, E., Szot, A., Cote, M.D., Yang, T.Y., Partsey, R., Desai, R., Clegg, A.W., Hlavac, M., Min, S.Y. and Vondruš, V.* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2310.13724) [[Code]](https://aihabitat.org/habitat3/)


* **HabiCrowd** <br>
*Vuong, A.D., Nguyen, T.T., VU, M.N., Huang, B., Nguyen, D., Binh, H.T.T., Vo, T. and Nguyen, A.* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2306.11377) [[Code]](https://github.com/Fsoft-AIC/HabiCrowd) ⭐37


* **SAPIEN** <br>
*Xiang, F., Qin, Y., Mo, K., Xia, Y., Zhu, H., Liu, F., Liu, M., Jiang, H., Yuan, Y., Wang, H. and Yi, L.* <br>
CVPR, 2020. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Xiang_SAPIEN_A_SimulAted_Part-Based_Interactive_ENvironment_CVPR_2020_paper.pdf) [[Code]](https://github.com/haosulab/SAPIEN) ⭐767


* **CrowdBot Sim** <br>
*Grzeskowiak, F., Gonon, D., Dugas, D., Paez-Granados, D., Chung, J.J., Nieto, J., Siegwart, R., Billard, A., Babel, M. and Pettré, J.* <br>
ICRA, 2021. [[Paper]](https://arxiv.org/pdf/2104.14177) [[Code]](https://gitlab.inria.fr/CrowdBot/CrowdBotChallenge)


* **iGibson** <br>
*Li, C., Xia, F., Martín-Martín, R., Lingelbach, M., Srivastava, S., Shen, B., Vainio, K., Gokmen, C., Dharan, G., Jain, T. and Kurenkov, A.* <br>
arXiv, 2021. [[Paper]](https://arxiv.org/pdf/2108.03272.pdf&quot;&gt;iGibson) [[Code]](https://github.com/StanfordVL/iGibson) ⭐806


* **CrowdNav** <br>
*Chen, C., Liu, Y., Kreiss, S. and Alahi, A.* <br>
ICRA, 2019. [[Paper]](https://arxiv.org/pdf/1809.08835) [[Code]](https://github.com/vita-epfl/CrowdNav) ⭐716


* **Arena-Rosnav** <br>
*Kästner, L., Buiyan, T., Jiao, L., Le, T.A., Zhao, X., Shen, Z. and Lambrecht, J.* <br>
IROS, 2021. [[Paper]](https://arxiv.org/pdf/2104.03616) [[Code]](https://github.com/Arena-Rosnav/arena-rosnav) ⭐118


* **nav-gym** <br>
*Lee, K., Kim, S. and Choi, J.* <br>
ICRA, 2023. [[Paper]](https://arxiv.org/pdf/2305.19746) [[Code]](https://github.com/leekwoon/nav-gym) ⭐27


* **gym-collision-avoidance** <br>
*Everett, M., Chen, Y.F. and How, J.P.* <br>
IROS, 2018. [[Paper]](https://arxiv.org/pdf/1805.01956) [[Code]](https://github.com/mit-acl/gym-collision-avoidance) ⭐320


* **navrep** <br>
*Dugas, D., Nieto, J., Siegwart, R. and Chung, J.J.* <br>
ICRA, 2021. [[Paper]](https://arxiv.org/pdf/2012.04406) [[Code]](https://github.com/ethz-asl/navrep) ⭐104


* **gym ped sim** <br>
*Tai, L., Zhang, J., Liu, M. and Burgard, W.* <br>
ICRA, 2018. [[Paper]](https://arxiv.org/pdf/1710.02543) [[Code]](https://github.com/onlytailei/gym_ped_sim) ⭐122


* **Social Gym** <br>
*Sprague, Z., Chandra, R., Holtz, J. and Biswas, J.* <br>
arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2303.05584) [[Code]](https://amrl.cs.utexas.edu/SocialGym2/)


* **RDS Sim** <br>
*Gonon, D.J., Paez-Granados, D. and Billard, A.* <br>
IEEE RAL, 2021. [[Paper]](https://ieeexplore.ieee.org/iel7/7083369/7339444/09385856.pdf) [[Code]](https://github.com/epfl-lasa/rds) ⭐24








## <a name="crowd_sim"></a> Crowd Behavior


* **RVO2** <br>
*Van Den Berg, J., Guy, S.J., Snape, J. Lin, M. and Manocha, D.* <br>
[[Code (C++)]](https://github.com/snape/RVO2) ⭐944 [[Code (Python)]](https://github.com/sybrenstuvel/Python-RVO2) ⭐234


* **UMANS** <br>
*van Toll, W., Grzeskowiak, F., Gandía, A.L., Amirian, J., Berton, F., Bruneau, J., Daniel, B.C., Jovane, A. and Pettré, J.* <br>
I3D, 2020. [[Paper]](https://inria.hal.science/hal-02497176/document) [[Code]](https://github.com/amiryanj/UMANS) ⭐4 [[Website]](https://project.inria.fr/crowdscience/project/ocsr/umans/)


* **PySocialForce** <br>
*Gao, Y.* [[Code]](https://github.com/yuxiang-gao/PySocialForce) ⭐178


* **Deep Social Force** <br>
*Kreiss, S.* [[Paper]](https://arxiv.org/pdf/2109.12081) [[Code]](https://github.com/svenkreiss/socialforce) ⭐141


* **CROMOSIM** <br>
*Faure, S.* [[Code]](https://github.com/sylvain-faure/cromosim) ⭐44 [[Website]](https://www.cromosim.fr/)


* **CrowdDynamics** <br>
*Group, C.D.* [[Code]](https://github.com/crowddynamics/crowddynamics) ⭐45


* **JuPedSim** <br>
*Dynamics, P.* [[Code]](https://github.com/PedestrianDynamics/jupedsim) ⭐80


* **Mesa** <br>
*Masad, D. and Kazil, J.L.* <br>
SciPy, 2015. [[Paper]](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=25e969b8cf94d925afc38f6cc678cf22cc523f52) [[Code]](https://github.com/projectmesa/mesa) ⭐3658 [[Website]](https://mesa.readthedocs.io/stable/)


* **Agents.jl** <br>
*Datseris, G., Vahdati, A.R. and DuBois, T.C.* <br>
Simulation, 2024, [[Paper]](https://journals.sagepub.com/doi/pdf/10.1177/00375497211068820) [[Code]](https://github.com/JuliaDynamics/Agents.jl) ⭐905 [[Website]](https://juliadynamics.github.io/Agents.jl/stable/)


* **Vadere** <br>
*Kleinmeier, B., Zönnchen, B., Gödel, M. and Köster, G.* <br>
arXiv, 2019. [[Paper]](https://arxiv.org/pdf/1907.09520) [[Code]](https://github.com/learup/vadere) ⭐2 [[Website]](https://www.vadere.org/)













## <a name="contributing"></a> Contributing
To add a new paper via pull request: Fork the repo, edit `README.md`, and add the new paper at the correct position with the following format. <br>

```
* **Paper Title** <br>
*Authors (Harvard Style)* <br>
Conference, Year. [[Paper]](link) [[Code]](link) [[Video]](link) [[Website]](link)
```
