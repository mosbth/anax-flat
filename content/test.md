---
views:
    byline:
        region: after-main
        template: default/content
        sort: 1
        data:
            meta:
                type: content
                route: block/byline

    flashy:
        region: flash
        template: default/content
        sort: -1
        data:
            meta:
                type: content
                route: block/byline

    sidebar1:
        region: sidebar-left
        template: default/content
        sort: -1
        data:
            meta:
                type: content
                route: block/byline

    sidebar2:
        region: sidebar-right
        template: default/content
        sort: -1
        data:
            meta:
                type: content
                route: block/byline
...
Testsida
==============================================

Detta är min testsida.

![Jag själv](https://dbwebb.se/image/mikael-roos/me-happy.jpg?w=200)
