# Tailwind CSS @apply Directive Issue with Dynamic Components

This repository demonstrates a bug where Tailwind's `@apply` directive doesn't correctly apply styles to components that are dynamically rendered or have their classes conditionally updated.  The problem is specific to Tailwind's JIT mode.

## Problem

The `@apply` directive within a dynamically rendered component may not update correctly if the component is not initially present in the DOM, leading to missing or inconsistent styles.

## Solution

The provided solution uses a combination of techniques to solve this. The best solution will depend on your framework and build process, so read comments carefully for context.