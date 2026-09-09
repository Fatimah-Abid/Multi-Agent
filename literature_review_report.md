# Systematic Literature Review: Distributed Systems

**Generated:** September 09, 2026
**Papers Analyzed:** 25
**Total Citations Across Papers:** 0
**Average Citations per Paper:** 0

---

## Abstract

This systematic literature review provides a comprehensive analysis of 25 research papers relevant to the specified research topic. The corpus includes 13 papers published since 2022, representing approximately 52 percent of the analyzed literature, indicating recent research activity in this domain. Citation analysis reveals limited research impact to date, which may indicate an emerging research area with significant growth potential. Key research areas identified in the literature include Optimization, Security and Privacy, Mobile and Sensor Computing, Detection and Classification. Methodological analysis reveals that Mobile/Sensor-based, CNN, Machine Learning represent the dominant approaches employed in current research. This review synthesizes current knowledge, compares methodological approaches, identifies critical research gaps, and proposes future research directions to advance the field.

---

## 1. Introduction

This systematic literature review provides a comprehensive analysis of research on Distributed Systems. A total of 25 relevant papers were identified and analyzed using academic databases including Semantic Scholar and arXiv. The review synthesizes existing knowledge, compares methodological approaches, identifies research gaps, and proposes future research directions.

---

## 2. Papers Analyzed


### Paper 1: The Devil Is in the Details: An Efficient Convolutional Neural Network for Transport Mode Detection

- **Source:** arXiv
- **Publication Year:** 2021
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Hugues Moreau, Andréa Vassilev, Liming Chen
- **Abstract:** Transport mode detection is a classification problem aiming to design an algorithm that can infer the transport mode of a user given multimodal signals (GPS and/or inertial sensors). It has many applications, such as carbon footprint tracking, mobility behaviour analysis, or real-time door-to-door smart planning. Most current approaches rely on a classification step using Machine Learning techniques, and, like in many other classification problems, deep learning approaches usually achieve better results than traditional machine learning ones using handcrafted features. Deep models, however, have a notable downside: they are usually heavy, both in terms of memory space and processing cost. We show that a small, optimized model can perform as well as a current deep model. During our experiments on the GeoLife and SHL 2018 datasets, we obtain models with tens of thousands of parameters, that is, 10 to 1,000 times less parameters and operations than networks from the state of the art, which still reach a comparable performance. We also show, using the aforementioned datasets, that the current preprocessing used to deal with signals of different lengths is suboptimal, and we provide better replacements. Finally, we introduce a way to use signals with different lengths with the lighter Convolutional neural networks, without using the heavier Recurrent Neural Networks.

---


### Paper 2: 6G Enabled Advanced Transportation Systems

- **Source:** arXiv
- **Publication Year:** 2023
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Ruiqi Liu, Meng Hua, Ke Guan
- **Abstract:** With the emergence of communication services with stringent requirements such as autonomous driving or on-flight Internet, the sixth-generation (6G) wireless network is envisaged to become an enabling technology for future transportation systems. In this paper, two ways of interactions between 6G networks and transportation are extensively investigated. On one hand, the new usage scenarios and capabilities of 6G over existing cellular networks are firstly highlighted. Then, its potential in seamless and ubiquitous connectivity across the heterogeneous space-air-ground transportation systems is demonstrated, where railways, airplanes, high-altitude platforms and satellites are investigated. On the other hand, we reveal that the introduction of 6G guarantees a more intelligent, efficient and secure transportation system. Specifically, technical analysis on how 6G can empower future transportation is provided, based on the latest research and standardization progresses in localization, integrated sensing and communications, and security. The technical challenges and insights for a road ahead are also summarized for possible inspirations on 6G enabled advanced transportation.

---


### Paper 3: Inferring transportation modes from GPS trajectories using a convolutional neural network

- **Source:** arXiv
- **Publication Year:** 2018
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Sina Dabiri, Kevin Heaslip
- **Abstract:** Identifying the distribution of users' transportation modes is an essential part of travel demand analysis and transportation planning. With the advent of ubiquitous GPS-enabled devices (e.g., a smartphone), a cost-effective approach for inferring commuters' mobility mode(s) is to leverage their GPS trajectories. A majority of studies have proposed mode inference models based on hand-crafted features and traditional machine learning algorithms. However, manual features engender some major drawbacks including vulnerability to traffic and environmental conditions as well as possessing human's bias in creating efficient features. One way to overcome these issues is by utilizing Convolutional Neural Network (CNN) schemes that are capable of automatically driving high-level features from the raw input. Accordingly, in this paper, we take advantage of CNN architectures so as to predict travel modes based on only raw GPS trajectories, where the modes are labeled as walk, bike, bus, driving, and train. Our key contribution is designing the layout of the CNN's input layer in such a way that not only is adaptable with the CNN schemes but represents fundamental motion characteristics of a moving object including speed, acceleration, jerk, and bearing rate. Furthermore, we ameliorate the quality of GPS logs through several data preprocessing steps. Using the clean input layer, a variety of CNN configurations are evaluated to achieve the best CNN architecture. The highest accuracy of 84.8% has been achieved through the ensemble of the best CNN configuration. In this research, we contrast our methodology with traditional machine learning algorithms as well as the seminal and most related studies to demonstrate the superiority of our framework.

