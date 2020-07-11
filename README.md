# python_usecase
This is all about python use case e.g List, function

`code`

# Theory: Operations with list

You already know how to create lists, even empty ones, so, no wonder, that you might want to change your lists somehow. There are lots of things to do with a list, you can read about them in the documentation. In this topic, we will consider only basic ones.

Adding one element
A list is a dynamic collection and it means you can add and remove elements. To take a closer look, let's create an empty list of dragons.
```python
fruits = []  # we do not have dragons yet
```
What's next? The first thing that comes to mind is, of course, to add new elements to the list.

To add a new element to the end of an existing list, you need to invoke list.append(element) function. It takes only a single argument, so this way you can add only one element to the list at a time.
```scala
fruits.append('Mango')
fruits.append('Orange')
fruits.append('Coconut')
```
Now you have exactly three dragons, moreover, they are ordered the way you added them:
```
print(fruits)  # ['Mango', 'Orange', 'Coconut']
```
