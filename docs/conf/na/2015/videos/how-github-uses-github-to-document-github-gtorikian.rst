:template: 2017/video-details.html

How GitHub uses GitHub to document GitHub
=========================================

{% set talk = conferences[2015]['na']['speakers'][8] %}
{% set output %}
{% include conf_py_root + '/_templates/video-details-body.html' %}
{% endset %}
.. raw:: html

    {{ output|indent(4) }}
