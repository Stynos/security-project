# security project django
Creating a social webapp in where in can implement security measures for the secure developer program
run the following command when in the securesite folder to start the app:
gunicorn securesite.wsgi     --keyfile private_key.pem     --certfile certificate.pem