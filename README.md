# nuve-api

## Changelog
*0.5*:
* Added includes for manager and subscriptions to /orgs and /orgs/{id}
* Changed POST /orgs to only accept an individual org
* Changed POST /users to only accept an individual user

*0.4*:
* Added /subscriptions
  * Subscriptions are used to determine the current status of organizations, with respect to whether or not they are active
  * Relationships for retrieving subscriptions based upon the organization and to retrieve an organization based upon its subscriptions
* Add org manager and billing contact
  * Org manager is the user in the platform that is the point of contact for who manages the relationship with Nuve or the parent of the organization.
  * Billing contact is the person in charge of billing questions which are directed to an organization

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
