---
title: "diagrams and flowcharts"
date: 2020-05-25T21:59:10-07:00
draft: true
mermaid: true
Description: ""
Tags: []
Categories: []
Series: []
---

## Basic Pie Chart

{{<mermaid>}}
pie
    title Key elements in Product X
    "Calcium" : 42.96
    "Potassium" : 50.05
    "Magnesium" : 10.01
    "Iron" :  5
{{</mermaid>}}


## Basic flowchart

{{% mermaid %}}
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
{{% /mermaid %}}

## User Journey Diagram

{{% mermaid %}}
journey
title My working day
section Go to work
  Make tea: 5: Me
  Go upstairs: 3: Me
  Do work: 1: Me, Cat
section Go home
  Go downstairs: 5: Me
  Sit down: 5: Me
{{% /mermaid %}}
