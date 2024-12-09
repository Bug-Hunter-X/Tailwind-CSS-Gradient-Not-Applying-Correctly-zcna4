# Tailwind CSS Gradient Issue

This repository demonstrates a common issue encountered when using Tailwind CSS gradients. The gradient does not apply correctly and results in a single color instead of a smooth transition.

## Bug Description

The gradient utility classes `bg-gradient-to-r`, `from-blue-500`, and `to-purple-500` are used, but the output shows only one color (`blue-500` in this case).

## Solution

The issue may be caused by incorrect configuration or conflicting styles. The solution involves verifying Tailwind's configuration and ensuring no conflicting CSS rules override the gradient styles.