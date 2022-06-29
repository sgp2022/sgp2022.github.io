---
title: "Program"
layout: "program"
type: "page"
menu: program


speakers: 
  - name: Angela Dai
    url: https://www.professoren.tum.de/dai-angela
    affiliation: Technical University of Munich
    title: "Towards Structured Geometric Understanding for 3D Perception"
    abstract: "Semantic perception of 3D environments has seen remarkable advances in recent years, with a significant focus on object-based understanding. We propose to learn structured, intermediary representations, such as object parts, in order to provide a robust understanding of diverse 3D geometric structures from observations of real-world environments. This can enable more effective geometric reconstruction of objects in 3D scenes, enabling inter- and intra-object reasoning, as well as establish efficient structured representations for reconstruction and tracking of objects undergoing complex deformations."
    portrait: /images/Dai.jpg
  - name: Ligang Liu
    url: http://staff.ustc.edu.cn/~lgliu/
    affiliation: University of Science and Technology of China
    title: "Computational 3D Visual Art Design"
    abstract: "3D visual arts are highly diverse, including sculpture, architecture, ceramics, etc., in our lives.  Traditionally, artists use their rich imagination and experience to design 3D objects to give the audience a memorable experience. The design process takes a lot of trial and error, so it is often very time-consuming. It has attracted the attention of many researchers in the community of geometry processing and computer graphics, proposing various algorithms to simplify the initial complicated design process and help artists quickly realize the art in their minds. Moreover, the advent of digital modeling and 3D printing enables artists to create more complex 3D visual artworks.  In this talk, we will show a few interesting 3D visual art works and propose automatic methods to solve various problems in the design process of these art works.  From these examples, we reveal the close connection between geometry processing techniques and various 3D visual art design problems. Moreover, we will discuss about the current research trends and provide an outlook for future research directions and solutions."
    portrait: /images/Liu.png     
  - name: Caitlin Mueller
    url: http://www.caitlinmueller.com/
    affiliation: MIT Architecture
    title: "Geometry for design and construction of high-performance architecture"
    abstract: "Design and construction in the built environment present significant challenges and opportunities for impact: Buildings contribute to about 40% of global carbon emissions through their materials and operations, often due to inefficiencies stemming from a lack of integration between architectural design, engineering, and construction processes.  While this disconnect has been critiqued for decades, today's emerging techniques in computation, and in particular, geometry, can allow for a new layer of interdisciplinary communication and collaboration that transforms traditional workflows and empowers novel visual languages for high-performance architecture.  In this talk, Mueller will share recent work that contributes to this goal, demonstrating new techniques for computational design that integrate engineering principles and sustainability goals without overriding creative autonomy, and new fabrication methods that can materialize efficient geometries economically.  In particular, the talk will demonstrate how techniques developed in geometry processing and related fields can empower significant innovation in architectural domains, and will propose emerging problem spaces and applications for future geometry research."  
    portrait: /images/Mueller.png      
  - name: Daniele Panozzo
    url: https://cims.nyu.edu/gcl/daniele.html
    affiliation: New York University
    title: "Robust Geometry Processing for Physical Simulation"
    abstract: "The numerical solution of partial differential equations (PDE) is ubiquitously used for physical simulation in scientific computing, computer graphics, and engineering. Ideally, a PDE solver should be opaque: the user provides as input the domain boundary, boundary conditions, and the governing equations, and the code returns an evaluator that can compute the value of the solution at any point of the input domain. This is surprisingly far from being the case for all existing open-source or commercial software, despite the research efforts in this direction and the large academic and industrial interest. To a large extent, this is due to lack of robustness and generality in the geometry processing algorithms used to convert raw geometrical data into a format suitable for a PDE solver. I will discuss the limitations of the current state of the art, and present a proposal for an integrated pipeline, considering data acquisition, meshing, basis design, and numerical optimization as a single challenge, where tradeoffs can be made between different phases to increase automation and efficiency. I will demonstrate that this integrated approach offers many advantages, while opening exciting new geometry processing challenges, and that a fully opaque meshing and analysis solution is already possible for heat transfer and elasticity problems with contact. I will present a set of applications enabled by this approach in reinforcement learning for robotics, force measurements in biology, shape design in mechanical engineering, stress estimation in biomechanics, and simulation of deformable objects in graphics."
    portrait: /images/Panozzo.jpg

