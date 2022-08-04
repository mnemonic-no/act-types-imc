# ACT infrastructure model component (IMC) types

## Introduction

This repository contains files that can be used to bootstrap an instance of the [ACT platform](https://github.com/mnemonic-no/act-platform) with IMC object/fact type definitions.

## Installation
- You will need an installation of the [act-platform](https://github.com/mnemonic-no/act-platform).
- Install admin tools to manage type definitions:
```bash
pip install act-admin
```
- Add types (change baseurl and user that matches your installation)
```bash
act-types --object-types-file object-types-imc.json --fact-types-file fact-types-imc.json --meta-fact-types-file meta-fact-types-imc.json --act-baseurl http://localhost:8888 --user-id 1 --add
```

## About

The Adversary Emulation Planner is developed in the SOCCRATES innovation project (<https://soccrates.eu>). SOCCRATES has received funding from the European Union’s Horizon 2020 Research and Innovation program under Grant Agreement No. 833481.
