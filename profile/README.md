# Atlantic Coast Center for Infectious Disease Dynamics and Analytics (ACCIDDA)

ACCIDDA develops infectious disease models, combines public-health data, and trains researchers and public-health practitioners. Its work includes forecasting and analysis for smaller populations, particularly rural communities. As the Insight Net coordination center, ACCIDDA organizes network meetings, technical workshops, and modeling challenges.

# Project Highlights

## AI Tools

Our public work on machine learning for infectious disease forecasting includes:

- **Influpaint** ([GitHub](https://github.com/ACCIDDA/influpaint), [paper](https://arxiv.org/abs/2604.24913), [documentation](https://accidda.github.io/influpaint/)) uses diffusion models and [inpainting](https://en.wikipedia.org/wiki/Inpainting#Digital_inpainting) to generate forecast trajectories.
- [LEMMA-forecast](https://github.com/ACCIDDA/LEMMA-forecast) combines predictions from mechanistic models with machine-learning adjustments based on their errors.

## Dashboards

Public dashboards present surveillance data, forecasts, and vaccination estimates:

- **RespiLens** ([GitHub](https://github.com/ACCIDDA/RespiLens), [visit RespiLens](https://www.respilens.com/)) displays local respiratory disease data and forecasts, including CDC data. It also includes the [Forecastle](https://www.respilens.com/forecastle) forecasting exercise and an analysis [toolbox](https://www.respilens.com/toolbox).
- [Forecast-viz Creator](https://github.com/ACCIDDA/forecast-viz-creator) generates public forecast dashboards.
- The [NC Measles Vaccine Coverage](https://www.dph.ncdhhs.gov/programs/epidemiology/communicable-disease/infectious-respiratory-diseases/measles-rubeola/nc-measles-vaccination-data-dashboard) dashboard shows estimated vaccine protection across the state, derived from our [imuGAP](https://github.com/ACCIDDA/imuGAP) tool.

## Decision Support

We develop calculators and simulation pipelines for comparing interventions and running modeling studies:

- [tti](https://github.com/HopkinsIDD/tti/) provides a calculator to evaluate Test-Trace-Isolate interventions. [Learn how to use it here](https://www.coursera.org/learn/measuring-and-maximizing-impact-of-covid-19-contact-tracing).
- [FlepiMoP2](https://github.com/ACCIDDA/flepimop2/), the _Flexible Pipeline for Interchangeable Model Processing_, runs configuration-defined simulation and analysis campaigns. Its provider interfaces separate model specification, numerical integration, parameters, processing and persistence. See the [current documentation](https://accidda.github.io/flepimop2/latest/). The earlier [flepiMoP](https://github.com/HopkinsIDD/flepiMoP/) remains available for legacy workflows.

## Modeling tools

These public tools support model construction, parameter specification, simulation, and scenario comparisons:

- [tabularepimdl](https://github.com/UNCIDD/tabularepimdl), the _Tabular Epidemiological Model_ framework, provides a language for specifying and modifying infectious disease models.
- [paramix](https://github.com/CMMID/paramix) scales parameters for compartmental models. See the [method paper](https://doi.org/10.1371/journal.pcbi.1013420).
- [hashPRNG](https://github.com/epinowcast/hashprng) supports matched random-number streams for scenario comparisons.
- [op_system](https://github.com/ACCIDDA/op_system/) compiles PDE/field, nonlocal and reaction model specifications into shaped numerical evaluators and operator contracts, with reaction metadata, named observables and forcing schedules. The core is [published on PyPI](https://pypi.org/project/op-system/); see its [capabilities and examples](https://accidda.github.io/op_system/latest/guides/capabilities/).
- [op_engine](https://github.com/ACCIDDA/op_engine/) supplies PDE/nonlocal operator methods and deterministic/stochastic reaction solvers, including independent NumPy SSA banks, observations and replay. The core is [published on PyPI](https://pypi.org/project/op-engine/); its [qualification matrix](https://accidda.github.io/op_engine/latest/guides/backend-qualification/) states the tested CPU methods and backends. Both cores can be used directly or through separate FlepiMoP2 provider packages.

[op_infer](https://jcmacdonald.dev/projects/inference_calibration/) is in development. It connects Bayesian fitting through established inference libraries, simulation-based calibration and replicated study-design checks. It remains private, pre-alpha and unreleased while broader interfaces and application studies develop.

## Specialized Inference Models

We also develop modeling packages focused on key epidemiological questions:

- [imuGAP](https://github.com/ACCIDDA/imuGAP/) estimates vaccine coverage by age and place from vaccination data recorded at different levels of temporal, spatial, and age aggregation.
- [hestia](https://github.com/ACCIDDA/hestia/) allows users to build custom disease and observation models to evaluate household study data and estimate key epidemiological parameters.
- [SeverityEstimate](https://github.com/ACCIDDA/SeverityEstimate) is an R package for estimating the severity of infections from line list data that include active and passive detection.
- [vaxflux](https://github.com/ACCIDDA/vaxflux/) is a python package for modeling seasonal vaccine uptake like influenza vaccines.

# Get in touch

Please contact project maintainers for specific questions and if you would like to contribute.

For more general inquiries, to be connected with an ACCIDDA member expert on a particular project, or to talk to us about sponsoring infectious disease modeling research and development reach out to [ACCIDDA.info@unc.edu](mailto:ACCIDDA.info@unc.edu)
