<!-- omit in toc -->
# ICE-ATIS NLU Evaluation

<!-- Badges -->
![Python package](https://github.com/egillanton/ice-atis-nlu-evaluation/workflows/Python%20package/badge.svg)

<!-- omit in toc -->
## Table of Contents

<details>
<summary>Click to expand</summary>

- [1. Introduciton](#1-introduciton)
	- [1.1. Comparing NLU System Output and Golden Standard](#11-comparing-nlu-system-output-and-golden-standard)
		- [1.1.1. Tokens and Slot-Tags match](#111-tokens-and-slot-tags-match)
		- [1.1.2. System hypothesized a slot-tag](#112-system-hypothesized-a-slot-tag)
		- [1.1.3. System misses a slot-tag](#113-system-misses-a-slot-tag)
		- [1.1.4. System assigns the wrong slot-tag](#114-system-assigns-the-wrong-slot-tag)
		- [1.1.5. System gets the boundaries of the tokens wrong](#115-system-gets-the-boundaries-of-the-tokens-wrong)
		- [1.1.6. System gets the boundaries and slot-tag wrong](#116-system-gets-the-boundaries-and-slot-tag-wrong)
- [2. Setup](#2-setup)
	- [2.1. Create a virtual environment](#21-create-a-virtual-environment)
	- [2.2. Activate virtual environment](#22-activate-virtual-environment)
	- [2.3. Install dependecies](#23-install-dependecies)
	- [2.4. Set evironment variable](#24-set-evironment-variable)
- [3. Results](#3-results)
- [4. Contributors](#4-contributors)
</details>

## 1. Introduciton

### 1.1. Comparing NLU System Output and Golden Standard
When comparing the golden standard annotations with the output of a NLU system different scenarios might occur:

#### 1.1.1. Tokens and Slot-Tags match

<p align="center">
  <img src="https://user-images.githubusercontent.com/9976294/91733376-f834fd00-eb98-11ea-94cb-73e81cd10cef.png" />
</p>

#### 1.1.2. System hypothesized a slot-tag

#### 1.1.3. System misses a slot-tag

#### 1.1.4. System assigns the wrong slot-tag

#### 1.1.5. System gets the boundaries of the tokens wrong

#### 1.1.6. System gets the boundaries and slot-tag wrong

## 2. Setup

Make sure you have python version 3.6 or higher.

[Install python](https://www.python.org/downloads/)

### 2.1. Create a virtual environment

```console
$ python3 -m venv venv
```

### 2.2. Activate virtual environment

```console
$ . ./venv/Scripts/activate
```

### 2.3. Install dependecies

```console
(venv)$ pip install -r requirements.txt
```

### 2.4. Set evironment variable

```console
(venv)$ export PYTHONPATH=src
```

## 3. Results

## 4. Contributors
<a href="https://github.com/egillanton/ice-atis-nlu-evaluation/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=egillanton/ice-atis-nlu-evaluation" />
</a>
<!-- Made with [contributors-img](https://contributors-img.web.app). -->

[Become a contributor](CONTRIBUTING.md)

<p align="center">
🌟 PLEASE STAR THIS REPO IF YOU FOUND SOMETHING INTERESTING 🌟
</p>