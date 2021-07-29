---
title: "AntiCopyPaster"
collection: tools
permalink: /tool/anti-copy-paster
tag: 'A plugin for IntelliJ IDEA that tracks the pasting of code inside the IDE and suggests appropriate Extract Method refactorings to combat the propagation of duplicates.'
tool: 'https://github.com/JetBrains-Research/anti-copy-paster'
video: 'https://www.youtube.com/watch?v=pazQDNcNtBw'
abstract: '<p><b>AntiCopyPaster</b> is a plugin for IntelliJ IDEA that tracks the pasting of code inside the IDE and suggests appropriate Extract Method refactorings to combat the propagation of duplicates. To implement the plugin, we gathered a dataset of code fragments that should and should not be extracted, compiled a list of metrics of code that can influence the decision, and trained several popular classifying machine learning models, of which Random Forest showed the best results. When a developer pastes a code fragment, the plugin searches for duplicates in the currently opened file. If there are any, it waits for a short period of time to allow the developer to edit the code. If the code duplicates are still present after a delay, \toolname calculates the metrics for the fragment and inferences the decision: if the fragment should be extracted, the plugin suggests to refactor it.</p>'
---