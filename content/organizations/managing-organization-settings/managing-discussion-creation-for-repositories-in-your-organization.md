---
title: Managing discussion creation for repositories in your organization
intro: You can choose the permission levels that members require to create discussions in repositories owned by your organization.
redirect_from:
  - /github/setting-up-and-managing-organizations-and-teams/managing-discussion-creation-for-repositories-in-your-organization
permissions: Organization owners can manage discussion creation for repositories owned by the organization.
versions:
  feature: discussions
topics:
  - Organizations
  - Teams
shortTitle: Manage repository discussions
---


## Allowing or disallowing users with read access to create discussions

By default, organization members with read access can create discussions if a repository administrator or organization owner enables discussions for a repository owned by the organization.

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.member-privileges %}
5. Under "Repository discussions", select or deselect **Allow users with read access to create discussions**.
  ![Checkbox to allow people with read access to create discussions](/assets/images/help/discussions/toggle-allow-users-with-read-access-checkbox.png)
6. Click **Save**.
  !["Save" button for discussions settings](/assets/images/help/discussions/click-save.png)

## Further reading

- "[AUTOTITLE](/discussions/collaborating-with-your-community-using-discussions/about-discussions)"
- "[AUTOTITLE](/discussions/managing-discussions-for-your-community)"
- "[AUTOTITLE](/organizations/managing-organization-settings/enabling-or-disabling-github-discussions-for-an-organization)"
