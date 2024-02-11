version: 2
updates:
  # shields.io dependencies
  - package-ecosystem: npm
    directory: '/'
    schedule:
      interval: weekly
      day: friday
      time: '12:00'
    open-pull-requests-limit: 99
    rebase-strategy: disabled
    ignore:
      # https://github.com/badges/shields/issues/7324
      # https://github.com/badges/shields/issues/7447
      # we're stuck with these versions until Safari is compatible with lookbehind regex syntax
      # https://caniuse.com/js-regexp-lookbehind
      - dependency-name: 'decamelize'
      - dependency-name: 'humanize-string'

  # badge-maker package dependencies
  - package-ecosystem: npm
    directory: '/badge-maker'
    schedule:
      interval: weekly
      day: friday
      time: '12:00'
    open-pull-requests-limit: 99
    rebase-strategy: disabled

  # GH actions
  - package-ecosystem: 'github-actions'
    directory: '/'
    schedule:
      interval: weekly
    open-pull-requests-limit: 99
    rebase-strategy: disabled

    # docusaurus-swizzled-warning package dependencies
  - package-ecosystem: npm
    directory: '/.github/actions/docusaurus-swizzled-warning'
    schedule:
      interval: weekly
      day: friday
      time: '12:00'
    open-pull-requests-limit: 99
    rebase-strategy: disabled

---

###
<p align="center">
  <img height="144" src="https://github-readme-stats.vercel.app/api?username=Nkipohcs&show_icons=true&theme=apprentice&hide=contribs,prs" alt="GitHub Stats"/>
</p>

---
<p align="right">
  <img height="23" src="https://komarev.com/ghpvc/?username=Nkipohcs&color=blue" alt="Profile views"/>
</p>
