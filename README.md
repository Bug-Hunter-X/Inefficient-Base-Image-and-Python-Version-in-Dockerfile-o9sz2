# Inefficient Base Image and Python Version in Dockerfile

This repository demonstrates a common Dockerfile issue: using a large, generic base image (`ubuntu:latest`) and not specifying a Python version. This leads to larger image sizes and potential compatibility problems.

The `Dockerfile` shows the original problematic code. The `Dockerfile-solution` shows how to improve it.