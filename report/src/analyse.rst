.. 7p: 2100 words

Analyse
=======

The following chapter presents a background research on the technologies that can be used for graph exploration without the use of sight and a description of the contributions from previous work of the HaptiQ. It will first start with a task analysis on graph exploration.
This chapter aims at giving a wider outlook on the alternatives and additional understanding on what characteristics should be considered for graph exploration.

Task analysis
-------------

Finding visually impaired people for collaboration with is not an easy task (<<<<is this phrase relevant or interesting for research?>>>>). The partnership between IJA and ELIPSE tries to overcome this issue, yet many different projects are running at the same time and each one of them needs this precious collaboration (<<<<remove "precious". not academic + personal>>>>). In order to avoid constant requests of their presence in the laboratories, ELIPSE has the undergoing policy to restrict these requests to the evaluation phase.

This makes the user centered development process not ideal (This is a major drawback for a user centered development process). Nevertheless, I have managed to find alternative ways of tackling the usability issues. This has surrounded me with sources focusing on the users (<<< did not really get this phrase, maybe my correction is not relevant >>>).

(<<< Who are these people? Please state clearly >>>>)
- A direct contact with Bernard Orniola - one of the permanent members of ELIPSE who happens to be visually impaired. He has provided me with key understanding of this handicap in a day-to-day perspective
- My tutor Christophe Jouffrais, who has a long experience in working with visually impaired people and was able to emphasize some aspects he could feel I was missing
- My participation in general meetings on larger-scale projects such as AccessiMap has given me insight on how to adapt a development process to the needs of the blind
- A direct contact with X, who was doing his master internship in the cognitive science field; he has pointed out the limits of my design when I have exposed it to him (<<< you are using many synonyms to say the same thing in the end; chaning them does not bring anything new to the message: expose and show? choose one >>>)
- Colleagues who have tried a previous uncomplete version of the HaptiQ; they have warned me about the major issues that they have experienced with (?) users

By these proxies (<<<proxies? maybe intermediaries? assistants? supportive colleagues?>>>), I was able to come up wit the following task analysis.

Giving a blind exploration using only a haptic (<<<what is haptic? my dictionary does not know it>>>) device and a trained user on the interaction techniques, the task would be decomposed into the following steps:

1. Feeling the device
2. Moving (depending on a possible strategy) and waiting for a feedback
3. If there is no tactile feedback, continue moving
4. If there is a tactile feedback, process to understand what the encoded information is
5. Given the new piece of information acquired, adapt the strategy of exploration
6. While exploration is not completed go back to step 2

These steps may seem fairly simple. Yet they give us some clues on the importance of having a recognisable tactile signal during the explroation phase.

Another interesting aspect is the fact that an exploration is the result of a sum of strategies. We can consider that finding the network is the first goal. The next one is to explore all the nodes, which can mean following the network as much as possible. A possible solution to improve this strategy may involve building tactile signals that would naturally suggest (<<<I guess??>>>) strategies and confort (<<<< confort? are you sure? are they sad? do they need to be conforted? not confront? support? offer positive feedback? encourage? assist?>>>) the users in their choice.


Related research
----------------

Making an exhaustive taxonomy would be illusionnary as research related to haptics (<<< oh... haptic is a proper noun... please capitalise it then>>>) devices has extended its scope and depth over the last twenty five years [ref needed]. This chapter will nevertheless attempt to present technologies used as a way to acquire data through graphs and maps exploration for the sightless.   (<<< 'the different technologies for blind people that could be used as a way to acquire data through graphs and maps exploration' is ambiguous as it may indicate the blind are used to acquire data >>>)

This (<<< just used 'this', think of varying the vocabulary >>>) background research is based on the doctoral thesis of Thomas_Pietrzak__ on "Dissemination of haptics information in a multimodal environnement" and on the master thesis of Simone__ on "The HaptiQ: A Haptic Device for Graph Exploration by People with Visual Disabilities".


.. ref needed
Braille
^^^^^^^

Braille is a tactile writing system that has been spreaded over the world since 1824 (<<< introduced in 1824 and spread the same year? or introduced earlier and spread in 1824? >>>). Although it could be regarded as some form of graphs with series of dots, arrows and bullets, it is intended for text reading. The main issue remains the fact that it is difficult to learn. Thinking that all blind people would know it is a common misinformation (<<< misconception, no? nobody really informed us that everyone can read it, right?>>>).


