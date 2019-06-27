# Jshift

Jshift is a collection of plugins and libraries that are used for generating and deploying Kubernetes/Openshift manifests at compile
time. It brings your Java applications on to Kubernetes and OpenShift. It provides a tight integration into Maven and benefits from 
the build configuration already provided. This project focus on two tasks: Building Docker images and creating Kubernetes and 
OpenShift resource descriptors.

## Features
 - **Jshift-kit**
   - **Generator** framework for automatically generating Docker images by examining project information.
   - **Enricher** framework for creating and enhancing Kubernetes/Openshift resource descriptors.
   - **Profile** combining configuration for generators and enrichers.
   - **Resource Configuration** model objects for a simplified configuration of Kubernetes/Openshift resource.
   - **Image Configuration** model objects for modeling Docker image configuration.

 - **Kubernetes Maven Plugin**
   - Generates docker images with flexible and powerful configuration.
   - Supports generating Kubernetes descriptors
   - Provides **Zero Configuration** for a quick ramp-up where opinionated defaults will be pre-selected.
   - Provides **Inline Configuration** within the plugin configuration in an XML syntax.
   - Provides **External Configuration** templates of real deployment descriptors which are enriched by plugin.
 
 - **Openshift Maven Plugin**
   - Dealing with S2I images and hence inherits its flexible and powerful configuration
   - Supports generating Openshift descriptors
   - Provides **Zero Configuration** for a quick ramp-up where opinionated defaults will be pre-selected.
   - Provides **Inline Configuration** within the plugin configuration in an XML syntax.
   - Provides **External Configuration** templates of real deployment descriptors which are enriched by plugin.
 
 - **Odo Java**
   - Includes java library for using using [odo](https://github.com/redhat-developer/odo)
   - Includes **Odo Maven Plugin** which allows seamless integration of odo cli with Maven.

## Getting Started
 - Check out our asciicasts for:
   - [Kubernetes Maven Plugin](https://asciinema.org/a/253747)
      ![Sample Demo](https://raw.githubusercontent.com/jshiftio/kubernetes-maven-plugin/master/k8s-maven-plugin-demo.gif)
   - [Openshift Maven Plugin](https://asciinema.org/a/253742)
      ![Sample Demo](https://raw.githubusercontent.com/jshiftio/openshift-maven-plugin/master/oc-maven-plugin-demo.gif)

 - Visit our [quickstarts samples](https://github.com/jshiftio/jshift-quickstarts) on github.

## Getting Involved
  - Follow us on [Twitter](https://twitter.com/jshiftio)
  - Contribute via bug fixes or issues on [Github](https://github.com/jshiftio)
  - Our mailing list: jshift@googlegroups.com
  - Reach out to us on IRC at #jshiftio on freenode.

