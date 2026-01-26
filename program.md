# Workshop Program

The workshop will take place {{site.timestring}} each day from
{{site.firstdate}} through {{site.lastdate}}.

{% if site.attendance == 'in-person' %}
{% if site.location %}
The workshop will be held **in-person** at
{% if site.loclink %}[{{ site.location }}]({{ site.loclink }}){% else %}{{ site.location }}{% endif %}.
{% else %}
The workshop will be held **in-person**. Participants will be sent
the workshop address upon registration.
{% endif %}
{% elsif site.attendance == 'online' %}
The workshop will be held **online** over Zoom. Participants will be
sent a workshop Zoom link upon registration.
{% elsif site.attendance == 'hybrid' %}
The workshop will be held both **online** and **in-person**; you must
register for one or the other.
{% if site.location %}
The in-person site of the workshop will be held at
{% if site.loclink %}[{{ site.location }}]({{ site.loclink }}){% else %}{{ site.location }}{% endif %}.
{% else %}
In-person participants will be sent the workshop address upon
registration.
{% endif %}
Online attendees will be sent a Zoom link upon registration.
{% endif %}

Each day of the workshop will focus on a different topics. These topics are
additionally laid out in the [Lesson
Site]({{ site.bookurl }}). They are as follows:
* **Day 1**. Unsupervised learning: tools for organizing and simplifying data
  that don't require one to have a specific goal or any examples of "correct"
  organization/simplification.
* **Day 2**. Supervised learning: tools that can model data but that require
  one to have some examples of what a "correct" model would predict.
* **Day 3**. Nonlinear models and optimization: tools for constructing one's
  own models and how to fit them to a datasets.
* **Day 4**. Neural networks and deep learning: tools that use simple linear
  systems to model a wide variety of data, including convolutional neural
  networks (CNNs).