---


### Paper 4: Exploring the Roles of Large Language Models in Reshaping Transportation Systems: A Survey, Framework, and Roadmap

- **Source:** arXiv
- **Publication Year:** 2025
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Tong Nie, Jian Sun, Wei Ma
- **Abstract:** Modern transportation systems face pressing challenges due to increasing demand, dynamic environments, and heterogeneous information integration. The rapid evolution of Large Language Models (LLMs) offers transformative potential to address these challenges. Extensive knowledge and high-level capabilities derived from pretraining evolve the default role of LLMs as text generators to become versatile, knowledge-driven task solvers for intelligent transportation systems. This survey first presents LLM4TR, a novel conceptual framework that systematically categorizes the roles of LLMs in transportation into four synergetic dimensions: information processors, knowledge encoders, component generators, and decision facilitators. Through a unified taxonomy, we systematically elucidate how LLMs bridge fragmented data pipelines, enhance predictive analytics, simulate human-like reasoning, and enable closed-loop interactions across sensing, learning, modeling, and managing tasks in transportation systems. For each role, our review spans diverse applications, from traffic prediction and autonomous driving to safety analytics and urban mobility optimization, highlighting how emergent capabilities of LLMs such as in-context learning and step-by-step reasoning can enhance the operation and management of transportation systems. We further curate practical guidance, including available resources and computational guidelines, to support real-world deployment. By identifying challenges in existing LLM-based solutions, this survey charts a roadmap for advancing LLM-driven transportation research, positioning LLMs as central actors in the next generation of cyber-physical-social mobility ecosystems. Online resources can be found in the project page: https://github.com/tongnie/awesome-llm4tr.

---


### Paper 5: Online Prediction-Assisted Safe Reinforcement Learning for Electric Vehicle Charging Station Recommendation in Dynamically Coupled Transportation-Power Systems

- **Source:** arXiv
- **Publication Year:** 2024
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Qionghua Liao, Guilong Li, Jiajie Yu
- **Abstract:** With the proliferation of electric vehicles (EVs), the transportation network and power grid become increasingly interdependent and coupled via charging stations. The concomitant growth in charging demand has posed challenges for both networks, highlighting the importance of charging coordination. Existing literature largely overlooks the interactions between power grid security and traffic efficiency. In view of this, we study the en-route charging station (CS) recommendation problem for EVs in dynamically coupled transportation-power systems. The system-level objective is to maximize the overall traffic efficiency while ensuring the safety of the power grid. This problem is for the first time formulated as a constrained Markov decision process (CMDP), and an online prediction-assisted safe reinforcement learning (OP-SRL) method is proposed to learn the optimal and secure policy by extending the PPO method. To be specific, we mainly address two challenges. First, the constrained optimization problem is converted into an equivalent unconstrained optimization problem by applying the Lagrangian method. Second, to account for the uncertain long-time delay between performing CS recommendation and commencing charging, we put forward an online sequence-to-sequence (Seq2Seq) predictor for state augmentation to guide the agent in making forward-thinking decisions. Finally, we conduct comprehensive experimental studies based on the Nguyen-Dupuis network and a large-scale real-world road network, coupled with IEEE 33-bus and IEEE 69-bus distribution systems, respectively. Results demonstrate that the proposed method outperforms baselines in terms of road network efficiency, power grid safety, and EV user satisfaction. The case study on the real-world network also illustrates the applicability in the practical context.

---


### Paper 6: Using coarse GPS data to quantify city-scale transportation system resilience to extreme events

- **Source:** arXiv
- **Publication Year:** 2015
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Brian Donovan, Daniel B. Work
- **Abstract:** This article proposes a method to quantitatively measure the resilience of transportation systems using GPS data from taxis. The granularity of the GPS data necessary for this analysis is relatively coarse; it only requires coordinates for the beginning and end of trips, the metered distance, and the total travel time. The method works by computing the historical distribution of pace (normalized travel times) between various regions of a city and measuring the pace deviations during an unusual event. This method is applied to a dataset of nearly 700 million taxi trips in New York City, which is used to analyze the transportation infrastructure resilience to Hurricane Sandy. The analysis indicates that Hurricane Sandy impacted traffic conditions for more than five days, and caused a peak delay of two minutes per mile. Practically, it identifies that the evacuation caused only minor disruptions, but significant delays were encountered during the post-disaster reentry process. Since the implementation of this method is very efficient, it could potentially be used as an online monitoring tool, representing a first step toward quantifying city scale resilience with coarse GPS data.

---


### Paper 7: Transportation mode recognition based on low-rate acceleration and location signals with an attention-based multiple-instance learning network

- **Source:** arXiv
- **Publication Year:** 2024
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Christos Siargkas, Vasileios Papapanagiotou, Anastasios Delopoulos
- **Abstract:** Transportation mode recognition (TMR) is a critical component of human activity recognition (HAR) that focuses on understanding and identifying how people move within transportation systems. It is commonly based on leveraging inertial, location, or both types of signals, captured by modern smartphone devices. Each type has benefits (such as increased effectiveness) and drawbacks (such as increased battery consumption) depending on the transportation mode (TM). Combining the two types is challenging as they exhibit significant differences such as very different sampling rates. This paper focuses on the TMR task and proposes an approach for combining the two types of signals in an effective and robust classifier. Our network includes two sub-networks for processing acceleration and location signals separately, using different window sizes for each signal. The two sub-networks are designed to also embed the two types of signals into the same space so that we can then apply an attention-based multiple-instance learning classifier to recognize TM. We use very low sampling rates for both signal types to reduce battery consumption. We evaluate the proposed methodology on a publicly available dataset and compare against other well known algorithms.

