FROM anguis/django-wazzup
MAINTAINER Rustem Kamun a.k.a "xepa4ep"

ENV PYTHONUNBUFFERED 1

RUN apt-get update && apt-get install -qq -y \
	libjpeg-dev \
    libpng-dev \
    libpq-dev \
    libxml2-dev \
    libxslt1-dev

# Service
EXPOSE 8000