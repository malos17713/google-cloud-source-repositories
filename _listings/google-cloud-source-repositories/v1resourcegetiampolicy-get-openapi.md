---
swagger: "2.0"
x-collection-name: Google Cloud Source Repositories
x-complete: 0
info:
  title: Cloud Source Repositories API Get Access Control Policy
  description: |-
    Gets the access control policy for a resource.
    Returns an empty policy if the resource exists and does not have a policy
    set.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: sourcerepo.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}:
    delete:
      summary: Delete Repo
      description: Deletes a repo.
      operationId: sourcerepo.projects.repos.delete
      x-api-path-slug: v1name-delete
      parameters:
      - in: path
        name: name
        description: The name of the repo to delete
      responses:
        200:
          description: OK
      tags:
      - Repository
    get:
      summary: Get Repo
      description: Returns information about a repo.
      operationId: sourcerepo.projects.repos.get
      x-api-path-slug: v1name-get
      parameters:
      - in: path
        name: name
        description: The name of the requested repository
      responses:
        200:
          description: OK
      tags:
      - Repository
  /v1/{name}/repos:
    get:
      summary: Get Repos
      description: Returns all repos belonging to a project.
      operationId: sourcerepo.projects.repos.list
      x-api-path-slug: v1namerepos-get
      parameters:
      - in: path
        name: name
        description: The project ID whose repos should be listed
      responses:
        200:
          description: OK
      tags:
      - Repository
  /v1/{parent}/repos:
    post:
      summary: Create Repo
      description: |-
        Creates a repo in the given project with the given name..

        If the named repository already exists, `CreateRepo` returns
        `ALREADY_EXISTS`.
      operationId: sourcerepo.projects.repos.create
      x-api-path-slug: v1parentrepos-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: parent
        description: The project in which to create the repo
      responses:
        200:
          description: OK
      tags:
      - Repository
  /v1/{resource}:getIamPolicy:
    get:
      summary: Get Access Control Policy
      description: |-
        Gets the access control policy for a resource.
        Returns an empty policy if the resource exists and does not have a policy
        set.
      operationId: sourcerepo.projects.repos.getIamPolicy
      x-api-path-slug: v1resourcegetiampolicy-get
      parameters:
      - in: path
        name: resource
        description: 'REQUIRED: The resource for which the policy is being requested'
      responses:
        200:
          description: OK
      tags:
      - Repository Policy
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---