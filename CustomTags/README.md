# Custom tags

## Write a very simple tag to get a random number in the template. For this, you need to import randint
## Write template tag which generate different shapes like circle, triangle, rectangle
### For example:

```
{% generate_shape “rectangle” as rectangle %}
{{ rectangle }}

{% generate_shape “triangle” as triangle %}
{{ triangle }}

{% generate_shape “circle” as circle %}
{{ circle }}

```

![Result](https://i.ibb.co/M1rThDw/django-task-7.png)
