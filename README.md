# Django-Tenant


This application enables django powered websites to have multiple tenants via PostgreSQL schemas. A vital feature for every Software-as-a-Service (SaaS) website.


# Setup & Documentation
DATABASES = {
    'default': {
        'ENGINE': 'django_tenants.postgresql_backend',
        
     }
} 