graduateSchoolCourses:
  - title: Deep Learning on Point Clouds
    teaser: /images/default_thumbnail.jpg
    speakers:
      - name: Hao Su
        url: https://cseweb.ucsd.edu/~haosu/
        affiliation: UC San Diego
    abstract: |
                Point cloud is an important type of geometric data structure. They are simple and unified structures that avoid the combinatorial irregularities and complexities of meshes. These properties make point clouds widely used for 3D reconstruction or visual understanding applications, such as AR, autonomous driving, and robotics. This course will teach how we apply deep learning methods to point cloud data. We will cover the following topics in this short course and will end with some open problems.
                
                1) &bull; Basic neural architectures to process point cloud as input or to generate point cloud as output
                2) &bull; Scene-level understanding of static and dynamic point clouds 
                3) &bull; Point cloud based inverse graphics 
                4) &bull; Learning to convert point cloud to other 3D representations 
                5) &bull; Learning to map point cloud with data in other modalities (images, languages)
                    
               
  - title: Learning to Represent 3D Shapes with Programs
    teaser: /images/default_thumbnail.jpg
    speakers:
      - name: Daniel Ritchie
        url: https://dritchie.github.io/
        affiliation: Brown University
    abstract: |
                There are many representations for 3D shapes: triangle meshes, point clouds, parametric surfaces, signed distance fields, and so on. Different representations may be better for certain tasks: acquisition, editing, rendering, etc. In recent years, the space of possible 3D shape representations has been a topic of much discussion because of a new task: machine learning. Specifically, researchers have been exploring the following question: which 3D shape representations are best for learning from data?
                In this course, we'll discuss a 3D shape representation with an old history that has been receiving renewed attention in today's learning-based era: programs. Programs (i.e. executable symbolic descriptions of a structure) have several properties that make them attractive for learning. For example, they can be constructed such that they cannot represent certain undesirable geometric artifacts that often plague learning-based systems, and their discrete symbolic nature makes them well-suited for processing with powerful neural language models such as Transformers.
                Specifically, this course will cover the following, and we'll conclude with some thoughts on current open problems in this field as well as ideas for new graduate students to pursue.
                
                1) &bull; Learning problems/tasks involving program representations (visual program induction, generative modeling)
                2) &bull; Domain-specific languages (DSLs) for shape modeling: current popular choices and considerations to make when choosing/designing one for your own project
                3) &bull; Machine learning model architectures for learning/processing program representations
                4) &bull; Algorithms for supervised and unsupervised learning of program representations for 3D shapes

                
  - title: 3D Morphable Face Models
    teaser: /images/default_thumbnail.jpg
    speakers:
      - name: Bernhard Egger
        url: https://www.ki.fau.de/speakers/prof-dr-bernhard-egger/
        affiliation: Friedrich-Alexander-University, Erlangen-Nürnberg
    abstract: "A 3D Morphable Model (3DMM) is a statistical object model separating shape from appearance variation. Typically, 3DMMs are used as a statistical prior in computer graphics and vision. A model is learned from high-quality 3D scans of multiple object instances. It reduces the dimensionality and provides a low-dimensional, parametric object representation. The resulting model is generative, which means that from a set of randomly sampled parameters a novel realistic object instance arises. Such a model can then be used in various settings, we will focus on the inverse rendering setting, where we try to reconstruct the 3D face from a 2D image with the 3DMM as prior. In this tutorial I will introduce 3DMMs from scratch and focus on explaining every single component behind a 3DMM. We will also have a short outlook at various applications and how 3DMMs are used today and combined with other modeling techniques."
  - title: Character animation
    teaser: /images/default_thumbnail.jpg
    speakers:
      - name: Taku Komura
        url: https://i.cs.hku.hk/~taku/
        affiliation: University of Hong Kong
    abstract: "Character animation is a topic that has a wide range of applications for films, computer games, digital entertainment, automatic driving, Metaverse and virtual reality.  In this lecture, I will start from the basics of character animation and then discuss novel topics in facial animation, data-driven full body motion synthesis based on neural networks, reinforcement learning and physically-based animation."
  - title: Geometric Computing for Biomedicine
    teaser: /images/default_thumbnail.jpg
    speakers:
      - name: Tao Ju
        url: https://www.cse.wustl.edu/~taoju/
        affiliation: Washington University in St. Louis
    abstract: "With the advance of biomedical imaging technology, research in biology and medicine increasingly relies on the ability to robustly and efficiently extract knowledge from raw images. The goal of this course is to offer an overview of the roles that geometry processing can play in this data-to-knowledge process. The course starts with a brief introduction to biomedical imaging and the typical computational tasks on these images (e.g., segmentation, analysis, registration, etc.). The bulk of the course will be devoted to several examples of geometry processing problems that arise from accomplishing these tasks, including meshing of scalar fields, slice-based surface reconstruction, topology simplification, and skeletonization, and progress made so far for solving each problem. The course will end with a few example biomedical applications that utilize geometry processing algorithms."
  - title: An Introduction to High-Order Mesh Generation
    teaser: /images/default_thumbnail.jpg
    speakers: 
      - name: Daniele Panozzo
        url: https://cims.nyu.edu/gcl/daniele.html
        affiliation: NYU
    abstract: | 
                Meshes with curved edges are a useful discretization to represent curved geometries or high-order displacement fields more compactly than their linear counterpart. The smaller number of degrees of freedom, coupled with the additional flexibility in the shape of the elements, has major computational advantages. However, the curved geometry introduces additional algorithmic and numerical challenges.
                In this lecture, we discuss the advantages and disadvantages of linear and curved meshes and overview the current state of the art in both curved mesh generation and their use for the solution of partial differential equations with the finite element method. A particular focus is on the major open geometric challenges introduced by the curved boundaries, including checking for inversions, Boolean operations, collision detection, and input sanitization for the commonly used SVG and STEP industrial standards.
                The prerequisites for this lecture are an undergraduate linear algebra course and an undergraduate graphics or geometry processing course. A course on numerical methods and/or on the finite element method is a plus but not necessary.

  - title: "The Fusion 360 Gallery Dataset: Learning segmentation, reconstruction and assembly modeling"
    teaser: /images/default_thumbnail.jpg
    speakers: 
      - name: Joseph Lambourne
        url: https://www.autodesk.com/research/people/joseph-lambourne
        affiliation: Autodesk
      - name: Karl Willis
        url: https://www.karlddwillis.com/
        affiliation: Autodesk, London
    abstract: "Almost every manufactured object in the world around us starts life as a computer-aided design (CAD) model. Industrial CAD models contain rich, multi-faceted data describing precise geometry as analytical surfaces, complex topology for parts as well as assemblies, and the underlying sequential modeling operations invoked by the CAD user. This talk introduces the Fusion 360 Gallery Dataset, a collection of CAD data submitted by users to the Autodesk Online Gallery. We give an overview of the available data and present some of our recent research which utilizes this for segmentation, CAD sequence determination and assembly modeling. We also outline unsolved challenges and areas for future investigation."
  - title: Learning to Understand 3D from Large-Scale Indoor Scene Data
    teaser: /images/default_thumbnail.jpg
    speakers: 
      - name: Angela Dai
        url: https://www.professoren.tum.de/dai-angela
        affiliation: Technical University of Munich
    abstract: "We have seen a revolution in 2D image understanding, driven by large-scale image datasets coupled with advances in deep learning. How can we bring this to 3D perception, which is fundamental to understanding scene structure to enable higher-level understanding such as interaction with environments? This talk will discuss the creation of large-scale 3D annotated datasets to enable learning strong data-driven priors, with focus on the ScanNet dataset. We will additionally discuss open challenges with existing 3D data, learning efficiently in limited data scenarios, and under potentially imperfect data."
  - title: Replicability in Computer Graphics
    teaser: /images/default_thumbnail.jpg
    speakers: 
      - name: Nicolas Mellado
        url: https://www.irit.fr/recherches/STORM/MelladoNicolas/
        affiliation: CNRS - IRIT
      - name: Julie Digne
        url: https://perso.liris.cnrs.fr/julie.digne/
        affiliation: CNRS - LIRIS   
      - name: Nicolas Bonneel
        url: https://perso.liris.cnrs.fr/nicolas.bonneel/
        affiliation: CNRS
      - name: David Coeurjolly
        url: https://perso.liris.cnrs.fr/david.coeurjolly/
        affiliation: CNRS - LIRIS
    abstract: | 
                In this talk, we will introduce the concept of replicability, and its benefits in research. 
                We will present how replicability affects the work of researchers, the visibility of the research outcomes, and the impact on their diffusion. We will also cover the tools that are today available to develop replicable research, and attempt to sketch guidelines and best practices for research practitioners, e.g., students, researchers.
  - title: Practical Design and Analysis of Directional Fields. 
    teaser: /images/default_thumbnail.jpg
    speakers: 
      - name: Amir Vaxman
        url: https://webspace.science.uu.nl/~vaxma001/
        affiliation: Utrecht University
    abstract: "Directional fields on surfaces and in volumes are important features of geometry processing. Such fields can represent flows, alignments, or trends in geometry. In this tutorial, we will learn some of the elementary building blocks of directional field processing. Namely, we will demonstrate how to build discrete consistent representations, connections, and differential operators. Finally, we will talk about field visualization. These constructions will be represented using examples from Directional (https://github.com/avaxman/Directional)."
  - title: Blender for Academic Papers
    teaser: /images/default_thumbnail.jpg
    speakers: 
      - name: Silvia Sellán
        url: https://www.silviasellan.com/
        affiliation: University of Toronto
    abstract: "There are a lot of great Blender tutorials online, and they are usually aimed at artists or animators who want to generate full scenes from scratch for short films. They go into depth on how to model a shape, how to pick the best lighting, how to design a material, create textures, etc. These can be overwhelming if you are an academic and all you want is to render your object beautifully for a SIGGRAPH paper figure. This can lead to a lot of frustration especially near deadlines, when one does not have the time or energy to learn a whole new aspect of the software just for a minor change in a paper figure. In this course, aimed at absolute Blender beginners, we will mitigate this frustration by walking slowly from .obj file to beautiful paper figure, showing tricks to save time and effort."


