# 学习笔记

* TapType: Ten-finger text entry on everyday surfaces via Bayesian inference

  * Abstract

    * Despite the advent of touchscreens, typing on physical keyboards remains most efficient for entering text, because users can leverage all fingers across a full-size keyboard for convenient typing. As users increasingly type on the go, text input on mobile and wearable devices has had to compromise on full-size typing. In this paper, we present TapType, a mobile text entry system for full-size typing on passive surfaces—without an actual keyboard. From the inertial sensors inside a band on either wrist, TapType decodes and relates surface taps to a traditional QWERTY keyboard layout. The key novelty of our method is to predict the most likely character sequences by fusing the finger probabilities from our Bayesian neural network classifier with the characters’ prior probabilities from an n-gram language model. In our online evaluation, participants on average typed 19 words per minute with a character error rate of 0.6% after 30 minutes oftraining. Expert typists thereby consistently achieved more than 25WPM at a similar error rate. We demonstrate applications of TapType in mobile use around smartphones and tablets, as a complement to interaction in situated Mixed Reality outside visual control, and as an eyes-free mobile text input method using an audio feedback-only interface.

* TapID: Rapid Touch Interaction in Virtual Reality using Wearable Sensing

  * Abstract

    * Current Virtual Reality systems typically use cameras to capture user input from controllers or free-hand mid-air interaction. In this paper, we argue that this is a key impediment to productivity scenarios in VR, which require continued interaction over prolonged periods of time—a requirement that controller or free-hand input in mid-air does not satisfy. To address this challenge, we bring rapid touch interaction on surfaces to Virtual Reality—the input modality that users have grown used to on phones and tablets for continued use. We present TapID, a wrist-based inertial sensing system that complements headset-tracked hand poses to trigger input in VR. TapID embeds a pair of inertial sensors in a flexible strap, one at either side of the wrist; from the combination of registered signals, TapID reliably detects surface touch events and, more importantly, identifies the ﬁnger used for touch. We evaluated TapID in a series of user studies on event-detection accuracy (F1 = 0.997) and hand-agnostic ﬁnger-identiﬁcation accuracy (within-user: F1 = 0.93; across users: F1 =0.91 after 10 reﬁnement taps and F1 =0.87 without reﬁnement) in a seated table scenario. We conclude with a series of applications that complement hand tracking with touch input and that are uniquely enabled by TapID, including UI control, rapid keyboard typing and piano playing, as well as surface gestures.

* TypingRing: A Wearable Ring Platform for Text Input

  * Abstract

    * This paper presents TypingRing, a wearable ring platform that enables text input into computers of different forms, such as PCs, smartphones, tablets, or even wearables with tiny screens. The basic idea of TypingRing is to have a user wear a ring on his middle finger and let him type on a surface – such as a table, a wall, or his lap. The user types as if a standard QWERTY keyboard is lying underneath his hand but is invisible to him. By using the embedded sensors TypingRing determines what key is pressed by the user. Further, the platform provides visual feedback to the user and communicates with the computing device wirelessly. This paper describes the hardware and software prototype of TypingRing and provides an in-depth evaluation of the platform. Our evaluation shows that TypingRing is capable of detecting and sending key events in real-time with an average accuracy of 98.67%. In a ﬁeld study, we let seven users type a paragraph with the ring, and we ﬁnd that TypingRing yields a reasonable typing speed (e.g., 33 - 50 keys per minute) and their typing speed improves over time.

* FingerSound: Recognizing unistroke thumb gestures using a ring

  * Abstract

    * We introduce FingerSound, an input technology to recognize unistroke thumb gestures, which are easy to learn and can be performed through eyes-free interaction. The gestures are performed using a thumb-mounted ring comprising a contact microphone and a gyroscope sensor. A K-Nearest-Neighbor(KNN) model with a distance function ofDynamic Time Warping (DTW) is built to recognize up to 42 common unistroke gestures. A user study, where the real-time classification results were given, shows an accuracy of 92%-98% by a machine learning model built with only 3 training samples per gesture. Based on the user study results, we further discuss the opportunities, challenges and practical limitations of FingerSound when deploying it to real-world applications in the future.

