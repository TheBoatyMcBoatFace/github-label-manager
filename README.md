# github-label-manager

To sync and manage the labels I use

## Label Groups

| **Defaults**                                        | Points                                                              | Status | Type                                         | State                                                      |
| --------------------------------------------------- | ------------------------------------------------------------------- | ------ | -------------------------------------------- | ---------------------------------------------------------- |
| Standard labels commonly used in most repositories. | Describes the relative effort to complete an issue or pull request. | df     | Describes the type of issue or pull request. | Describes the decision state of the issue or pull request. |

| Label | Color | Description | Alias |

[./labels/good%20first%20issue]

https://github.com/TheBoatyMcBoatFace/github-label-manager/labels/good%20first%20issue

![](https://img.shields.io/badge/-status:wip-5319e7.svg)
![][~comments]
![][~enhancement]

[~comments]: https://img.shields.io/badge/-comments-006b75.svg
[~enhancement]: https://img.shields.io/badge/-enhancement-84b6eb.svg

![label: comments][~comments]
![label: enhancement][~enhancement]

[~comments]: https://img.shields.io/badge/-comments-006b75.svg
[~enhancement]: https://img.shields.io/badge/-enhancement-84b6eb.svg

[![label: good first issue](./labels/good%20first%20issue)

[![label: bug][~bug]](https://github.com/isaacs/github/labels/bug)
[![label: code review][~code review]](https://github.com/isaacs/github/labels/code%20review)

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
