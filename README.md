# Python jupyter notebooks for using the Qumulo REST API

This reposity is a collection of python jupyter notebooks that help Qumulo users & customers explore and leverage the power of Qumulo's RESTful API.


### Setup

1. Install **python 2.7**. The Qumulo API bindings are not yet ported to python 3. Many people like the one-stop-shop offered by Anaconda: https://www.continuum.io/downloads
2. Install **pip**. There are a number of methods to do that. Many are described here: http://stackoverflow.com/questions/17271319/how-do-i-install-pip-on-macos-or-os-x
3. Optional, though recommended. Set up python virtual environments via `pip install virtualenv`
4. Install **jupyter notebook**. `pip install jupyter`
5. Install **Qumulo API python bindings** `pip install qumulo_api`


### Getting started.

For the quickest setup of credentials, that will be used by all notebooks, run the following commands with your own credentials:
```
export API_HOSTNAME={qumulo cluster name}
export API_USER={qumulo user name}
export API_PASSWORD={qumulo password}
```

Now you're ready to go. From the command line, inside of this locally downloaded repository:
```$ jupyter-notebook```

Navigate to one of the following jupyter notebooks in the `notebooks/` folder, or just click the links below if you're browsing on github:
- **[Quickstart guide for Qumulo python API.ipynb](notebooks/Quickstart%20guide%20for%20Qumulo%20python%20API.ipynb)** - This is the quickest way to get up and running with the python bindings and the Qumulo API.
- **[Exploring the Qumulo API python bindings.ipynb](notebooks/Exploring%20the%20Qumulo%20API%20python%20bindings.ipynb)** - A deeper dive into the modules of the Qumulo API, including filesystem, configuration, analytics and more.
- **[Raw REST examples for the Qumulo API with python.ipynb](notebooks/Raw%20REST%20examples%20for%20the%20Qumulo%20API%20with%20python.ipynb)** - How to use the python `requests` library to make raw HTTP REST requests against Qumulo.
