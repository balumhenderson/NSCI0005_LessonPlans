# Announcements
## Week 1 - 28/10/2022
Welcome to your NSCI0005 tutorials!

The [Moodle Page](https://moodle.ucl.ac.uk/course/view.php?id=26023) for this course holds all of the information you should need, including questions sheets, deadline information, contact details and submission links.

A Teams group has been set up for these tutorials, and you should all have been added to that. Please feel free to ask me or each other any questions about the course content, and if you need any help with something I will do my best to reply there, or you can [email me](mailto:calum.henderson.19@ucl.ac.uk).

For submitting your weekly marked questions, as well as your assessments and final exam, you need to use the [Office Lens App](https://wiki.ucl.ac.uk/display/ELearningStudentSupport/Office+Lens). When laying out your submissions, please make it legible by making everything large enough and spacing out your answers. It really does help when your solutions are clearer.

## Week 3 - 18/11/2022
This isn't your first introduction to calculus, but it is always useful to revise the basics!

### Derivative rules
```{figure} Images/derivativeRules.png
---
width: 16cm
---
```

### Integration rules
```{figure} Images/integralRules.png
---
width: 16cm
---
```

### Integration by parts
One of the nice ways to think about integration by parts is as the 'opposite' to the product rule.

```{math}
\frac{\mathrm{d}}{\mathrm{d}x}\left[\mathrm{f}(x) \cdot \mathrm{g}(x)\right] = \mathrm{f}'(x) \cdot \mathrm{g}(x) + \mathrm{f}(x) \cdot \mathrm{g}'(x)
```

Rearrange this to get

```{math}
\mathrm{f}(x) \cdot \mathrm{g}'(x) = \frac{\mathrm{d}}{\mathrm{d}x}\left[\mathrm{f}(x) \cdot \mathrm{g}(x)\right] - \mathrm{g}(x) \cdot \mathrm{f}'(x)
```

Now integrate both sides of the equation:

```{math}
\int \big( \mathrm{f}(x) \cdot \mathrm{g}'(x)\big) \mathrm{d}x = \int \big( \frac{\mathrm{d}}{\mathrm{d}x}\left[\mathrm{f}(x) \cdot \mathrm{g}(x)\right] - \mathrm{g}(x) \cdot \mathrm{f}'(x) \big) \mathrm{d}x
```

Split the right hand side into 2 using the sum rule:

```{math}
\int \big( \mathrm{f}(x) \cdot \mathrm{g}'(x)\big) \mathrm{d}x = \int \big( \frac{\mathrm{d}}{\mathrm{d}x}\left[\mathrm{f}(x) \cdot \mathrm{g}(x)\right] \big) \mathrm{d}x - \int \big( \mathrm{g}(x) \cdot \mathrm{f}'(x) \big) \mathrm{d}x
```

The first integral on the right undoes the differentiation:

```{math}
\int \big( \mathrm{f}(x) \cdot \mathrm{g}'(x)\big) \mathrm{d}x = \left[\mathrm{f}(x) \cdot \mathrm{g}(x)\right] - \int \big( \mathrm{g}(x) \cdot \mathrm{f}'(x) \big) \mathrm{d}x
```
And here we are left with integration by parts, in a form we can recognise! Simplifying slightly by letting $u=\mathrm{f}(x)$ and $v=\mathrm{g}(x)$ we obtain the very familiar:

```{math}
\int u \mathrm{d}v = u v - \int v \mathrm{d}u