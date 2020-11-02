# Drupal Orange Profile

**NOTICE**\
Development for this theme has moved to [Drupal.org](https://www.drupal.org/). If you want to submit issues, develop, or use this theme please visit the [new project page](https://www.drupal.org/project/orange_profile).
No pull requests submitted to this repository will be accepted from now on.

> Custom profile by Acro Media Inc.

An installation profile for Drupal 8.x that includes common modules for projects.

Used by [AcroMedia/drupal-orange-project](https://github.com/AcroMedia/drupal-orange-project).

## Quick Start Guide

> Get your site setup in minutes.

- Start your project with [Drupal Orange Project](https://github.com/AcroMedia/drupal-orange-project).
- Begin a fresh Drupal install and choose the `Orange Profile`. Wait for Drupal to finish installing (grab a coffee, build a log cabin in the woods by hand etc).
- After the install finishes, fill out your general Drupal site settings and proceed to configure items below.
- **Homepage**
  - *Structure > Content types > Homepage > Manage fields*
  - `/admin/structure/types/manage/homepage/fields`
  - Setup your homepage fields based on your project/homepage design.
  - Think of the homepage as a landing page the client could re-use if they wanted. All elements should be configured through fields and/or Paragraphs. Make sure fields are labelled clearly and have descriptions where necessary so it's clear when the client is using the site.
- Configure any other content-types or fields required for your project.

### Post Configuration To-Dos

- **Add Site Admin User**
  - *People > Add a new user* 
  - URL: `/admin/people/create`
  - Setup a `siteadmin` user with the `Administrator` role assigned.
  - Add the entered information to the appropriate 1Password account. Clients will use this information for site access.
- **Review Permissions**
  - *People > Permissions*
  - URL: `/admin/people/permissions`
  - After setting up new product types, variations etc. you will want to review the permissions and update appropriately so users/admins can properly access the areas they need to.
