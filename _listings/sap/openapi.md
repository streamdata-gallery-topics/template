swagger: "2.0"
x-collection-name: SAP
x-complete: 1
info:
  title: SAP Translation Hub
  description: to-provide-users-of-software-in-a-global-market-with-texts-in-their-own-language-translations-are-required--sap-translation-hub-enables-you-to-draw-on-saps-translation-experience-across-multiple-products-and-languages-to-propose-translations-for-short-texts-
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /templateTypes:
    get:
      summary: Retrieves collaboration room template types
      description: Retrieves available collaboration room template types.
      operationId: retrieves-available-collaboration-room-template-types
      x-api-path-slug: templatetypes-get
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Collaboration
      - Room
      - Template
      - Types