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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/apis.md
specificationVersion: "0.14"
apis:
- name: Cloud Source Repositories API Delete Repo
  x-api-slug: cloud-source-repositories-api
  description: Deletes a repo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com////v1/{name}
  tags: Repository
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-delete-openapi.md
- name: Cloud Source Repositories API Get Repo
  x-api-slug: cloud-source-repositories-api
  description: Returns information about a repo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com////v1/{name}
  tags: Repository
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1name-get-openapi.md
- name: Cloud Source Repositories API Get Repos
  x-api-slug: cloud-source-repositories-api
  description: Returns all repos belonging to a project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com////v1/{name}/repos
  tags: Repository
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1namerepos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1namerepos-get-openapi.md
- name: Cloud Source Repositories API Create Repo
  x-api-slug: cloud-source-repositories-api
  description: |-
    Creates a repo in the given project with the given name..

    If the named repository already exists, `CreateRepo` returns
    `ALREADY_EXISTS`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com////v1/{parent}/repos
  tags: Repository
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1parentrepos-post-openapi.md
- name: Cloud Source Repositories API Get Access Control Policy
  x-api-slug: cloud-source-repositories-api
  description: |-
    Gets the access control policy for a resource.
    Returns an empty policy if the resource exists and does not have a policy
    set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com////v1/{resource}:getIamPolicy
  tags: Repository Policy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcegetiampolicy-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcegetiampolicy-get-openapi.md
- name: Cloud Source Repositories API Set Access Control Policy
  x-api-slug: cloud-source-repositories-api
  description: |-
    Sets the access control policy on the specified resource. Replaces any
    existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com////v1/{resource}:setIamPolicy
  tags: Repository Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcesetiampolicy-post-openapi.md
- name: Cloud Source Repositories API Return Permissions
  x-api-slug: cloud-source-repositories-api
  description: |-
    Returns permissions that a caller has on the specified resource.
    If the resource does not exist, this will return an empty set of
    permissions, not a NOT_FOUND error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com////v1/{resource}:testIamPermissions
  tags: Repository Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/v1resourcetestiampermissions-post-openapi.md
- name: Cloud Source Repositories API
  x-api-slug: cloud-source-repositories-api
  description: Google Cloud Source Repositories provides Git version control to support
    collaborative development of any application or service, including those that
    run on Google App Engine and Google Compute Engine. If you are using the Stackdriver
    Debugger, you can use Cloud Source Repositories and related tools to view debugging
    information alongside your code during application runtime. Cloud Source Repositories
    also provides a source browser that you can use to view your repository files
    from within the Cloud Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-repositories.png
  humanURL: https://cloud.google.com/source-repositories/
  baseURL: ://sourcerepo.googleapis.com//
  tags: Google Cloud Source Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-source-repositories/master/_listings/google-cloud-source-repositories/openapi.md
x-common:
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