* BiTipText: Bimanual Eyes-Free Text Entry on a Fingertip Keyboard

  * Abstract

    * We present a bimanual text input method on a miniature fingertip keyboard, that invisibly resides on the first segment of a user’s index finger on both hands. Text entry can be carried out using the thumb-tip to tap the tip of the index finger. The design of our keyboard layout followed an iterative process, where we first conducted a study to understand the natural expectation of the handedness of the keys in a QWERTY layout for users. Among a choice of 67,108,864 design variations, we identified 1295 candidates offering a good satisfaction for user expectations. Based on these results, we computed an optimized bimanual keyboard layout, while considering the joint optimization problems of word ambiguity and movement time. Our user evaluation revealed that participants achieved an average text entry speed of 23.4 WPM.

* ARKB: 3D vision-based Augmented Reality Keyboard

  * Abstract

    * In this paper, we propose a wearable 3D Augmented Reality Keyboard (ARKB) which enables a user to type text or control CG objects without using conventional interfaces, such as keyboard or mouse. The proposed ARKB exploits 3D depth information obtained through a stereo camera attached to an HMD. The ARKB consists of three modules: (i) 3D vision-based tracking, (ii) natural interaction with fingers, and (iii) audiovisual feedback on the 3D video see-through HMD. The proposed ARKB can be applied as an interface for typing in AR environment. The remaining challenges are study on tracking method to improve accuracy and newly designed virtual keyboard which is proper in representing the advantage of the interaction in 3D space.

* DigiTouch: Reconfigurable Thumb-to-Finger Input and Text Entry on Head-mounted Displays

  * Abstract

    * Input is a significant problem for wearable systems, particularly for head mounted virtual and augmented reality displays. Existing input techniques either lack expressive power or may not be socially acceptable. As an alternative, thumb-to-finger touches present a promising input mechanism that is subtle yet capable of complex interactions. We present DigiTouch, a reconfigurable glove-based input device that enables thumb-to-finger touch interaction by sensing continuous touch position and pressure. Our novel sensing technique improves the reliability of continuous touch tracking and estimating pressure on resistive fabric interfaces. We demonstrate DigiTouch’s utility by enabling a set of easily reachable and reconfigurable widgets such as buttons and sliders. Since DigiTouch senses continuous touch position, widget layouts can be customized according to user preferences and application needs. As an example of a real-world application of this reconfigurable input device, we examine a split-QWERTY keyboard layout mapped to the user’s fingers. We evaluate DigiTouch for text entry using a multi-session study. With our continuous sensing method, users reliably learned to type and achieved a mean typing speed of 16.0 words per minute at the end of ten 20-minute sessions, an improvement over similar wearable touch systems.

* TipText: Eyes-Free Text Entry on a Fingertip Keyboard

  * Abstract

    * In this paper, we propose and investigate a new text entry technique using micro thumb-tip gestures. Our technique features a miniature QWERTY keyboard residing invisibly on the first segment of the user’s index finger. Text entry can be carried out using the thumb-tip to tap the tip of the index finger. The keyboard layout was optimized for eyesfree input by utilizing a spatial model reflecting the users’ natural spatial awareness of key locations on the index finger. We present our approach of designing and optimizing the keyboard layout through a series of user studies and computer simulated text entry tests over 1,146,484 possibilities in the design space. The outcome is a 2×3 grid with the letters highly confining to the alphabetic and spatial arrangement of QWERTY. Our user evaluation showed that participants achieved an average text entry speed of 11.9 WPM and were able to type as fast as 13.3 WPM towards the end of the experiment.