---


### Paper 8: Exploring Preferences for Transportation Modes in the City of Munich after the Recent Incorporation of Ride-Hailing Companies

- **Source:** arXiv
- **Publication Year:** 2022
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Maged Shoman, Ana Tsui Moreno
- **Abstract:** The growth of ridehailing (RH) companies over the past few years has affected urban mobility in numerous ways. Despite widespread claims about the benefits of such services, limited research has been conducted on the topic. This paper assesses the willingness of Munich transportation users to pay for RH services. Realizing the difficulty of obtaining data directly from RH companies, a stated preference survey was designed. The dataset includes responses from 500 commuters. Sociodemographic attributes, current travel behavior and transportation mode preference in an 8 km trip scenario using RH service and its similar modes (auto and transit), were collected. A multinomial logit model was used to estimate the time and cost coefficients for using RH services across income groups, which was then used to estimate the value of time (VOT) for RH. The model results indicate RH services popularity among those aged 18 to 39, larger households and households with fewer autos. Higher income groups are also willing to pay more for using RH services. To examine the impact of RH services on modal split in the city of Munich, we incorporated RH as a new mode into an existing nested logit mode choice model using an incremental logit. Travel time, travel cost and VOT were used as measures for the choice commuters make when choosing between RH and its closest mode, metro. A total of 20 scenarios were evaluated at four different congestion levels and four price levels to reflect the demand in response to acceptable costs and time tradeoffs.

---


### Paper 9: Toward Copyright Integrity and Verifiability via Multi-Bit Watermarking for Intelligent Transportation Systems

- **Source:** arXiv
- **Publication Year:** 2025
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Yihao Wang, Lingxiao Li, Yifan Tang
- **Abstract:** Intelligent transportation systems (ITS) use advanced technologies such as artificial intelligence to significantly improve traffic flow management efficiency, and promote the intelligent development of the transportation industry. However, if the data in ITS is attacked, such as tampering or forgery, it will endanger public safety and cause social losses. Therefore, this paper proposes a watermarking that can verify the integrity of copyright in response to the needs of ITS, termed ITSmark. ITSmark focuses on functions such as extracting watermarks, verifying permission, and tracing tampered locations. The scheme uses the copyright information to build the multi-bit space and divides this space into multiple segments. These segments will be assigned to tokens. Thus, the next token is determined by its segment which contains the copyright. In this way, the obtained data contains the custom watermark. To ensure the authorization, key parameters are encrypted during copyright embedding to obtain cipher data. Only by possessing the correct cipher data and private key, can the user entirely extract the watermark. Experiments show that ITSmark surpasses baseline performances in data quality, extraction accuracy, and unforgeability. It also shows unique capabilities of permission verification and tampered location tracing, which ensures the security of extraction and the reliability of copyright verification. Furthermore, ITSmark can also customize the watermark embedding position and proportion according to user needs, making embedding more flexible.

---


### Paper 10: Cybersecurity in Transportation Systems: Policies and Technology Directions

- **Source:** arXiv
- **Publication Year:** 2025
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Ostonya Thomas, M Sabbir Salek, Jean-Michel Tine
- **Abstract:** The transportation industry is experiencing vast digitalization as a plethora of technologies are being implemented to improve efficiency, functionality, and safety. Although technological advancements bring many benefits to transportation, integrating cyberspace across transportation sectors has introduced new and deliberate cyber threats. In the past, public agencies assumed digital infrastructure was secured since its vulnerabilities were unknown to adversaries. However, with the expansion of cyberspace, this assumption has become invalid. With the rapid advancement of wireless technologies, transportation systems are increasingly interconnected with both transportation and non-transportation networks in an internet-of-things ecosystem, expanding cyberspace in transportation and increasing threats and vulnerabilities. This study investigates some prominent reasons for the increase in cyber vulnerabilities in transportation. In addition, this study presents various collaborative strategies among stakeholders that could help improve cybersecurity in the transportation industry. These strategies address programmatic and policy aspects and suggest avenues for technological research and development. The latter highlights opportunities for future research to enhance the cybersecurity of transportation systems and infrastructure by leveraging hybrid approaches and emerging technologies.

---


### Paper 11: Multi-Point Detection of the Powerful Gamma Ray Burst GRB221009A Propagation through the Heliosphere on October 9, 2022

