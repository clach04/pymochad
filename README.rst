# pymochad

A python library for sending commands to the mochad TCP gateway daemon for
the X10 CMA15A controller:

https://sourceforge.net/projects/mochad/

Complete documentation is here: http://pymochad.readthedocs.io/en/latest/


## Getting Started

To get started:

    pip install -r requirements.txt

## Usage

Using PyMochad is pretty straightforward you just need to init a PyMochad object
and then issue commands to it. For example::

    from pymochad import controller

    mochad = controller.PyMochad()
    print(mochad.status())

will connect to a running mochad instance (running on your localhost) and print the device status.

For a complete API documentation see: :ref:`pymochad_api`.
