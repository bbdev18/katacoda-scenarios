Bismillah A Katacoda scenario is a series of Markdown files, bash scripts and a JSON file to define how your scenario should be configured, the text for the scenario and any automation required.

## Task 1
Check what version of terminal and OS:
`cat /etc/os-release`{{executre}}

Or

`lsb_release -a`{{executre}}

Or

`hostnamectl`{{execute}}

## Task 2
Check what files are currently in the directory

## Task 3

## Task 4

## Task 5

Clone our example repository that contains the set of documentation with the following command:

`git clone https://github.com/katacoda/scenario-examples.git katacoda-scenario-examples`{{execute}}

Within the repository, you will see a set of examples of implementing various Katacoda functionality.

The scenario you are currently reading is in the directory `ls -lha katacoda-scenario-examples/create-scenario-101`{{execute}}. The directory name is what defines the URL.

An example of the current step is `katacoda-scenario-examples/create-scenario-101/step1.md`{{open}}

All the steps are collected via a JSON file, for example, `katacoda-scenario-examples/create-scenario-101/index.json`{{open}}.

The JSON file defines the scenario title, the description, steps order, the UI layout and environment. You can find more about the layouts within our scenarios at [katacoda.com/docs/scenarios/layouts](https://katacoda.com/docs/scenarios/layouts) and environments at [katacoda.com/docs/scenarios/environments](https://katacoda.com/docs/scenarios/environments).
