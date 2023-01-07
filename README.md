# github-label-manager

To sync and manage the labels I use

## Label Groups

| **Defaults**                                        | Points                                                              | Status | Type                                         | State                                                      |
| --------------------------------------------------- | ------------------------------------------------------------------- | ------ | -------------------------------------------- | ---------------------------------------------------------- |
| Standard labels commonly used in most repositories. | Describes the relative effort to complete an issue or pull request. | df     | Describes the type of issue or pull request. | Describes the decision state of the issue or pull request. |

## Inspiration

The [Label Sync](https://github.com/marketplace/actions/label-sync) Github Action by @EndBug

Label Exporter - https://github.com/marketplace/actions/export-label-config

---

- name: A label
  color: '000000'

- name: Another label
  color: '111111'
  description: A very inspiring description

- name: Yet another label
  color: '222222'
  aliases: ['first', 'second', 'third']
