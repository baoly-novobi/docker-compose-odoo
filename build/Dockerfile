FROM novobidevops/docker-base:odoo-18-v0.1.0
# Odoo 17: novobidevops/docker-base:odoo-17-v0.1.0
# Odoo 16: novobidevops/docker-base:odoo-16-v0.1.0
# ...

USER root

COPY requirements.txt /etc/
RUN pip3 install --break-system-packages -r /etc/requirements.txt
