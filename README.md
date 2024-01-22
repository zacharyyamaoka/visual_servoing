"I build to understand" - Sebastian Thrun

Goal - Basically Reinforcement Learning.

Find a policy that maximises the reward.

I think that model based RL, using supervised/unsupervised learning to build representations has alot of promise!

Sequence of Camera images (video), motor positions, torques -> Sequence of motor commands

---

To start I should likely do a classical technique


First some References:

https://spectrum.ieee.org/ai-guided-robots-are-ready-to-sort-your-recyclables

YOLO detection for real time computer detection

"We train our systems by giving them images of materials belonging to each category, sourced from recycling facilities around the world."

"We continuously collect random samples from all the facilities that use our systems, and then annotate them, add them to our database, and retrain our neural networks. We also test our networks to find models that perform best on target material and do targeted additional training on materials that our systems have trouble identifying correctly."

"In general, neural networks are susceptible to learning the wrong thing. Pictures of cows are associated with milk packaging, which is commonly produced as a fiber carton or HDPE container. But milk products can also be packaged in other plastics"

https://www.instructables.com/Recycle-Sorting-Robot/

Basic steps are likely the same.

Google Coral USB Acclerator - Interesting


ML Infastructure:

https://insights.sei.cmu.edu/blog/a-hitchhikers-guide-to-ml-training-infrastructure/
https://fullstackdeeplearning.com/course/2022/

CV Papers:
https://arxiv.org/abs/2106.02740


Existing Datasets:
https://github.com/dbash/zerowaste/?tab=readme-ov-file
https://github.com/AgaMiko/waste-datasets-review

Research Papers
- ZeroWaste Dataset: Towards Deformable Object Segmentation in Cluttered Scenes

Dataset is collacted in actual application, this avoids distirbution shift. ChatGBT is trained and tested on the same task. Makes it simpler. +1 to Teleoperation

* Dealing with class imbalances

*On Mask RCNN "Yet due to their data-hungry nature, these methods rely on large volumes of annotated data for training, which can be challenging and expensive, especially in specialized application scenarios"

* Use of semi-supervised methods to increase dataset size, make data labeling easier

* Damping pads used to counter ground vibrations from machinery 