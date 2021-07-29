---
title: "Using Large-Scale Anomaly Detection on Code to Improve Kotlin Compiler"
authors: '<i>Timofey Bryksin, Victor Petukhov, Ilya Alexin, Stanislav Prikhodko, Alexey Shpilman, Vladimir Kovalenko, and Nikita Povarov</i>'
collection: publications
permalink: /publication/2020-06-29-kotlin-anomalies
date: 2020-06-29
venue: "proceedings of <b>MSR'20</b>"
paperurl: 'https://doi.org/10.1145/3379597.3387447'
pdf: 'https://arxiv.org/pdf/2004.01618.pdf'
video: 'https://www.youtube.com/watch?v=6oAIzisevhA'
data: 'https://zenodo.org/record/3733794'
abstract: "<p><b>Abstract</b>. In this work, we apply anomaly detection to source code and bytecode to facilitate the development of a programming language and its compiler. We define anomaly as a code fragment that is different from typical code written in a particular programming language. Identifying such code fragments is beneficial to both language developers and end users, since anomalies may indicate potential issues with the compiler or with runtime performance. Moreover, anomalies could correspond to problems in language design. For this study, we choose Kotlin as the target programming language. We outline and discuss approaches to obtaining vector representations of source code and bytecode and to the detection of anomalies across vectorized code snippets. The paper presents a method that aims to detect two types of anomalies: syntax tree anomalies and so-called compiler-induced anomalies that arise only in the compiled bytecode. We describe several experiments that employ different combinations of vectorization and anomaly detection techniques and discuss types of detected anomalies and their usefulness for language developers. We demonstrate that the extracted anomalies and the underlying extraction technique provide additional value for language development.</p>"
---