- **Source:** arXiv
- **Publication Year:** 2023
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Andrii Voshchepynets, Oleksiy Agapitov, Lynn Wilson
- **Abstract:** We present the results of processing the effects of the powerful Gamma Ray Burst GRB221009A captured by the charged particle detectors (electrostatic analyzers and solid-state detectors) onboard spacecraft at different points in the heliosphere on October 9, 2022. To follow the GRB221009A propagation through the heliosphere we used the electron and proton flux measurements from solar missions Solar Orbiter and STEREO-A; Earth magnetosphere and the solar wind missions THEMIS and Wind; meteorological satellites POES15, POES19, MetOp3; and MAVEN - a NASA mission orbiting Mars. GRB221009A had a structure of four bursts: less intense Pulse 1 - the triggering impulse - was detected by gamma-ray observatories at 131659 UT (near the Earth); the most intense Pulses 2 and 3 were detected on board all the spacecraft from the list, and Pulse 4 detected in more than 500 s after Pulse 1. Due to their different scientific objectives, the spacecraft, which data was used in this study, were separated by more than 1 AU (Solar Orbiter and MAVEN). This enabled tracking GRB221009A as it was propagating across the heliosphere. STEREO-A was the first to register Pulse 2 and 3 of the GRB, almost 100 seconds before their detection by spacecraft in the vicinity of Earth. MAVEN detected GRB221009A Pulses 2, 3, and 4 at the orbit of Mars about 237 seconds after their detection near Earth. By processing the time delays observed we show that the source location of the GRB221009A was at RA 288.5 degrees, Dec 18.5 degrees (J2000) with an error cone of 2 degrees

---


### Paper 12: A Perspective on the Challenges and Opportunities for Privacy-Aware Big Transportation Data

- **Source:** arXiv
- **Publication Year:** 2018
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Godwin Badu-Marfo, Bilal Farooq, Zachary Patterson
- **Abstract:** In recent years, and especially since the development of the smartphone, enormous amounts of data relevant for transportation have become available. These data hold out the potential to redefine how transportation system (i.e. design, planning and operations) is done. While researchers in both academia and industry are making advances in using this data to transportation system ends (e.g. information inference from collected data), little attention has been paid to four larger scale challenges that will need to be overcome if the potential for Big Transportation Data is to be harnessed for transportation decision-making purposes. This paper aims to provide awareness of these large-scale challenges and provides insight into how we believe these challenges are likely to be met.

---


### Paper 13: Behavioural Change Support Intelligent Transportation Applications

- **Source:** arXiv
- **Publication Year:** 2017
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Efthimios Bothos, Babis Magoutas, Brian Caulfield
- **Abstract:** This workshop invites researchers and practitioners to participate in exploring behavioral change support intelligent transportation applications. We welcome submissions that explore intelligent transportation systems (ITS), which interact with travelers in order to persuade them or nudge them towards sustainable transportation behaviors and decisions. Emerging opportunities including the use of data and information generated by ITS and users' mobile devices in order to render personalized, contextualized and timely transport behavioral change interventions are in our focus. We invite submissions and ideas from domains of ITS including, but not limited to, multi-modal journey planners, advanced traveler information systems and in-vehicle systems. The expected outcome will be a deeper understanding of the challenges and future research directions with respect to behavioral change support through ITS.

---


### Paper 14: Trends and Characteristics of High-Frequency Type II Bursts Detected by CALLISTO Spectrometers

- **Source:** arXiv
- **Publication Year:** 2021
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** A. C. Umuhire, J. Uwamahoro, K. Sasikumar Raja
- **Abstract:** Solar radio type II bursts serve as early indicators of incoming geo-effective space weather events such as coronal mass ejections (CMEs). In order to investigate the origin of high-frequency type II bursts (HF type II bursts), we have identified 51 of them (among 180 type II bursts from SWPC reports) that are observed by ground-based Compound Astronomical Low-cost Low-frequency Instrument for Spectroscopy and Transportable Observatory (CALLISTO) spectrometers and whose upper-frequency cutoff (of either fundamental or harmonic emission) lies in between 150 MHz-450 MHz during 2010-2019. We found that 60% of HF type II bursts, whose upper-frequency cutoff $\geq$ 300 MHz originate from the western longitudes. Further, our study finds a good correlation $\sim $ 0.73 between the average shock speed derived from the radio dynamic spectra and the corresponding speed from CME data. Also, we found that analyzed HF type II bursts are associated with wide and fast CMEs located near the solar disk. In addition, we have analyzed the spatio-temporal characteristics of two of these high-frequency type II bursts and compared the derived from radio observations with those derived from multi-spacecraft CME observations from SOHO/LASCO and STEREO coronagraphs.

---


### Paper 15: A One-Dimensional Energy Balance Model Parameterization for the Formation of CO2 Ice on the Surfaces of Eccentric Extrasolar Planets

- **Source:** arXiv
- **Publication Year:** 2025
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Vidya Venkatesan, Aomawa L. Shields, Russell Deitrick
- **Abstract:** Eccentric planets may spend a significant portion of their orbits at large distances from their host stars, where low temperatures can cause atmospheric CO2 to condense out onto the surface, similar to the polar ice caps on Mars. The radiative effects on the climates of these planets throughout their orbits would depend on the wavelength-dependent albedo of surface CO2 ice that may accumulate at or near apoastron and vary according to the spectral energy distribution of the host star. To explore these possible effects, we incorporated a CO2 ice-albedo parameterization into a one-dimensional energy balance climate model. With the inclusion of this parameterization, our simulations demonstrated that F-dwarf planets require 29% more orbit-averaged flux to thaw out of global water ice cover compared with simulations that solely use a traditional pure water ice-albedo parameterization. When no eccentricity is assumed, and host stars are varied, F-dwarf planets with higher bond albedos relative to their M-dwarf planet counterparts require 30% more orbit-averaged flux to exit a water snowball state. Additionally, the intense heat experienced at periastron aids eccentric planets in exiting a snowball state with a smaller increase in instellation compared with planets on circular orbits; this enables eccentric planets to exhibit warmer conditions along a broad range of instellation. This study emphasizes the significance of incorporating an albedo parameterization for the formation of CO2 ice into climate models to accurately assess the habitability of eccentric planets, as we show that, even at moderate eccentricities, planets with Earth-like atmospheres can reach surface temperatures cold enough for the condensation of CO2 onto their surfaces, as can planets receiving low amounts of instellation on circular orbits.

