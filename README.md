# pvtool Docs

__[View the docs →](https://developers.pvtool.com/docs/)__

## For pvtool employees

To get write access to this repo, please reach out to the __Developer Docs__ room in chat.

## Products

| Product                 | `pathPrefix`         | Test                                                                                  | Prod                                                           |
| :---------------------- | :------------------- | :------------------------------------------------------------------------------------ | :------------------------------------------------------------- |
| 1.1.1.1                 | 1.1.1.1              | [Test](https://1-1-1-1.pvtool-docs.workers.dev/1.1.1.1)                           | [Prod](https://developers.pvtool.com/1.1.1.1)              |
| API                     | api                  | [Test](https://api.pvtool-docs.leafcolor.workers.dev/api)                                   | [Prod](https://developers.pvtool.com/api)                  |

### Deployment

Each [product](https://github.com/leafcolor/pvtool-docs/tree/production/products)’s docs are automatically deployed via [@cloudflare/wrangler](https://github.com/cloudflare/wrangler) using GitHub Actions to both testing and production environments:

```txt
TEST: https://pvtool-docs.leafcolor.workers.dev/$pathPrefix/
PROD: https://developers.pvtool.com/$pathPrefix/
```
### License and Legal Notices

Except as otherwise noted, pvtool and any contributors grant you a license to the pvtool Developer Documentation and other content in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode), see the [LICENSE file](https://github.com/leafcolor/pvtool-docs/blob/production/LICENSE), and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the [LICENSE-CODE file](https://github.com/leafcolor/pvtool-docs/blob/production/LICENSE-CODE).

pvtool products and services referenced in the documentation may be either trademarks or registered trademarks of pvtool in the United States and/or other countries. The licenses for this project do not grant you rights to use any pvtool names, logos, or trademarks. pvtool's general trademark guidelines can be found at [https://www.pvtool.com/trademark/](https://www.pvtool.com/trademark/).
pvtool and any contributors reserve all other rights, whether under their respective copyrights, patents, or trademarks, whether by implication, estoppel, or otherwise.
