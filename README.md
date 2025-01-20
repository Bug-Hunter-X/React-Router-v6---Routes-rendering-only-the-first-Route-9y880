# React Router v6 Routing Issue

This repository demonstrates a common issue encountered when using React Router v6: only the first `Route` within the `Routes` component renders, regardless of the URL path.  The provided solution demonstrates how to resolve this issue.

## Problem

The original `App.js` uses the new `Routes` and `Route` components of React Router v6. However, only the Home component is rendered, even when navigating to '/about' or '/contact'.

## Solution

The `AppSolution.js` file provides a corrected implementation.  The solution is to ensure correct usage of the `Routes` component with its child `Route` components, making sure the paths are correctly defined and that there are no conflicting route definitions.