* QwertyRing: Text Entry on Physical Surfaces Using a Ring

  * Abstract

    * The software keyboard is widely used on digital devices such as smartphones, computers, and tablets. The software keyboard operates via touch, which is efficient, convenient, and familiar to users. However, some emerging technology devices such as AR/VR headsets and smart TVs do not support touch-based text entry. In this paper, we present QwertyRing, a technique that supports text entry on physical surfaces using an IMU (Inertial Measurement Unit) ring. Users wear the ring on the middle phalanx of the index finger and type on any desk-like surface, as if there is a QWERTY keyboard on the surface. While typing, users do not focus on monitoring the hand motions. They receive text feedback on a separate screen, e.g., an AR/VR headset or a digital device display, such as a computer monitor. The basic idea ofQwertyRing is to detect touch events and predict users’ desired words by the orientation of the IMU ring. We evaluate the performance of QwertyRing through a five-day user study. Participants achieved a speed of 13.74 WPM in the first 40 minutes and reached 20.59 WPM at the end. The speed outperforms other ring-based techniques [24, 30, 45, 68] and is 86.48% of the speed of typing on a smartphone with an index finger. The results show that QwertyRing enables efficient touch-based text entry on physical surfaces.

* ATK: Enabling Ten-Finger Freehand Typing in Air Based on 3D Hand Tracking Data

  * Abstract

    * Ten-finger freehand mid-air typing is a potential solution for post-desktop interaction. However, the absence of tactile feedback as well as the inability to accurately distinguish tapping ﬁnger or target keys exists as the major challenge for mid-air typing. In this paper, we present ATK, a novel interaction technique that enables freehand ten-ﬁnger typing in the air based on 3D hand tracking data. Our hypothesis is that expert typists are able to transfer their typing ability from physical keyboards to mid-air typing. We followed an iterative approach in designing ATK. We ﬁrst empirically investigated users’ mid-air typing behavior, and examined ﬁngertip kinematics during tapping, correlated movement among ﬁngers and 3D distribution of tapping endpoints. Based on the ﬁndings, we proposed a probabilistic tap detection algorithm, and augmented Goodman’s input correction model to account for the ambiguity in distinguishing tapping ﬁnger. We ﬁnally evaluated the performance of ATK with a 4-block study. Participants typed 23.0 WPM with an uncorrected word-level error rate of 0.3% in the ﬁrst block, and later achieved 29.2 WPM in the last block without sacriﬁcing accuracy.

* FingerT9: Leveraging Thumb-to-finger Interaction for Same-side-hand Text Entry on Smartwatches

  * Abstract

    * We introduce FingerT9, leveraging the action of thumb-tofinger touching on the finger segments, to support same-sidehand (SSH) text entry on smartwatches. This is achieved by mapping a T9 keyboard layout to the finger segments. Our solution avoids the problems of fat finger and screen occlusion, and enables text entry using the same-side hand which wears the watch. In the pilot study, we determined the layout mapping preferred by the users. We conducted an experiment to compare the text-entry performances of FingerT9, the tilt-based SSH input, and the direct-touch nonSSH input. The results showed that the participants performed significantly faster and more accurately with FingerT9 than the tilt-based method. There was no significant difference between FingerT9 and direct-touch methods in terms of efficiency and error rate. We then conducted the second experiment to study the learning curve on SSH text entry methods: FingerT9 and the tilt-based input. FingerT9 gave significantly better long-term improvement. In addition, eyes-free text entry (i.e., looking at the screen output but not the keyboard layout mapped on the finger segments) was made possible once the participants were familiar with the keyboard layout.

* Huffman Base-4 Text Entry Glove (H4-TEG)

  * Abstract

    * We designed and evaluated a Huffman base-4 Text Entry Glove (H4-TEG). H4-TEG uses pinches between the thumb and fingers on the user’s right hand. Characters and commands use base-4 Huffman codes for efficient input. In a longitudinal study, participants reached 14.0 wpm with error rates <1%. In an added session without visual feedback, entry speed dropped only by 0.4 wpm. Yet another session was added that required entry of text with punctuation and other symbols. Entry speed dropped by 1.5 wpm.

* RotoSwype: Word-Gesture Typing using a RingD

  * Abstract

    * We propose RotoSwype, a technique for word-gesture typing using the orientation ofa ring worn on the index finger. RotoSwype enables one-handed text-input without encumbering the hand with a device, a desirable quality in many scenarios, including virtual or augmented reality. The method is evaluated using two arm positions: with the hand raised up with the palm parallel to the ground; and with the hand resting at the side with the palm facing the body. A five-day study finds both hand positions achieved speeds of at least 14 words-per-minute (WPM) with uncorrected error rates near 1%, outperforming previous comparable techniques.

