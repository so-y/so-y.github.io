---
title: "IntelliTC: Automating Type Changes in IntelliJ IDEA"
authors: '<i>Oleg Smirnov, Ameya Ketkar, Timofey Bryksin, Nikolaos Tsantalis, and Danny Dig</i>'
status: "accepted"
collection: publications
permalink: /publication/2022-05-08-intellitc
date: 2022-05-08
venue: "<b>ICSE'22</b>"
pdf: 'https://arxiv.org/abs/2112.03619'
tool: 'https://github.com/JetBrains-Research/data-driven-type-migration'
video: 'https://www.youtube.com/watch?v=pdcfvADA1PY'
abstract: "<p><b>Abstract</b>. Developers often change the types of program elements. Such a refactoring frequently involves updating not only the type of the element itself, but also the API of all type-dependent references in the code, thus it is tedious and time-consuming. Despite type changes being more frequent than renamings, just a few current IDE tools provide partially-automated support only for a small set of hard-coded types. Researchers have recently proposed a data-driven approach to inferring API rewrite rules for type change patterns in Java using code commits history. In this paper, we build upon these recent advances and introduce IntelliTC - a tool to perform Java type change refactoring. We implemented it as a plugin for IntelliJ IDEA, a popular Java IDE developed by JetBrains. We present 3 different ways of providing support for such a refactoring from the standpoint of the user experience: Classic mode, Suggested Refactoring, and Inspection mode. To evaluate these modalities of using IntelliTC, we surveyed 15 experienced software developers. They positively rated the usefulness of the tool.</p><p>The source code and distribution of the plugin are available on GitHub: <a href='https://github.com/JetBrains-Research/data-driven-type-migration'>https://github.com/JetBrains-Research/data-driven-type-migration</a>. A demonstration video is on YouTube: <a href='https://www.youtube.com/watch?v=pdcfvADA1PY'>https://www.youtube.com/watch?v=pdcfvADA1PY</a>.</p>"
---