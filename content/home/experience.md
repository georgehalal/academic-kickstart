+++
# Experience widget.
widget = "experience"  # Do not modify this line!
active = true  # Activate this widget? true/false

title = "Analysis Projects"
subtitle = ""

# Order that this section will appear in.
weight = 8

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Feasibility of Tagging Heavy Flavor Jets at RHIC Using Machine Learning"
  company = "Yale University"
  company_url = ""
  location = ""
  date_start = "2018-01-01"
  date_end = ""
  description = """
  Advisors: Helen Caines & John Harris
  
  * Simulated proton-proton collisions at RHIC energies using PYTHIA, and clustered final state particles into jets using FastJet.
  * Trained an artificial neural network using Keras on a list of discriminators to be able to classify charm, bottom, and light jets.
  * Included STAR detector effects and tracking efficiency.
  * Developed a new jet tagging strategy for RHIC.
  * Presented results at the 2018 STAR Winter Analysis Meeting at Brookhaven National Laboratory.
  """

[[experience]]
  title = "Centrality & Event Plane (EP) Determination Using Machine Learning with the STAR Event Plane Detector (EPD)"
  company = "Lehigh University & The Ohio State University"
  company_url = ""
  location = ""
  date_start = "2018-01-01"
  date_end = ""
  description = """
  Advisors: Rosi Reed & Michael Lisa
  
  * Trained an artificial neural network (ANN) to identify the centrality of a collision, based on which EPD tiles are hit during a given event.
  * Trained another ANN to identify the 2nd order EP of a collision by minimizing the difference between the EPs measured by the east and west EPDs
  * Tried different machine learning packages in ROOT and Python to determine which performs the best.
  * Presented results at the 2018 STAR Collaboration Meeting at Lehigh University
  * My plots were also presented by Dr. Michael Lisa at the Workshop on Chirality, Vorticity and Magnetic Field in Heavy Ion Collisions in Florence, Italy.
  """
  
[[experience]]
  title = "Performance Analysis of the STAR Event Plane Detector (EPD)"
  company = "Lehigh University"
  company_url = ""
  location = ""
  date_start = "2017-01-01"
  date_end = "2018-01-01"
  description = """
  Advisors: Rosi Reed & Michael Lisa
  
  * Analyzed data collected by the eighth of the EPD that was installed for the RHIC 2017 run, colliding protons at √s = 510 GeV and gold ions at √sNN = 54.4 GeV, to optimize its final design
  * Compared the EPD to the other detectors at the STAR experiment to verify that they are measuring the same collisions at the same time and that the electronics work properly.
  * Analyzed the charged particle multiplicity distribution in the EPD as a function of pseudorapidity and compared it to the results from the RHIC PHOBOS experiment and to Monte Carlo simulations.
  * Studied the ADC distributions of the tiles in the EPD to quantify the number of minimum ionizing particles (MIP) hitting the detector.
  * Studied whether it is useful to have a maximum ADC cap for each tile in the EPD in order to suppress the effects of large Landau fluctuations and what that value is.
  """

+++
