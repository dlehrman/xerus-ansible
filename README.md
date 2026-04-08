# Community Xerus Collection for Ansible
<!-- Add CI and code coverage badges here. Samples included below. -->
<!-- [![CI](https://github.com/dlehrman/xerus-ansible/workflows/CI/badge.svg?event=push)](https://github.com/dlehrman/xerus-ansible/actions) [![Codecov](https://img.shields.io/codecov/c/github/dlehrman/xerus-ansible)](https://codecov.io/gh/dlehrman/xerus-ansible) -->

Ansible roles to manage Legrand/Raritan/Server Technology Xerus&trade; devices via JSON-RPC API.

# Code of Conduct

We follow the [Ansible Code of Conduct](https://docs.ansible.com/projects/ansible/devel/community/code_of_conduct.html) in all our interactions within this project.

If you encounter abusive behavior, please refer to the [policy violations](https://docs.ansible.com/projects/ansible/devel/community/code_of_conduct.html#policy-violations) section of the Code for information on how to raise a complaint.

# Contributing to this collection

<!--Describe how the community can contribute to your collection. At a minimum, fill up and include the CONTRIBUTING.md file containing how and where users can create issues to report problems or request features for this collection. List contribution requirements, including preferred workflows and necessary testing, so you can benefit from community PRs. If you are following general Ansible contributor guidelines, you can link to - [Ansible Community Guide](https://docs.ansible.com/projects/ansible/devel/community/index.html). List the current maintainers (contributors with write or higher access to the repository). The following can be included:-->

The content of this collection is made by people like you, a community of individuals collaborating on making the world better through developing automation software.

We are actively accepting new contributors and all types of contributions are very welcome.

Don't know how to start? Refer to the [Ansible community guide](https://docs.ansible.com/projects/ansible/devel/community/index.html)!

Want to submit code changes? Take a look at the [Quick-start development guide](https://docs.ansible.com/projects/ansible/devel/community/create_pr_quick_start.html).

We also use the following guidelines:

* [Collection review checklist](https://docs.ansible.com/projects/ansible/devel/community/collection_contributors/collection_reviewing.html)
* [Ansible development guide](https://docs.ansible.com/projects/ansible/devel/dev_guide/index.html)
* [Ansible collection development guide](https://docs.ansible.com/projects/ansible/devel/dev_guide/developing_collections.html#contributing-to-collections)

# Collection maintenance

The current maintainers are listed in the [MAINTAINERS](MAINTAINERS) file. If you have questions or need help, feel free to mention them in the proposals.

To learn how to maintain/become a maintainer of this collection, refer to the [Maintainer guidelines](https://docs.ansible.com/projects/ansible/devel/community/maintainers.html).

It is necessary for maintainers of this collection to be subscribed to:

* The collection itself (the `Watch` button -> `All Activity` in the upper right corner of the repository's homepage).
* The [news-for-maintainers repository](https://github.com/ansible-collections/news-for-maintainers).

They also should be subscribed to Ansible's [The Bullhorn newsletter](https://docs.ansible.com/projects/ansible/devel/community/communication.html#the-bullhorn).

# Governance

<!--Describe how the collection is governed. Here can be the following text:-->

The process of decision making in this collection is based on discussing and finding consensus among participants.

Every voice is important. If you have something on your mind, create an issue or dedicated discussion and let's discuss it!

# Tested with Ansible

<!-- List the versions of Ansible the collection has been tested with. Must match what is in galaxy.yml. -->

# External requirements

<!-- List any external resources the collection depends on, for example minimum versions of an OS, libraries, or utilities. Do not list other Ansible collections here. -->

### Supported connections
<!-- Optional. If your collection supports only specific connection types (such as HTTPAPI, netconf, or others), list them here. -->

# Included content

<!-- Galaxy now usually displays full module and plugin docs within the UI. If you don't use Galaxy for your collection, you may need to either describe your plugins etc here, or point to an external docsite to cover that information. -->

# Using this collection

<!--Include some quick examples that cover the most common use cases for your collection content. It can include the following examples of installation and upgrade (change NAMESPACE.COLLECTION_NAME correspondingly):-->

### Installing the Collection from Ansible Galaxy

Before using this collection, you need to install it with the Ansible Galaxy command-line tool:
```bash
ansible-galaxy collection install NAMESPACE.COLLECTION_NAME
```

You can also include it in a `requirements.yaml` file and install it with `ansible-galaxy collection install -r requirements.yaml`, using the format:
```yaml
---
collections:
  - name: NAMESPACE.COLLECTION_NAME
```

Note that if you install the collection from Ansible Galaxy, it will not be upgraded automatically when you upgrade the `ansible` package. To upgrade the collection to the latest available version, run the following command:
```bash
ansible-galaxy collection install NAMESPACE.COLLECTION_NAME --upgrade
```

You can also install a specific version of the collection, for example, if you need to downgrade when something is broken in the latest version (please report an issue in this repository). Use the following syntax to install version `0.1.0`:

```bash
ansible-galaxy collection install NAMESPACE.COLLECTION_NAME:==0.1.0
```

See [using Ansible collections](https://docs.ansible.com/projects/ansible/devel/user_guide/collections_using.html) for more details.

# Release notes

See the [changelog](https://github.com/ansible-collections/REPONAMEHERE/tree/main/CHANGELOG.rst).

# Roadmap

<!-- Optional. Include the roadmap for this collection, and the proposed release/versioning strategy so users can anticipate the upgrade/update cycle. -->

# More information

<!-- List out where the user can find additional information, such as working group meeting times, slack/IRC channels, or documentation for the product this collection automates. At a minimum, link to: -->

- [Ansible user guide](https://docs.ansible.com/projects/ansible/devel/user_guide/index.html)
- [Ansible developer guide](https://docs.ansible.com/projects/ansible/devel/dev_guide/index.html)
- [Ansible collections requirements](https://docs.ansible.com/projects/ansible/devel/community/collection_contributors/collection_requirements.html)
- [Ansible community Code of Conduct](https://docs.ansible.com/projects/ansible/devel/community/code_of_conduct.html)
- [The Bullhorn (the Ansible contributor newsletter)](https://docs.ansible.com/projects/ansible/devel/community/communication.html#the-bullhorn)
- [Important announcements for maintainers](https://github.com/ansible-collections/news-for-maintainers)

# Licensing

<!-- Include the appropriate license information here and a pointer to the full licensing details. If the collection contains modules migrated from the ansible/ansible repo, you must use the same license that existed in the ansible/ansible repo. See the GNU license example below. -->

GNU General Public License v3.0 or later.

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.


# Trademark & Affiliation Disclaimer

The namespace has been set to `community` as the intent is to submit this for inclusion into the Ansible community once it is ready. However, at the time of this writing, the repo has not been submitted to or accepted by the Ansible community.

Xerus&trade; is a registered trademark of its respective owner.

This project is not affiliated with, endorsed by, or sponsored by Legrand, Raritan, or Server Technology in any way. All product names, logos, and brands referenced in this repository are the property of their respective trademark holders.

Any use of the Legrand, Raritan, Server Technology, or Xerus name or descriptions of Legrand, Raritan, or Server Technology products is for identification and interoperability purposes only. This community project is provided independently and carries no guarantee of accuracy, support, or compatibility from Legrand, Raritan, or Server Technology.
