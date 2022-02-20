# Dockerized Trading Research Droplet

The contents herein provide everything needed to deploy a Docker image on a DigitalOcean droplet designed for backtesting trading strategies in Jupyter Lab.  

Whether it's installing a new package, testing a new strategy, switching workstations, or reproducing work in a book on algorithmic trading the success and ease of the effort often depend on the programming environment being configured just right. This container and remote deployment was built to make it fast and easy to get up running testing trading strategies without the need to be a DevOps expert.

<br>

## Technologies

This project leverages the following programs and platforms:  

* [DigitalOcean](https://www.digitalocean.com/)
* [Docker](https://docs.docker.com/)
* [Jupyter Lab](https://jupyter.org/)
* [Miniconda](https://docs.conda.io/en/latest/miniconda.html)  

The Docker image includes the basic suite of packages necessary to get started analyzing financial data and backtesting trading strategies:  

_For importing data_  

* [Alpaca](https://alpaca.markets/)
* [Quandl](https://data.nasdaq.com/) (Now known as Nasdaq Data Link)  

_For working with data_  

* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)  

_For visualizing data_  

* [Bokeh](https://bokeh.org/)
* [Holoviews](https://holoviews.org/)
* [Matplotlib](https://matplotlib.org/)
* [Plotly](https://plotly.com/)
* [Seaborn](https://seaborn.pydata.org/)  

_For modeling_  

* [Prophet](https://facebook.github.io/prophet/)
* [Scikit-learn](https://scikit-learn.org/stable/)  

This list is not exhaustive of the packages included in the image, and new packages will be added to `environment_conda.yml` periodically.

<br>

## Set Up

The Dockerized Jupyter Lab environment can be run locally or remotely. This section provides instructions for both options. The remote option uses a DigitalOcean Droplet. With minimal modifications to the shell scripts the set up of the environment can be automated on other cloud platforms like AWS, Azure, Google Cloud, etc.  

__Local__  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.  

__Remote__  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.  

<br>

## Usage

__Local__  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.  

__Remote__  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<br>

## Contributors
Josh Mischung: [josh@knoasis.io](josh@knoasis.io), [LinkedIn](https://www.linkedin.com/in/joshmischung/)

<br>

## License

MIT License

Copyright (c) [2022] [Joshua Mischung]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
