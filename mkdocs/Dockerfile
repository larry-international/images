# Author: Rían Errity [rian@paradaux.io]
# Since: 9/03/2021
# License: Creative Commons Legal Code 1.0

FROM python:2.7

COPY ./docs/ /docs
WORKDIR /docs

RUN pip install mkdocs

EXPOSE 8080

CMD ["mkdocs", "serve"]