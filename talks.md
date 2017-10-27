**Eric Xing** (Professor, CMU)

Title: System and algorithm co-design for distributed machine learning: theory and practice
 
Abstract:
The rise of Big Data has led to new demands for Machine Learning systems to learn complex models with millions to billions of parameters that promise adequate capacity to digest massive datasets and offer powerful predictive analytics thereupon. A recent trend toward building new distributed frameworks for machine learning at massive scale is known as “system and algorithm co-design” -- system designs are tailored to the unique properties of ML algorithms, and algorithms are re-designed to better fit into the system architecture. In this talk, I discuss a series of interesting questions emerged from such work that inspire new engineering design and theoretical analysis: How to distribute an ML problem over a cluster? How to bridge ML computation with inter-machine communication? How to perform such communication? What should be communicated between machines? I show how one can explore the underlying statistical and algorithmic characteristics unique to ML programs but not typical in traditional computer programs in designing the system architecture to achieve significant, universal, and theoretically sound power-up of machine learning program across the board (e.g., a 20X speedup of deep learning models over tensor-flow on GPU cluster, and a 200X speedup of several machine learning algorithms over spark on CPU cluster). I will end with a briefly introduction of the Petuum system based on such interdisciplinary innovations, and views on opportunities for researchers and practitioners to further shape and grow the area that lies between ML and systems.

Bio:
Eric P. Xing is a Professor of Computer Science at Carnegie Mellon University, and the Associate Department Head of the Machine Learning Department there. He has founded the Artificial Intelligence Platform and Solution company Petuum Inc., and serves as CEO and Chief Scientist. Professor Xing completed his undergraduate study at Tsinghua University, and holds a PhD in Molecular Biology and Biochemistry from the State University of New Jersey, and a PhD in Computer Science from the University of California, Berkeley. His main research interests are the development of machine learning and statistical methodology, and large-scale computational system and architectures, for solving problems involving automated learning, reasoning, and decision-making in high-dimensional, multimodal, and dynamic possible worlds in artificial, biological, and social systems. Prof. Xing currently holds or has held the following positions: associate editor of the Journal of the American Statistical Association (JASA), Annals of Applied Statistics (AOAS), IEEE Journal of Pattern Analysis and Machine Intelligence (PAMI) and the PLoS Journal of Computational Biology; action editor of the Machine Learning Journal (MLJ) and Journal of Machine Learning Research (JMLR); member of the United States Department of Defense Advanced Research Projects Agency (DARPA) Information Science and Technology (ISAT) advisory group. He is a recipient of the National Science Foundation (NSF) Career Award, the Alfred P. Sloan Research Fellowship in Computer Science, the United States Air Force Office of Scientific Research Young Investigator Award, the IBM Open Collaborative Research Faculty Award, as well as several best paper awards. Prof Xing is a board member of the International Machine Learning Society; in 2014, he served as the Program Chair of the International Conference of Machine Learning (ICML), and in 2019, he will serve as the General Chair of ICML. He was elected a Fellow of the Association of Advancement of Artificial Intelligence in 2015.


***

**Paul Barham** (Principal Scientist, Google Brain)

Title: Future Directions in Large Scale Machine Learning, or... Programming Supercomputers from Python
 
Abstract:
In this talk I will describe recent changes and future directions for machine learning systems like TensorFlow, driven by the requirements of a rapidly growing ML research community. I will discuss evolution of programming models and ML model architectures, and the exciting opportunities provided by powerful new hardware platforms (TPUs).

Bio:
Paul Barham is currently a Principal Scientist in the Google Brain team working on low-level performance aspects of the TensorFlow system, most recently adding support for the next generation TPUv2 hardware platform.  Prior to joining Google, he spent 4 years as a Principal Researcher at Microsoft Research in Silicon Valley and 12 years at MSR Cambridge UK where he led the Systems and Networking group.  
His research interests include performance analysis of distributed systems, operating systems and virtualization.  Past work includes Naiad, Microsoft HoloLens, the Barrelfish multi-kernel operating system, the Xen virtual machine monitor, the Singularity managed code research OS, Vigilante (a system to automatically prevent internet worms), Magpie, Constellation, and the Nemesis operating system.

***

**Joseph Gonzalez** (Assistant Professor, UC Berkeley)

Title: RISE to the Challenges of AI Systems

