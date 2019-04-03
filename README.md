# Week 8<br>OpenStreetMap and Urban Networks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/week-8/master?filepath=lecture-8.ipynb)

## Updating your local environment

There are a few new packages this week so we'll need
to update your Python environment. The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.

## Reference

- OSMnx
  - [GitHub](https://github.com/gboeing/osmnx)
  - [Introductory Blog Post](https://geoffboeing.com/2016/11/osmnx-python-street-networks/)
  - [Jupyter Notebook Examples](https://github.com/gboeing/osmnx-examples/tree/master/notebooks)
  - [Documentation](https://osmnx.readthedocs.io)
- Pandana
  - [GitHub](https://github.com/UDST/pandana)
  - [Jupyter Notebook Examples](https://github.com/UDST/pandana/tree/master/examples)
  - [Documentation](http://udst.github.io/pandana/)
- OpenStreeMap
  - [OSM Wikipedia](https://wiki.openstreetmap.org/wiki)
  - [List of OSM amenities](https://wiki.openstreetmap.org/wiki/Key:amenity)
- [Bounding box tool](http://boundingbox.klokantech.com/)
