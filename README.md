# RiddleDocumentation

The documentation project for the Hacktoberfest 2021 Event of Hacktoberfest Munich.

## Make changes

To make changes to the documentation edit the files under `docs/`.
After adding or change your points open a PR and request a Review from a member of the Hacktoberfest Munich team.
When merged the documentation will be automatically updated. 

You can view the documentation here:

https://hacktoberfestmunich.github.io/RiddleDocumentation/

## Generate docs locally

To generate the documentation locally checkout the repository first.
After that make sure you have installed `python3` and `python3-pip` installed on your system (Python3 on Mac and Windows).

Then open the folder of the project files with a terminal and create virtual python environment with

```shell
python3 -m venv .venv
```

and activate the environment in the current console with and install the initial python packages

```shell
source .venv/bin/activate
pip install -r requirements.txt
```

After that the documentation can be build with

```shell
tox -e ALL
```

The generated files are now available under `artifacts/doc/html` and can be opened with your favorite browser.
