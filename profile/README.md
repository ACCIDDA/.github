# Atlantic Coast Center for Infectious Disease Dynamics and Analytics (ACCIDDA)

Welcome to the Atlantic Coast Center for Infectious Disease Dynamics and Analytics (ACCIDDA) GitHub organization!

ACCIDDA is devoted to rapid, coordinated response to infectious disease threats through innovative modeling techniques, enhanced data integration, and training a new generation of public health experts. By prioritizing predictive analytics relevant to smaller, often overlooked populations—particularly rural communities—ACCIDDA ensures that local public health decisions are informed by comprehensive insights. As the Insight Net coordination center, ACCIDDA fosters collaboration and readiness across the network through network-wide meetings, tech transfer workshops, and modeling challenges.

# Project Highlights

## AI Tools

We develop several cutting-edge AI methods to improve forecasts of infectious disease dynamics. Our publicly released methods include:

- **Influpaint** ([GitHub](https://github.com/ACCIDDA/influpaint), [paper](https://arxiv.org/abs/2604.24913), [documentation—start here](https://accidda.github.io/influpaint/)) uses generative AI methods called diffusion models to produce diverse and flexible forecasts—similarly to how images are generated—using [inpainting](https://en.wikipedia.org/wiki/Inpainting#Digital_inpainting).
- [LEMMA-forecast](https://github.com/ACCIDDA/LEMMA-forecast) generates intermediate predictions using simple mechanistic models, learns from their mistakes, and generates the final predictions using Machine Learning.

## Dashboards

Rapid visualization of operationally-relevant trends is key to decision-making and is a routine part of our work. In additional to custom products, we also have publicly available examples like:

- **RespiLens** ([GitHub](https://github.com/ACCIDDA/RespiLens), [visit RespiLens](https://www.respilens.com/)) is a convenient web app for exploring local respiratory disease data and forecasts, featuring the latest CDC data. Test your forecasting skills with [Forecastle](https://www.respilens.com/forecastle), and explore our [toolbox](https://www.respilens.com/toolbox) to see how RespiLens can help you analyze disease trends.
- [Forecast-viz Creator](https://github.com/ACCIDDA/forecast-viz-creator) provides a tool to rapidly generate public dashboards for visualizing forecasts.
- The [NC Measles Vaccine Coverage](https://www.dph.ncdhhs.gov/programs/epidemiology/communicable-disease/infectious-respiratory-diseases/measles-rubeola/nc-measles-vaccination-data-dashboard) dashboard shows estimated vaccine protection across the state, derived from our [imuGAP](https://github.com/ACCIDDA/imuGAP) tool.

## Decision Support

Our work on infectious disease modeling focuses on turning analysis into better outcomes. To that end, we make tools that commodify complex calculations and pipeline frameworks to reduce overhead of big-data analyses. Some of those tools include:

- [tti](https://github.com/HopkinsIDD/tti/) provides a simple calculator to evaluate Test-Trace-Isolate interventions. [Learn how to use it here](https://www.coursera.org/learn/measuring-and-maximizing-impact-of-covid-19-contact-tracing).
- [FlepiMoP2](https://github.com/ACCIDDA/flepimop2/), the _Flexible Pipeline for Interchangeable Model Processing_, runs configuration-defined simulation and analysis campaigns. Its provider interfaces separate model specification, numerical integration, parameters, processing and persistence. See the [current documentation](https://accidda.github.io/flepimop2/latest/). The earlier [flepiMoP](https://github.com/HopkinsIDD/flepiMoP/) remains available for legacy workflows.

## Cutting Edge Modeling Toolkit

In addition to bespoke modeling applications, we are constantly refining general purpose tools to be ready for the next problem. We make many of these tools publicly available, including:

- [tabularepimdl](https://github.com/UNCIDD/tabularepimdl) the _Tabular Epidemiological Model_ framework is a model-building domain specific language (DSL) for rapid prototyping and modification of infectious disease models.
- [paramix](https://github.com/CMMID/paramix) is a tool to properly scale parameters for compartmental modeling, a common approach to infectious disease dynamics. Read more [about the method here](https://doi.org/10.1371/journal.pcbi.1013420).
- [hashPRNG](https://github.com/epinowcast/hashprng) is drop-in replacement library for creating the properly matched model worlds which are necessary for high resolution scenario comparison.
- [op_system](https://github.com/ACCIDDA/op_system/) compiles structured model specifications into numerical right-hand sides, with reaction metadata, named observables and forcing schedules. The core is [published on PyPI](https://pypi.org/project/op-system/); see its [capabilities and examples](https://accidda.github.io/op_system/latest/guides/capabilities/).
- [op_engine](https://github.com/ACCIDDA/op_engine/) supplies deterministic and stochastic solvers, including independent NumPy SSA banks, observations and replay. The core is [published on PyPI](https://pypi.org/project/op-engine/); its [qualification matrix](https://accidda.github.io/op_engine/latest/guides/backend-qualification/) states the tested CPU methods and backends. Both cores can be used directly or through separate FlepiMoP2 provider packages.

## Specialized Inference Models

We also develop modeling packages focused on key epidemiological questions:

- [imuGAP](https://github.com/ACCIDDA/imuGAP/) can use a wide variety of vaccination data, resolving data missingness and mixed aggregation across time, space, and age to provide high resolution age-and-place estimates of vaccine coverage
- [hestia](https://github.com/ACCIDDA/hestia/) allows users to build custom disease and observation models to evaluate household study data and estimate key epidemiological parameters.
- [SeverityEstimate](https://github.com/ACCIDDA/SeverityEstimate) is an R package for estimating the severity of infections from line list data that include active and passive detection.
- [vaxflux](https://github.com/ACCIDDA/vaxflux/) is a python package for modeling seasonal vaccine uptake like influenza vaccines.

# Get in touch

Please contact project maintainers for specific questions and if you would like to contribute.

For more general inquiries, to be connected with an ACCIDDA member expert on a particular project, or to talk to us about sponsoring infectious disease modeling research and development reach out to [ACCIDDA.info@unc.edu](mailto:ACCIDDA.info@unc.edu)
