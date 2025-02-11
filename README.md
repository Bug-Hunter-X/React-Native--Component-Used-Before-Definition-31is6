# React Native: Component Used Before Definition

This repository demonstrates an uncommon error in React Native where a component is used before it's fully defined. This often happens due to dynamic imports or circular dependencies, resulting in cryptic error messages.  The example showcases the issue and provides a solution.

## Problem

The `bug.js` file demonstrates the error.  When the app tries to render `ComponentB`, it hasn't been fully processed yet, leading to an error.

## Solution

The `bugSolution.js` file shows how to resolve this, using techniques to ensure component definitions are complete before use.