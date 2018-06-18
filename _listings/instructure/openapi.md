---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Sections API
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sections/{id}/crosslist:
    delete:
      summary: De-cross-list a Section
      description: De-cross-list a section.
      operationId: decrosslist-a-section
      x-api-path-slug: sectionsidcrosslist-delete
      responses:
        200:
          description: OK
      tags:
      - Sections
      - Id
      - Crosslist
  /sections/{id}/crosslist/new_course_id:
    post:
      summary: Cross-list a Section
      description: Cross-list a section.
      operationId: crosslist-a-section
      x-api-path-slug: sectionsidcrosslistnew-course-id-post
      responses:
        200:
          description: OK
      tags:
      - Sections
      - Id
      - Crosslist
      - New
      - Course
      - Id
---