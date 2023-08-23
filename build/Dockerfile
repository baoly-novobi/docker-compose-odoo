FROM novobidevops/odoo:16

USER root

RUN apt-get update && apt-get install -y \
        git \
        ipython

COPY python3-requirements.txt /etc/
RUN pip3 install -r /etc/python3-requirements.txt

# USER odoo