---


### Paper 16: FlexPool: A Distributed Model-Free Deep Reinforcement Learning Algorithm for Joint Passengers & Goods Transportation

- **Source:** arXiv
- **Publication Year:** 2020
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Kaushik Manchella, Abhishek K. Umrawal, Vaneet Aggarwal
- **Abstract:** The growth in online goods delivery is causing a dramatic surge in urban vehicle traffic from last-mile deliveries. On the other hand, ride-sharing has been on the rise with the success of ride-sharing platforms and increased research on using autonomous vehicle technologies for routing and matching. The future of urban mobility for passengers and goods relies on leveraging new methods that minimize operational costs and environmental footprints of transportation systems.
  This paper considers combining passenger transportation with goods delivery to improve vehicle-based transportation. Even though the problem has been studied with a defined dynamics model of the transportation system environment, this paper considers a model-free approach that has been demonstrated to be adaptable to new or erratic environment dynamics. We propose FlexPool, a distributed model-free deep reinforcement learning algorithm that jointly serves passengers & goods workloads by learning optimal dispatch policies from its interaction with the environment. The proposed algorithm pools passengers for a ride-sharing service and delivers goods using a multi-hop transit method. These flexibilities decrease the fleet's operational cost and environmental footprint while maintaining service levels for passengers and goods. Through simulations on a realistic multi-agent urban mobility platform, we demonstrate that FlexPool outperforms other model-free settings in serving the demands from passengers & goods. FlexPool achieves 30% higher fleet utilization and 35% higher fuel efficiency in comparison to (i) model-free approaches where vehicles transport a combination of passengers & goods without the use of multi-hop transit, and (ii) model-free approaches where vehicles exclusively transport either passengers or goods.

---


### Paper 17: On Mobility Equity and the Promise of Emerging Transportation Systems

- **Source:** arXiv
- **Publication Year:** 2024
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Heeseung Bang, Aditya Dave, Filippos N. Tzortzoglou
- **Abstract:** This paper introduces a mobility equity metric (MEM) for evaluating fairness and accessibility in multi-modal intelligent transportation systems. The MEM simultaneously accounts for service accessibility and transportation costs across different modes of transportation and social demographics. We provide a data-driven validation of the proposed MEM to characterize the impact of various parameters in the metric across cities in the U.S. We subsequently develop a routing framework that aims to optimize MEM within a transportation network containing both public transit and private vehicles. Within this framework, a system planner provides routing suggestions to vehicles across all modes of transportation to maximize MEM. We evaluate our approach through numerical simulations, analyzing the impact of travel demands and compliance of private vehicles. This work provides insights into designing transportation systems that are not only efficient but also equitable, ensuring fair access to essential services across diverse populations.

---


### Paper 18: Fuzzy Ontology-Based Sentiment Analysis of Transportation and City Feature Reviews for Safe Traveling

- **Source:** arXiv
- **Publication Year:** 2017
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Farman Ali, D. Kwak, Pervez Khan
- **Abstract:** Traffic congestion is rapidly increasing in urban areas, particularly in mega cities. To date, there exist a few sensor network based systems to address this problem. However, these techniques are not suitable enough in terms of monitoring an entire transportation system and delivering emergency services when needed. These techniques require real-time data and intelligent ways to quickly determine traffic activity from useful information. In addition, these existing systems and websites on city transportation and travel rely on rating scores for different factors (e.g., safety, low crime rate, cleanliness, etc.). These rating scores are not efficient enough to deliver precise information, whereas reviews or tweets are significant, because they help travelers and transportation administrators to know about each aspect of the city. However, it is difficult for travelers to read, and for transportation systems to process, all reviews and tweets to obtain expressive sentiments regarding the needs of the city. The optimum solution for this kind of problem is analyzing the information available on social network platforms and performing sentiment analysis. On the other hand, crisp ontology-based frameworks cannot extract blurred information from tweets and reviews; therefore, they produce inadequate results. In this regard, this paper proposes fuzzy ontology-based sentiment analysis and SWRL rule-based decision-making to monitor transportation activities and to make a city- feature polarity map for travelers. This system retrieves reviews and tweets related to city features and transportation activities. The feature opinions are extracted from these retrieved data, and then fuzzy ontology is used to determine the transportation and city-feature polarity. A fuzzy ontology and an intelligent system prototype are developed by using Protégé OWL and Java, respectively.

---


### Paper 19: Subtree Mode and Applications