* ThumbText: Text Entry for Wearable Devices Using a Miniature Ring

  * Abstract

    * Users can benefit from using an auxiliary peripheral that could mitigate many concerns with direct text entry on wearable devices. We introduce ThumbText, a thumb-operated text entry approach for a ring-sized touch surface. Through a multi-part exploration, we first identify a suitable discretization of the miniature touch surface for thumb input. We then design a number of two-step selection techniques for supporting the input of at least 28 characters. On a miniature touch surface, we find that a continuous touch-slide-lift selection technique in a 2×3 grid discretization offers improved performance gains over other selection methods. Finally, we evaluate ThumbText against techniques also designed for wearable devices and find that ThumbText allows for higher text entry rates than SwipeBoard and H4-Writer.

* FingerPing: Recognizing Fine-grained Hand Poses using Active Acoustic On-body Sensing

  * Abstract

    * FingerPing is a novel sensing technique that can recognize various fine-grained hand poses by analyzing acoustic resonance features. A surface-transducer mounted on a thumb ring injects acoustic chirps (20Hz to 6,000Hz) to the body. Four receivers distributed on the wrist and thumb collect the chirps. Different hand poses of the hand create distinct paths for the acoustic chirps to travel, creating unique frequency responses at the four receivers. We demonstrate how FingerPing can differentiate up to 22 hand poses, including the thumb touching each of the 12 phalanges on the hand as well as 10 American sign language poses. A user study with 16 participants showed that our system can recognize these two sets of poses with an accuracy of 93.77% and 95.64%, respectively. We discuss the opportunities and remaining challenges for the widespread use of this input technique.

* A NewWearable Input Device: SCURRY

  * Abstract

    * A new wearable input device named SCURRY, developed by the Samsung Advanced Institute of Technology, is introduced in this paper. Based on inertial sensors, this device allows a human operator to select a specified character, an event, or an operation as the input he/she wants spatially through both hand motion and ﬁnger clicking. It is a glovelike device, which can be worn on the human hand, composed of a base module, including one controller and two angular-velocity sensors (gyroscopes) on the back of the hand, and four ring-type modules (rings), including two-axis acceleration sensors (accelerometers) on four ﬁngers. The base and the ring modules are integrated modules containing sensors, a transceiver or receiver for communication, and a microcontroller, which makes the device compact and light. The two gyroscopes embedded in the base module have a role in detecting the direction (up, down, right, and left) of the handmotion, and the accelerometers have a role in detecting ﬁnger motion generated by ﬁnger clicking. An algorithm for the exact ﬁnger-click recognition composed of three parts (feature extraction, valid-click discrimination, and crosstalk avoidance) is proposed to improve the recognition performance of ﬁnger clicking on SCURRY. The experimental results and discussions are presented. SCURRY can be used as a wearable mouse spatially, by allowing any three ﬁngers to be operated as the left, middle, and right mouse buttons, and in a similar manner, as a wearable keyboard, as it allows a human operator to point and select any character, event, or operation by his hand motion and ﬁnger clicking.

* An Energy Harvesting Wearable Ring Platform for Gesture Input on Surfaces

  * Abstract

    * This paper presents a remote gesture input solution for interacting indirectly with user interfaces on mobile and wearable devices. The proposed solution uses a wearable ring platform worn on a user’s index finger. The ring detects and interprets various gestures performed on any available surface, and wirelessly transmits the gestures to the remote device. The ring opportunistically harvests energy from an NFC-enabled phone for perpetual operation without explicit charging. We use a ﬁnger-tendon pressure-based solution to detect touch, and a light-weight audio based solution for detecting ﬁnger motion on a surface. The two-level energy efficient classiﬁcation algorithms identify 23 unique gestures that include tapping, swipes, scrolling, and strokes for hand written text entry. The classiﬁcation algorithms have an average accuracy of 73% with no explicit user training. Our implementation supports 10 hours of interactions on a surface at 2 Hz gesture frequency. The prototype was constructed with off-the-shelf components and has a form factor comparable to a large ring.

