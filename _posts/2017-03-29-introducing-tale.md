---
layout: post
title: Help Build NODE-ECON
author: Kyle
published: true
---

## Origins
Around 2000 or 2001, I started working with [Max/MSP](https://cycling74.com/) and [Pure Data](https://puredata.info/) for sound synthesis. As a technically-minded creator of music, the interface and underlying concepts were intuitive and allowed for rapid development of sound-making objects that worked without the need for writing tons of code. At the same time, these objects were highly customizable themselves, so if I ever needed to get under the hood and alter more fundamental aspects of the tools, those options were available to me.

Around the same time, I started my formal studies in economics while working as a market analyst. Spending so much time on collecting, cleaning up, and managing data led me to think about better ways to do all of this on a shoestring budget, and without having to double major in computer science. The knowledge management systems our company was considering were six-figure propositions at the time, and we simply didn't have the resources for sustained in-house software development, so we kept using what we had, which was Excel and, eventually, a SQL back end.

## The graphical object and flow model
I started toying around with a Max/MSP-like interface for the work I was doing, with modules for cleaning up and extracting data, running different kinds of statistical analysis, and feeding data to templates that were built for specific purposes, such as PDF/print output, merging into other document types, and data feeds that could be repurposed at the client end.

I learned a little R and a little Matlab and a modest amount of Python, but the data management aspects of all those tools never really stuck with me. I'm an out-of-sight, out-of-mind kind of person; all of that command line stuff has its place, but I've never enjoyed it as a way of actually working with my data.

Whatever the case, without any realistic way of making any change happen, this idea remained in limbo for much of the past decade.

## Then I saw NODE-RED
If you've read this far, I presume you know about NODE-RED. If you don't, you can find what you need [here](https://flows.nodered.org/).

That's it. That's the interface I was looking for. Some of the most common NODE-RED use cases are for IoT applications, but I think there's a ton of potential for adapting the concepts and the toolsets for use in the kind of flow-based modeling for economic analysis. 

The goal is to create modules that work together. This requires some thinking about how data go into and out of individual modules, and quality control, and a whole lot of other considerations. Think about it for a moment. Can you imagine a tool that you can build that handles things like:

-Data ingestion from disparate sources: APIs, web scraping, CSVs, legacy systems, emails, hand-scrawled notes
-Unit conversions and other transformations
-More complex activities, like agent-based models, market simulations, bio-geo-economic models
-Summing and weighting of models

Yes, I know all this stuff already exists. But I don't think it exists in this form, in a way usable to the people who actually consume and make decisions based on the data. The people who don't have an extra ten hours a day to learn the finer points but who are perfectly capable of generating sophisticated and useful models with the right set of tools.


## Use it. Modify it. Contribute to it.
NODE-ECON is intended for all to use, all here in our [GitHub repository](https://github.com/node-econ). 

What we could really use is your help in building this idea into a living, breathing system, for use by practitioners in all of the possible econ variants, from applied to theoretical, from micro to macro, from environmental and natural resources to information technology.

Contact me at [kyle@integrativeecon.com](kyle@integrativeecon.com) if you'd like to get involved!