Abstract:
A long-standing grand challenge in computing is to enable machines to act autonomously and intelligently: to rapidly and repeatedly take appropriate actions based on information in the world around them.  Driven by trends in the data economy, rapid progress in AI, and an increasingly programmable physical world we are at an inflection point which demands a new class of AI system.  This new class of systems will go beyond training models at scale, to connecting models with the world, rendering predictions in real-time under heavy query load, adapting to new observations and contexts.  These systems will need to be composable and elastically scalable to accommodate new technologies and variations in workloads.  Operating in the physical world, observing intimate details of our lives, and making critical decisions, these systems must also be secure. 

At UC Berkeley we are starting a new five year effort to study the design of Real-time, Intelligent, and Secure (RISE) Systems that brings together researchers across AI, robotics, security, and data systems.  In this talk, I will present our research vision and then dive into ongoing projects in prediction serving and hardware enabled distributed analytics on encrypted data.  

Bio: 
Joseph Gonzalez is an assistant professor at UC Berkeley and co-director of the UC Berkeley RISE Lab where he studies the design of algorithms, abstractions, and systems for scalable machine learning.  Before joining UC Berkeley, Joseph co-founded Turi Inc. (formerly GraphLab) to develop AI tools for data scientists and later sold Turi to Apple. Joseph holds a PhD in Machine Learning from Carnegie Mellon University and is a member of the Apache Spark PMC.

***

**Bryan Catanzaro** (Vice President of Applied Deep Learning Research, Nvidia)

Title: Accelerated Computing for AI
 
Abstract:
Training and deploying deep neural networks is computationally intensive, which has led to significant interest in accelerators for AI, including GPUs, TPUs, and various custom processors with a range of goals and capabilities. Although the need for accelerated computing seems clear, perhaps less appreciated is the need for programmability to accompany acceleration.
In this talk, I will discuss Volta, NVIDIA's newest GPU, designed for AI, including programmable Tensor Cores that dramatically accelerate training and deployment, as well as high-bandwidth off-chip memory and inter-processor interconnect. I'll also discuss the software libraries that enable researchers using Volta to create new types of networks efficiently.
 
Bio:
Bryan Catanzaro is VP of Applied Deep Learning Research at NVIDIA, where he leads a team solving problems in domains ranging from video games to chip design using deep learning. Bryan earned his PhD from Berkeley, where he focused on parallel computing, machine learning, and programming models. He earned his MS and BS from Brigham Young University, where he worked on higher radix floating-point representations for FPGAs.
Bryan worked at Baidu to create next generation systems for training and deploying deep learning models for speech recognition. Before that, he was a researcher at NVIDIA, where he worked on programming modelsfor parallel processors, as well as libraries for deep learning, which culminated in the creation of the widely used CUDNN library. 

***

**Matei Zaharia** (Assistant Professor, Stanford)

***

**Yangqing Jia** (Research Scientist in Applied ML, Facebook)


***

**Alex Smola** (Director of Machine Learning, Amazon)

Title: The components of a High Performance Deep Learning Framework

Abstract:
Apache MxNet offers excellent performance for training and inference on a variety of programming languages (Python, R, C++, Perl, Scala), hardware platforms (ranging from 16 GPU servers in the cloud to mobile devices), and programming paradigms (symbolic and imperative). In this talk we give an overview over the design decisions guiding model definition, compute graph optimization, parameter server, and optimization for a wide range of hardware platforms using TVM.

***

**Tianqi Chen** (UW)

Title: TVM, An End to end IR Stack for Deep Learning Systems

Abstract:
Deep learning has become ubiquitous and indispensable. Part of this revolution has been fueled by scalable deep learning systems. In this talk, I am going to talk about TVM: a unified intermediate representation (IR) stack that will close the gap between the productivity-focused deep learning frameworks, and the performance- or efficiency-oriented hardware backends.   TVM is a novel framework that can: Represent and optimize the common deep learning computation workloads for CPUs, GPUs, and other specialized hardware; Automatically transform the computation graph to minimize memory utilization, optimize data layout and fuse computation patterns; Provide an end-to-end compilation from existing front-end frameworks down to bare-metal hardware. I will talk about the problems and chance of learning system research around TVM stack and NNVM compiler.
 
Bio:
Tianqi is a PhD student in University of Washington, working on machine learning and systems. He received his bachelor and master degrees from Shanghai Jiao Tong University. He is recipient of a Google PhD Fellowship in Machine Learning.


***

**Takuya Akiba** (Researcher, Preferred Networks)

Title: ChainerMN: Scalable Distributed Deep Learning with Chainer

