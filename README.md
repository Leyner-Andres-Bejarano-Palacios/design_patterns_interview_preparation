# design_patterns_interview_preparation
By now you already know what "interview preparation" repos are about, so enjoy.

## Theorical Questions Section

### Theorical Question 1

Do you know what the MVC model is ?

<details><summary><b>Answer</b></summary>

MVC consists of three kinds of objects. The Model is the application object, the View is
its screen presentation, and the Controller defines the way the user interface reacts to
user input. Before MVC, user interface designs tended to lump these objects together.
MVC decouples them to increase flexibility and reuse.

MVC decouples views and models by establishing a subscribe/notify protocol between
them. A view must ensure that its appearance reflects the state of the model. Whenever
the model's data changes, the model notifies views that depend on it. In response, each
view gets an opportunity to update itself. This approach lets you attach multiple views
to a model to provide different presentations. You can also create new views for a model
without rewriting it.

</details>

<details><summary><b>Source</b></summary>
Design Patterns: Elements of Reusable Object-Oriented Software - pag 4
</details>