- **Source:** arXiv
- **Publication Year:** 2025
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Jialong Zhou, Ben Bals, Matei Tinca
- **Abstract:** The mode of a collection of values (i.e., the most frequent value in the collection) is a key summary statistic. Finding the mode in a given range of an array of values is thus of great importance, and constructing a data structure to solve this problem is in fact the well-known Range Mode problem. In this work, we introduce the Subtree Mode (SM) problem, the analogous problem in a leaf-colored tree, where the task is to compute the most frequent color in the leaves of the subtree of a given node. SM is motivated by several applications in domains such as text analytics and biology, where the data are hierarchical and can thus be represented as a (leaf-colored) tree. Our central contribution is a time-optimal algorithm for SM that computes the answer for every node of an input $N$-node tree in $O(N)$ time. We further show how our solution can be adapted for node-colored trees, or for computing the $k$ most frequent colors, for any given $k=O(1)$, in the optimal $O(N)$ time. Moreover, we prove that a similarly fast solution for when the input is a sink-colored directed acyclic graph instead of a leaf-colored tree is highly unlikely. Our experiments on real datasets with trees of up to $7.3$ billion nodes demonstrate that our algorithm is faster than baselines by at least one order of magnitude and much more space efficient. They also show that it is effective in pattern mining, sequence-to-database search, and biology applications.

---


### Paper 20: Transportation Cyber Incident Awareness through Generative AI-Based Incident Analysis and Retrieval-Augmented Question-Answering Systems

- **Source:** arXiv
- **Publication Year:** 2025
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Ostonya Thomas, Muhaimin Bin Munir, Jean-Michel Tine
- **Abstract:** Technological advancements have revolutionized numerous industries, including transportation. While digitalization, automation, and connectivity have enhanced safety and efficiency, they have also introduced new vulnerabilities. With 95% of data breaches attributed to human error, promoting cybersecurity awareness in transportation is increasingly critical. Despite numerous cyberattacks on transportation systems worldwide, comprehensive and centralized records of these incidents remain scarce. To address this gap and enhance cyber awareness, this paper presents a large language model (LLM) based approach to extract and organize transportation related cyber incidents from publicly available datasets. A key contribution of this work is the use of generative AI to transform unstructured, heterogeneous cyber incident data into structured formats. Incidents were sourced from the Center for Strategic & International Studies (CSIS) List of Significant Cyber Incidents, the University of Maryland Cyber Events Database (UMCED), the European Repository of Cyber Incidents (EuRepoC), the Maritime Cyber Attack Database (MCAD), and the U.S. DOT Transportation Cybersecurity and Resiliency (TraCR) Examples of Cyber Attacks in Transportation (2018 to 2022). These were classified by a fine tuned LLM into five transportation modes: aviation, maritime, rail, road, and multimodal, forming a transportation specific cyber incident database. Another key contribution of this work is the development of a Retrieval Augmented Generation question answering system, designed to enhance accessibility and practical use by enabling users to query the curated database for specific details on transportation related cyber incidents. By leveraging LLMs for both data extraction and user interaction, this study contributes a novel, accessible tool for improving cybersecurity awareness in the transportation sector.

---


### Paper 21: Mobility Functional Areas and COVID-19 Spread

- **Source:** arXiv
- **Publication Year:** 2021
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Stefano Maria Iacus, Carlos Santamaria, Francesco Sermi
- **Abstract:** This work introduces a new concept of functional areas called Mobility Functional Areas (MFAs), i.e., the geographic zones highly interconnected according to the analysis of mobile positioning data. The MFAs do not coincide necessarily with administrative borders as they are built observing natural human mobility and, therefore, they can be used to inform, in a bottom-up approach, local transportation, spatial planning, health and economic policies. After presenting the methodology behind the MFAs, this study focuses on the link between the COVID-19 pandemic and the MFAs in Austria. It emerges that the MFAs registered an average number of infections statistically larger than the areas in the rest of the country, suggesting the usefulness of the MFAs in the context of targeted re-escalation policy responses to this health crisis. The MFAs dataset is openly available to other scholars for further analyses.

---


### Paper 22: Smartphone Transportation Mode Recognition Using a Hierarchical Machine Learning Classifier and Pooled Features From Time and Frequency Domains

- **Source:** arXiv
- **Publication Year:** 2020
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Huthaifa I. Ashqar, Mohammed H. Almannaa, Mohammed Elhenawy
- **Abstract:** This paper develops a novel two-layer hierarchical classifier that increases the accuracy of traditional transportation mode classification algorithms. This paper also enhances classification accuracy by extracting new frequency domain features. Many researchers have obtained these features from global positioning system data; however, this data was excluded in this paper, as the system use might deplete the smartphone's battery and signals may be lost in some areas. Our proposed two-layer framework differs from previous classification attempts in three distinct ways: 1) the outputs of the two layers are combined using Bayes' rule to choose the transportation mode with the largest posterior probability; 2) the proposed framework combines the new extracted features with traditionally used time domain features to create a pool of features; and 3) a different subset of extracted features is used in each layer based on the classified modes. Several machine learning techniques were used, including k-nearest neighbor, classification and regression tree, support vector machine, random forest, and a heterogeneous framework of random forest and support vector machine. Results show that the classification accuracy of the proposed framework outperforms traditional approaches. Transforming the time domain features to the frequency domain also adds new features in a new space and provides more control on the loss of information. Consequently, combining the time domain and the frequency domain features in a large pool and then choosing the best subset results in higher accuracy than using either domain alone. The proposed two-layer classifier obtained a maximum classification accuracy of 97.02%.

