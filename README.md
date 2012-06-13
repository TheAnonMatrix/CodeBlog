# CodeBlog #

---

###### Yes, this is our jazz-zone :3 ######

---

### Motivation ###
This is simply a project for fun fun fun, collaborating on the web and getting experience using Django and python. This said, we of course hope to get this blog up and running successfully.

---

### Versions ###
Python 2.7

Django version: 1.4.0

If you're in doubt about what Django version you're running, you can do the following to check:

<code>
    python -c "import django; print django.get_version();"
</code>

The Django version is probably the most important one, since python is rather good at not breaking things, and doesn't need to introduce as much structural changes as Django might have to.

---

### Installation ###

Other than cloning (or forking then cloning) the project down, there are a couple of things that are needed.

To install this Django version 1.4.0, use pip and do

<code>
    pip install Django=1.4.0
</code>

After that, install [Zinnia's blog](http://django-blog-zinnia.com/documentation/getting-started/install/ "Zinnia's blog") app:

`pip install django-blog-zinnia`

You might also need to do `export LANG="en_US.UTF-8"`, this is a [problem/bug](https://code.djangoproject.com/ticket/16017 "Create superuser fails") in Django version 1.4.

---