---
title: JrDoc Category tag
---

The `@category` tag is used to group routes together. This is useful for organizing routes in the documentation.
It is also used for the middlewares to determine which routes to apply to.

!!! example

    ```jsdoc
    My Special Route!
    @category MyCategory
    ```
    In this example, the route is in the category `MyCategory`.

!!! warning

    The `@category` tag currently should only be placed ***once*** in the jrdoc. In the future,
    you will be able to assign a route to multiple categories.
