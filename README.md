# Hubot Darts

Have an office dart fight even when working from home!

[![Build Status](https://travis-ci.org/bsensale/hubot-darts.png)](https://travis-ci.org/bsensale/hubot-darts) [![NPM version](https://badge.fury.io/js/hubot-darts.png)](http://badge.fury.io/js/hubot-darts)

## Usage:

hubot shoot target (in the head/body/legs) - Fire's a foam dart at the target.
Optionally tries to hit a particular target.

### Sample Interaction:

    user1> hubot shoot user2
    hubot> user1: Target acquired
    hubot> * hubot fires a foam dart at users2's body.  The shot bounces off users2's shoulder.
    user1> hubot: shoot user2 in the legs
    hubot> user1: Target acquired.
    hubot> * hubot fires a foam dart at users2's legs.  The dart hits right on users2's shin, knocking them to the ground

## Installation

Add the package `hubot-darts` entry to the `external-scripts.json` file
(you may need to create this file).

    "dependencies": {
      "hubot-darts": "1.0.x"
    }

Run the following command to make sure the module is installed.

    #npm install hubot-darts

To enable the script, add the `hubot-darts` entry to the `packages.json`
file (you may need to create this file).

    ["hubots-darts"]
