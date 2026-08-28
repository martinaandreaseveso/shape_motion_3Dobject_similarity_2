# shape_motion_3Dobject_similarity_2

**Contributors**
Martina Andrea Seveso,
Rebecca Hirst,
Alan O'Dowd,
Fiona N. Newell

This experiment used a Garner interference paradigm to test whether motion is integrated into object representations in memory. Participants classified objects based on shape while ignoring motion.

**Research aims**

To investigate if shape and motion of 3D novel objects are either separable or integral dimensions of the stimuli.

Garner’s speeded-classification task provides a reliable measure of how efficiently individuals can process one dimension of an object while ignoring its other dimensions. In a typical Garner experiment participants are asked to classify objects on the basis of a single dimension under two different conditions:
1) Baseline = the task-irrelevant dimension is held constant, so that only the relevant dimension varies each trials;
2) Filtering = the task-irrelevant dimensions vary randomly along with relevant dimension.
Garner Interference = MRT (Filtering) – MRT (Baseline); where MRT is the mean reaction time to correctly classify the relevant dimension.

The difference in performance between the two conditions reveals the success of selective attention to the relevant dimension.
1) If participants are able to process the two dimensions independently then the speed and accuracy should be identical for the baseline and filtering conditions.
2) If participants cannot process the two dimensions independently then performance should be worse for the filtering condition than for the baseline condition, because participants cannot ‘filter out’ the changes in the irrelevant dimension.
We adapted the Garner Interference paradigm to develop a matching task with moving and static 3D novel objects, considering alternatively shape and motion as relevant dimensions.

**Method and Procedure**

The study is develop in PsychoPy (version *2023; Peirce et al., 2019) and it is conducted online through Pavlovia.

The study is a matching task with moving and static 3D novel objects. We considered alternatively shape and motion as relevant dimensions. Participants are before exposed to a training phase (to familiarise with the procedure) and a testing phase. Both phases were structured as followed.

Instructions: please examine the pair of objects simultaneously presented and decide if they have the same shapes or motion (i.e., they move in the same way). To do so, please press “A” to indicate YES and “L” to indicate NO. .

The total duration of the experiment was around 20-25 minutes.

**Stimuli**

The experiment presents with static or moving 3D objects shapes of unfamiliar objects.

_Development of 3D shapes_: The 2D shapes were extracted from a visual circular shape space, designed and validated by Li et al. (2020). The 3D modelling procedure was accomplished with the software Blender 3.5.0 (2023) (www.blender.org). The 2D shape outline was rotate of 360 degrees along the central vertical axes though the Spin Function in Edit mode (degrees 360, steps 100).

_Stimulus design pipeline for the 3D object models_: The objects were created using the pipeline (1) each shape was converted from .png to Scalable Vector Graphics (.svg) keeping three different colour levels constant (e.g., white, black, grey); (2) each vector was imported into the 3D-space; (3) the outline was isolated and converted into a mesh; (4)each mesh was rotated along the central vertical axes through the Spin Function in Edit mode (360°, steps-100); (5) each 3D-shape was extracted from Blender. The 3D-space, lighting (point, radius-0.1m,1000W; coordinates:11m,-14 m,6.9m; rotation:40°, 34.8°) and viewpoint (coordinates: 10.9m, -14m, 4m; rotation:70°, 0°) settings were kept constant. Each 3D-object was rendered using the Workbench Engine (28-render samples, Single pass Anti-Aliasing viewpoint; Studio Lighting, Colour Material [dark grey, RGB:107,109,109,254; HEX:#6b6d6d] and Specular Lighting). All the object images were extracted with a resolution of 1080 x 1080 px, scale100%, and presented in a canonical, 3/4view so that the 3D-object and relevant features (e.g., concavities) were visually accessible in the image. The camera angle (coordinates:10.9m, -14m, 4m; rotation:70°, 0°) and lighting (point, radius-0.1m, 1000W; coordinates: 11m, -14 m, 6.9m; rotation:40°, 34.8°) were both held constant.

_Animation procedure_: Four main motion types were defined: swinging or jumping along the vertical axes, and continuous rotation and vibration along the horizontal axes. Each action was completed once during the video sequence, which had a total duration of 2 seconds.

**Design**

The study is a fully within-subjects/repeated measures Design. Both relevant dimensions conditions are presented in a block design, which order is fully randomised and counterbalanced across participants. All participants experience both conditions, such as Shape as the relevant dimension and Motion as the relevant dimension and the relative conditions as summaries below.
1) Shape as the relevant dimension: baseline (only shape varies, motion is constant), filtering (both motion and shape randomly vary), correlation (specific shapes are presented with specific motion)
2) Motion as the relevant dimension: baseline (only motion varies, shape is constant), filtering (both motion and shape randomly vary), correlation (specific shapes are presented with specific motion).
The full randomisation of both the blocks (shape and motion as relevant dimensions) and the conditions (baseline, filtering and correlation) presentation order is determined by PsychoPy.

**Dependent variables**

The two outcome variables are accuracy and reaction times (RTs) of the matching task. This is measured by asking participants to decide if the objects they just saw have the same shape or motion (“Yes”/“No” as responses).

**Independent variables**

1) Relevant dimension (RD): RD is Shape and the Irrelevant dimension (IRRD) is Motion, RD Motion and the Irrelevant dimension (IRRD) is Shape,
2) Conditions: Baseline (only RD varies, IRRD is constant), Filtering (both RD and IRRD randomly vary), Correlation (specific RD are presented with specific IRRD)

**Covariates
**
Age, sex.

**Sample size**

The total sample size is 30 participants.

Power analysis was conducted on PANGEA (https://jakewestfall.shinyapps.io/pangea/) for a 2x3 within-subjects design. For the 2x3 interaction effect (Relevant Dimension x Conditions) 80% power was achieved with 30 participants, assuming an effects size (Cohen’s d) of 0.3.

**Ethics**

Full ethical approval was obtained from the School of Psychology Ethics Committee, Trinity College Dublin.

**References:**

Peirce, J. W., Gray, J. R., Simpson, S., MacAskill, M. R., Höchenberger, R., Sogo, H., Kastman, E., Lindeløv, J. (2019). PsychoPy2: experiments in behavior made easy. Behavior Research Methods. 10.3758/s13428-018-01193-y

Garner, W. R., & Felfoldy, G. L. (1970). Integrality of stimulus dimensions in various types of information processing. Cognitive Psychology, 1(3), 225–241.
Garner WR (1974) The processing of information and structure, 1st edn. Psychology Press, New York.
Garner WR (1978) Selective attention to attributes and to stimuli. J Exp Psychol Gen 107:287–308.

Ganel, T., & Goodale, M. A. (2014). Variability-based Garner interference for perceptual estimations but not for grasping. Experimental brain research, 232, 1751-1758.
Freud, E., & Ganel, T. (2015). Visual control of action directed toward two-dimensional objects relies on holistic processing of object shape. Psychonomic Bulletin & Review, 22, 1377-1382.
Wang, Yamin, et al. “Discriminability effect on Garner interference: evidence from recognition of facial identity and expression.” Frontiers in Psychology 4 (2013): 943.

Li, A. Y., Liang, J. C., Lee, A. C., & Barense, M. D. (2020). The validated circular shape space: Quantifying the visual similarity of shape. Journal of Experimental Psychology: General, 149(5), 949.

**License**
a. Code (analysis scripts, stimuli generation): MIT License
b. All other materials (data, stimuli, experimental design): CC BY 4.0

All stimuli were created by the author (Seveso, M., A.). Data has been anonymised and contains no personal information.
