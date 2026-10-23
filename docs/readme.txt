create project :

django-admin startproject core myJWTApiRest


Installation & Setup

For this tutorial we are going to use the djangorestframework_simplejwt library, recommended by the DRF developers.

pip install djangorestframework_simplejwt

settings.py

REST_FRAMEWORK = {
    'DEFAULT_AUTHENTICATION_CLASSES': [
        'rest_framework_simplejwt.authentication.JWTAuthentication',
    ],
}