Abstract:
We'll present ChainerMN, a multi-node distributed deep learning framework. Even though GPUs are continuously gaining more computation throughput, it is still very time-consuming to train state-of-the-art deep neural network models. For better scalability and productivity, it is paramount to accelerate the training process by using multiple GPUs. To enable high-performance and flexible distributed training, we developed ChainerMN, built on top of Chainer. We'll first introduce the basic approaches to distributed deep learning. Then, we'll explain the design choice, basic usage, and implementation details of Chainer and ChainerMN. We'll report benchmark results using hundreds of GPUs and discuss the future directions of distributed deep learning.

Bio:
Takuya Akiba is a researcher at Preferred Networks, Inc., working on research and development for making deep learning faster and more scalable. He received a Ph.D. in information science and technology from the University of Tokyo, Japan, in 2015. He is a Kaggle Master.

***

**Jun Xu** (Professor, Institute of Computing Technology, Chinese Academy of Sciences)

Title: Ease the Process of Machine Learning with Dataflow

Abstract: 
The success application of machine learning relies not only on the advanced algorithms, but also on the systems that help users to apply these algorithms. In the talk, I will present a general-purpose dataflow-based system for easing the process of applying machine learning to real tasks. In the system, a learning task is formulated as a dataflow DAG where the nodes and edges represent the algorithms and the flow of data, respectively. Interactive GUI is implemented for enabling the users to create, configure, submit, and monitor a machine learning task in a drag-and-drop manner. The system has been deployed as a web service (http://159.226.40.104:18080/dev/) and the source code has been released at Github (http://www.github.com/ict-bda/easyml). 

Bio: 
Dr. Jun Xu received his B.E. and Ph.D. in Computer Science from Nankai University, in 2001 and 2006, respectively. After that, he worked as an associate researcher, researcher, and senior researcher at Microsoft Research Asia and Huawei Noah's Ark Lab. In 2014, he joined Institute of Computing Technology, Chinese Academy of Sciences as a professor of computer science. Jun Xu's research interests focus on applying machine learning to information retrieval. He has published over 50 papers and 1 monograph at top international journals and conferences, including TOIS, JMLR, SIGIR, CIKM, ACL etc. Jun Xu has been active in the research communities and severed or is serving the top conferences, journals, and publishers. For example, in 2017, he was the Senior PCs of SIGIR '17 and ACML 2017; PC members of KDD ’17, NIPS '17, CIKM '17, AAAI '18, and WSDM '18; reviewers of NOW publishers, TOIS, TKDE etc. Jun Xu has also been working on the development of several commercial products (e.g., Microsoft Bing 2010, Microsoft Office 2011, and Huawei GTS search) and is leading the Easy Machine Learning open source project. 

***

**Siddhartha Sen** (Researcher, Microsoft Research)

Title: Decision Service: Bringing the Power of Offline Evaluation to Online Decision Making

Abstract:
Applications and systems are constantly faced with decisions that require picking from a set of actions based on contextual information. Reinforcement-based learning algorithms such as contextual bandits can be very effective in these settings, but applying them in practice faces fundamental challenges, and no general system exists that supports them completely. To address this problem, we created the Decision Service: the first end-to-end system for contextual learning. The Decision Service enables all aspects of contextual bandit learning using a loop of four system abstractions: explore (the decision space), log, learn, and deploy. These abstractions, together with a carefully synthesized ML methodology, enable a powerful capability called *offline evaluation*, which allows us to accurately evaluate policies without deploying them. The Decision Service has a simple user interface and has been deployed with strong results in a variety of settings, including content recommendation, customer tech support, and machine failure handling. The Decision Service is publicly offered as a Microsoft Cognitive Service and is also available as open-source.

Bio:
Siddhartha Sen is a Researcher at Microsoft Research in New York City, and previously a researcher at the MSR Silicon Valley lab. He creates distributed systems that use novel data structures and algorithms to deliver unprecedented functionality or performance. Some of his data structures have been incorporated into undergraduate textbooks and curricula. Recently, he has generalized this approach by using contextual machine learning to optimize various decisions in Microsoft’s cloud infrastructure. Siddhartha received his BS degrees in computer science and mathematics and his MEng degree in computer science from MIT. From 2004-2007 he worked as a developer at Microsoft and built a network load balancer for Windows Server. He returned to academia and completed his PhD from Princeton University in 2013. Siddhartha received the first Google Fellowship in Fault-Tolerant Computing in 2009, the best student paper award at PODC 2012, and the best paper award at ASPLOS 2017.