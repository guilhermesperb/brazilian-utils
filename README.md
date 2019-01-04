# :brazil: Brazilian Utils

[![Build Status](https://travis-ci.org/brazilian-utils/brazilian-utils.svg?branch=master)](https://travis-ci.org/brazilian-utils/brazilian-utils) [![Coverage Status](https://codecov.io/gh/brazilian-utils/brazilian-utils/branch/master/graph/badge.svg)](https://codecov.io/gh/brazilian-utils/brazilian-utils) [![Known Vulnerabilities](https://snyk.io/test/github/brazilian-utils/brazilian-utils/badge.svg?targetFile=package.json)](https://snyk.io/test/github/brazilian-utils/brazilian-utils?targetFile=package.json) [![Maintainability](https://api.codeclimate.com/v1/badges/05d3cd8492ed438bf51d/maintainability)](https://codeclimate.com/github/hyanmandian/brazilian-utils/maintainability) [![Lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/) [![All Contributors](https://img.shields.io/badge/all_contributors-9-orange.svg?style=flat-square)](#contributors) [![License: MIT](https://img.shields.io/github/license/hyanmandian/brazilian-utils.svg)](LICENSE)

Utils library for specific Brazilian businesses.

## Packages

| Package                                                        | Description                       | Size                                                                                                                                                                                                                                                                                                                                                                 |
| :------------------------------------------------------------- | :-------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [@brazilian-utils/is-valid-cpf](./packages/is-valid-cpf)       | Check if CPF is valid             | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/is-valid-cpf)](https://packagephobia.now.sh/result?p=@brazilian-utils/is-valid-cpf) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/is-valid-cpf/dist/index.umd.js?compression=gzip)](https://unpkg.com/@brazilian-utils/is-valid-cpf/dist/index.umd.js)             |
| [@brazilian-utils/is-valid-cnpj](./packages/is-valid-cnpj)     | Check if CNPJ is valid            | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/is-valid-cnpj)](https://packagephobia.now.sh/result?p=@brazilian-utils/is-valid-cnpj) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/is-valid-cnpj/dist/index.umd.js?compression=gzip)](https://unpkg.com/@brazilian-utils/is-valid-cnpj/dist/index.umd.js)         |
| [@brazilian-utils/is-valid-cep](./packages/is-valid-cep)       | Check if CEP is valid             | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/is-valid-cep&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/is-valid-cep) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/is-valid-cep/dist/index.umd.js?compression=gzip)](https://unpkg.com/@brazilian-utils/is-valid-cep/dist/index.umd.js)           |
| [@brazilian-utils/is-valid-boleto](./packages/is-valid-boleto) | Check if Boleto is valid          | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/is-valid-boleto)](https://packagephobia.now.sh/result?p=@brazilian-utils/is-valid-boleto) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/is-valid-boleto/dist/index.umd.js?compression=gzip)](https://unpkg.com/@brazilian-utils/is-valid-boleto/dist/index.umd.js) |
| [@brazilian-utils/is-valid-phone](./packages/is-valid-phone)   | Check if phone is valid           | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/is-valid-phone)](https://packagephobia.now.sh/result?p=@brazilian-utils/is-valid-phone) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/is-valid-phone/dist/index.umd.js?compression=gzip)](https://unpkg.com/@brazilian-utils/is-valid-phone/dist/index.umd.js)     |
| [@brazilian-utils/format-cpf](./packages/format-cpf)           | Return CPF formatted with mask    | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/format-cpf&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/format-cpf) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/format-cpf/dist/index.umd.js?compression=gzip&1)](https://unpkg.com/@brazilian-utils/format-cpf/dist/index.umd.js)                 |
| [@brazilian-utils/format-cnpj](./packages/format-cnpj)         | Return CNPJ formatted with mask   | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/format-cnpj&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/format-cnpj) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/format-cnpj/dist/index.umd.js?compression=gzip&1)](https://unpkg.com/@brazilian-utils/format-cnpj/dist/index.umd.js)             |
| [@brazilian-utils/format-boleto](./packages/format-boleto)     | Return boleto formatted with mask | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/format-boleto&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/format-boleto) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/format-boleto/dist/index.umd.js?compression=gzip&1)](https://unpkg.com/@brazilian-utils/format-boleto/dist/index.umd.js)     |
| [@brazilian-utils/generate-cpf](./packages/generate-cpf)       | Generates a valid CPF             | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/generate-cpf&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/generate-cpf) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/generate-cpf/dist/index.umd.js?compression=gzip&1)](https://unpkg.com/@brazilian-utils/generate-cpf/dist/index.umd.js)         |

## Other Packages

| Package                                              | Description    | Size                                                                                                                                                                                                                                                                                                                                                 |
| :--------------------------------------------------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [@brazilian-utils/validators](./packages/validators) | All validators | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/validators)](https://packagephobia.now.sh/result?p=@brazilian-utils/validators) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/validators/dist/index.umd.js?compression=gzip)](https://unpkg.com/@brazilian-utils/validators/dist/index.umd.js)     |
| [@brazilian-utils/formatters](./packages/formatters) | All formatters | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/formatters&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/formatters) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/formatters/dist/index.umd.js?compression=gzip&1)](https://unpkg.com/@brazilian-utils/formatters/dist/index.umd.js) |

## Helper Packages (used internally, but may be useful for you :smile:)

| Package                                                                          | Description                                                | Size                                                                                                                                                                                                                                                                                                                                                                                                         |
| :------------------------------------------------------------------------------- | :--------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [@brazilian-utils/helper-is-last-char](./packages/helper-is-last-char)           | Check if the index is the same as last index of the string | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/helper-is-last-char)](https://packagephobia.now.sh/result?p=@brazilian-utils/helper-is-last-char) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/helper-is-last-char/dist/index.umd.js?compression=gzip)](https://unpkg.com/@brazilian-utils/helper-is-last-char/dist/index.umd.js)                         |
| [@brazilian-utils/helper-only-numbers](./packages/helper-only-numbers)           | Strips all non numeric characters                          | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/helper-only-numbers&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/helper-only-numbers) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/helper-only-numbers/dist/index.umd.js?compression=gzip&1)](https://unpkg.com/@brazilian-utils/helper-only-numbers/dist/index.umd.js)                     |
| [@brazilian-utils/helper-generate-checksum](./packages/helper-generate-checksum) | Generates a checksum                                       | [![Install size](https://packagephobia.now.sh/badge?p=@brazilian-utils/helper-generate-checksum&1)](https://packagephobia.now.sh/result?p=@brazilian-utils/helper-generate-checksum) [![GZIP size](http://img.badgesize.io/https://unpkg.com/@brazilian-utils/helper-generate-checksum/dist/index.umd.js?compression=gzip&1)](https://unpkg.com/@brazilian-utils/helper-generate-checksum/dist/index.umd.js) |

## Contributors

Thanks go to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars2.githubusercontent.com/u/5044101?v=3" width="100px;"/><br /><sub><b>Hyan Mandian</b></sub>](https://github.com/hyanmandian)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=hyanmandian "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=hyanmandian "Documentation") [🤔](#ideas-hyanmandian "Ideas, Planning, & Feedback") [⚠️](https://github.com/hyanmandian/brazilian-utils/commits?author=hyanmandian "Tests") | [<img src="https://avatars2.githubusercontent.com/u/4587602?v=3" width="100px;"/><br /><sub><b>Lucas Veloso</b></sub>](https://github.com/lucassveloso)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=lucassveloso "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=lucassveloso "Documentation") [🤔](#ideas-lucassveloso "Ideas, Planning, & Feedback") [⚠️](https://github.com/hyanmandian/brazilian-utils/commits?author=lucassveloso "Tests") | [<img src="https://avatars2.githubusercontent.com/u/508827?v=3" width="100px;"/><br /><sub><b>Andreo Vieira</b></sub>](https://github.com/andreoav)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=andreoav "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=andreoav "Documentation") [🤔](#ideas-andreoav "Ideas, Planning, & Feedback") [🔧](#tool-andreoav "Tools") | [<img src="https://avatars3.githubusercontent.com/u/12724212?v=4" width="100px;"/><br /><sub><b>Matheus Almeida</b></sub>](http://matalmeida.me)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=matAlmeida "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=matAlmeida "Documentation") [⚠️](https://github.com/hyanmandian/brazilian-utils/commits?author=matAlmeida "Tests") | [<img src="https://avatars2.githubusercontent.com/u/32275453?s=400&u=55d9685df8b4dc14169719993d4997b2a9adda61&v=4" width="100px;"/><br /><sub><b>Fernando Rogelin</b></sub>](https://github.com/FernandoRogelin)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=fernandorogelin "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=fernandorogelin "Documentation") [⚠️](https://github.com/hyanmandian/brazilian-utils/commits?author=fernandorogelin "Tests") | [<img src="https://avatars2.githubusercontent.com/u/24531420?v=4" width="100px;"/><br /><sub><b>rodineijf</b></sub>](https://github.com/rodineijf)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=rodineijf "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=rodineijf "Documentation") [⚠️](https://github.com/hyanmandian/brazilian-utils/commits?author=rodineijf "Tests") | [<img src="https://avatars2.githubusercontent.com/u/10627086?v=4" width="100px;"/><br /><sub><b>Emerson Laurentino</b></sub>](https://twitter.com/elaurent_)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=emersonlaurentino "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=emersonlaurentino "Documentation") [⚠️](https://github.com/hyanmandian/brazilian-utils/commits?author=emersonlaurentino "Tests") |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [<img src="https://avatars2.githubusercontent.com/u/14338574?v=4" width="100px;"/><br /><sub><b>Leonardo Dutra</b></sub>](https://github.com/Leonardo18)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=Leonardo18 "Code") [📖](https://github.com/hyanmandian/brazilian-utils/commits?author=Leonardo18 "Documentation") [⚠️](https://github.com/hyanmandian/brazilian-utils/commits?author=Leonardo18 "Tests") | [<img src="https://avatars3.githubusercontent.com/u/357835?v=4" width="100px;"/><br /><sub><b>Victor Magalhães</b></sub>](https://victormagalhaes.codes)<br />[💻](https://github.com/hyanmandian/brazilian-utils/commits?author=vhfmag "Code") [🔧](#tool-vhfmag "Tools") |

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind are welcome!

## License

[MIT](LICENSE)
