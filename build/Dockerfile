FROM novobidevops/odoo:16

USER root

RUN apt-get update && apt-get install -y \
        git \
        ipython

COPY requirements.txt /etc/
RUN pip3 install -r /etc/requirements.txt

# USER odoo
