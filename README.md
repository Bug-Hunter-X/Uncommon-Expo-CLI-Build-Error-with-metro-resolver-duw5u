# Uncommon Expo CLI Build Error with metro-resolver

This repository demonstrates an uncommon build error encountered when using the Expo CLI. The error originates from the `metro-resolver` package and is characterized by vague and inconsistent error messages, making debugging difficult.

## Problem

The build process halts with an error related to `metro-resolver`.  The exact error message varies on each attempt, making it difficult to identify the root cause. Standard troubleshooting steps (cache clearing, reinstalling dependencies) do not resolve the issue.

## Solution

The solution involves a specific combination of dependency versioning and configuration updates that addresses underlying conflicts and ensures compatibility.

## Reproduction

The `bug.js` file showcases a sample Expo project (though the error isn't necessarily tied to specific project code).  Running `expo start` and then attempting a build will potentially trigger the error.

## Steps to Reproduce the Bug

1. Clone this repository.
2. Run `npm install`.
3. Run `expo start`.
4. Attempt to build the project (e.g., `expo build:ios`).

## How to Fix the Bug (Solution)

Detailed steps are provided in the `bugSolution.js` along with the corrected dependencies. Follow the steps in `bugSolution.js` to fix the build error.  Key steps may involve updating Expo CLI version and related packages, as well as carefully checking package.json for any conflicts.