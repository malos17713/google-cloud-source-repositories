---
name: Google Cloud Source Repositories
x-slug: google-cloud-source-repositories
description: Google Cloud Source Repositories provides Git version control to support
  collaborative development of any application or service, including those that run
  on Google App Engine and Google Compute Engine. If you are using the Stackdriver
  Debugger, you can use Cloud Source Repositories and related tools to view debugging
  information alongside your code during application runtime. Cloud Source Repositories
  also provides a source browser that you can use to view your repository files from
  within the Cloud Console.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud Source Repositories
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/apis.md
specificationVersion: "0.14"
apis:
- name: Cloud Source Repositories - Delete Repo
  x-api-slug: v1name-delete
  description: Deletes a repo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google APIs, GitHub, Code, SDK, Orchestration, Stack Network, SDKs, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-delete-openapi.md
- name: Cloud Source Repositories - Get Repo
  x-api-slug: v1name-get
  description: Returns information about a repo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google APIs, GitHub, Code, SDK, Orchestration, Stack Network, SDKs, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-get-openapi.md
- name: Cloud Source Repositories - Get Repos
  x-api-slug: v1namerepos-get
  description: Returns all repos belonging to a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google APIs, GitHub, Code, SDK, Orchestration, Stack Network, SDKs, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1namerepos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1namerepos-get-openapi.md
- name: Cloud Source Repositories - Create Repo
  x-api-slug: v1parentrepos-post
  description: |-
    Creates a repo in the given project with the given name..

    If the named repository already exists, `CreateRepo` returns
    `ALREADY_EXISTS`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google APIs, GitHub, Code, SDK, Orchestration, Stack Network, SDKs, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1parentrepos-post-openapi.md
- name: Cloud Source Repositories - Get Access Control Policy
  x-api-slug: v1resourcegetiampolicy-get
  description: |-
    Gets the access control policy for a resource.
    Returns an empty policy if the resource exists and does not have a policy
    set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google APIs, GitHub, Code, SDK, Orchestration, Stack Network, SDKs, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcegetiampolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcegetiampolicy-get-openapi.md
- name: Cloud Source Repositories - Set Access Control Policy
  x-api-slug: v1resourcesetiampolicy-post
  description: |-
    Sets the access control policy on the specified resource. Replaces any
    existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google APIs, GitHub, Code, SDK, Orchestration, Stack Network, SDKs, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcesetiampolicy-post-openapi.md
- name: Cloud Source Repositories - Return Permissions
  x-api-slug: v1resourcetestiampermissions-post
  description: |-
    Returns permissions that a caller has on the specified resource.
    If the resource does not exist, this will return an empty set of
    permissions, not a NOT_FOUND error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google APIs, GitHub, Code, SDK, Orchestration, Stack Network, SDKs, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcetestiampermissions-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.resource.manager.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.source.repositories.stack.network
- type: x-concepts
  url: https://cloud.google.com/source-repositories/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/source-repositories/docs/
- type: x-getting-started
  url: https://cloud.google.com/source-repositories/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/source-repositories/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/source-repositories/pricing
- type: x-website
  url: https://cloud.google.com/source-repositories/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---