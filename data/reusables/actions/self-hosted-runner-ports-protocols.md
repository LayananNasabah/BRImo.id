{% ifversion ghes %}
The connection between self-hosted runners and {% data variables.product.product_name %} is over {% ifversion ghes %}HTTP (port 80) or {% endif %}HTTPS (port 443). {% ifversion ghes %}To ensure connectivity over HTTPS, configure TLS for {% data variables.location.product_location %}. For more information, see "[AUTOTITLE](/admin/configuration/configuring-network-settings/configuring-tls)."{% endif %}
{% endif %}
