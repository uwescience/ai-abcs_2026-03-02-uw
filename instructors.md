# Workshop Organizers

## Instructors

{% for who in site.instructors %}
  <table style="width:100%">
    <tr>
      <td class="speaker-image-left">
        {% if who.photo %}
           <img src="{{ who.photo }}" width="175"/>
        {% elsif who.github %}
           <img src="https://github.com/{{ who.github }}.png" width="175"/>
        {% endif %}</td>
      <td class="speaker-bio">
        <p class="hbio">
           {% if who.url %} <a href="{{ who.url }}">{{ who.name }}</a>
           {% else %} {{who.name}}
           {% endif %} </p>
        {% if who.div %}<p class="hbio">{{ who.div }}</p>{% endif %}
        {% if who.org %}<p class="hbio">{{ who.org }}</p>{% endif %}
        <p> {% if who.github %}
               <a href="https://github.com/{{ who.github }}">
               <i class="svg-icon github"></i></a>
            {% endif %}
            {% if who.email %}
               <a href="mailto:{{ who.email }}">
               <i class="svg-icon email"></i></a>
            {% endif %} </p>
        </td></tr></table>
{% endfor %}


{% if site.helpers %}

## Helpers

Helpers assist the instructor by answering questions and debugging
technological issues that arise during the course.

{% for who in site.helpers %}
  <table style="width:100%">
    <tr>
      <td class="speaker-image-left">
        {% if who.photo %}
           <img src="{{ who.photo }}" width="175"/>
        {% elsif who.github %}
           <img src="https://github.com/{{ who.github }}.png" width="175"/>
        {% endif %}</td>
      <td class="speaker-bio">
        <p class="hbio">
           {% if who.url %} <a href="{{ who.url }}">{{ who.name }}</a>
           {% else %} {{who.name}}
           {% endif %} </p>
        {% if who.div %}<p class="hbio">{{ who.div }}</p>{% endif %}
        {% if who.org %}<p class="hbio">{{ who.org }}</p>{% endif %}
        <p> {% if who.github %}
               <a href="https://github.com/{{ who.github }}">
               <i class="svg-icon github"></i></a>
            {% endif %}
            {% if who.email %}
               <a href="mailto:{{ who.email }}">
               <i class="svg-icon email"></i></a>
            {% endif %} </p>
        </td></tr></table>
{% endfor %}
{% endif %}


{% if site.helpers %}

## Administrators

{% for who in site.admin %}
  <table style="width:100%">
    <tr>
      <td class="speaker-image-left">
        {% if who.photo %}
           <img src="{{ who.photo }}" width="175"/>
        {% elsif who.github %}
           <img src="https://github.com/{{ who.github }}.png" width="175"/>
        {% endif %}</td>
      <td class="speaker-bio">
        <p class="hbio">
           {% if who.url %} <a href="{{ who.url }}">{{ who.name }}</a>
           {% else %} {{who.name}}
           {% endif %} </p>
        {% if who.div %}<p class="hbio">{{ who.div }}</p>{% endif %}
        {% if who.org %}<p class="hbio">{{ who.org }}</p>{% endif %}
        <p> {% if who.github %}
               <a href="https://github.com/{{ who.github }}">
               <i class="svg-icon github"></i></a>
            {% endif %}
            {% if who.email %}
               <a href="mailto:{{ who.email }}">
               <i class="svg-icon email"></i></a>
            {% endif %} </p>
        </td></tr></table>
{% endfor %}
{% endif %}
