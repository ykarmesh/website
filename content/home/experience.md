---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Robotics Engineer
    company: isee
    company_url: 'www.isee.ai'
    location: Pittsburgh
    date_start: '2020-07-01'
    date_end: ''
    description: |2-
        * Investigating online methods to estimate tracking performance of AVs using deep flow-based models.
        * Developed the speed planning module for safely achieving three-fold increase in operating speed

  - title: Software Development Intern
    company: isee
    company_url: 'www.isee.ai'
    location: Boston
    date_start: '2019-05-20'
    date_end: '2019-08-10'
    description: |2-
        * Built toolboxes to automate the system identification and calibration procedure of Isee’s vehicles.
        * Researched and implemented various vehicle and tire models for control application in AVs.

  - title: Graduate Research Assistant
    company: Robotics Research Center, IIITH
    company_url: 'https://robotics.iiit.ac.in/'
    location: Hyderabad
    date_start: '2017-08-01'
    date_end: '2018-06-12'
    description: |2-
        * Created a Q-Learning based planner to prevent monocular slam failure on non-holonomic robots.
        * Developed a simulation environment in Gym-Gazebo for training, with Navigation Stack for planning and ORB-SLAM for perception and localization.

  - title: Intern, Autonomous Driving Team
    company: Mathworks
    company_url: 'https://www.mathworks.com/'
    location: Hyderabad
    date_start: '2017-08-01'
    date_end: '2017-11-24'
    description: |2-
        * Optimized ORB-SLAM and made it more robust to fuse its position output with RTK-GPS, IMU & Wheel Encoder data using an EKF.
        * Worked on SLAM pose covariance estimation and extrinsic calibration of IMU and cameras        

  - title: Research Intern
    company: Intelligent Vehicles Lab, National Taiwan University
    company_url: 'http://140.112.14.7/~kangli1234/IVMechatronics/index.html'
    location: Taipei
    date_start: '2016-05-15'
    date_end: '2016-07-20'
    description: |2-
        * Developed a two-level motion planner, utilizing the A-star (A*) and Rapidly-exploring Random Tree (RRT) algorithm, on a local map built using laser scanners for an electric golf cart.
        * Created a vehicle model and forward-simulated the vehicle trajectory using Pure Pursuit steering controller and Proportional-Integral (PI) speed controller.
---