* Decoding Surface Touch Typing from Hand-Tracking

  * Abstract

    * We propose a novel text decoding method that enables touch typing on an uninstrumented flat surface. Rather than relying on physical keyboards or capacitive touch, our method takes as input hand motion of the typist, obtained through hand-tracking, and decodes this motion directly into text. We use a temporal convolutional network to represent a motion model that maps the hand motion, represented as a sequence of hand pose features, into text characters. To enable touch typing without the haptic feedback of a physical keyboard, we had to address more erratic typing motion due to drift of the fingers. Thus, we incorporate a language model as a text prior and use beam search to efﬁciently combine our motion and language models to decode text from erratic or ambiguous hand motion. We collected a dataset of 20 touch typists and evaluated our model on several baselines, including contactbased text decoding and typing on a physical keyboard. Our proposed method is able to leverage continuous hand pose information to decode text more accurately than contact-based methods and an ofﬂine study shows parity (73 WPM, 2.38% UER) with typing on a physical keyboard. Our results show that hand-tracking has the potential to enable rapid text entry in mobile environments.

* Argot: A Wearable One-Handed Keyboard Glove

  * Abstract

    * The Argot glove is a one-handed, wearable input device that allows a user to type all English letters, numbers, and symbols without use of a traditional keyboard. The device design considers variables and constraints such as dexterity, feedback, mobility, learnability, speed of input, errors and false inputs, permanence, and comfort, as well as previous user knowledge. The glove design was informed by experimental investigations aimed at balancing tradeoffs between physical variables (reach, dexterity, haptics) and cognitive variables (learnability, text-entry method). It uses weak magnetic interactions during “key” presses to provide passive haptic feedback and reduce the need for precision in proprioceptive hand positioning.

* Airwriting: Hands-free Mobile Text Input by Spotting and Continuous Recognition of 3d-Space Handwriting with Inertial Sensors

  * Abstract

    * We present an input method which enables complex hands-free interaction through 3d handwriting recognition. Users can write text in the air as if they were using an imaginary blackboard. Motion sensing is done wirelessly by accelerometers and gyroscopes which are attached to the back of the hand. We propose a two-stage approach for spotting and recognition of handwriting gestures. The spotting stage uses a Support Vector Machine to identify data segments which contain handwriting. The recognition stage uses Hidden Markov Models (HMM) to generate the text representation from the motion sensor data. Individual characters are modeled by HMMs and concatenated to word models. Our system can continuously recognize arbitrary sentences, based on a freely definable vocabulary with over 8000 words. A statistical language model is used to enhance recognition performance and restrict the search space. We report the results from a nine-user experiment on sentence recognition for person dependent and person independent setups on 3d-space handwriting data. For the person independent setup, a word error rate of 11% is achieved, for the person dependent setup 3% are achieved. We evaluate the spotting algorithm in a second experiment on a realistic dataset including everyday activities and achieve a sample based recall of 99% and a precision of 25%. We show that additional ﬁltering in the recognition stage can detect up to 99% of the false positive segments.

* Vision-Based Handwriting Recognition for Unrestricted Text Input in Mid-Air

  * Abstract

    * We propose a vision-based system that recognizes handwriting in mid-air. The system does not depend on sensors or markers attached to the users and allows unrestricted character and word input from any position. It is the result of combining handwriting recognition based on Hidden Markov Models with multi-camera 3D hand tracking. We evaluated the system for both quantitative and qualitative aspects. The system achieves recognition rates of 86.15% for character and 97.54% for small-vocabulary isolated word recognition. Limitations are due to slow and low-resolution cameras or physical strain. Overall, the proposed handwriting recognition system provides an easy-to-use and accurate text input modality without placing restrictions on the users.

* Selection-Based Mid-Air Text Entry on Large Displays

  * Abstract

    * Most text entry methods require users to have physical devices within reach. In many contexts of use, such as around large displays where users need to move freely, device-dependent methods are ill suited. We explore how selection-based text entry methods may be adapted for use in mid-air. Initially, we analyze the design space for text entry in mid-air, focusing on singlecharacter input with one hand. We propose three text entry methods: H4 MidAir (an adaptation of a game controller-based method by MacKenzie et al. [21]), MultiTap (a mid-air variant of a mobile phone text entry method), and Projected QWERTY (a mid-air variant of the QWERTY keyboard). After six sessions, participants reached an average of 13.2 words per minute (WPM) with the most successful method, Projected QWERTY. Users rated this method highest on satisfaction and it resulted in the least physical movement.

