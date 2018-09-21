---
title: 'Template Chapter 1'
description: 'This is a template chapter.'
---

## An exercise title written in sentence case

```yaml
type: NormalExercise
key: 43a704ed72
lang: r
xp: 100
skills: 1
```

This is the Context. It should help provide students with the background information needed.
The Instructions that follow should be in bullet point form with clear guidance for what is expected.

`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{r}
# Load datasets and packages here.
```

`@sample_code`
```{r}
# Your
# sample
# code
# should
# be
# ideally
# 10 lines or less,
# with a max
# of 16 lines.
```

`@solution`
```{r}
# Answer goes here
# Make sure to match the comments with your sample code
# to help students see the differences from solution
# to given.
```

`@sct`
```{r}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```

---

## Insert exercise title here

```yaml
type: MultipleChoiceExercise
key: ede91c9c3d
xp: 50
```

What's the color of the sky?

`@instructions`
yellow
green
blue
black

`@hint`
... you should know!

`@pre_exercise_code`
```{r}
print("toto")
```

`@sct`
```{r}
print("blue")
```
