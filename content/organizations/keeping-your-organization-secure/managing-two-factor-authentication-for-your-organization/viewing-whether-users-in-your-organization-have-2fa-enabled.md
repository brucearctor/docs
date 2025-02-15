---
title: Viewing whether users in your organization have 2FA enabled
intro: 'You can see which organization owners, members, and outside collaborators have enabled two-factor authentication.'
redirect_from:
  - /articles/viewing-whether-users-in-your-organization-have-2fa-enabled
  - /github/setting-up-and-managing-organizations-and-teams/viewing-whether-users-in-your-organization-have-2fa-enabled
  - /organizations/keeping-your-organization-secure/viewing-whether-users-in-your-organization-have-2fa-enabled
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: View 2FA usage
---

{% note %}

**Note:** You can require that all members{% ifversion fpt or ghec %}, including, owners, billing managers and{% else %} and{% endif %} outside collaborators in your organization have two-factor authentication enabled. For more information, see "[AUTOTITLE](/organizations/keeping-your-organization-secure/managing-two-factor-authentication-for-your-organization/requiring-two-factor-authentication-in-your-organization)."

{% endnote %}

{% data reusables.profile.access_org %}
{% data reusables.user-settings.access_org %}
{% data reusables.organizations.people %}
4. To view organization members, including organization owners, who have enabled or disabled two-factor authentication, on the right, click **2FA**, and select **Enabled** or **Disabled**.
 ![filter-org-members-by-2fa](/assets/images/help/2fa/filter-org-members-by-2fa.png)
5. To view outside collaborators in your organization, under the "People" tab, click **Outside collaborators**.
![select-outside-collaborators](/assets/images/help/organizations/select-outside-collaborators.png)
6. To view which outside collaborators have enabled or disabled two-factor authentication, on the right, click **2FA**, and select **Enabled** or **Disabled**.
![filter-outside-collaborators-by-2fa](/assets/images/help/2fa/filter-outside-collaborators-by-2fa.png)

## Further reading

- "[AUTOTITLE](/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-your-membership-in-organizations/viewing-peoples-roles-in-an-organization)"
