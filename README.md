# DTS aggregator

An aggregator of known [DTS](https://w3id.org/dts/) APIs, implemented as a DTS API and running as a [Flask](https://flask.palletsprojects.com/) application.

**What does it mean?** This registry is itself a DTS collection of DTS APIs.

A demo version of the DTS aggregator is accessible at <https://dts-aggregator.herokuapp.com/>.

A list of known APIs is maintained in [`registry.json`](./registry.json).
Are you aware of a DTS API that is not listed there? Please add it to the registry file and open a Pull Request.

## Application

### Install

```bash
pip install -r requirements.txt
```

### Run

```bash
flask run
```
