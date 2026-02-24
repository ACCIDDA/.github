# Atlantic Coast Center for Infectious Disease Dynamics and Analytics (ACCIDDA)

Welcome to the Atlantic Coast Center for Infectious Disease Dynamics and Analytics (ACCIDDA) GitHub organization!

ACCIDDA is devoted to rapid, coordinated response to infectious disease threats through innovative modeling techniques, enhanced data integration, and training a new generation of public health experts. By prioritizing predictive analytics relevant to smaller, often overlooked populations—particularly rural communities—ACCIDDA ensures that local public health decisions are informed by comprehensive insights. As the Insight Net coordination center, ACCIDDA fosters collaboration and readiness across the network through network-wide meetings, tech transfer workshops, and modeling challenges.

# Project Highlights

## AI Tools

We use a variety of cutting edge AI techniques in our work. The publicly released ones include:

 - [influpaint](https://github.com/jcblemai/influpaint) uses a novel "[inpainting](https://en.wikipedia.org/wiki/Inpainting#Digital_inpainting)" technique to generate infectious disease trends.
 - [LEMMA-forecast](https://github.com/ACCIDDA/LEMMA-forecast) generates intermediate predictions using simple mechanistic models, learns from their mistakes, and generates the final predictions using Machine Learning.

## Dashboards

Rapid visualization of operationally-relevant trends is key to decision-making and is a routine part of our work. In additional to custom products, we also have publicly available examples like:

 - [RespiLens](https://github.com/ACCIDDA/RespiLens) provides a flexible dashboard for respiratory disease trends; [check it out here](https://www.respilens.com)! Also, be sure to try [Forecastle](https://www.respilens.com/forecastle) to test your skill at forecasting.
 - [Forecast-viz Creator](https://github.com/ACCIDDA/forecast-viz-creator) provides a tool to rapidly generate public dashboards for visualizing forecasts.
 - The [NC Measles Vaccine Coverage](https://www.dph.ncdhhs.gov/programs/epidemiology/communicable-disease/infectious-respiratory-diseases/measles-rubeola/nc-measles-vaccination-data-dashboard) dashboard shows estimated vaccine protection across the state, derived from our [imuGAP](https://github.com/ACCIDDA/imuGAP) tool.

## Decision Support

Our work on infectious disease modeling focuses on turning analysis into better outcomes. To that end, we make tools that commodify complex calculations and pipeline frameworks to reduce overhead of big-data analyses. Some of those tools include:

 - [tti](https://github.com/HopkinsIDD/tti/) provides a simple calculator to evaluate Test-Trace-Isolate interventions. [Learn how to use it here](https://www.coursera.org/learn/measuring-and-maximizing-impact-of-covid-19-contact-tracing).
 - [flepiMoP](https://github.com/ACCIDDA/flepimop2/), the *fle*xible *epi*demic *mo*deling *p*ipeline is an analysis framework for managing complex infectious disease simulations, inference, and scenario projection. You can read the [documentation here](https://accidda.github.io/flepimop). The previous version of [flepimop](https://github.com/HopkinsIDD/flepimop) is still available, but no longer maintained.

## Cutting Edge Modeling Toolkit

In addition to bespoke modeling applications, we are constantly refining general purpose tools to be ready for the next problem. We make many of these tools publicly available, including:

 - [tabularepimdl](https://github.com/UNCIDD/tabularepimdl) the _Tabular Epidemiological Model_ framework is a model-building domain specific language (DSL) for rapid prototyping and modification of infectious disease models.
 - [paramix](https://github.com/CMMID/paramix) is a tool to properly scale parameters for compartmental modeling, a common approach to infectious disease dynamics. Read more [about the method here](https://doi.org/10.1371/journal.pcbi.1013420).
 - [hashPRNG](https://github.com/epinowcast/hashprng) is drop-in replacement library for creating the properly matched model worlds which are necessary for high resolution scenario comparison.
 - the [op_system](https://github.com/ACCIDDA/op_system/) and [op_engine](https://github.com/ACCIDDA/op_engine/) tools provide general-purpose model builder and runner framework; they're also designed to work as modules with flepimop. 

## Specialized Inference Models

We also develop modeling packages focused on key epidemiological questions:

 - [imuGAP](https://github.com/ACCIDDA/imuGAP/) can use a wide variety of vaccination data, resolving data missingness and mixed aggregation across time, space, and age to provide high resolution age-and-place estimates of vaccine coverage
 - [hestia](https://github.com/ACCIDDA/hestia/) allows users to build custom disease and observation models to evaluate household study data and estimate key epidemiological parameters.

# Get in touch

Please contact project maintainers for specific questions and if you would like to contribute. 

For more general inquiries, to be connected with an ACCIDDA member expert on a particular project, or to talk to us about sponsoring infectious disease modeling research and development reach out to [ACCIDDA.info@unc.edu](mailto:ACCIDDA.info@unc.edu)