---


### Paper 23: Parseval's Identity and Optimal Transport Maps

- **Source:** arXiv
- **Publication Year:** 2018
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Novin Ghaffari, Stephen Walker
- **Abstract:** Recent findings for optimal transport maps between distribution functions sharing the same copula show that componentwise the solution is the optimal map between marginal distributions. This is an important discovery since in the multivariate setting optimal maps are difficult to find and only known in a few special cases. In this paper, we extend the result on common copulas by showing that orthonormal transformations of variables sharing a common copula also have a known optimal map. We illustrate this by establishing optimal maps between members of a class of scale mixture of normal distributions.

---


### Paper 24: New Technologies for Sustainable Urban Transport in Europe

- **Source:** arXiv
- **Publication Year:** 2006
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Michel Parent
- **Abstract:** In the past few years, the European Commission has financed several projects to examine how new technologies could improve the sustainability of European cities. These technologies concern new public transportation modes such as guided buses to form high capacity networks similar to light rail but at a lower cost and better flexibility, PRT (Personal Rapid Transit) and cybercars (small urban vehicles with fully automatic driving capabilities to be used in carsharing mode, mostly as a complement to mass transport). They also concern private vehicles with technologies which could improve the efficiency of the vehicles as well as their safety (Intelligent Speed Adaptation, Adaptive Cruise >.Control, Stop&Go, Lane Keeping,...) and how these new vehicles can complement mass transport in the form of car-sharing services.

---


### Paper 25: SPO-VCS: An End-to-End Smart Predict-then-Optimize Framework with Alternating Differentiation Method for Relocation Problems in Large-Scale Vehicle Crowd Sensing

- **Source:** arXiv
- **Publication Year:** 2024
- **Venue:** arXiv Preprint
- **Citation Count:** 0
- **Authors:** Xinyu Wang, Yiyang Peng, Wei Ma
- **Abstract:** Ubiquitous mobile devices have catalyzed the development of vehicle crowd sensing (VCS). In particular, vehicle sensing systems show great potential in the flexible acquisition of spatio-temporal urban data through built-in sensors under diverse sensing scenarios. However, vehicle systems often exhibit biased coverage due to the heterogeneous nature of trip requests and routes. To achieve a high sensing coverage, a critical challenge lies in optimally relocating vehicles to minimize the divergence between vehicle distributions and target sensing distributions. Conventional approaches typically employ a two-stage predict-then-optimize (PTO) process: first predicting real-time vehicle distributions and subsequently generating an optimal relocation strategy based on the predictions. However, this approach can lead to suboptimal decision-making due to the propagation of errors from upstream prediction. To this end, we develop an end-to-end Smart Predict-then-Optimize (SPO) framework by integrating optimization into prediction within the deep learning architecture, and the entire framework is trained by minimizing the task-specific matching divergence rather than the upstream prediction error. Methodologically, we formulate the vehicle relocation problem by quadratic programming (QP) and incorporate a novel unrolling approach based on the Alternating Direction Method of Multipliers (ADMM) within the SPO framework to compute gradients of the QP layer, facilitating backpropagation and gradient-based optimization for end-to-end learning. The effectiveness of the proposed framework is validated by real-world taxi datasets in Hong Kong. Utilizing the alternating differentiation method, the general SPO framework presents a novel concept of addressing decision-making problems with uncertainty, demonstrating significant potential for advancing applications in intelligent transportation systems.

---


## 3. Methodology Analysis

- **Mobile/Sensor-based:** 0% of papers (0 out of 25)
- **CNN:** 4% of papers (1 out of 25)
- **Machine Learning:** 12% of papers (3 out of 25)
- **Reinforcement Learning:** 8% of papers (2 out of 25)
- **Random Forest:** 4% of papers (1 out of 25)
- **SVM:** 0% of papers (0 out of 25)
- **Deep Learning:** 8% of papers (2 out of 25)
- **Regression:** 4% of papers (1 out of 25)

## 4. Research Topics

- Optimization
- Security and Privacy
- Mobile and Sensor Computing
- Detection and Classification
- Prediction and Forecasting
- Distributed Systems


## 5. Comparative Analysis

### Comparative Analysis of 25 Research Papers

**Most Influential Papers Based on Citation Count**

No papers with significant citations were found in this search. This may indicate an emerging research area or niche topic.

**Methodology Distribution Across Analyzed Papers**

- **CNN:** Used in 1 out of 25 papers, representing 4% of the analyzed literature.
- **Machine Learning:** Used in 3 out of 25 papers, representing 12% of the analyzed literature.
- **Reinforcement Learning:** Used in 2 out of 25 papers, representing 8% of the analyzed literature.
- **Random Forest:** Used in 1 out of 25 papers, representing 4% of the analyzed literature.
- **Deep Learning:** Used in 2 out of 25 papers, representing 8% of the analyzed literature.
- **Regression:** Used in 1 out of 25 papers, representing 4% of the analyzed literature.