paperSessions: 
  - name: MODELING & MAPPING
    chair: Mirela Ben-Chen
    papers:
      - title: "Harmonic Shape Interpolation on Multiply-connected Domains"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Dongbo Shi
          - name: Renjie Chen
      - title: "Localized Shape Modelling with Global Coherence: An Inverse Spectral Approach"
        teaser: /preview/MODELING_MAPPING/2.png
        authors: 
          - name: Marco Pegoraro
          - name: Simone Melzi
          - name: Umberto Castellani
          - name: Riccardo Marin
          - name: Emanuele Rodola
      - title: "Non-Isometric Shape Matching via Functional Maps on Landmark-Adapted Bases (CGF)"
        teaser: /preview/MODELING_MAPPING/3.png
        authors: 
          - name: Mikhail Panine
          - name: Maxime Kirgo
          - name: Maks Ovsjanikov
          
  - name: CURVES & FEATURES
    chair: Jorg Peters
    papers:
      - title: "Smooth Interpolating Curves with Local Control and Monotone Alternating Curvature"
        teaser: /preview/CURVES_FEATURES/1.png
        authors:
          - name: Alexandre Binninger
          - name: Olga Sorkine-Hornung
      - title: "b/Surf: Interactive Bézier Splines on Surface Meshes (TVCG)"
        teaser: /preview/CURVES_FEATURES/2.png
        authors:
          - name: Claudio Mancinelli
          - name: Giacomo Nazzaro   
          - name: Fabio Pellacini    
          - name: Enrico Puppo     
      - title: "SGLBP: Subgraph-based Local Binary Patterns for Feature Extraction on Point Clouds (CGF)"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Bao Guo
          - name: Yuhe Zhang     
          - name: Jian Gao,  
          - name: Chunhui Li
          - name: Yao Hu   
 
  - name: LEARNING & CREATING
    chair: Julie Digne
    papers:
      - title: "PriFit: Learning to Fit Primitives Improves Few Shot Point Cloud Segmentation"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Gopal Sharma
          - name: Bidya Dash
          - name: Aruni RoyChowdhury
          - name: Matheus Gadelha
          - name: Marios Loizou
          - name: Liangliang Cao
          - name: Rui Wang
          - name: Erik G. Learned-Miller
          - name: Subhransu Maji
          - name: Evangelos Kalogerakis
      - title: "SDF-StyleGAN: Implicit SDF-Based StyleGAN for 3D Shape Generation"
        teaser: /preview/LEARNING_CREATING/2.png
        authors:
          - name: Xinyang Zheng
          - name: Yang Liu
          - name: Pengshuai Wang
          - name: Tong Xin
      - title: "MendNet: Restoration of Fractured Shapes Using Learned Occupancy Functions"
        teaser: /preview/LEARNING_CREATING/3.png
        authors:
          - name: Nikolas Lamb
          - name: Sean Banerjee
          - name: Natasha Banerjee

  - name: MESHES & PARTITIONS
    chair: David Bommes
    papers:
      - title: "Precise High-order Meshing of 2D Domains with Rational Bézier Curves"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Jinlin Yang
          - name: Shibo Liu
          - name: Shuangming Chai
          - name: Ligang Liu
          - name: Xiao-Ming Fu
      - title: "Rational Bézier Guarding"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Payam Khanteimouri
          - name: Manish Mandad
          - name: Marcel Campen
      - title: "Simplification of 2D Polygonal Partitions via Point-line Projective Duality, and Application to Urban Reconstruction (CGF)"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Julien Vuillamy
          - name: Andre Lieutier    
          - name: Florent Lafarge   
          - name: Pierre Alliez
         
  - name: TOOLS & DATA
    chair: Justin Solomon
    papers:
      - title: "Deterministic Linear Time for Maximal Poisson-Disk Sampling using Chocks without Rejection or Approximation"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Scott Mitchell 
      - title: "TinyAD: Automatic Differentiation in Geometry Processing Made Simple"
        teaser: /preview/TOOLS_DATA/2.png
        authors:
          - name: Patrick Schmidt
          - name: Janis Born
          - name: David Bommes 
          - name: Marcel Campen  
          - name: Leif Kobbelt
      - title: "Hex Me If You Can"
        teaser: /images/default_thumbnail.jpg
        authors:
          - name: Pierre-Alexandre Beaufort
          - name: Maxence Reberol
          - name: Denis Kalmykov
          - name: Heng Liu
          - name: Franck Ledoux
          - name: David Bommes 

  - name: TILING & NESTING
    chair: Pierre Alliez
    papers:
      - title: "Constructing L∞ Voronoi Diagrams in 2D and 3D"
        teaser: /preview/TILING_NESTING/1.png
        authors:
          - name: Dennis Bukenberger
          - name: Kevin Buchin
          - name: Mario Botsch
      - title: "Fabricable Multi-Scale Wang Tiles"
        teaser: /preview/TILING_NESTING/2.png
        authors:
          - name: Xiaokang Liu
          - name: Chenran Li
          - name: Lin Lu
          - name: Oliver Deussen
          - name: Changhe Tu 
      - title: "Topological Simplification of Nested Shapes"
        teaser: /preview/TILING_NESTING/3.png
        authors:
          - name: Dan Zeng
          - name: Erin Chambers 
          - name: David Letscher
          - name: Tao Ju
