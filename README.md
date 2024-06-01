# MachineLearningToolkit

This is the basics of Umbrella Projects in Elixir You typically create an Umbrella project by creating a normal project but passing the --umbrella flag

for example ............

```
   mix new machine_learning_toolkit --umbrella
```

Inside your project, you will find an apps/ directory where you can create and host many apps:

```
    cd machine_learning_toolkit
    cd apps
    mix new my_app
```

Commands like "mix compile" and "mix test" when executed in the umbrella project root will automatically run for each application in the apps/ directory.
