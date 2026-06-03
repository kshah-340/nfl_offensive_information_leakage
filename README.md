# Offensive Information Leakage (OIL)

A framework for quantifying the tradeoff between play quality and play predictability in NFL offensive decision-making.

![OIL Demo](images/oil_demo.png)

OIL measures how much expected value an offense sacrifices when a theoretically optimal play becomes too predictable, helping identify situations where strategic unpredictability creates competitive advantage.

## Project Motivation

Traditional NFL analytics focuses on identifying the play with the highest expected value (often defined as EPA, or Expected Points Added) in a given situation.

However, offenses do not operate in a vacuum. Defenses form expectations based on game state, personnel, formations, and historical tendencies.

This creates a tradeoff:

- Highly effective plays become predictable.
- Predictable plays become easier to defend.
- Less optimal plays may regain value through a concealed "surprise factor".

The Offensive Information Leakage (OIL) framework attempts to quantify this tradeoff and identify when (and how often) offenses should deviate from the theoretically optimal play.
