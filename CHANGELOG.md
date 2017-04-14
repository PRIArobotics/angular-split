
<a name="0.2.0"></a>
# 0.2.0 (2017-03-30)

* **ng upgrade:** upgrade to angular `^4.0.0`, replace `<template>` by `<ng-template>` and rebuild dist folder.


<a name="0.1.20"></a>
# 0.1.20 (2017-03-11)

* **wording:** add mention about CSS flexbox layout use, so `angular-split` is not compatible on browser not supporting it (like ios8).

### Feature

* **visibility toggle transition:** add transition (optionnal: `<split [visibleTransition]="true">`) when toggling visibility and `visibleTransitionEnd` event ` [pr11](https://github.com/bertrandg/angular-split/pull/11).


<a name="0.1.19"></a>
# 0.1.19 (2017-02-09)

### Bug fix

* **gutter height on Safari:** fix a weird bug about anormal gutter height when direction is 'vertical' on Safari only [issue5](https://github.com/bertrandg/angular-split/issues/5). Note that `angular-split` isn't working on browser without flexbox support, so not working on ios older than 9.


<a name="0.1.18"></a>
# 0.1.18 (2017-02-04)

### Bug fix

* **visibility toggle:** fix a bug I introduced in 0.1.17 while merging [pr10](https://github.com/bertrandg/angular-split/pull/10).


<a name="0.1.17"></a>
# 0.1.17 (2017-02-03)

### Feature

* **visibility toggle:** add possibility to show/hide areas using `<split-area [visible]="boolean">` without removing them from the DOM, useful for specific case [like with router](https://github.com/jitsmaster/angular-split/commit/c7c92b9a1d1c00623660aeb7bc048509255e763b). Thanks to [jitsmaster](https://github.com/jitsmaster) ([pr8](https://github.com/bertrandg/angular-split/pull/8) / [pr10](https://github.com/bertrandg/angular-split/pull/10))
