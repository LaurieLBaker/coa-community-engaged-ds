---
date: "2022-09-07 T00:00:00Z"
external_link: ""
image:
  caption: 
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: 
slides: 
summary: 
tags:
- Energy Efficiency Monitoring
- Environmental Science
title: Developing a Comprehensive Monitoring Program for Community-wide Energy Efficiency Upgrades
publishDate: "2022-04-25T00:00:00Z"
url_code: ""
url_slides: ""
url_video: ""
editor_options: 
  markdown: 
    wrap: 72
---

## Project Background

Project is working with Maine Community-wide Comprehensive Energy
Upgrades Program. Helping them to develop their website and quarto
reproducible report as energy audits.

More about Maine Community-wide Comprehensive Energy Upgrades Program:
MCWCEU is Government-funded program committed to providing free
high-quality energy audits and catalyze low-cost energy improvements to
Maine homeowners. Implemented by the COA’s Community Energy Center
directed by David Gibson. As a pilot program, CEC is starting their
services with the Great Cranberry Island community this summer 2024. The
Participating Home owners. Will be provided with a free comprehensive
energy audit, giving them an objective look at their home’s energy
systems. Then, they will be provided several options for improving their
home’s efficiency, and CEC will negotiate with contractors on homeowners
behalf to integrate the solutions they choose. Throughout this process,
CEC will consider all available options and ensure participants gain the
most benefit for the lowest cost available, both through government
rebates and community-wide benefits.

## Project Outputs

### Website

This website serves as the project hub for information surrounding the
government grant, the community energy center, what the project is
trying to accomplish, how it will accomplish it and what that
accomplishment looks like. This website is for potential and current
participants to get updated, accurate information regaring home energy
audits, government rebates and other related information.

<iframe src="https://coa-energy-upgrade-project.netlify.app" width="100%" height="500" title="COA Energy Project Website">

</iframe>

### Quarto Reproducible Reports

We created the Quarto Reproducible Reports template. It will be used for
Energy Audits for the Maine Community Wide Comprehensive Energy Upgrades
program. The work flow for the creation of the audits is:

1.  Collect the data (happens during an audit)

2.  Report the data to google form (happens during/after the audit)

3.  Render the reports (happens after data reporting)

After render the homeowners would have access to comprehensive summer
about their property. For the data collection, reporting and rendering
the Building Performance Institute (BPI) Standards are followed closely.
As the energy auditors are BPI certified. Audits look into insulation,
energy bills, heating sources, windows, excessive moisture, air
barriers, domestic water heating etc. Here is just a glimpse of what the
summary of the energy audit looks like.

<figure>

<img src="/img/energy_audit_summery.png" alt="Example of energy audit&apos;s summery"/>

<figcaption>Example of energy audit's summery.</figcaption>

</figure>

### Arduino Air Quality Dashboard

Some of the homes participating in the project will have wifi enabled
Arduino air quality monitors installed in them, so one of the goals of
this project was to develop a way to analyze the data from the monitors
to assess the impacts of energy upgrades. The monitors output a readout
every 20 minutes that includes temperature, relative humidity, PM10 and
PM2.5 concentrations, nitrogen oxide index, and volatile organic
compound index.

<figure>

<img src="/img/monitor_schema.png" alt="Simple diagram of Arduino monitor"/>

<figcaption>Schematic of Arduino monitor.</figcaption>

</figure>

Using a third party R package called rduinoiot, developed by Flavio
Leccese, we were able to link the Arduino API to R in order to pull the
data into a dataframe. Using this, we will develop an RShiny web app
dashboard to easily navigate and summarize the data. In the future, we
would like to implement a database in order to analyze the data over
longer timescales and improve app response speed, and potentially
implement the ability for the owners of homes with monitors installed to
log in and view the data from their, and only their, monitor.

<figure>

<img src="/img/arduino_graph_ex.png" alt="Example Arduino monitor graph"/>

<figcaption>Figure 3. Example Arduino ouput graph with lines
representing safe pollutant levels, currently at placeholder
values.</figcaption>

</figure>

## Team

Mabon Young - COA '26 - Website and Arduino

Adler Garner - COA '26 - Website and Case Studies

Rudolfs Lukasevics - COA '25 - Website and Quarto Reproducible Report

## Data

Access the project on
[github](https://github.com/LaurieLBaker/CEDS-Energy).

## Resources

-   [Reproducible Reporting with
    Quarto](https://jadeyryan.quarto.pub/ceds-quarto-workshop/) by Jadey
    Ryan

-   [Official quarto website](https://quarto.org/)

Thanks to: David Gibson and Nicole Grohoski the director of energy and
energy project manager at COA; Laurie Baker, CEDS Instructor; Nicolo
Mega, Arduino monitor designer and producer; Flavio Leccese, rduinoiot
developer