.. ref needed
ScreenReaders 
^^^^^^^^^^^^^

VIP (<<<< please avoid VIP... espcially without introducing it. I understand it means Visually Impaired People, but using it like this is soooooo dangerous, and you know why. Drop or disambiguate >>>) rely heavily on their audition in order to compensate for their handicap. This heavy (<<< you've just used 'heavy'. it's becoming heavy ;) >>>) usage would even trigger an "obstacle perception" [95] (<<< what is an obstacle perception? don't assume your reader knows it >>>). ScreenReaders provides an efficient alternative to access text and many are available [#]_.
If only a few would enable navigation tasks as well like JAWS or VoiceOver, the main issue remains the usage of audio as a channel for spatial guidance (<<< did not get the phrase >>>). VIP are not necessarily inclined to use either cardinal points or the four directions (up, down, right, left) to orient themselves. That is why map exploration through a Screen Reader would require a constant audio feedback. This interaction may provide a useful help for graph exploration, yet it cannot be qualified as the most suited (<<< I've lost you here >>>). Besides, it is preferable to interfer with the audio channel as little as possible in order to facilitate the debit of textual information expressed this way. In other ways (?), it would be beneficial to leave this channel for other types of information compatible with it (<<<right?>>>).

.. [#] http://alternativeto.net/tag/screen-reader/ (accessed the 19/08/15)


Tactile Maps
^^^^^^^^^^^^

Tactile maps are made of paper heated to form bumps and relief. It thus creates shapes, lines and dots. These are popular among visually impaired people learning geometry or exploring a map. Even though they offer a lot of tactile freedom (<<< 'lots' is very coloquial >>>), it is easier to grasp a general idea of the shapes by using the ten fingers. They do not provide further interaction unless they are combined with a tabletop such as the Multimodal Interactive Maps (MIMs) project [6]. MIMs is an input / output system mixing different technolgies. It keeps the possibility of a ten fingers exploration, but requires a new printing for each visualisation.
MIMs fall short of rendering VIPs autonomous: scanning and printing  would require the help of another person.


Machanical actuators 
^^^^^^^^^^^^^^^^^^^^

Presented as the technologic equivalency of braille, they can dynamically change a matrix of actuators in order to provide  information which can be a Braille symbol or simple shapes. This matrix can be placed on the finger zone of a mouse like the VTP layer [ref needed] or the Tactiball [ref needed] which implies that the moving hand is also receiving the tactile information or it can be separated like the Tactos device [ref needed] but with a smaller matrix. Their failure (<<< or did you mean lack of popularity? >>>) could result from poor quality software applications, as Thomas Pietrzak suggests. Given Jansson [84] mouses are not compatible with navigation tasks for visually impaired people (<<< this is a fragment, not a true phrase, consider revising >>>).

Other displays, like the Brailliant from Humanware [link needed], offer a full range of actuators forming braille letters, but remain fairly expensive.

HTP, a precursor of the HaptiQ, deserves particular attention. One of my tutors -- Miguel Nacenta, has been involved in the design of this input/output device with a single actuator in the center [ref needed]. The purpose of the HTP is to explore other possible interactions with tabletops like their further work has suggested [ref needed]. It renders unconventional outputs like friction and softness which can be integrated in various applications. Although innovative, its usage is supported by visual elements and has not been though for visually impaired people.

Vibrations
^^^^^^^^^^

Some devices use vibrations in oder to provide feedbacks. Small vibro-motors can be attached to a glove which makes the device adapted to a hand like the Cybertouch [ref needed]. They could also be integrated on a small surface imitating a matrix of actuators like the Optacon [ref needed].

Vibrations can be used in a matrix of thin vertical panels trigerring a feeling of cavity or bumps when a hand is set on it as in STReSS [ref needed].

Electrovibration is used in the TeslaTouch and Revel systems [ref needed, ref needed]; it is imitating the sensation of friction and is therefore only perceptable when the fingers are in motion (<<< Good! Very good, nice, clear phrase. And you have used the semicolon as you should have >>>).


Forcefeedback
^^^^^^^^^^^^^

Forcefeedback has known a famous entry in the gaming field with Joystick and Wheels. But their application goes far beyond that. One of the most recurrent names is the PHANToM [ref needed] that forces the point in certain directions. 
Forcefeedback comes in a variety of techniques in order to push a single point into a certain direction (articulated arm, pantographes, or pneumatics).

Having a single point of contact does not allow users to follow lines easily orto  understand shapes [ref needed]. This make Forcefeedback unsuitable for our project. 

Air
^^^

Feedbacks can be perceived via air motion. It triggers the same signals as with tactile motion (<<< or just 'touch' >>>) thanks to the variety of sensitivy receptors [88, 101]. AIREAL [19] makes this approach possible and uses a motion detector camera as input. Using highly pressured air waves allows long distance interaction (10m). Besides, it is scalable and affordable. Even though they offer a wide range of angles from which the air is pushed, the lack of resolution limits its usage tremendously. Besides (<<< again 'besides'? >>>), AIREAL is presented more as an interaction (<<< more than whom? more than what? >>>) in order to enhance user experience than an input output system.

No hands involved
^^^^^^^^^^^^^^^^

(FIGURE: Homonculus sensoriel)

If we were to represent the human body by its touch sensitivy, we would end up with a weak figurine with enormous hands, lips and tongue.
This is maybe why bolder interactions are exploiting the latter with the Tongue Display Unit [9]. This display places a seven by seven grid filled with electrodes on the tongue and can be used in a no-hands-involved scenario: as for instance a working surgeon. Others would use the brow with the Forhead Retina System [ref needed].

Although intriguing, both of these displays allow limited interaction and are suited for very particular scenarios.


Previous versions
-----------------

FIGURE haptiQ evolution, tactons

In 2014, Simone I.C. (<<< in English you would say I.C.Simone, as the forenames come first >>>) has worked on a first version of HaptiQ at the University of St Andrews. His development process was focused on the engineering of a device to handle multiple actuators. These actuators could therefore have their own language in order to transmit information. He has designed multiple cases for embarking (<<< embarking? where? maybe you meant launching? >>>) the HaptiQ and maintaining all the servomotors.

His work on a background research narrowed the disadvantages of other haptics solutions. He has also implied that a vector based mechanical actuator such as the HaptiQ is unique. His ideas on possible applications in order to help math signal representation (like in Figure ?) are highly valuable.

Even though his design on the caps does not appear in his report, we have to give him credit for it. 
Although (<<< use a different introductury word, you have just used his brother >>>) his work on tactons seems promising, it is not backed up by any user study. This imposes its reconsideration.

He (<< Mr Hacenta, we start forgetting the guy >>>) has also managed to extend this first version with button (mmmmm) and has started to work on different possible interactions with pressure (<<< do you need this tail?>>> which still seems a valid option).

Finally, he has briefly pointed out the issue of having multiple wires running in order to control the servomotors which has led me to prefer solutions allowing the device to be as nomad as possible (<<< I know you like the Nomads group, but consider using 'authonomous' or 'independent' instead >>>).


Conclusion
----------

Haptics devices demand material and often electronic circuits to be build. This results in high costs overall and is often dedicated to a specific usage. If our goal is to provide a solution for VIP around the world, then we should take into account other aspects such as making it easily replicable and allowing applications to be build on top of the key interactions like the Haptic Puck Tabletop and the Phantom (<<< rephrase maybe>>>). But this goal requires various skills and a careful design.

Many alternatives exist, yet the issue remains the same: we are too focueds on data represenation than on data meaning. It might be more relevant to focus on the general trends than on the exact measurements. Let us remember that it is really hard to learn the simple concept of a squared angle for VIP (<<< you just make the blind look stupid. Plus you generalise, babe >>>). The challenge is there: trying to give a natural interaction for the strategies involved in exploration. A way of solving it is to take a step back in the representation of information: we are not interested in the value of a perticular pixel but its meaning, its purpose. Is it a part of an edge? Is it filling a cue point? Or is it just random noise? These problems can be solved by giving meaning (to what? please complete the phrase); this is why we are focusing only on graphs. They are a scalable and precise representation of the key information. Understanding graphs is mastering a way to easily acquire conceptual and spatial information.
(ref: 01__)
