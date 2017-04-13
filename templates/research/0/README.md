# My Research Portal

### Summary:

A pretend pre-packaged research portal based on PHP and MySQL for the Spin Hands-on Demo.

### Purpose:

Create your own research portal in just a few minutes!

This simplified example demonstrates how NERSC might pre-package software for users to easily deploy against their own data.

It has these features:

* **Customizable "skin":** Specify a directory containing a style sheet to control look and feel. (In actual use, one might supply a directory with a custom config file, or even a directory containing an entire data set for software to act on. The point is that it is externally configurable.)

* **Customizable, self-bootstrapping database:** Choose a research area, and a corresponding MySQL database is automatically loaded on startup. (In actual use, one might specify a data output file from a previous workflow stage to be parsed and loaded for further processing. The point is that a database can be created and populated on demand.)

### How it works:

Follow the instructor's directions to fill in the settings below.

Your entries are incorporated into a YAML template created by ISG for the My Research Portal service. The resulting YAML is passed to the Rancher API, which creates a complete running portal. That's it!

Later in the session, we will examine the YAML that the Rancher system uses to create the service.