* AirStroke: Bringing Unistroke Text Entry to Freehand Gesture Interfaces

  * Abstract

    * In this paper, we explore the opportunity of bringing unistroke text entry to freehand gesture interfaces. Using existing text entry methods directly in such interfaces is impractical because of the differences between freehand gestures and traditional forms of input. To address this problem, we consider the design constraints of text entry methods using freehand gestures, and present AirStroke, a new technique based on a reengineering of the well-known unistroke technique Graffiti. Using Graffiti’s alphabet, AirStroke takes advantage of the richer input capabilities of two-handed freehand gestures by providing combined mode selection and character entry with one hand, as well as word completion with the other hand. A longitudinal study suggests that AirStroke has competitive speed and accuracy to unistroke methods based on stylus input.

* WrisText: One-handed Text Entry on Smartwatch using Wrist Gestures

  * Abstract

    * We present WrisText - a one-handed text entry technique for smartwatches using the joystick-like motion of the wrist. A user enters text by whirling the wrist of the watch hand, towards six directions which each represent a key in a circular keyboard, and where the letters are distributed in an alphabetical order. The design of WrisText was an iterative process, where we first conducted a study to investigate optimal key size, and found that keys needed to be 55º or wider to achieve over 90% striking accuracy. We then computed an optimal keyboard layout, considering a joint optimization problem of striking accuracy, striking comfort, word disambiguation. We evaluated the performance of WrisText through a five-day study with 10 participants in two text entry scenarios: hand-up and handdown. On average, participants achieved a text entry speed of 9.9 WPM across all sessions, and were able to type as fast as 15.2 WPM by the end of the last day.

* Vulture: A Mid-Air Word-Gesture Keyboard

  * Abstract

    * Word-gesture keyboards enable fast text entry by letting users draw the shape of a word on the input surface. Such keyboards have been used extensively for touch devices, but not in mid-air, even though their fluent gestural input seems well suited for this modality. We present Vulture, a word-gesture keyboard for mid-air operation. Vulture adapts touch based word-gesture algorithms to work in midair, projects users’ movement onto the display, and uses pinch as a word delimiter. A first 10-session study suggests text-entry rates of 20.6 Words Per Minute (WPM) and finds hand-movement speed to be the primary predictor of WPM. A second study shows that with training on a few phrases, participants do 28.1 WPM, 59% of the text-entry rate of direct touch input. Participants’ recall of trained gestures in mid-air was low, suggesting that visual feedback is important but also limits performance. Based on data from the studies, we discuss improvements to Vulture and some alternative designs for mid-air text entry.

* Fast and Precise Touch-Based Text Entry for Head-Mounted Augmented Reality with Variable Occlusion

  * Abstract

    * We present the VISAR keyboard: An augmented reality (AR) head-mounted display (HMD) system that supports text entry via a virtualised input surface. Users select keys on the virtual keyboard by imitating the process of single-hand typing on a physical touchscreen display. Our system uses a statistical decoder to infer users’ intended text and to provide error-tolerant predictions. There is also a high-precision fall-back mechanism to support users in indicating which keys should be unmodified by the auto-correction process. A unique advantage of leveraging the well-established touch input paradigm is that our system enables text entry with minimal visual clutter on the see-through display, thus preserving the user’s field-of-view. We iteratively designed and evaluated our system and show that the final iteration of the system supports a mean entry rate of 17.75wpm with a mean character error rate less than 1%. This performance represents a 19.6% improvement relative to the state-of-the-art baseline investigated: A gaze-then-gesture text entry technique derived from the system keyboard on the Microsoft HoloLens. Finally, we validate that the system is effective in supporting text entry in a fully mobile usage scenario likely to be encountered in industrial applications of AR HMDs.