**Key Observations from the Comparative Analysis**

- None of the 25 papers analyzed have received citations yet, suggesting this may be a newly emerging research area.
- Recent research activity is evident with 12 papers published since 2023, indicating growing interest in this domain.
- Mobile/Sensor-based emerges as the predominant methodology, though direct performance comparison across studies remains challenging due to varying evaluation protocols and datasets.
- A notable observation is the lack of standardized benchmark datasets and evaluation metrics, which currently limits fair comparison between different approaches.


## 6. Research Gaps


### Gap 1: Limited High-Impact Research

Out of 25 papers analyzed, only 0 papers have received significant citation impact (more than 10 citations). This indicates that the research field is still in its early stages or that existing work has not yet achieved widespread recognition or adoption. Future research should focus on producing high-quality, reproducible studies that can serve as foundational work for the community.

*Supporting Evidence:* Citation analysis shows 0 out of 25 papers have more than 10 citations


### Gap 2: Lack of Methodological Standardization

The literature employs diverse methodologies including Mobile/Sensor-based, CNN, Machine Learning. However, there is no standardized evaluation framework or benchmark dataset that allows fair comparison between these different approaches. Each study uses its own experimental setup, dataset, and evaluation metrics, making it difficult to determine which methodology performs best under comparable conditions.

*Supporting Evidence:* 8 different methodologies identified across 25 papers without unified evaluation standards


### Gap 3: Need for Comprehensive Evaluation Frameworks

Based on the analysis of 25 papers, there is a clear need for establishing comprehensive evaluation frameworks that include standardized benchmarks, reproducible experimental protocols, and fair comparison metrics. Such frameworks would accelerate progress by enabling direct comparison of different approaches and identifying the most promising research directions.

*Supporting Evidence:* Analysis of 25 papers reveals inconsistent evaluation methodologies


## 7. Future Research Directions


### Addressing the Limited High-Impact Research

The primary research gap identified in this review is the limited high-impact research. To address this gap, future research should focus on Out of 25 papers analyzed, only 0 papers have received significant citation impact (more than 10 citations). This indicates that the research field is More specifically, researchers should design studies that directly target this gap with clear experimental validation.

- **Priority:** High Priority
- **Timeline:** 6 to 9 months


### Advancing Mobile/Sensor-based for This Domain

Mobile/Sensor-based currently represents the most frequently used methodology in the analyzed literature. However, there remains significant room for optimization and adaptation to the specific requirements of this research domain. Future work should explore hybrid approaches that combine Mobile/Sensor-based with complementary techniques, as well as investigate parameter tuning and architectural innovations to improve performance.

- **Priority:** High Priority
- **Timeline:** 6 to 12 months


### Establishing Performance Baselines

The current literature lacks clear performance baselines and benchmarks. Future research should first focus on establishing standardized evaluation protocols and reporting performance metrics consistently. This foundational work would enable meaningful comparisons and help identify the most promising research directions for subsequent investigation.

- **Priority:** High Priority
- **Timeline:** 3 to 6 months


### Cross-Domain Validation and Generalization Studies

Current research predominantly focuses on specific datasets or controlled conditions. Future work must extend validation across diverse domains, environments, and data distributions. This includes conducting rigorous cross-dataset evaluations, investigating domain adaptation techniques, and studying model robustness under varying real-world conditions. Such studies are essential for determining the practical applicability and limitations of proposed methods.

- **Priority:** Medium Priority
- **Timeline:** 9 to 12 months


### Real-World Deployment and Field Validation

Moving beyond laboratory settings to real-world deployment represents a critical next step for this research domain. Future studies should include field trials, deployment case studies, and practical application evaluations. This includes addressing challenges related to scalability, latency, resource constraints, and system integration that are often overlooked in controlled experimental settings.

- **Priority:** High Priority
- **Timeline:** 12 to 18 months


## 8. Conclusion

This literature review analyzed 25 research papers to assess the current state of research. Key finding one: None of the analyzed papers have received significant citation impact, indicating that this is an emerging research area with substantial potential for foundational contributions. Key finding two: 13 papers (approximately 52 percent) were published in the last two years, demonstrating growing research interest and recent momentum in this domain. Key finding four: Critical research gaps identified include Limited High-Impact Research, Lack of Methodological Standardization, Need for Comprehensive Evaluation Frameworks. These gaps represent significant opportunities for future investigation and potential breakthroughs. In conclusion, while progress has been made in this research domain, substantial opportunities remain for advancing the field through addressing the identified gaps and pursuing the proposed future research directions.

## 9. Suggested Thesis Titles

1. A Comprehensive Systematic Literature Review of Distributed Systems: Current State, Methodological Analysis, and Future Research Directions
2. Advancing the Field of Distributed Systems: A Critical Review of Existing Literature and Identification of Research Gaps
3. Towards Robust and Deployable Distributed Systems: Challenges, Opportunities, and a Research Agenda
4. Comparative Analysis of Methodologies for Distributed Systems: Performance Evaluation, Research Gaps, and Future Trajectories

---

*Report generated by DeepResearch-AI - Academic Literature Analysis System*
*Data sources: Semantic Scholar, arXiv*
*Report date: 2026-09-09 11:15:08*
