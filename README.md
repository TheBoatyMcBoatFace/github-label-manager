# github-label-manager

To sync and manage the labels I use

## Label Groups

| **Defaults**                                        | Points                                                              | Status | Type                                         | State                                                      |
| --------------------------------------------------- | ------------------------------------------------------------------- | ------ | -------------------------------------------- | ---------------------------------------------------------- |
| Standard labels commonly used in most repositories. | Describes the relative effort to complete an issue or pull request. | df     | Describes the type of issue or pull request. | Describes the decision state of the issue or pull request. |

![](https://img.shields.io/badge/-status:wip-5319e7.svg)
![][~comments]
![][~enhancement]

[~comments]: https://img.shields.io/badge/-comments-006b75.svg
[~enhancement]: https://img.shields.io/badge/-enhancement-84b6eb.svg

![label: comments][~comments]
![label: enhancement][~enhancement]

[~comments]: https://img.shields.io/badge/-comments-006b75.svg
[~enhancement]: https://img.shields.io/badge/-enhancement-84b6eb.svg

[![label: good first issue][~good first issue]](./labels/good%20first%20issue)

[![label: bug][~bug]](https://github.com/isaacs/github/labels/bug)
[![label: code review][~code review]](https://github.com/isaacs/github/labels/code%20review)

[~api]: https://img.shields.io/badge/-api-0052cc.svg
[~bug]: https://img.shields.io/badge/-bug-f00.svg
[~code review]: https://img.shields.io/badge/-code%20review-e5f78a.svg

nline Linked Label Markdown
\*\not all for this repo
[![](https://i.imgur.com/9wQkGeP.png)](../labels/comments)
[![](https://i.imgur.com/Bie8PhC.png)](../labels/enhancement)
[![](https://i.imgur.com/BMrO7QS.png)](../labels/ui)
[![](https://i.imgur.com/e0ZyrVw.png)](../labels/markdown)
[![](https://i.imgur.com/hgS76Kz.png)](../labels/help-wanted)
[![](https://i.imgur.com/JflcH01.png)](../labels/bug)
[![](https://i.imgur.com/olsmFk3.png)](../labels/notifications)
[![](https://i.imgur.com/PTZYyYI.png)](../labels/bug)
[![](https://i.imgur.com/r14Ea9n.png)](../labels/issues)
[![](https://i.imgur.com/sIQuybV.png)](../labels/search)
[![](https://i.imgur.com/xJMMtqj.png)](../labels/pull-requests)

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
