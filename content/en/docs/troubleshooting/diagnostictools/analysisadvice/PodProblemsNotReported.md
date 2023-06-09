---
title: Problem Pods
linkTitle: Problem Pods
description: Analysis detected pods with potential issues
weight: 5
draft: false
---

### Summary
Analysis detected that there were pods which were not in a running, succeeded, or pending state.

The analysis was not able to determine a specific root cause, however, it might have supplied data that is related to the pods in question.
The root cause might be obvious from the supporting data, but the analysis tool isn't isolating the specific scenario yet.

### Steps
Review the analysis data. At a minimum, it should indicate which pods are being impacted and it might give other clues on the root cause.

### Related information
* [Kubernetes Troubleshooting](https://kubernetes.io/docs/tasks/debug/)
