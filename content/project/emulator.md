+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Bayesian Regional Climate Model Emulator"

# Project summary to display on homepage.
summary = "A Bayesian statistical framework to emulate RCM output variables using output variables from Global Circulation Models (GCM) as covariates."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "resolution.jpeg"

# Tags: can be used for filtering projects.
# Example: `tags = ["bayesian", "climate models"]`
tags = ["stats"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

+++

Regional Climate Models (RCM) provide high-resolution climate simulations that are important to investigate variation in regional scale projections. We introduce a Bayesian statistical framework to emulate RCM output variables using output variables from Global Circulation Models (GCM) as covariates. This emulator is an alternative to the RCM runs, which are computationally expensive. 

The Bayesian RCM emulator has spatially varying coefficients with data-dependent priors to perform variable selection in each location. To that end, we model both the spatially varying coefficients and the response as smooth spatial processes. The method is then applied to emulate precipitation from the CRCM regional model output from the North American Regional Climate Change Assessment Program (NARCCAP) using a set of variables from the CCSM global circulation model output. 

Furthermore, the prior weights are used to assess the usefulness of each covariate from the global model output, to emulate the regional model for each location of the NARCCAP data domain. We built the model on Summer data from 1970 to 1998 over a spatial domain covering the Western part of the continental United States and Canada and validate it with data from 1999-2000 over the same spatial domain. 