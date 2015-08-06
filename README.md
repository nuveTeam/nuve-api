# nuve-api

## Changelog

*0.3*:
* Doc is now generated using final release of Swagger 1.5.0
* Updates to organization endpoints:
  * Specification of POST body
  * /orgs/{id} now returns an individual org
  * Added a PUT, for updating orgs
  * Endpoints for retrieving an orgs' geozones and assets
* Org resource - Added phone, email and address for a billing contact
* User resource:
  * GET for all users and an individual users
  * POST for creating new users
  * Retrieve a user's org

*0.2*:
* Added ability to create organizations
* First version of analyses
* First version of activations
