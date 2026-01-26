# Registration

## Before Registration

### Prerequisites
Primarily, you must be comfortable with basic Python. Advanced knowledge is not
required, but at a minimum students should be comfortable with Python syntax
and familiar with the [NumPy](https://numpy.org/) library and the
[Pandas](https://pandas.pydata.org/) library. See the [preparation
page]({{base.siteurl}}/prep) for more information.

The course also uses a small amount of
[git](https://github.com/git-guides/install-git) and
[Docker](https://www.docker.com/get-started/) to coordinate the lessons, but
novices to these tools are welcome to register.


### Setup Instructions
You must bring a laptop to the course (not a tablet or chromebook), and you
must install a few pieces of software on it:
* **Docker**. Docker is a virtual machine tool that is used in the
  workshop. Installation instructions for all major operating systems can be
  found [here](https://www.docker.com/get-started/).
* **A Unix Shell/Terminal**. Window's command prompt/`CMD.EXE` will not
  suffice. See [these instructions](
  https://carpentries.github.io/workshop-template/install_instructions/#shell)
  for Windows, Mac, and Linux.
* **Git**. See [these instructions](
  https://carpentries.github.io/workshop-template/install_instructions/#git)
  for Windows, Mac, and Linux.

**You cannot complete the registration process without this software
installed.**


## How to Register

{% if site.registration and site.registration.link %}
   {% if site.registration.cost %}
   Registration fees are {{ site.registration.cost }}.
   {% endif %}
   <a href="{{ site.registration.link }}">You can register here.</a>
{% else %}
   Registration information will be posted soon. Please check back.
{% endif %}
