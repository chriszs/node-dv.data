# DocumentVision

Training data for [DocumentVision](https://github.com/creatale/node-dv), a [node.js](http://nodejs.org) library for processing and understanding scanned documents.

The training data is packaged this way as it very seldomly changes. The set includes:

- English language support (`'eng'`)
- German language support (`'deu'`)
- Data for OSD mode

The module itself only exports two strings: `filename` contains `module.filename` and `tessdata` points
to the tessdata directory (fully resolved).

## Versioning

DocumentVision is maintained under the [Semantic Versioning](http://semver.org/) guidelines as much as possible:

- Version number format is `<major>.<minor>.<patch>`
- Breaking backward compatibility bumps the major (resetting minor and patch)
- New additions without breaking backward compatibility bumps the minor (resetting patch)
- Bug fixes and other changes bumps the patch

## License

Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT License](http://creativecommons.org/licenses/MIT/). Copyright &copy; 2012 Christoph Schulz.