---  
&nbsp;

&nbsp;

The detailed [**Conference Program Schedule**](/images/SGP_2022_Program.pdf) is available as PDF.

*(The file with timestamp 2022-06-20 09:00:00 is the current one)*

<!-- 

paperUSB: https://cloud.fraunhofer.at/s/sY2mezd4NgRRoPM/download/USB-SGP2021.zip
paperURL: https://diglib.eg.org/handle/10.2312/2633079     

speakers: 
  - name: Keynote speaker Name
    youtube: https://www.youtube.com/embed/
    url: https://speakerurl
    affiliation: affiliation Speaker
    title: "Title title tilte"
    abstract: "Abstract."
    bio: "Bio."
    portrait: /images/brportrait.jpg

    
graduateSchoolCourses:
  - title: Learning on Point Clouds
    speakers:
      - name: Hao Su
        url: https://cseweb.ucsd.edu/~haosu/
        affiliation: UC San Diego
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/...
  - title: Learning on 3D Structures
    speakers:
      - name: Daniel Ritchie
        url: 
        affiliation: 
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/...    
  - title: 3D Morphable Face Models
    speakers:
      - name: Bernhard Egger
        url: https://www.ki.fau.de/speakers/prof-dr-bernhard-egger/
        affiliation: 
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/...    
  - title: Character animation
    speakers:
      - name: Taku Komura
        url: 
        affiliation: 
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/...    
  - title: Geometric Computing for Biomedicine
    speakers:
      - name: Tao Ju
        url: https://www.cse.wustl.edu/~taoju/
        affiliation: Washington University in St. Louis
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/... 
  - title: High-order mesh generation
    speakers: 
      - name: Daniele Panozzo
        url: https://cims.nyu.edu/gcl/daniele.html
        affiliation: NYU
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/... 
  - title: Fusion 360 Gallery Dataset
    speakers: 
      - name: Joseph Lambourne
        url: 
        affiliation: 
      - name: Karl Willis
        url: 
        affiliation:         
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/... 
  - title: ScanNet Dataset
    speakers: 
      - name: Angela Dai
        url: 
        affiliation: 
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/... 
  - title: Code Replicability
    speakers: 
      - name: Nicolas Mellado
        url: 
        affiliation: 
      - name: Julie Digne
        url: 
        affiliation:    
      - name: Nicolas Bonneel
        url: 
        affiliation: 
      - name: David Coeurjolly
        url: 
        affiliation:         
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/...    
  - title: Directional
    speakers: 
      - name: Amir Vaxman
        url: https://webspace.science.uu.nl/~vaxma001/
        affiliation: Utrecht University
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/...     
  - title: Blender for Paper
    speakers: 
      - name: Silvia Sellán
        url: 
        affiliation: 
    abstract: "Abstract TBD"
    teaser: /images/unknown.jpg
    youtube: https://www.youtube.com/embed/...          
    
paperSessions: 
  - name: Session Name
    youtube: https://www.youtube.com/embed/videoseries?list=
    chair: Session Chair
    teaser: /images/unknown.jpg
    papers:
      - title: "Paper1"
        authors:
          - name: Author1
          - name: Author2
      - title: "Paper2"
        authors: 
          - name: Author1
          - name: Author2   
          
          
-->
