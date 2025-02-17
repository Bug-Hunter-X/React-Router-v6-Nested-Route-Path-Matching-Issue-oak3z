# React Router v6 Nested Route Path Matching Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router v6.  The problem arises when a route with a more specific path (e.g., '/about') doesn't match as expected, and the root path ('/') is incorrectly matched instead.

## Problem

The provided `App.js` shows a simple setup with nested routes. However, even when navigating to '/about', the Home component renders.  This indicates an issue with path matching priority.

## Solution

The `AppSolution.js` file offers a corrected version of the code, showcasing the proper way to handle nested routes and ensure correct path matching.