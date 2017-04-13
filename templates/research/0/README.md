# My Research Portal

### Summary:

A pre-packaged, pretend research portal based on PHP and MySQL for the Spin Hands-on Demo.

### Purpose:

Create your own research portal in just a few minutes!

This simple example demonstrates how NERSC might pre-package software for users to easily deploy against their own data.

It has these features:

* **Customizable "skin":** Specify a directory containing a style sheet to control look and feel. (In actual use, one might specify a directory with a custom config file, a directory containing a data set to act on, etc. The point is that it is externally configurable.)

* **Customizable, self-bootstrapping database:** Choose a research area, and a corresponding MySQL database is automatically loaded on startup. (In actual use, one might specify a data output file from a previous workflow stage to be parsed and loaded for further processing. The point is that a database can be created and populated with data on demand.)

### How it works:

Follow the instructor's directions to fill in the settings below.

The values you enter are applied to a template that describes how to create an instance of the My Research Portal service. Rancher fetches the Docker containers and starts them, passing in the values you supply to make your instance unique. That's it!

Later in the session, we will examine the YAML that the Rancher system uses to create the service. There, you'll see where the values from the form below were applied in the template.
